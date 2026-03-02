# Physics

This main content of this physics repository is a minibook on classical physics. I've also included my notes on special relativity, which are much shorter, but should also be pretty helpful to the beginner :)

## Classical physics

Other books on classical physics introduce the fundamental notions (force and inertial reference frames) quickly, by leaning on the crutch of handwavy intuition. This minibook aims to elucidate things which are glossed over by such approaches, and which are even obscured in Newton's original statement of his laws:

* I begin everything with the axiom that total momentum is conserved in isolated systems.
* I *don't* start things off with the definition of unbiased perspectives (inertial reference frames), as this begs the question "How would you know to expect that perspectives can be biased?''
* **I explain why $\mathbf{F}_{\text{tot}} = m\frac{d^n\mathbf{x}}{dt^n}$, where $n = 2$, is the proper definition of force, and why no other $n$ works.** 
  * I explain how one trap that even experienced physicists fall into is assuming as axiom that the systems we *perceive* to be isolated are actually indeed isolated systems. This axiom is often unwittingly assumed when the law of conservation of momentum is attempted to be proven to be a consequence of a definition. That can't be done! The law of conservation of momentum is best seen to be the fundamental axiom from which all other concepts emerge.
* I certainly don't immediately and with no explanation assert that unbiased perspectives travel with constant velocity relative to each other. Instead, I take the experimental truth which is really at the heart of things- the law of conservation of momentum- as axiom, use this truth to derive that there do indeed exist unbiased perspectives, characterize them, and thus derive that unbiased perspectives travel with constant velocity relative to each other.

After I give an improved presentation of Newton's laws, I present the original Newton's laws (and definitions, which are too commonly forgotten!) for comparison. I find them extremely interesting. It's awe-inspiring and humbling to think about Newton grappling directly with the nature of reality as humans were just starting to get a sense of mathematics. Now, we may stand on the shoulders of his Giant.

### Sections after the discussion of Newton's laws

There are a couple more sections after the several on Newton's laws:

* Energy
  * This section does a good job of showing how the definition of kinetic energy naturally arises, rather than using the [conjecture and prove method](https://github.com/rossgk2/physmath?tab=readme-ov-file#specifics-of-pedagogy) which is usually used to explain it. 
* Rotational dynamics
  * This section has my thoughts on various ways to derive the definition of torque in a first-principles, not pedagogically circular way.
* Analytical mechanics
  * In this section I describe the typical unmotivated approach of randomly claiming that the integral of $T - U$ is minimized by Nature, and how there is a better approach: derive a scalar equivalent to the vector equation that is Newton's second law, called d'Alembert's principle; then change coordinates, derive the differential Euler-Lagrange equations; then derive that the integral of $T - U$ is minimized.
* Discovering special relativity

## Special relativity

My notes on special relativity describe how to arrive at the core theoretical tool of special relativity, which is an inner product space with inner product, called *the Minkowsi metric*, inducing the norm $||(ct, x, y, z)|| = (ct)^2 - ||(x, y, z)||^2$. Usually, explanations of special relativity start by assuming the Minkowski norm as a given, and thus obscure the core intuition of the theory.