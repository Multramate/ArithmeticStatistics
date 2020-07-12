# Arithmetic Statistics for Elliptic Curves

#### Modelling the Selmer group, the Tate-Shafarevich group, and the Mordell-Weil rank of elliptic curves over number fields

## Information

This repository contains the final report and the presentation slides of an advanced research project in mathematics (M4R) that together constitute my final year master's thesis, which is submitted in partial fulfillment of the requirement for the award of MEng Pure Mathematics and Computational Logic degree of the Department of Computing in Imperial College London.

## Abstract

The Mordell-Weil theorem states that any elliptic curve E defined over a number field K is a finitely generated abelian group, so that E(K) is isomorphic to a direct product of a finite torsion subgroup and a free abelian group of finite rank. Over the rationals, while the torsion subgroup is fully understood from a result by Mazur, the Mordell-Weil rank is much less understood. For instance, it remains an open question if it is bounded above, with a historical belief that it is not, due to much empirical evidence.

A recent probabilistic model proposed by Poonen et al provides theoretical evidence to refute this claim, namely that all but finitely many rational elliptic curves have rank at most 21. Their proposed heuristic is based on modelling Tate-Shafarevich groups using random alternating matrices, and has its grounds in a theorem that a p^e-Selmer group is almost always the intersection of two Lagrangian direct summands of a metabolic quadratic Z/p^e-module of infinite rank, a consequence of standard arithmetic duality theorems.

This project aims to serve as an introduction to the style of arguments in arithmetic statistics by providing a full proof of this result, as well as verifying desired properties of a heuristic that models this result. As a consequence, important predictions on Selmer groups, Tate-Shafarevich groups, and Mordell-Weil ranks can be made, including the conjecture that n-Selmer groups have average size equal to the sum of divisors of n, as well as the folklore conjecture that there are finitely many rational elliptic curves of rank greater than 21.

## Contents

The following is the table of contents as in the final report.

### Introduction
The first chapter introduces some motivation for the main conjecture and the overall structure of the discussion in the report.
1. Motivational background
2. Report structure

### Preliminary background
The second chapter provides ample background on algebraic number theory and arithmetic geometry relevant to the remainder of the report for the reader's convenience.
1. Galois cohomology
    * Group cohomology
    * Non-abelian cohomology
    * Galois cohomology
    * Class field theory
    * Arithmetic duality theorems
2. Elliptic curves
    * Elliptic curves
    * Divisors and linear systems
    * Selmer and Tate-Shafarevich groups
    * Twists and torsors
    * Arithmetic duality theorems

### Modelling Selmer groups
The third chapter details a heuristic proof for the main conjecture by constructing a linear algebraic model for Selmer groups supported by arithmetical evidence.
1. Quadratic modules
    * Definitions
    * Examples
2. Arithmetic of Selmer groups
    * Non-degeneracy of the local quadratic module
    * Lagrangian submodules and weak metabolicity
    * Triviality of the first Tate-Shafarevich group
    * Direct summands and strong metabolicity
    * Ubiquity of surjective Galois representations
3. Model for Selmer groups
    * Lagrangian Grassmannians
    * Combinatorial linear algebra
    * Sizes of Lagrangian Grassmannians
    * Average sizes of Selmer groups
    * Freeness of the ambient module

### Heuristic consequences
The fourth chapter concludes the report by applying the heuristic arguments to predict the distribution of Tate-Shafarevich groups and Mordell-Weil ranks.
1. Modelling short exact sequences
2. Modelling Tate-Shafarevich groups
3. Modelling Mordell-Weil ranks

## Acknowledgements

I would like to express my sincere gratitude to everyone who have supported me academically and socially during the two months of report writing, as well as throughout my four years in Imperial.

In particular, I would like to thank Professor Johannes Nicaise for introducing me to the arithmetic of elliptic curves in a summer research project two years ago. His willingness to supervise me and the few conversations we had were very encouraging to my early mathematical career, and I have since delved deeper into the area and developed a keen research interest.

Moreover, I would like to thank Dr David Helm for introducing me to the machinery of Galois cohomology as applied to class field theory in a summer research project last year. Despite being busy, he was willing to meet me in the afternoons every week, and we engaged in many enthusiastic conversations on a broad range of number-theoretic ideas, albeit only at a high-level. His insights and viewpoints have since solidified my thoughts and improved my mathematical maturity.

Furthermore, I would like to thank my current project supervisors Professor Toby Gee and Professor Alexei Skorobogatov for their support and guidance throughout the duration of the research project. I had several doubts about the scope of the material early on, and some ideas I could not follow, but they clarified all of them in great detail through office hours and email exchanges.

Additionally, I would like to thank Mr Stephen Diehl and Adjoint UK Ltd for providing me with a summer internship opportunity last year on pairing-based elliptic curve cryptography. It was a very enjoyable experience working with number theory in Haskell, which helped me appreciate the existence of applications of pure mathematics outside of academia.

Last but not least, I would also like to thank all of my colleagues whom I have had intellectual discussions with, including Christopher Burns, Alberto Centelles, Jiang Wei, and Wu Peiran, who have all helped me one way or another in this project. I am especially grateful to Wu Peiran who did a thorough proofreading of my report, even after the submission deadline.

## Miscellaneous

I attached the slides to a twenty-minute presentation on the overall theme of the project as a gentle introduction to my report.