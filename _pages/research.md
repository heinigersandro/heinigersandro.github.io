---
layout: archive
title: "Research projects"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

<br/> 
<br/> 

- - -

# Completed projects and work in progress

**Judging the judges: evaluating the accuracy and national bias of international gymnastics judges.** (with H. Mercier). <br/>
<small>[ <a href="#/" onclick="visib('judging2021')">Abstract</a> | <a href="https://www.degruyter.com/document/doi/10.1515/jqas-2019-0113/html?lang=en" target="_blank" rel="noopener noreferrer">Paper</a> ]  </small>

<div id="judging2021" style="display: none; text-align: justify; line-height: 1.2" ><small>
We design, describe and implement a statistical engine to analyze the performance of gymnastics judges with three objectives: (1) provide constructive feedback to judges, executive committees and national federations; (2) assign the best judges to the most important competitions; (3) detect bias and persistent misjudging. Judging a gymnastics routine is a random process, and we model this process using heteroscedastic random variables. The developed marking score scales the difference between the mark of a judge and the true performance level of a gymnast as a function of the intrinsic judging error variability estimated from historical data for each apparatus. This dependence between judging variability and performance quality has never been properly studied. We leverage the intrinsic judging error variability and the marking score to detect outlier marks and study the national bias of judges favoring athletes of the same nationality. We also study ranking scores assessing to what extent judges rate gymnasts in the correct order. Our main observation is that there are significant differences between the best and worst judges, both in terms of accuracy and national bias. The insights from this work have led to recommendations and rule changes at the Fédération Internationale de Gymnastique.
</small><br><br/></div>

**The heterogeneous response of real estate asset prices to a global shock.** (with W. Koeniger and M. Lechner). <br/>
<small>[ <a href="#/" onclick="visib('re21')">Abstract</a> | <a href="./files/Paper_HKL.pdf" target="_blank" rel="noopener noreferrer">Working Paper</a> ] </small>

<div id="re21" style="display: none; text-align: justify; line-height: 1.2" ><small>
We estimate the transmission of the pandemic shock in 2020 to prices in the residential and commercial real estate market by causal machine learning, using granular data at the municipal level for Germany. We exploit differences in the incidence of Covid infections and short-time work at the municipal level for the identification of epidemiological and economic efects of the pandemic. We find that (i) a larger incidence of Covid infections temporarily reduced rents for retail real estate; (ii) a larger incidence of short-time work temporarily reduced rents of office real estate; and (iii) the pandemic increased asset prices of real estate, particularly in the top price segment of commercial real estate.
</small><br><br/></div>

**A general framework to quantify the event importance in multi-event contests.** (with D. Goller). <br/>
<small>[ <a href="#/" onclick="visib('event_importance')">Abstract</a> | <a href="./files/Paper_GH.pdf" target="_blank" rel="noopener noreferrer">Working Paper</a> ] </small>

<div id="event_importance" style="display: none; text-align: justify; line-height: 1.2" ><small>
We propose a statistical framework for quantifying the importance of single events that do not provide intermediate rewards but offer implicit incentives through scheduling and the reward structure at the end of a multi-event contest. Applying the framework to primary elections in the US, where earlier elections have greater importance and influence, we show that schedule variations can mitigate the problem of front-loading elections. When applied to European football, we demonstrate the utility and meaningfulness of quantified event importance in relation to the in-match performance of contestants, to improve outcome prediction and to provide an early indication of public interest.
</small><br><br/></div>

**Judging the judges: A general framework for evaluating the performance of international sports judges.** (with H. Mercier). <br/>
<small>[ <a href="#/" onclick="visib('judging2018')">Abstract</a> | <a href="./files/Paper_HM.pdf" target="_blank" rel="noopener noreferrer">Working Paper</a> ] </small>

<div id="judging2018" style="display: none; text-align: justify; line-height: 1.2" ><small>
The monitoring of judges in sports is an important topic due to the media exposure of international sporting events and the huge monetary sums that directly depend on the outcomes of competitions. We present a method to assess the accuracy of sports judges applicable to all sports where panels of judges evaluate athletic performances on a finite scale. We analyze judging scores from eight different sports with comparable judging systems: artistic swimming, diving, dressage, figure skating, freestyle skiing, freestyle snowboard, gymnastics and ski jumping. We identify, for each aforementioned sport, a general and accurate pattern of the intrinsic judging error variability as a function of the performance level of the athlete. With the notable exception of dressage, this intrinsic judging inaccuracy is heteroscedastic and can be approximated by a concave quadratic curve, indicating increased consensus among judges towards the best athletes. Using this observation, we can evaluate the performance of judges compared to their peers, and distinguish erratic from precise judges and potential cheating from unintentional misjudging. Our analysis also reveals valuable insights about the judging practices of the sports under consideration, including a systemic problem in dressage where judges disagree on what constitutes a good performance.
</small><br><br/></div>

**Data-supported model selection within the matrix completion method in causal panel data models.** <br/>
<small>[ <a href="#/" onclick="visib('matrix_completion')">Abstract</a> ] </small>

<div id="matrix_completion" style="display: none; text-align: justify; line-height: 1.2" ><small>
Matrix completion estimators for causal panel data models use nuclear norm minimization to regularize the rank of the underlying factor model. This convex optimization problem allows for a simultaneous regularization of a potentially high-dimensional set of covariates. This integrated model selection property does not affect the theoretical bounds of the estimator. A two-step procedure with first selecting the optimal model and a second estimation without covariate regularisation ensures unbiased estimates of the average treatment effects on the treated. Simulations show that the proposed estimator is  consistent in parameter estimation and variable selection. 
</small><br><br/></div>
<br/> 
- - - 

# Early stage projects

**Common support violations in causal forest estimators** (with M. Lechner and F. Muny). <br/>

**Identification of factors driving the prevalence of match-fixing in professional sports** (with E. Brox and M. Lechner).<br/>

[//]: This java script is the button to show Abstract
<script>
 function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>

[//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>

