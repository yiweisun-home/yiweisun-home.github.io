---
permalink: /research/
toc: false
classes: wide
---

My research aims to understand how to draw credible conclusions from data under more realistic assumptions, with particular emphasis on extrapolation and external validity. I am interested in using credible econometric methods to provide reliable empirical evidence for program evaluation and policy making.

## Working Papers

- **Sensitivity Analysis for Difference-in-Discontinuities Designs** \
(draft available soon)
    <details>
    <summary>Abstract</summary>
    <p>
  	Difference-in-discontinuities (DiDC) designs aim to identify the local effect of a treatment introduced at a cutoff that also determines exposure to a confounding policy by differencing the pre-treatment regression discontinuity and the post-treatment regression discontinuity, under the assumption that the effect of the confounding policy at the cutoff remains constant over time. We establish identification results under relaxation of this restriction when there are multiple pre-treatment periods. We  show that we can leverage the vector of period-specific RD estimands to impose restrictions on the evolution of the counterfactual discontinuity based on its observed pre-treatment path, following the sensitivity framework developed in the Difference-in-Difference literature. The resulting identified sets nest the conventional point-identified estimands as special cases. We propose an estimation and inference procedure for the identified set and show its practical usefulness through simulation. 
    </p>
    </details>

- **Externally Valid Selection of Experimental Sites via the k-Median Problem** (2026) \
  with [José Luis Montiel Olea](https://joseluismontielolea.com), [Brenda Prallon](https://brendaprallon.github.io), [Chen Qiu](https://sites.google.com/view/chen-qiu), and [Jörg Stoye](https://stoye.economics.cornell.edu) \
  <span style="font-size:0.8em;">Revision Requested at *JPE:Micro* </span> \
  <span style="font-size:0.8em;">Extended abstract in *Proceedings of the 26th ACM Conference on Economics and Computation (EC'25)*</span> \
  [[`arXiv`](https://arxiv.org/abs/2408.09187)] | [[`EC'25`](https://dl.acm.org/doi/10.1145/3736252.3742590)]
  <details>
  <summary>Abstract</summary>
  <p>
  We present a decision-theoretic justification for viewing the question of how to best choose
  where to experiment in order to optimize external validity as a k-median problem, a popular
  problem in computer science and operations research. In particular, when treatment effect
  heterogeneity across experimental and policy-relevant sites is substantial (in a sense we make
  precise), we present conditions under which minimizing the worst-case, welfare-based regret
  among all nonrandom schemes that select k sites to experiment is equivalent to solving a
  k-median problem. The connection costs in the relevant k-median problem are given by ex-ante 
  bounds on worst-case voltage effects between sites, and minimizing the sum of worst-case
  voltage effects can be cast as a linear integer program. Two empirical applications illustrate
  the theoretical and computational benefits of the suggested procedure.
  </p>
  </details>
  
- **Extrapolating Away from the Cutoff in Regression Discontinuity Designs** (2025) \
  [[`arXiv`](https://arxiv.org/abs/2311.18136)] (updated draft available upon request)
  <details>
  <summary>Abstract</summary>
  <p>
  Canonical RD designs yield credible local estimates of the treatment effect at the cutoff under mild continuity assumptions, but they fail to identify treatment effects away from the cutoff without additional assumptions. The fundamental challenge of identifying treatment effects away from the cutoff is that the counterfactual outcome under the alternative treatment status is never observed. This paper aims to provide a methodological blueprint to identify treatment effects away from the cutoff in various empirical settings by offering a non-exhaustive list of assumptions on the counterfactual outcome. Instead of assuming the exact evolution of the counterfactual outcome, this paper bounds its variation using the data and sensitivity parameters. The proposed assumptions are weaker than those introduced previously in the literature, resulting in partially identified treatment effects that are less susceptible to assumption violations. This approach accommodates both single cutoff and multi-cutoff designs. The specific choice of the extrapolation assumption depends on the institutional background of each empirical application. Additionally, researchers are recommended to conduct sensitivity analysis on the chosen parameter and assess resulting shifts in conclusions. The paper compares the proposed identification results with results using previous methods via an empirical application and simulated data. It demonstrates that set identification yields a more credible conclusion about the sign of the treatment effect.
  </p>
  </details>

## Peer-Reviewed Publication 

- **Abelian difference sets with the symmetric difference property** (2021) \
  with James A. Davis,  J. J. Hoo, Connor Kissane, Ziming Liu, Calvin Reedy, Kartikey Sharma, Ken Smith \
  <span style="font-size:0.8em;"> *Designs, Codes and Cryptography* </span> \
  [[`Paper`](https://link.springer.com/article/10.1007/s10623-020-00829-5)]
  <details>
  <summary>Abstract</summary>
  <p>
  A (v, k, λ) symmetric design is said to have the symmetric difference property (SDP) if the symmetric difference of any three blocks is either a block or the complement of a block. The designs associated to the   symplectic difference sets introduced by Kantor (J Algebra 33:43–58, 1975) have the SDP. Parker (J Comb Theory Ser A 67:23–43, 1994) claimed that the symplectic design on 64 points is the only SDP design on 64 points admitting an abelian regular automorphism group (an abelian difference set). We show in this paper that there is an SDP design on 64 points that is not isomorphic to the symplectic design and yet admits the group C<sub>8</sub> &times; C<sub>4</sub> &times; C<sub>2</sub> as a regular automorphism group. This abelian difference set is the first in an infinite family of abelian difference sets whose designs have the SDP and yet are not isomorphic to the symplectic designs of the same order. We define a new method for establishing the non-isomorphism of the two families.
  </p>
  </details>
