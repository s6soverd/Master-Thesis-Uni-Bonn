## Measuring the Sensitivity of Parameter Estimates to Estimation Moments In the paper “Testing for Altruism and Social Pressure in Charitable Giving”: A Replication Project
#### Master Thesis, University of Bonn, June, 2022

What is the main driver for the generosity behind charitable giving? The authors (Della Vigna et al., 2010) of the paper “Testing for Altruism and Social Pressure in Charitable Giving” attempts to answer this question by first defining two main motivations behind such generosity, altruism on one side and social pressure on the other side, and by designing a door-to-door fund-raising experiment such that they could gauge which motivation will weigh heavier. Their results suggest that door-to-door fund-raising decreases on average the social welfare, due to welfare-decreasing motives - social pressure. In this thesis work, on top of the implementation of the main results from this paper, a sensitivity analysis is evaluated, by loosening some of the assumptions behind parameter identification, and derivative-based analysis method for Decomposition of Giving is provided.

**Main Conclusions:**

Della Vigna et al. starts off their research with an interesting question of whether giving to charities associated with fund-raising activities increases the welfare of the giver. Although in the paper, different model specifications are tested out, when the parameter estimation uses different sets of moments as inputs as robustness check, no sensitivity analysis or model misspecification is provided. Using the sensitivity formalization in Andrews et al. (2017), I relaxed two assumptions to see whether the parameter in question is overstated /understated. Under the assumption that perhaps, some people might prefer to pay exactly 10 dollar not due to social pressure but due to its being “convenient cash denomination”, just 1% model-violation results in 5% upward bias in social pressure cost parameter. The idea behind this first assumption was already present in Andrews et al. (2017). Under the second assumption that perhaps the reason behind people under the opt-out treatment giving larger amounts is driven partly by the compensation for the considerateness shown to opt-out box in the flyer, just 1% percent model-violation results in 0.5% overstatement of mean altruism parameter. The outcomes of partial-derivative based local sensitivity analysis for the Not Happy Givers is that for the higher values of the social pressure cost parameter, the rate of change of the function is flatter, whereas for the lower values of the social pressure cost parameter, the rate is steeper; whether it is because of very high social pressure cost, more and more people are willing to donate to a charity, this as an alternative explanation can only be true only if the model is true. Rate of change for Happy Givers function with respect to curvature of altruism parameter for $g^s=10$ and $g^s=50$ is consistent with the assumptions imposed on these parameters. 

To view the code for reduced-form, structural-form estimation, sensitivity analysis and partial-derivative based local sensitivity analysis, nbviewer can be used since GitHub is unable to render the jupyter notebook files.

Code for reduced-form estimation:

---
<a href="https://nbviewer.jupyter.org/github/s6soverd/Master-Thesis-Uni-Bonn/blob/main/Part_1.ipynb"
   target="_parent">
   <img align="center"
  src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.png"
      width="109" height="20">
</a>
<a href="https://mybinder.org/v2/gh/s6soverd/Master-Thesis-Uni-Bonn/blob/master?filepath=Part_1.ipynb"
    target="_parent">
    <img align="center"
       src="https://mybinder.org/badge_logo.svg"
       width="109" height="20">
</a>
---

Code for Structural-form Estimation, Sensitivity Analysis, and Partial-Derivative Based local sensitivity analysis:

---
<a href="https://nbviewer.jupyter.org/github/s6soverd/Master-Thesis-Uni-Bonn/blob/main/Part_2.ipynb"
   target="_parent">
   <img align="center"
  src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.png"
      width="109" height="20">
</a>
<a href="https://mybinder.org/v2/gh/s6soverd/Master-Thesis-Uni-Bonn/blob/master?filepath=Part_2.ipynb"
    target="_parent">
    <img align="center"
       src="https://mybinder.org/badge_logo.svg"
       width="109" height="20">
</a>
---

