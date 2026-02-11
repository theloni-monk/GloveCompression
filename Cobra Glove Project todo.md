### Reading
- [x] [https://www.nature.com/articles/s41586-025-09255-w](https://www.nature.com/articles/s41586-025-09255-w) ✅ 2026-01-19
- [x] Read mujoco / myosuite constraint specification 
- [ ] read about pose SOTA
- [ ] Write blurb advertising a reading group: 📅 2026-02-01 
	Motion Analysis and Synthesis "in the Wild"
		Topics of interest: 
		 * Representation theory of Lie groups/algebras for characterizing kinematic state. 
		 * Computational aspects of geometrically-constrained estimation problems. 
		 * Neural circuit models of motion synthesis. 
		 * Notions of sparsity in communications for control. 
### Viz
- [x] check that X maps to twisting, Y maps to ab/adduciton ✅ 2026-01-20
^ correct, y is palm-plane rotation, x is knuckle-plain rotation
- Trial-avg version + sem to sanity check that initial starting position
    - check if this makes sense?
- [x] fix task aggregation 📅 2026-01-26 ✅ 2026-01-26
- [x] make initial pose box plot 📅 2026-01-27 ✅ 2026-01-26
![[Pasted image 20260126064859.png]]
- [x] make video export pipeline with a few known tasks 📅 2026-01-26 ✅ 2026-01-26
- [x] fix thumb hardcoding
- [x] root-offset rotation📅 2026-02-09 
- [ ] side-by-side PCA viz  #TODAY
- [x] Component Anaylsi:  Number of PCs per task (for 1 participant), how generalizable are PCs across task? ✅ 2026-02-08

### Explore
Compute decompositions 
* [x] PCA baselines
* PCA on Euclidean position space
* PCA on Euclidean embedding of joint-angle space
* Euclidean PCA on position forward-differences
* Euclidean PCA on joint-angle forward-differences
* [x] FISTA-based LCA over knuckles ✅ 2026-02-03
* [x] L0 branch-and-bound combinatorial search over joint combos ✅ 2026-02-03
* [x] intra patient variance comparison
![[ev prog across patients by task.png]]
* [x] intra task variance comparison
![[ev prog across tasks by patient.png]]
- [ ] Nonlinear analysis
* pca on SO(3) group via Schmidt decomp : trace(irrepA'irrepB) as inner product
* pca on so(3) vector algebra of forward-differences 
* LCA same as above
Implementing constraints from biomechanics:  
- 1) limits on jt angles/ combinations
    - rough guesses based on own hand
- 2) dynamics learned from data (e.g. could be participant-specific)

### Comm
- [x] Talk to Jorge about CIVO access to Meta Wristband devkit ✅ 2026-01-21
- [x] add my lab notebook to lab wiki 
