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

- - -

# Published Articles

**The heterogeneous response of real estate asset prices to a global shock** (with W. Koeniger and M. Lechner). <br/>
<small>[ <a href="#/" onclick="visib('re21')">Abstract</a> | <a href="https://academic.oup.com/jrsssa/advance-article/doi/10.1093/jrsssa/qnae078/7742468" target="_blank" rel="noopener noreferrer">Paper</a> | <a href="https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/OIW7VX" target="_blank" rel="noopener noreferrer">Replication Code</a> ] </small>

<div id="re21" style="display: none; text-align: justify; line-height: 1.2" ><small>
We estimate the transmission of the pandemic shock in 2020 to the residential and commercial real estate market by causal machine learning, using granular data for Germany. We exploit differences in the incidence of Covid infections and short-time work at the municipal level for the identification of epidemiological and economic effects of the pandemic. We find that (i) a larger incidence of Covid infections temporarily reduced rents for retail real estate; (ii) a larger incidence of short-time work temporarily reduced rents of office real estate; (iii) the pandemic increased prices, particularly in the top price segment of commercial real estate.
</small><br><br/></div>

**A general framework to quantify the event importance in multi-event contests** (with D. Goller). <br/>
<small>[ <a href="#/" onclick="visib('event_importance')">Abstract</a> | <a href="https://link.springer.com/article/10.1007/s10479-023-05540-x" target="_blank" rel="noopener noreferrer">Paper</a>| <a href="https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/F3QA9N" target="_blank" rel="noopener noreferrer">Replication Code</a> ] </small>

<div id="event_importance" style="display: none; text-align: justify; line-height: 1.2" ><small>
We propose a statistical framework for quantifying the importance of single events that do not provide intermediate rewards but offer implicit incentives through scheduling and the reward structure at the end of a multi-event contest. Applying the framework to primary elections in the US, where earlier elections have greater importance and influence, we show that schedule variations can mitigate the problem of front-loading elections. When applied to European football, we demonstrate the utility and meaningfulness of quantified event importance in relation to the in-match performance of contestants to improve outcome prediction and to provide an early indication of public interest.
</small><br><br/></div>

**Judging the judges: evaluating the accuracy and national bias of international gymnastics judges** (with H. Mercier). <br/>
<small>[ <a href="#/" onclick="visib('judging2021')">Abstract</a> | <a href="https://www.degruyter.com/document/doi/10.1515/jqas-2019-0113/html?lang=en" target="_blank" rel="noopener noreferrer">Paper</a> ]  </small>

<div id="judging2021" style="display: none; text-align: justify; line-height: 1.2" ><small>
We design, describe and implement a statistical engine to analyze the performance of gymnastics judges with three objectives: (1) provide constructive feedback to judges, executive committees and national federations; (2) assign the best judges to the most important competitions; (3) detect bias and persistent misjudging. Judging a gymnastics routine is a random process, and we model this process using heteroscedastic random variables. The developed marking score scales the difference between the mark of a judge and the true performance level of a gymnast as a function of the intrinsic judging error variability estimated from historical data for each apparatus. This dependence between judging variability and performance quality has never been properly studied. We leverage the intrinsic judging error variability and the marking score to detect outlier marks and study the national bias of judges favoring athletes of the same nationality. We also study ranking scores assessing to what extent judges rate gymnasts in the correct order. Our main observation is that there are significant differences between the best and worst judges, both in terms of accuracy and national bias. The insights from this work have led to recommendations and rule changes at the Fédération Internationale de Gymnastique.
</small><br><br/></div>
<br/> 
- - - 

# Work in Progress

**Data-driven model selection within the matrix completion method for causal panel data models** <br/>
<small>[ <a href="#/" onclick="visib('matrix_completion')">Abstract</a> | <a href="https://arxiv.org/abs/2402.01069	" target="_blank" rel="noopener noreferrer">Working Paper</a>  ] </small>

<div id="matrix_completion" style="display: none; text-align: justify; line-height: 1.2" ><small>
Matrix completion estimators are employed in causal panel data models to regulate the rank of the underlying factor model using nuclear norm minimization. This convex optimization problem enables concurrent regularization of a potentially high-dimensional set of covariates to shrink the model size. For valid finite sample inference, we adopt a permutation-based approach and prove its validity for any treatment assignment mechanism. Simulations illustrate the consistency of the proposed estimator in parameter estimation and variable selection. An application to public health policies in Germany demonstrates the data-driven model selection feature on empirical data and finds no effect of travel restrictions on the containment of severe Covid-19 infections.
</small><br><br/></div>

**Judging the judges: A general framework for evaluating the performance of international sports judges** (with H. Mercier). <br/>
<small>[ <a href="#/" onclick="visib('judging2018')">Abstract</a> | <a href="../files/Paper_HM.pdf" target="_blank" rel="noopener noreferrer">Working Paper</a> ] </small>

<div id="judging2018" style="display: none; text-align: justify; line-height: 1.2" ><small>
The monitoring of judges in sports is an important topic due to the media exposure of international sporting events and the huge monetary sums that directly depend on the outcomes of competitions. We present a method to assess the accuracy of sports judges applicable to all sports where panels of judges evaluate athletic performances on a finite scale. We analyze judging scores from eight different sports with comparable judging systems: artistic swimming, diving, dressage, figure skating, freestyle skiing, freestyle snowboard, gymnastics and ski jumping. We identify, for each aforementioned sport, a general and accurate pattern of the intrinsic judging error variability as a function of the performance level of the athlete. With the notable exception of dressage, this intrinsic judging inaccuracy is heteroscedastic and can be approximated by a concave quadratic curve, indicating increased consensus among judges towards the best athletes. Using this observation, we can evaluate the performance of judges compared to their peers, and distinguish erratic from precise judges and potential cheating from unintentional misjudging. Our analysis also reveals valuable insights about the judging practices of the sports under consideration, including a systemic problem in dressage where judges disagree on what constitutes a good performance.
</small><br><br/></div>

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

# R-Packages

**MCMS** <br/>
<small>[ <a href="#/" onclick="visib('MCMS')">Description</a> | <a href="https://github.com/heinigersandro/MCMS" target="_blank" rel="noopener noreferrer">Download</a> ] </small>

<div id="MCMS" style="display: none; text-align: justify; line-height: 1.2" ><small>
The MCMS package provides functions to calculate the average treatment effect on the treated (ATET), estimating a low-rank factor model plus noise with a linear covariate term using the matrix completion method. The method uses nuclear norm regularization on the rank of the matrix of unobserved factors and l-1 regularization on the covariate model to simultaneously reduce the model complexity in the covariates.
</small><br><br/></div>

[//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>
[//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Description</button>

