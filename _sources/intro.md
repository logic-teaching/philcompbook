# Philcomp

## Aims and goals

This is an overview of philosophy of computation. We are going to starts with founding figures of Turing, Church, and Kleene and look at different conceptual analyses of computation (bounded and local search, beta reduction of lambda terms) which are related to the different models of computation (Turing machines, lambda calculi). Then we're going to look at effects of natural non-computability (Gödel's disjunction) and the non-computability of methods of verification (Rice's theorem). Then we're going to do topics such as:

- the apparent absoluteness of computation
- the confluence of different models of computation
- nature of feasibility (what is the intuitive notion)
- how semantics for procedures differs from semantics for indicative statements
- neural network models and its relation to computational theory of mind
- models of learning and its relation to reliability of inductive methods
- how computer learning is apparently different than human learning
- how fairness and explanation of machine learning methods can be assessed
- the physical implementation of computation and challenges from quantum computation.

## Prerequistes

This course does not presuppose any prior familiarity with the theory of computation or with programming. In terms of prior knowledge, this is structured so that its topic is to computation roughly what medical ethics is to medicine. Everyone should be able to get a lot out of it, due in part to the ubiquity of computation in our everyday lives. We will use the historical development to orientate the discussion.  

## Acknowledgements

Thanks to the wonderful students in [UCLA's Phlios 128 in Spring 2024](https://bruinlearn.ucla.edu/courses/186473) for their feedback on this material. This material owes a lot to my advisors [Peter Cholak](https://math.nd.edu/people/faculty/peter-cholak/) and [Mic Detlefsen](https://dailynous.com/2019/10/23/michael-detlefsen-1948-2019/), from whom I first learned the theory of computation and the philosophy of mathematics which primarily orientates my own thinking about these questions.

## Code and examples

Philosophy works best when there are good examples at play to motivate a position or to assess a position. And it is all the better when it is easy for everyone, with just a little bit of time and creativity, to come up with the examples. The recent popularity of python has made coming up with worked out examples easier than ever. Hence, there are many bits of python code and other code scattered throughout the text, mostly to illustrate key ideas with nice graphics, but also to provide an easy way to work out specific examples. 

For the python code, one can:

- click on the <i class="fa fa-rocket" aria-hidden="true"></i> icons at the top center-right of each chapter page, which will launch the page in a [binder](https://mybinder.org) which does not require you to install anything on your machine (but you won't be able to save anything)

Or one can just copy and paste the code into your favorite Python interpreter and run it. There are lots of easy ways to run python these days, including the following:

- [Programiz](https://www.programiz.com/python-programming/online-compiler/) (no set-up required; but don't use this if you want/need to easily save)
- [UCLA Jupyterhub](https://jupyter.idre.ucla.edu/hub/login?next=%2Fhub%2F) (virtually no set-up required; but requires UCLA sign on; your institution probably has Juptyerhub)
- [Anaconda Navigator](https://www.anaconda.com/anaconda-navigator) (requires about an hour to set up; for use on desktop machines; just watch some youtube videos if you need help getting started). Anaconda also has come out with [a web based platform](https://www.anaconda.com/), but I have less experience with this.

For the other kinds of code that show up, there is link to some an online interpeter given where possible and one can just cut and paste the code.

## Outline

The rough plan is as follows, where each Chapter corresponds to a lecture. There is a reference given which gives one a little sense of what we are going to look at.

Chapter 1: recursion in the 20s, primitive recursion and Skolem {cite}`Skolem1923-bb` {cite}`Skolem1967-du`, 

Chapter 2: recursion in the 20s, Hilbert and BHK {cite}`Hilbert1926-kk`, {cite}`Hilbert1967-ng`, {cite}`Brouwer1981-fb`, {cite}`Heyting1956aa`, {cite}`Heyting1931aa`

Chapter 3:  Turing machine model, boundedness and locality conditions. {cite}`Turing1937-ep`, {cite}`Sieg2009-xd`, {cite}`Gandy1980-xt`

Chapter 4: Some non-computable sets and some reducibilities. {cite}`Kolmogorov1932aa`, {cite}`Kolmogorov1998aa`, {cite}`Jenny2018-xh`

Chapter 5: Untyped lambda calculus, origin story of LISP and scheme; computation as reduction. 

Chapter 6: Curry-Howard isomorphism and proof verification; a glance at Lean. {cite}`Gallier1995-yf`

Chapter 7: Church-Turing thesis, confluence arguments, conceptual analysis vs. Carnapian explication. {cite}`Gandy1988-ib`, {cite}`Kleene1952-jt`

Chapter 8: Absoluteness of computation vs. relativity of proof; Godel's disjunction. {cite}`Godel1990-xe`, {cite}`Godel1995-cc`

Chapter 9: Feasibility and why philosophers should care about it. {cite}`Aaronson2013-ek`

Chapter 10: What programs mean: denotational. {cite}`Scott1971-jz`, {cite}`Winskel1993-ib`

Chapter 11: What programs mean: operational. {cite}`Turner2007-ue`, {cite}`Pierce2002-qb`

Chapter 12: Neural networks. {cite}`Siegelmann2012-ol`

Chapter 13: Computational theory of mind. {cite}`Edelman2008-fa`

Chapter 14: Vapnik on statistical learning theory. {cite}`Vapnik1998-bz`, {cite}`Vapnik2000-by`

Chapter 15: Harman on machine learning. {cite}`Harman2012-so`, {cite}`Kulkarni2011-ff`

Chapter 16: Buckner on deep learning, Dehane on human learning. {cite}`Buckner2024-pj`, {cite}`Dehaene2021-cs`

Chapter 17: Machine learning fairness. {cite}`Barocas2023-bi`

Chapter 18: Explanations and AI. {cite}`Molnar2022-sd`

Chapter 19: Physical computation. {cite}`Shagrir2022-oh`, {cite}`Piccinini2015-vn`

Chapter 20: Challenges from quantum computation. {cite}`Nielsen2011-sp`