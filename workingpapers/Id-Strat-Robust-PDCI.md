---
layout: single
classes: wide
title: "Beyond Parallel Trends: An Identification-Strategy-Robust Approach to Causal Inference with Panel Data"
permalink: /workingpapers/id-strat-robust-pdci
---
<div style="display: flex; justify-content: center; gap: 20px;">
  <img src="/files/CDST2025_figure.png" alt="Close Comparison Groups" width="450" />
</div>

<em>Callaway, Dyal, Sant'anna, and Tsyawo (2025)</em>

## Abstract
In this paper, we propose a new approach to causal inference with panel data.  Instead of using panel data to adjust for differences in the distribution of unobserved heterogeneity between the treated and comparison groups, we instead use panel data to search for "close comparison groups"---groups that are similar to the treated group in terms of pre-treatment outcomes.  Then, we compare the outcomes of the treated group to the outcomes of these close comparison groups in post-treatment periods.  We show that this approach is often *identification-strategy-robust* in the sense that our approach recovers the *ATT* under many different non-nested panel data identification strategies, including difference-in-differences, change-in-changes, or lagged outcome unconfoundedness, among several others.  We provide related, though non-nested, results under "time homogeneity", where outcomes do not systematically change over time for any comparison group.  Our strategy asks more out of the research design---namely that there exist close comparison groups or time homogeneity (neither of which is required for most existing panel data approaches to causal inference)---but, when available, leads to more credible inferences.

<a href="{{ '/files/CDST_2025.pdf' | relative_url }}"
   class="btn btn--primary"
   target="_blank">
  📄 Paper (PDF)
</a>

