---
layout: page
title: "Learning to Allocate: Capacity Constraints and Kidney Discard in Deceased Donor Allocation"
description: "Honors thesis on capacity-aware kidney allocation and organ discard."
img: /assets/img/honors-thesis-causal-diagram.png
importance: 0
category: work
---

This honors thesis studies how transplant-center capacity constraints, especially surgeon availability, contribute to kidney-offer rejections and organ discard in deceased donor allocation. Using SRTR offer data, it combines Bayesian mixed-effects modeling, capacity modeling, and allocation simulation to study policy changes that can reduce discard while preserving ex ante waitlist fairness.

[Read the full thesis]({{ '/assets/pdf/Berriman__Will_Honors_Thesis.pdf' | relative_url }})

<div class="row">
  <div class="col-sm-7 mt-3 mt-md-0">
    {% include figure.liquid path="/assets/img/honors-thesis-causal-diagram.png" title="Causal structure of deceased donor kidney allocation, showing how capacity constraints and repeated rejections can lead to discard." class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-5 mt-3 mt-md-0">
    {% include figure.liquid path="/assets/img/honors-thesis-capacity-results.png" title="Predicted monthly kidney transplants rise with surgeon supply, illustrating the operational role of capacity." class="img-fluid rounded z-depth-1" %}
  </div>
</div>

The analysis finds that capacity-aware acceptance modeling can substantially reduce simulated discard relative to a model that omits capacity, highlighting the importance of operational constraints in allocation design.
