# What is physics?

Physics is the *direct* study of reality itself. It's predicated on [mathematics](https://github.com/rossgk2/naturalphilosophy), that understanding of the abstract rules which govern all other rules, but goes further, searching for the discovery of deep, compelling reasons, or *laws*, that explain why phenomena- like the ripples of water in a pond- happen the way they do.

Since mathematics allows for the possibility of *all* physical worlds, it is always necessary to make some basic assumption about the nature of *our* reality when postulating the universal laws of Nature. A fact about our reality cannot be derived from ignorance of our reality. Something cannot come from nothing.

## Classical physics

In the late 1600s, [Isaac Newton](https://en.wikipedia.org/wiki/Isaac_Newton) formalized an assumption about our reality and presented humanity's first resoundingly successful theory of Nature. Reinterpreted from the modern point of view, Newton's core assumption is that a certain *quantity of motion* is conserved. His theory, *Newton's laws*, essentially consist of defining *force* as that which changes the quantity of motion, and leads to concepts like *momentum*, *energy*, *torque*, *voltage*, and *power*.

Two hundred years later, in the early 1900s, [Emmy Noether](https://en.wikipedia.org/wiki/Emmy_Noether) came up with a hint at a deeper reason for why Newton's assumption is true. She proved that if we assume the laws of physics take a certain form, and if we assume these laws are the same at every location in the universe, it follows that Newton's quantity of motion must be conserved[^2], thus justifying referring to Newton's quantity of motion as a "quantity of motion".

[^2]: If space is translationally invariant then momentum is conserved.

In some sense, Noether discovered the fundamental reason why Newton's laws are true, for if one is somehow lucky enough to divine the incredibly complicated formula Noether came up with, as a fundamental truth that precedes everything else, then yes, Newton's laws do follow. But if we're being more honest, we admit that Noether's insight is only reasonably discovered by first assuming Newton's laws. Nother's theorem, as it's called, is thus a beautiful *reinterpretation* of physics, not quite the *explanation* we wish for.

The question becomes: "Can we find a reason other than Newton's laws for why the laws of physics take the particular form they do in Noether's law?" Or even "Why must the laws of physics be the same everywhere?" 

Well, something cannot come from nothing. And there is clearly something. So I must advise anyone who pursues this line of questioning: you will *never* get a final answer. But, at the same time, I will also say: there is nothing wrong with that!

## Modern physics

Also in the early 1900s, humans had been investigating electromagnetism and finding extreme situations in which Newton's assumption did not hold. The assumption- that a certain quantity of motion is conserved- broke down for extremely fast things and extremely small things.

In 1905, to explain **extremely fast things**, [Albert Einstein](https://en.wikipedia.org/wiki/Albert_Einstein) replaced Newton's assumption with a new one[^3], leading to [a new theory](https://en.wikisource.org/wiki/On_the_Electrodynamics_of_Moving_Bodies_(1920_edition)) that elegantly encapsulates Newton's old theory when we return to the familiar scenario of lower speeds. Einstein's theory informs us that reality is not so intuitive as we thought: time passes significantly more slowly for quickly moving observers than it does for stationary ones, and from the perspective of a quickly moving observer, lengths of stationary objects become actually, physically contracted along the direction of motion to a significant extent. Thus, time and space depend on one's perspective. Since time and space must be considered *relative* to the point of view, the theory is called *special relativity*. 

[^3]: The speed at which light travels is the same no matter what reference frame the traveling light is observed from.

The theory of special relativity also shows that time and space are really not as different as we might think, and are best thought of as both being spatial dimensions. This is where the term *spacetime* comes from.

Ten years later in 1915, to explain what underlies **the mysterious "action-at-a-distance" force of gravity**, Einstein introduced yet another new assumption, resulting in the [theory of *general relativity*](https://en.wikisource.org/wiki/Translation:The_Field_Equations_of_Gravitation), which describes how mass curves spacetime to induce gravity. In the zero-mass case of general relativity, we reobtain special relativity, much like how in the low speed case of special relativity, we reobtain Newton's laws.

To explain **extremely small things**, different physicists (Heisenberg & Born in summer 1925, Schrodinger in winter 1925, and Feynman in 1941) actually came up with *three* different assumptions to resolve observed contradictions of Newton's laws. All three assumptions are equivalent. Each independently leads to a theory that predicts Nature is inherently random and that energy is *quantized* (i.e. there is a smallest unit of energy that cannot be divided into smaller bits): the theory is called *quantum mechanics* after this second result. Of course, when the number of particles considered by quantum mechanics is large, Newton's laws are reobtained.

To take a step towards **unifying the theories of the extremely fast (special relativity) and the extremely small (quantum mechanics)**, Paul Dirac introduced *quantum field theory* (QFT) in 1928, which assumes that all particles are actually localized excitations of a field (like an electromagnetic field). The theory was plagued by intractable infinite values for two decades, until physicists figured out an implementation of QFT that actually worked, called *quantum electrodynamics* (QED) in the late 1940s.

But to this day, **quantum mechanics is in apparent conflict with general relativity**. The next great leap in physics would be to figure out a *grand unification theory* to resolve the conflict between the results of those theories.

## Philosophically connecting with physics

Physical theories superseding Newton's laws- special relativity, general relativity, and quantum mechanics- are collectively referred to as *modern physics*, while Newton's laws are sometimes called *classical physics*.

Modern physics is wonderful, but bizarre, so bizarre that it's easy to forget that the theories of modern physics truly describe *what's actually happening in the real world*. (Yes, time really does slow down from the perspective of moving observers. Yes, it is truly impossible to know both the position and velocity of a particle.)

Classical physics, on the other hand, while by no means easy, is stumbled upon every day when your average person ponders the world around them. Its assumptions are so intuitive that it would take active thought for a non-physicist to believe anything else! Because it's so instinctual, and was our species' first attempt at an organized mathematical understanding of the world around us, spending a good amount of time thinking deeply about Nature in the intuitive classical way, even (or especially) after one has attained the requisite mathematical skill to approach modern physics, feels a certain kind of rewarding.

It's my belief that one has to follow this historical path before they can truly understand modern physics. Otherwise, modern physics just feels like science fiction.

# This repository

Unfortunately, most textbooks on modern physics obscure what should be a profound intellectual journey by blurring the lines between assumptions and definitions... and sometimes even facts. When it comes to facts, physics texts do tend to be better than their pure math counterparts about deriving facts over the course of a narrative, rather than treating them as mere items on a to-do list to be [conjectured-and-proved](https://github.com/rossgk2/physmath?tab=readme-ov-file#specifics-of-pedagogy), but the later still sometimes does happen. (The "work-energy theorem" is often conjectured-and-proved as a result of facts being presented out of order, when it can be as simple as defining the kinetic energy of a particle to be the total work done on a particle by all forces, and then computing the integral to obtain the usual formula $\frac{1}{2}mv^2$.)

So that students can walk the journey they deserve, I've created a minibook on classical physics. 

While the minibook on classical mechanics is the main content of this repository, I've also included my notes on special relativity, which are much shorter, but should also be pretty helpful.

## Minibook on classical physics

Other books on classical physics introduce the fundamental notions (force and inertial reference frames) quickly, by leaning on the crutch of handwavy intuition. This minibook aims to elucidate things which are glossed over by such approaches, and which are even obscured in Newton's original statement of his laws. In the minibook...

* We begin everything with the axiom that total momentum is conserved in isolated systems.
* We *don't* start things off with the definition of unbiased perspectives (inertial reference frames), as this begs the question "How would you know to expect that perspectives can be biased?''
* **We explain why $\mathbf{F}_{\text{tot}} = m\frac{d^n\mathbf{x}}{dt^n}$, where $n = 2$, is the proper definition of force, and why no other $n$ works.** 
  * In the course of doing so, we explain how sometimes even experienced physicists attempt to justify proving the law of conservation of momentum as the consequence of a definition, thus trying to conjure something from nothing- which can't be done! (When physicists seem to have successfully conjured something from nothing in this case, it is only because they have unwittingly, very subtly, assumed that the systems we *perceive* to be isolated are actually indeed isolated systems.)
* We certainly don't immediately and with no explanation assert that unbiased perspectives travel with constant velocity relative to each other. Instead, we take the experimental truth which is really at the heart of things- the law of conservation of momentum- as axiom, use this truth to derive that there do indeed exist unbiased perspectives, characterize them, and thus derive that unbiased perspectives travel with constant velocity relative to each other.

After the minibook gives an improved presentation of Newton's laws, we present the original Newton's laws (and definitions, which are too commonly forgotten!) for comparison. It's awe-inspiring and humbling to think about Newton grappling directly with the nature of reality as humans were just starting to get a sense of mathematics. Now, we may stand on the shoulders of his Giant.

### Sections after the discussion of Newton's laws

There are a couple more sections after the several on Newton's laws:

* Energy
  * This section does a good job of showing how the definition of kinetic energy naturally arises, rather than using the [conjecture-and-prove method](https://github.com/rossgk2/physmath?tab=readme-ov-file#specifics-of-pedagogy) which is usually used to explain it. 
* Rotational dynamics
  * This section has my thoughts on various ways to derive the definition of torque in a first-principles, not pedagogically circular way.
* Analytical mechanics
  * In this section I describe the typical unmotivated approach of randomly claiming that the integral of $T - U$ is minimized by Nature, and how there is a better approach: derive a scalar equivalent to the vector equation that is Newton's second law, called d'Alembert's principle; then change coordinates, derive the differential Euler-Lagrange equations; then derive that the integral of $T - U$ is minimized.
* Discovering special relativity

## Notes on special relativity

My notes on special relativity describe how to arrive at the core theoretical tool of special relativity, which is an inner product space with inner product, called *the Minkowsi metric*, inducing the norm $||(ct, x, y, z)|| = (ct)^2 - ||(x, y, z)||^2$. Usually, explanations of special relativity start by assuming the Minkowski norm as a given, and thus obscure the core intuition of the theory.