# local-surface-algebras
Study finite dimensional quotients of cyclic quivers
---
Taking quotients by paths of some maximal length $n$ of the cyclic quivers as described in [The Composition Algebra of a Cyclic Quiver](https://github.com/The-Singularity-Research/loac-surface-algebras/blob/main/15988304.pdf) we get finite dimensional algebras. A gluing
of a collection of such algebras according to the methods described in [Surface Algebras I](https://github.com/The-Singularity-Research/cirq_hybrid_codes/blob/master/Surface_Algebras_I%20(3).pdf) we obtain a finite dimensional surface algebra. Finite dimensional surface algebras and their representation theory can be studied using GAP and in particular the package [QPA](https://www.gap-system.org/Manuals/pkg/qpa/doc/chap0.html#contents) for quiver path algebras. We will call the cyclic quivers in the gluing *"local surface algebras"* and the algebras obtained from their gluings **"Finite Dimensional Surface Algebras"**. The Finite Dimensional Surface Algebras will have gentle relations corresponding to crossing over from one local cyclic quiver path algebra to another, along with the additional relations given by the quotient by paths of some maximal length on each cycle. The maximal length paths will in general be different for each local cyclic path algebra. Moreover, we can think of this as a generalization of G. t'Hooft's cyclic harmonic oscillators in his [Cellular Automata Approach to Quantum Mechanics](https://github.com/The-Singularity-Research/local-surface-algebras/blob/main/1405.1548.pdf) (see p. 23 of the arXiv version). See also the following lectures:

-[Lecture 1](https://www.youtube.com/watch?v=F3hPvusB0ds)
-[Lecture 2](https://www.youtube.com/watch?v=d2R9cbttqBY)
-[Lecture 3](https://www.youtube.com/watch?v=a7xw0p4WfDs)

Our generalization allows for high energy levels by allowing for returning to a vertex of the quiver (corresponding to a simple module of the path algebra in the Ringel paper) so that the system is a periodic covering of t'Hooft's "cogwheel model". This can be viewed as a cellular automata in much the same way as Conway's Game of Life on pixels in a square lattice in the plane 

$$\mathbb{Z}^2 \subset \mathbb{R}^2.$$

Our model allows for $$m = k|Q_0|$$ possible state (rather than just on/off in Conway's case). Here k is the maximal path length of the local cyclic quiver path algebra and also determines the number of sheets in the cyclic covering of t'Hooft's cogwheel. We view this as an $m$-dimensional qudit. We could also think of this as a $|Q_0|$ = $d$-dimensional qudit with phase factors or some variable of a ring separating the sheets of the covering. 

The gluin can then be though of as gluing *"quantum pixels"* together to form a generalized quantum cellular automaton. The gluing will in general not be a lattice but rather a graph cellular embedded in a $2$-dimensional manifold or *Riemann surface* known as a **dessin d'enfant** in number theory and the theory of automorphic representations (we have actions by several groups such as the cyclic groups for local cyclic quivers, loop groups and fibre products of loop groups especially if we do not restrict to maximal length paths on the local cyclic quivers, affine Kac-Moody Lie algebras given by central extensions of those loop groups, a fibre product of unitary groups $\mathbf{U}(n)$, a relative tensor product group where the relative tensor products are determined by certain ring theoretic considerations defined in [Surface Algebras I](https://github.com/The-Singularity-Research/cirq_hybrid_codes/blob/master/Surface_Algebras_I%20(3).pdf), etc.). 

This generalized quantum cellular automaton can be viewed as a finite dimensional cutoff (in the infrared direction if we allow rational functions and use instead Leavit-path algebras or graph C*-algebras, and in the UV direction if we are using the maximal lenght paths to truncate). 

The mathematics of the local picture can be found in the work of [Fargue-Scholze](https://github.com/The-Singularity-Research/local-surface-algebras/blob/main/2102.13459.pdf). The gluing of these algebras then provides the *global picture*.  
