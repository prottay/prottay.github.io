---
layout: archive
title: "Real-time Demonstrations"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

**PMU Pre-compliance test-suite:**

- A test-infrastructure is proposed that uses low-voltage signals to validate the functionalities of a PMU under test. The test infrastructure is based on National Instruments’ cRIO hardware.
- The test-hardware can be easily controlled by a user from the GUI-based software designed in LabVIEW.
- A prototype PMU is put under the tests (using our test-suite) and its performance is analyzed and compared with the others available in literature.
- Possible adjustments of the test-suit on hardware and software ends are proposed.




<img align="right" width="100%" src="https://user-images.githubusercontent.com/6533632/191937875-22fb1072-202e-4e8b-bdda-5f5ac7e5d33d.gif">



------


**Networking experiments on _Khorjin_ based synchrophasor synchornization gateway:**


 -  cRIO based HW-SW setup to parse, synchronize, timestamp, and display multiple C37.118 streams.  
 -  The PMU streams are corrupted with external networking hardware. 
 -  The network is tampered with delay, data-drip and jitter to test its resillience.
 -  Demonstrated in: [NASPI Meeting 2019](https://www.naspi.org/node/766)

<img align="right" width="100%" src="https://user-images.githubusercontent.com/6533632/191948548-a831b3dd-161d-42b5-8dc0-e14ac464c68f.gif">




------



**GFOV investigation in RT for DERs:**

 -  Investigates the presence and effect of Ground Fault Overvoltage (GFOV) phenomenon in Grid-Connected PV inverters. 
 -  Examines whether conventional neutral grounding, which eliminates this GFOV issue in synchronous generators- are necessary for inverter-based systems. 
 -  Tests the effectiveness of SPOV mechanism against GFOV and LROV. 
 -  Demonstrated in: [Congressional visit in 2021](https://cisl.rpi.edu/news/rensselaer-welcomes-congressional-bipartisan-discussion-future-energy), [IEEE Colloquium 2021](https://events.vtools.ieee.org/m/278815)
<!--  -  Experiments repeated with different load pf, different generation-to-load ratios (GLR), different SPOV settings, and different grounding transformer sizes.  -->

<img align="right" width="60%" src="https://user-images.githubusercontent.com/6533632/191942657-3789afaf-bcd0-4fd2-9f74-8f5eb8c771bd.gif">



------

**SSGC based resillient networked-control for BESS:**

 -  Implementation of a synchrophasor synchronization gateway and control (SSGC) hardware based on cRIO and _Khorjin_ library. 
 -  SSGC houses the secondary control functionalities for BESS which runs in a microgrid simulated in Typhoon HIL 604. 
 -  The network for the PMU placed at BESS is attacked with external hardware. 
 -  Network delay, data-drops and jitters were injected in the network to test the robustness of the control-network.
 -  An LPF was incorporated to get rid of all high frequency components of the control signal, to protect the Li-ion battery.   
 -  Demonstrated in: [Congressional visit in 2021](https://cisl.rpi.edu/news/rensselaer-welcomes-congressional-bipartisan-discussion-future-energy)

<img align="right" width="100%" src="https://user-images.githubusercontent.com/6533632/200471835-15738857-0e7c-47aa-95dc-2611f8115c04.gif">






