+++
date = "2019-03-11T2:27:40-04:00"
math = false
tags = ["application"]
title = "Optimizing wave energy converter array layouts"

+++

## Description
In the transition of the US energy economy from traditional technologies to renewables, ocean wave energy technology has a significant role to play. Almost all of the wave energy technologies involve the employment of Wave Energy Converters (WECs) -- some dynamically excited vibrating structures which interact with periodic ocean swells. 

{{< figure library="1" src="buoy.gif">}}

For WEC technologies to be relevant on a utility scale, it will be necessary to distribute vast arrays of energy-harvesting buoys across a wide expanse of ocean, as scaling up individual WECs to the several megawatts is economically impractical. Certain layout of WECs in an array can induce constructive hydrodynamic interactions between WECs, i.e., such interaction increases the power generation. Such effect gives rise to the layout optimization issue. However, the hydrodynamic analysis and performance estimation of different layout for WEC arrays have to be carried out using numerical models and thus becomes computationally expensive. Computational demand increases rapidly with the array size, making the determination of optimal layouts of WECs in arrays extremely challenging, even for arrays as small as 3-4 WECs.

{{< figure library="1" src="buoy_opt.jpg">}}

This project constitutes an effort to rectify these issues, and deliver an accurate and efficient approach for assessing and optimizing the power generation potential. The computational demand will be reduced by the incorporation of a statistical emulator (metamodel) that can efficiently predict the hydrodynamic interactions based on small number of evaluations of the initial, computationally expensive numerical model. Uncertainties both associated with such emulator prediction and with the wave climate will be characterized and incorporated into the formulation of optimization problem. The resultant WEC formation to emerge from this approach will be truly optimal; i.e., no other formation, regardless of how it is controlled, will out-perform it. Once developed, the technique can be applied for both for site scoping as well as actual array design.


{{< figure library="1" src="buoy_result.png">}}
