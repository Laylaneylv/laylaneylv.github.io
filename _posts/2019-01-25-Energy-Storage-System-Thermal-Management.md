---
layout: post
comments: true
title: Energy Storage System - Thermal Management

published: true
---

**Q: Energy Storage System (ESS)?**

A: A system, composed of batteries (Li-ion batteries), capable of storing energy and offering energy as needed.

**Q: Why ESS needs thermal management?**

A: Core components of ESS are Li-ion batteries, the batteries generate heat when they are discharging or charging. The heat comes from the movement of electrons, namely the electric current.

**Q: How to evaluate thermal performance of ESS?**

A: ESS, different from IGBT module, has no fixed structure. Therefore, no general thermal model is applicable. 
Highest/lowest temperature among batteries, and temperature uniformity of batteries (related to battery lifetime) are two points indicating thermal performance of ESS.

**Q: Thermal solution of ESS?**

A:

![](/images/201901/13.png)

![](/images/201901/14.png) ![](/images/201901/15.png)
   

Most of the thermal systems of ESS are following the above methods: 

1, Between Batteries and Case, PCM/high-conductive thermal material/Heat Pipe can be applied.

#### PCM

PCM absorbs Latent Heat when it is heated to the melting temperature, other times only Sensible Heat. As shown in the general characteristic of PCM, the Latent Heat, compared to the Sensible Heat, means amount of heat. 

By selecting appropriate PCM (with melting temperature close to 50〬C, also good thermal conductivity), the heat path from Batteries to Case can be improved by filling in such PCM.

#### Simulation

Because of PCM’s special heat curve along with temperature, a simplified curve of specific heat capacity (Cp) can be used to simulate PCM’s performance, as shown below:   

![](/images/201901/16.png) ![](/images/201901/17.png)

#### High-conductive thermal material

To conduct heat efficiently from Batteries to Case, special material with high thermal conductivity can be selected and made into mechanical structure, like high- thermal-conductive plastics.

#### Heat Pipe

Working principle is shown below, Heat Pipe can be applied as a thermal bridge between Batteries and Case. Example, when there are two-layer Batteries to dissipate heat out, the Heat Pipe can be buried into the system to transfer heat out from the interfacial structure to Case, to further spread heat through Case area.  

![](/images/201901/18.png)
 
2, Between Case and Ambient, Air cooling/Liquid cooling solution is utilized. 

#### Air Cooling

Air cooling solution is quite popular in market. Heat dissipation of ESS relies on the airflow through the external Case structure.

#### Liquid Cooling

Liquid cooling includes different types: 

1)	Liquid flow through channels (AKASOL).

![](/images/201901/19.png)
 
2)	Liquid flow through path wrapping Batteries (TESLA).

**US 2011/0206969 A1**

![](/images/201901/20.png)
 
3)	Immersion cooling technology (XINGMobility) 

(Potential challenges of 3M novec engineered fluid: handling, not-high boiling point, limited compatibility with contacting material, leakage problem.) 

https://www.xingmobility.com/xing-battery-system

**Q: Thermal management system design of ESS?**

![](/images/201901/21.png)
 
END.
