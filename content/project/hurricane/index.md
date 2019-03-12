+++
date = "2019-03-11T2:27:40-04:00"
math = false
tag = "application"
title = "Real-time storm surge prediction"


## Description

{{< figure library="1" src="hurricane1.png">}}

Over the past couple of decades, numerical advances have allowed producing high-fidelity storm surge simulation models that permit a detailed representation of hydrodynamic processes and therefore support high-accuracy forecasting. Unfortunately, the computational burden of such numerical models is large, requiring thousands of CPU hours for each simulation. During landfalling events such models can only be utilized to provide a small number of high-fidelity, deterministic predictions, but cannot support thousand-run ensembles to examine the impact of forecasting errors in the predicted track, or provide fast prediction updates once the new storm track information becomes available. Their implementation for regional hurricane risk assessment faces similar challenges.

{{< figure library="1" src="hurricane2.png">}}

I explored the use of Kriging surrogate models to address the aforementioned challenge. It can provide fast predictions using a database of high-fidelity, synthetic storms, with the goal of maintaining the accuracy of the numerical model utilized to produce this database, while providing greatly enhanced computational efficiency.

In addition, we proposed the adaptive selection strategy of synthetic storms for creating the database that will inform the surrogate model development. The idea is to sequentially seek for the optimal synthetic storm that minimizes the integrated mean squared error of the current surrogate model over the experimental region (parameter spaces for storms). 
{{< figure library="1" src="hurricane3.png">}}

(b) adjustments to support two implementation issues that might become more relevant due to climate change considerations: including the prediction for intensified storms exceeding all available ones in initial synthetic-storm database (which
unavoidably requires implementation for extrapolating predictions), and the surge estimation for sea level rise (SLR) scenarios.
{{< figure library="1" src="hurricane4.png">}}
+++
