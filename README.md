# local-surface-algebras
Studying finite dimensional quotients of cyclic quivers and surface algebras
---
Taking quotients by paths of some maximal length $n$ of the cyclic quivers as described in [The Composition Algebra of a Cyclic Quiver](https://github.com/The-Singularity-Research/loac-surface-algebras/blob/main/15988304.pdf) we get finite dimensional algebras. A gluing
of a collection of such algebras according to the methods described in [Surface Algebras I](https://github.com/The-Singularity-Research/cirq_hybrid_codes/blob/master/Surface_Algebras_I%20(3).pdf) we obtain a finite dimensional surface algebra. Finite dimensional surface algebras and their representation theory can be studied using GAP and in particular the package [QPA](https://www.gap-system.org/Manuals/pkg/qpa/doc/chap0.html#contents) for quiver [path algebras](https://www.gap-system.org/Manuals/pkg/qpa/doc/chap4.html). We will call the cyclic quivers in the gluing *"local surface algebras"* and the algebras obtained from their gluings **"Finite Dimensional Surface Algebras"**. The Finite Dimensional Surface Algebras will have gentle relations corresponding to crossing over from one local cyclic quiver path algebra to another, along with the additional relations given by the quotient by paths of some maximal length on each cycle. The maximal length paths will in general be different for each local cyclic path algebra. Moreover, we can think of this as a generalization of G. t'Hooft's cyclic harmonic oscillators in his [Cellular Automata Approach to Quantum Mechanics](https://github.com/The-Singularity-Research/local-surface-algebras/blob/main/1405.1548.pdf) (see p. 23 of the arXiv version). See also the following lectures:

-[Lecture 1](https://www.youtube.com/watch?v=F3hPvusB0ds)

-[Lecture 2](https://www.youtube.com/watch?v=d2R9cbttqBY)

-[Lecture 3](https://www.youtube.com/watch?v=a7xw0p4WfDs)

Our generalization allows for high energy levels by allowing for returning to a vertex of the quiver (corresponding to a simple module of the path algebra in the Ringel paper) so that the system is a periodic covering of t'Hooft's "cogwheel model". This can be viewed as a cellular automata in much the same way as Conway's Game of Life on pixels in a square lattice in the plane 

$$\mathbb{Z}^2 \subset \mathbb{R}^2.$$

Our model allows for $$m = k|Q_0|$$ possible state (rather than just on/off in Conway's case). Here k is the maximal path length of the local cyclic quiver path algebra and also determines the number of sheets in the cyclic covering of t'Hooft's cogwheel. We view this as an $m$-dimensional qudit. We could also think of this as a $|Q_0|$ = $d$-dimensional qudit with phase factors or some variable of a ring separating the sheets of the covering. 

The gluin can then be though of as gluing *"quantum pixels"* together to form a generalized quantum cellular automaton. The gluing will in general not be a lattice but rather a graph cellular embedded in a $2$-dimensional manifold or *Riemann surface* known as a **dessin d'enfant** in number theory and the theory of automorphic representations (we have actions by several groups such as the cyclic groups for local cyclic quivers, loop groups and fibre products of loop groups especially if we do not restrict to maximal length paths on the local cyclic quivers, affine Kac-Moody Lie algebras given by central extensions of those loop groups, a fibre product of unitary groups $\mathbf{U}(n)$, a relative tensor product group where the relative tensor products are determined by certain ring theoretic considerations defined in [Surface Algebras I](https://github.com/The-Singularity-Research/cirq_hybrid_codes/blob/master/Surface_Algebras_I%20(3).pdf), etc.). 

This generalized quantum cellular automaton can be viewed as a finite dimensional cutoff (in the infrared direction if we allow rational functions and use instead Leavit-path algebras or graph C*-algebras, and in the UV direction if we are using the maximal lenght paths to truncate). 

The mathematics of the local picture can be found in the work of [Fargue-Scholze](https://github.com/The-Singularity-Research/local-surface-algebras/blob/main/2102.13459.pdf) on the *"Geometrization of the Local Langlands Correspondence"*. The gluing of these algebras then provides the *global picture*. 

We may then study rulesets for cutting and gluing dessins d'enfants (or equivalently generalized quantum cellular automata) by methods developed recently by Matilde Marcolli on [Graph Grammars](https://github.com/The-Singularity-Research/local-surface-algebras/blob/main/GraphGrammars.pdf). 

Once we have more observational data from the James Webb space telescope, we can apply $2$-parameter [persistent homology](https://github.com/The-Singularity-Research/TDA-Entanglement) using a dynamic $2$-paramemeter version of a *"density based scan"* or [DB-scan](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html) to study the topological properties of cosmic microwave background radiation. This will provide a way of understanding the multi-scale entanglement structure of our local observable universe. We may look at the emergent structures at multiple scales and decompose the generalized quantum celllar automata present in the observed data to deduce a semantic graph structured understanding of the horizon of the local observable universe in the cosmic microwave background. From this, we may deduce what structures and complex physics is on the *other side* of the horizon of our observable universe. This can be seen as a generalization of the $1$-paramemeter case studied in [Persistent Topology of Syntax](https://github.com/The-Singularity-Research/local-surface-algebras/blob/main/PersistentTopologySyntax.pdf) assuming we have an appropriate understanding of the graph grammar and syntax of the cosmic microwave background. 

We will call this horizon a *cosmic microwave veil* or simply a *veil*. Such veils are present at all scales, and are more noticeable when one considered strength of entanglement as the fundamental measure of distance in the univers, from which distances in percieved space and time in traditional Minkowski spacetime $\mathbb{R}^{3+1}$. This approach would provide applications of quantum computing and quantum information processing to potentially decipher,  communicate, and visit observable universes beyond the veils we typically encounter. At a *"human"* scale this could produce new insights into neuroscience and *"quantum telepathy"*. See for example the following Githubs

-[Quantum-Pseudo-Telepathy](https://github.com/Strilanc/Quantum-Pseudo-Telepathy)

-[Winning The Game of Magic Square with Quantum Pseudo-Telepathy](https://github.com/qiskit-community/qiskit-community-tutorials/blob/master/terra/qis_adv/quantum_magic_square.ipynb)

Although entanglement is seen as something of a mystery, the mathematics underlying surface algebras gives a number theoretic implication and description of entanglement as a fundamental property and as something that is naturally encoded and decoded by emergent intelligences. Perception of p-adic geometries and group equivariance in "observed" physical phenomena can be seen as fundamental to developing perceptions of entanglement and quantum telepathy. 

## Continuum Limits and Periodic Truncation
---
We also note that there are multiple ways to understand infinite energy levels. For a periodic (cyclic) harmonic oscilator a la t'Hooft, we can allow for multiple cycles around the cogwheel before returning to our initial starting state via quotients of the path algebra by paths of some maximal allowable length. This [video](https://www.youtube.com/watch?v=a7xw0p4WfDs&list=RDLVa7xw0p4WfDs&start_radio=1&rv=a7xw0p4WfDs&t=131) describes a single trip around an cyclic harmonic oscillator of period $11$. However, if we allow for paths of length $22$ for example, we can make two full trips around the cogwheel. We can also take continuum limits. However, if the conintuum limit is always taken with respect to some rational angles, we will only ever obtain *rational rotation algebras* locally (which can also be made into cyclic graph C*-algebras or Leavitt path algebras depending on the context and applications). The path algebra of a corresponding quiver for each such circle would then be of type $\mathbb{A}_{\infty}$. If we wish to obtain a continuum limit for an irrational rotation algebra this will provide noncommutative geometric structures locally (and globally after gluing). 

Definining the gluing of circles in such a way as to accomodate this irrational rotation algebra and its corresponding noncommutative geometry is crucial to defining and accurate model of quantum mechanics locally and globally, something not addressed by t'Hooft. Gluing such noncommutative local structures should provide a new construction of (noncommutative) foliations of Riemann surfaces equivalent to the foliations defined by A. Connes in [Noncommutative Geometry](https://alainconnes.org/wp-content/uploads/book94bigpdf.pdf). We would glue a circle with equivalence classes of points defined by some irrational rotation for example, to another such circle, at points or intervals where the noncommutative structure is respected. This would require one of the following, 

1. Gluing at single points of an equivalence class, or

2. Gluing along intervals of circles with irrational rotation angles which are compatible, i.e. multiples of one another by some rational coefficient. 

3. We could also think of gluing a circle to itself in a similar way along points or intervals. 
