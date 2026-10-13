---
layout: home
cover-img: /assets/images/coriolis3.jpg
carousels:
  - images: 
    - image: /assets/images-cermics/image1.jpg
    - image: /assets/images-cermics/image6.jpg
    - image: /assets/images-cermics/image2.jpg
    - image: /assets/images-cermics/image4.jpg
    - image: /assets/images-cermics/image7.jpg
    - image: /assets/images-cermics/image8.jpg
---

{% include cermics-home.html %}

<img src="{{ '/assets/images/jpc.jpg' | relative_url }}"
     alt="Jean-Philippe Chancelier"
     style="float: right; width: 150px; margin: 0 0 20px 20px;" />
<p style="text-align: justify;">
  Researcher at <a href="{{ cermics }}">CERMICS</a> in the
  <a href="{{ cermics }}/optimization">Optimization</a> team and Professor at
  <a href="https://ecoledesponts.fr/">École Nationale des Ponts et Chaussées</a>.
</p>
<div style="clear: both;"></div>

### Research Themes

 - 2024 onwards: formal proofs, a new direction. Coq-checked proofs of
   conditional separation and of the Sands–Sauer–Woodrow theorem.

 - 2020 onwards: information structures, games and causality with M. De Lara and
   B. Heymann. This includes Kuhn's equivalence theorem (Games and Economic
   Behavior 2022), conditional separation and causal inference.

 - 2019 onwards: tropical (min-plus) dynamic programming with M. Akian and
   B. Tran (CDC 2019, MTNS 2022, Annals of OR 2025).

 - 2019 onwards: generalized convexity and sparsity with Michel De Lara, Seta
   Rakotomandimby, Adrien Le Franc, Antoine Deza and Lionel Pournin. Capra
   conjugacies and the ℓ<sub>0</sub> pseudonorm with M. De Lara, five of them in
   the Journal of Convex Analysis. This work extends
   to the geometry of norms (submitted to JMLR) and to machine learning
   (Fitzpatrick losses, NeurIPS 2024).

   <details>
   <summary>More on Capra conjugacies and the ℓ<sub>0</sub> pseudonorm</summary>
   <p style="text-align: justify;">
   The ℓ<sub>0</sub> pseudonorm counts the nonzero entries of a vector and is
   central to exact sparse optimization. As its Fenchel biconjugate is zero,
   classical convex analysis fails. Instead, we develop a generalized convexity
   based on Capra (Constant Along Primal RAys) couplings, built from a source
   norm. We introduce orthant-strictly monotonic norms (e.g. ℓ<sub>p</sub>,
   1 &lt; p &lt; ∞) together with generalized top-k and k-support norms. With
   these, we prove that ℓ<sub>0</sub> is Capra-convex, that is, equal to its
   Capra-biconjugate, when the source norm and its dual are orthant-strictly
   monotonic. Surprisingly, ℓ<sub>0</sub> then coincides, on the unit sphere of
   the source norm, with a proper convex lower semicontinuous function ("hidden
   convexity"). Capra conjugates and subdifferentials yield variational
   formulations and new norm-ratio lower bounds for ℓ<sub>0</sub>. We also cover
   a unified theory of polarity for functions, the geometry of k-support dual
   norms promoting k-sparse solutions, the characterization of Capra-convex
   sets, and a convergent Capra-cutting plane method for ℓ<sub>0</sub>
   minimization. Finally, H0-couplings extend the approach to all 0-homogeneous
   functions and yield their best convex lower envelopes, in particular for
   ℓ<sub>0</sub>.
   </p>
   </details>

 - 2018 onwards: multistage stochastic optimization and decomposition with
   Pierre Carpentier, Guy Cohen, Michel De Lara and PhD students.

   - Methods: SDDP bounds, decomposition (spatial, temporal, time blocks,
     two time scales) and time consistency.
   - Applications: hydro valleys, microgrids, a subway station, energy
     storage, hydrogen, maintenance, reservoirs, intraday markets and
     low-thrust space trajectories.

   <details>
   <summary>More on multistage stochastic optimization and decomposition</summary>
   <p style="text-align: justify;">
   A first theme is the framing of such problems: information structures,
   non-anticipativity, risk. A second theme is decomposition–coordination:
   splitting large problems along time, scenarios or space. We combine these
   decompositions, for instance spatial coordination with dynamic programming.
   Time-block decomposition lets us handle two-time-scale problems with hundreds
   of thousands of stages. Price and resource coordination give upper and lower
   bounds on the optimal cost, and policies usable online. We also study time
   consistency, chance constraints, and the differentiability of value
   functions. Our energy applications include unit commitment, hydro valleys,
   multi-usage dams and urban microgrids. They also include battery aging and
   renewal, braking-energy storage in subways, and home solar with storage. We
   assess our methods by simulation against model predictive control.
   </p>
   </details>

 - Ongoing: scientific software, Nsp and ScicosLab, with François Delebecque,
   Ramine Nikoukhah, Bruno Pinçon and others. Nsp is a GPL scientific computing
   environment, a complete rewrite of ScilabGtk; ScicosLab is its Scilab 4 based
   predecessor and the reference software of the book *Modeling and Simulation
   in Scilab/Scicos with ScicosLab 4.4* (Springer, 2010). See the
   [Nsp]({{ '/nsp' | relative_url }}) page for details. Related work: a
   Premia/Nsp parallel benchmark (2010), Scicos code generation (2015) and
   Simulink→Modelica translation (Modelica Conference 2019).

 - 2002–2013: stochastic control, finance and fixed points.

   - Impulse control and optimal stopping (with Øksendal and Sulem), and
     risk-sensitive portfolio optimization.
   - Single-author papers on iterative schemes for nonexpansive mappings
     (JMAA, Nonlinear Analysis).
   - Foundations of stochastic optimization: measurability constraints
     (SIAM J. Optim. 2009) and dynamic consistency.
   - Risk-averse bandit problems (Transportation Science).

 - 1994–1998: PDE models in water engineering.
   Settling-tank models, mostly with M. (Cohen) De Lara and F. Pacard,
   published in SIAM J. Appl. Math., M3AS, CRAS and Water Research
   (3 papers). Also tracing river pollution sources and hydro scheduling
   by decomposition.

 - 1986–1990: computer algebra for control.
   The Pandore expert system, with Jean-Pierre Quadrat, Agnès Sulem and
   Claude Gomez. It generated Fortran and LaTeX code automatically (Macrofort,
   Macrotex) and wrote reports on stochastic control problems.
