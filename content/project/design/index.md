+++
date = "2019-03-11T2:27:40-04:00"
math = false
tags = ["methodology"]
title = "Design under uncertainty"
+++

{{< figure library="1" src="design.PNG">}}

## Description
A central task in engineering system analyses is to identify optimal designs in the presence of uncertainties. Due to the needed many queries for optimization and uncertainty quantification, this task can be computationally demanding for systems described by complex numerical simulators. To reduce this computational overhead, I developed adaptive and iterative Kriging surrogate development strategy for both single and multiple objective design problems under uncertainty. The major contributions include a generalized adaptive design-of-experiment strategy that can identify and enhance surrogate accuracy around interesting domains for optimization, and a rationale probabilistic termination criterion to check if the surrogate model is sufficiently accurate for optimization purpose. The proposed optimizer has been demonstrated to converge with minimal computational effort and near-optimal solutions on high-dimensional nonlinear engineering optimization problems.

{{< figure library="1" src="design1.PNG">}}
