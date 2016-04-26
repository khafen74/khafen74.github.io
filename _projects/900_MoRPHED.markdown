---
layout: project
title: MoRPHED
desc: Model of Riverine PHyiscal Form and Eco-hydraulic Dynamics
picurl: https://goo.gl/xOQnLQ
---
<h3>Purpose</h3>
This research is aimed at developing the "middle ground" of modeling braided river morphodynamics. Current modeling approaches include computational fluid dynamics (CFD) and cellular automata 
(also known as reduced complexity) approaches. While all models are just representations of reality and will never exactly model the desired processes, they are important for assessing and furthering our knowledge, 
understanding, and representation of physical processes in braided rivers. CFD models erode and transport sediment at very small time-steps, recalculating a new hydraulic solution at each time-step. 
Hence, they are computationally expensive and run a slower than real-time. On the other hand, cellular automata models sacrifice hydraulic precision and use topography to drive sediment transport. 
The downside is that without account for momentum these models generally produce and unrealistic plane-bed system. Our goal is to develop a model that fits the "middle ground" between these two modeling approaches. 
We seek to develop a model that can represent hydraulics more accurately that a reduced complexity approach but will not be as computationally expensive as CFD models.  

<h3>Summary</h3>
Using long-term, repeat datasets from the Scotland's River Feshie and New Zeland's Rees River to inform
 and validate our design and decision we are creating a morphodynamic model (MoRPHED) that runs on an event scale time-step. This model relies on steady state hydraulics for an event to calculate erosion and sediment transport. 
 Hydraulics are retrieved from the Delft3D hydraulic model which is run directly from the MoRPHED model. The Rees River has 7 DEMs created from total station surveys after competent events, 
 while the River Feshie has 9 DEMs collected nearly annually from 2000 - 2013 with a total station survey at base flow.

<h3>My Contributions</h3>
[Joe Wheaton](www.joewheaton.org) and [Alan Kasprak](www.alankasprak.org) have researched and developed the geomorphic ideas, theories, processes and applications represented in the model. My contributions have been development of their ideas into code. 
Alan and I have worked together to develop geographic implementation for many of the processes we represent in the model. I have also written geoprocessing and analysis scripts used by the model to manipulate and prepare 
data to represent different physical processes.