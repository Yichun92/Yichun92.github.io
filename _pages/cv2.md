---
layout: archive
title: "Research"
permalink: /cv2/
author_profile: true
redirect_from:
  - /resume
---

Working Papers
======
* <b> [1] [Bargaining, Merger and Endogenous Network Formation: the Case of Power Plants and Coal Companies in the US](). </b> <b> (Job Market Paper). </b>

  <i> Abstract: </i> The outcome of a structural change, for instance, merger, entry, or exit, is a critical task in anti-trust economics. To get a more reasonable market outcome with privately-negotiated transactions, I include non-purchased goods as the threat of replacement. Buyers decide where to purchase and how much to purchase simultaneously. Built on the seminal works on endogenous network formation, I develop a complete structural model in this study, incorporating individual-level Nash bargaining, endogenous network formation, capacity constraints, and multiple continuous purchase behavior. I discuss the identification, implementation, and computational algorithms for estimation and counterfactual. Then I construct a comprehensive data set of power plants and coal companies from 1998 to 2008 to study the Arch-Triton merger in 2005. FTC initially challenged the Arch-Triton merger, and the case was closed, followed by a suspicious spot price increase afterward. I estimate the model with the data set and carry on counterfactual analysis with no merger or divestiture. It turns out that the inclusion of more primitives into the model complicates the analysis and generates ambiguous results.
  
* <b> [2] [An Alternating Maximizations Approach to Approximate Dynamic Programming](), </b> with [Adam Dearing](https://www.johnson.cornell.edu/faculty-research/faculty/aed237/). 

  <i> Abstract: </i> We propose a new unconstrained maximization approach to approximate the value and policy functions in a single-agent dynamic programming problem. The method follows the scheme of Howard's iteration and alternates between maximizing an unconstrained objective function over the (possibly approximate) value function given a policy function and the (possibly approximate) policy function given a value function. Our method is flexible since researchers can choose which part to approximate while solving the other part exactly, which helps utilize the characteristics of a specific problem. When polynomial approximations are adopted, the objective function is concave across various models, including the discrete choice in industrial organization and the continuous choice in Macroeconomics. We show that our algorithm is hill-climbing with a convergence guarantee under concavity. An upper bound then follows from an analogous minimization problem over the approximate value function. Simulations on both IO-type and Macro-type model demonstrate that our computational method provides significant computational gains, especially with colossal state space and without high-speed computing devices. 

* <b> [3] [A Frisch-Waugh-Lovell Theorem for Empirical Likelihood](https://yichun92.github.io/files/FWL_EL_writeup.pdf), </b> with [Adam Dearing](https://www.johnson.cornell.edu/faculty-research/faculty/aed237/). 
  
  <i> Abstract: </i> We present a Frisch-Waugh-Lovell-type (FWL) theorem for empirical likelihood estimation with instrumental variables. Our theorem is similar to the standard FWL theorem for partitioning-out exogenous regressors (including dummy variables), but the partitioning-out procedure uses the empirical likelihood weights at the solution instead of the original empirical distribution. We show how to leverage this result to simplify computation via an iterative estimation algorithm, where exogenous variables are partitioned out using weighted least squares, and these weights are updated between iterations. Furthermore, we show that iterations converge locally to the full empirical likelihood estimate at a stochastically super-linear rate. We also provide a feasible iterative constrained optimization algorithm for calculating empirical-likelihood-based confidence intervals and discuss its properties. Monte Carlo simulations on both point estimation and confidence intervals demonstrate that our iterative algorithms are robust and generate results within numerical tolerance of the full empirical likelihood estimator in the finite sample, while offering substantial savings on computation time as the number of exogenous regressors grows. 
        
* <b> [4] [Addressing Endogeneity Issues in a SAR Model using Copulas](https://yichun92.github.io/files/Copulas_LinSong.pdf),</b> with [Yanli Lin](https://www.yanlilinecon.com/). 
  
  <i> Abstract: </i> We provide a new copula method to tackle possible endogeneity issues in a spatial autoregressive (SAR) model, which might originate from an endogenous spatial weight matrix, endogenous heterogeneity specification, or endogenous regressors. Model specifications and estimations for the three variants of a SAR model are presented. Using copula endogeneity correction technique, we propose 3-stage estimation methods and establish their consistency and asymptotic normality. Monte Carlo experiments are performed to investigate finite sample performance of the estimators. We then apply our method to an empirical study of spatial spillovers in regional productivity with endogenous spatial weights constructed by the proximity of a meaningful socioeconomic characteristic - years of education. 
    
  [Online Supplement Materials](https://yichun92.github.io/files/Copulas_LinSong_supplement.pdf)
  
* <b> [5] [A Semi-Parametric Two-Stage Estimator with Machine Learning to Solve Endogeneity](https://yichun92.github.io/files/MLFirstStage.pdf), </b> with [Adam Dearing](https://www.johnson.cornell.edu/faculty-research/faculty/aed237/). 
    
  <i> Abstract: </i> Based on the fast development in machine learning techniques, we propose a semi-parametric two-stage estimator to solve the endogeneity in models when implementing the usual linear-IV is impossible. Those models include binary discrete-choice with endogenous regressors and multinomial Logit model with zero market share. Our first stage is a flexible estimation of the expected outcomes, conditional on the regressors and instruments, whereas the second stage is a simple linear-IV regression with first-stage results inserted. After adding an analytical-calculated correction term, the first-stage error up to $o(N^{-1/4})$ does not affect the asymptotic distribution of the second-stage structural parameter estimates, allowing for a variety of non-parametric methods in the first stage. We demonstrate the behavior of our estimator through a pile of simulations. Moreover, we demonstrate the performance by a simple application using the publicly-available 2011 to 2015 transaction-level data between coal mining companies and coal-fired power plants in the US. 
    
* <b> [6] [QML Estimation of a Spatial Autoregressive Model with Endogenous Heterogeneity](https://yichun92.github.io/files/EHSAR.pdf), </b> with [Yanli Lin](https://www.yanlilinecon.com/) and [Yang Yang](https://maximyang.wixsite.com/mysite). 

  <i> Abstract: </i> This paper develops a spatial autoregressive (SAR) model with endogenous heterogeneity. The scalar spatial coefficient is allowed to be a bounded function of a spatial unit's own endogenous characteristics. Of particular interest is a structural interaction model with nonlinear and endogenous spillover effects. We propose a quasi-maximum likelihood estimation (QMLE) with a control function approach for this model, and investigate the asymptotic properties of the estimator which is verified to have good performance in finite sample Monte Carlo simulations. We apply our model to an empirical study of regional economic performance in about 1,400 subnational regions from 110 different countries and detect that the spillovers of regional productivity are heterogeneous and depend on an endogenous variable - years of education.

Computational Notes
======
* <b> [7] </b> 

Work in Progress
======
* <b> [8] Non-semiparametric Demand Approximation without the Exact or Lp Sparsity. </b> (Second-year paper, draft under modification.)
  <i> Short Description: </i>

* <b> [9] Spatial Autoregressive Model with Copulas in Dynamic Panels, </b> with [Yanli Lin](http://academicpages.github.io/files/paper1.pdf) and [Yang Yang](https://maximyang.wixsite.com/mysite).

  <i> Short Description: </i> Panel data constitutes the main stream of research in economics. 
  
