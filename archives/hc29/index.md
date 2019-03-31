---
author: kevbroch
comments: false
date: 2017-09-06 17:55:33+00:00
excerpt: "\n\t\t\t\t\t\t"
layout: page
link: http://www.hotchips.org/archives/2010s/hc29/
slug: hc29
title: "\n\t\t\t\tHC29 (2017)\t\t"
wordpress_id: 3462
---


				Flint Center for the Performing Arts, Cupertino, California, Sunday-Tuesday, August 20-22, 2017.

[Zipfile of all program/poster slides.](/wp-content/uploads/hc_archives/hc29/HC29-allpapers.zip)

[accordion]
[tabs]
[tab title="Videos"]
Tutorial 1: P4 for Software Defined Networks: Language and Hardware Implementation
https://youtu.be/KD5J0LxryFA
Tutorial 2: Building Autonomous Vehicles with NVIDIA’s DRIVE Platform
https://youtu.be/4zrat3Mn410
Session 1: GPU & Gaming
https://youtu.be/jVNuZ4Rfs6k
Session 2: IOT/Embedded
https://youtu.be/cQXKiEMXggY
Keynote 1: Direct Human/Machine Interface
https://youtu.be/PVuSHjeh1Os
Session 3: Automotive
https://youtu.be/CTjlptJN84k
Session 4: Processors
https://youtu.be/6HNm5f7IArc
Session 5: FPGA
https://youtu.be/cmZjE3HHr9w
Session 6: Neural Net I
https://youtu.be/DbhAMiQ_yvs
Keynote 2: Advances in AI
https://youtu.be/VWdReme_5Vg
Session 7: Neural Net II
https://youtu.be/j0ra7XApB4c
Session 8: Architecture
https://youtu.be/7CiqlsAI5Xg
Session 9: Server
https://youtu.be/LUfJxHe1X7A

[/tab]
[tab title="At A Glance"]



 	
  * Sunday 8/20: Tutorials

 	
    * 8:00 AM - 9:00 AM: Breakfast

 	
    * 9:00 AM - 12:20 PM: Tutorial 1: P4 for Software Defined Networks: Language and Hardware Implementation

 	
    * 12:20 PM - 1:35 PM: Lunch

 	
    * 1:35 PM - 4:30 PM: Tutorial 2: Building Autonomous Vehicles with NVIDIA’s DRIVE Platform

 	
    * 4:30 PM - 6:00 PM: Reception






 	
  * Monday 8/21: Conference Day 1

 	
    * 7:30 AM - 9:15 AM: Breakfast

 	
    * 9:15 AM - 9:30 AM: Introduction

 	
    * 9:30 AM - 10:00 AM: GPU & Gaming

 	
    * 10:00 AM - 10:30 AM: Break (Eclipse Viewing)

 	
    * 10:30 AM - 11:30 AM: GPU & Gaming (cont)

 	
    * 11:30 AM - 12:30 PM: IOT/Embedded

 	
    * 12:30 PM - 1:45 PM: Lunch

 	
    * 1:45 PM - 2:45 PM: Keynote 1: Direct Human/Machine Interface...

 	
    * 2:45 PM - 3:45 PM: Automotive

 	
    * 3:45 PM - 4:15 PM: Break

 	
    * 4:15 PM - 6:15 PM: Processors

 	
    * 6:15 PM - 7:15 PM: Reception (Wine & Snacks)






 	
  * Tuesday 8/22: Conference Day 2

 	
    * 7:15 AM - 8:15 AM: Breakfast

 	
    * 8:15 AM - 10:15 AM: FPGA

 	
    * 10:15 AM - 10:45 AM: Break

 	
    * 10:45 AM - 11:45 AM: Neural Net

 	
    * 11:45 AM - 12:45 PM: Keynote 2: Advances in AI...

 	
    * 12:45 PM - 2:00 PM: Lunch

 	
    * 2:00 PM - 3:30 PM: Neural Net (cont)

 	
    * 3:30 PM - 4:30 PM: Architecture

 	
    * 4:30 PM - 5:00 PM: Break

 	
    * 5:00 PM - 7:00 PM: Server

 	
    * 7:00 PM - 7:15 PM: Closing Remarks





[/tab]
[tab title="Tutorials"]


# Tutorials


<table > 
<tbody >
<tr >

<td >**Sun 8/20**
</td>

<td >**Tutorial**
</td>

<td >**Title**
</td>

<td >**Presenter**
</td>

<td >**Affiliation**
</td>
</tr>
<tr >

<td >8:00 AM
</td>

<td >Breakfast
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
<tr >

<td colspan="5" >**Tutorial 1: P4 for Software Defined Networks: Language and Hardware Implementation**

The flexibility offered by Software Defined Networks (SDNs) is appealing to network operators, since it allows the customization of network behavior for application-specific needs. In SDNs, flexibility comes at the cost of running the network on general-purpose hardware, reducing the performance that one can obtain from specialization. A recent trend in the industry is to use specialized hardware (ASICs and FPGAs) to combine the best of SDN programmability and flexibility with hardware execution efficiency. Programmable networking hardware allows both enhancing legacy protocols (e.g. adding monitoring to a traditional L2/L3 switching) and developing new protocols at a much faster pace.

To support programmability for network devices, P4 (www.p4.org) has been developed as a new programming language for describing how network packets should be processed on a variety of targets ranging from general-purpose CPUs to NPUs, FPGAs, and custom ASICs. P4 was designed with three goals in mind: (i) protocol independence: devices should not “bake in” specific protocols; (ii) field reconfigurability: programmers should be able to modify the behavior of devices after they have been deployed; and (iii) portability: programs should not be tied to specific hardware targets. P4 is the first widely-adopted domain-specific language for packet processing. Several vendors have developed FPGA-based implementations and, with the arrival of Tofino, there is already at least one domain-specific processor optimized as a compiler target for P4 programs – a processor with a small instruction set that can process one header per cycle. The P4 community has created – and continues to maintain and develop – the language specification, a set of open-source tools (compilers, debuggers, code analyzers, libraries, software P4 switches, etc.), and sample P4 programs, all with the goal of making it easy for P4 users to quickly and correctly author new data-plane behaviors. Specialized backend compilers and optimizers for vendor targets are built upon the open source framework. Using P4 and the open source tools, it is easy to prototype new ideas for networking hardware and applications in P4, by simply augmenting the compiler with support for the new hardware.

The goal of the tutorial is to introduce attendees to the domain of specialized hardware and programming tools for SDN. We discuss the basic operations in networking and how they have influenced the design of the P4 language, and of specialized, programmable networking hardware. We will show how the design goals of P4 language are met through examples of programs that can run on a variety of architectures. We provide several examples of applications (e.g. monitoring) that are enabled only by the combination of programmable hardware. We expect that, at the end of the tutorial, attendees will be familiar with the application domain and with a set of several implementations from different vendors that demonstrate various trade-offs. We aim to encourage researchers to consider the programmable networking devices area as one of the areas where domain-specific specialization is already moving into commercial devices and to contribute to the development of the P4 based ecosystem.
</td>
</tr>
<tr >

<td >9:00 AM
</td>

<td >T1
</td>

<td >Background on Software Defined Networking
</td>

<td colspan="2" >Johann Tonsing, Netronome
</td>
</tr>
<tr >

<td >9:20 AM
</td>

<td >T1
</td>

<td >[P4 Language and Applications, Part 1 & 2](/wp-content/uploads/hc_archives/hc29/HC29.20-Tutorials-Pub/HC29.20.1-P4-Soft-Net-Pub/HC29.21.100-P4-Tutorial.pdf)
</td>

<td colspan="2" >Jeongkeun Lee, Barefoot Networks; and Robert Halstead, Xilinx
</td>
</tr>
<tr >

<td >10:20 AM
</td>

<td >Break
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
<tr >

<td >10:40 AM
</td>

<td >T1
</td>

<td >Overview of the P4 tools
</td>

<td colspan="2" >Andy Fingerhut, Cisco
</td>
</tr>
<tr >

<td >11:10 AM
</td>

<td >T1
</td>

<td >P4 Hardware Implementations
</td>

<td colspan="2" >Jeongkeun Lee, Barefoot Networks; Johann Tonsing, Netronome; and Robert Halstead, Xilinx
</td>
</tr>
<tr >

<td >12:10 PM
</td>

<td >T1
</td>

<td >Future Directions: Research Problems, Getting Involved, and Resources
</td>

<td colspan="2" >Andy Fingerhut, Cisco
</td>
</tr>
<tr >

<td >12:20 PM
</td>

<td >Lunch
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
<tr >

<td colspan="5" >**Tutorial 2: Building Autonomous Vehicles with NVIDIA’s DRIVE Platform**

It is not hard to imagine a day in the near future where explaining the concept of driving would be analogous to explaining the concept of using a cassette player to play music today. The path to this scenario is paved by the rise of autonomous vehicles towards making our roads safer, and in doing so, redefining transportation as we know it.

NVIDIA's DRIVE platform provides the foundation and the building blocks to enable development and a path to production for autonomous vehicle development. The hardware's rich sensor input capability enables data acquisition for use cases such as neural network training and HD map generation and updates. The provided software accelerates the development of autonomous vehicle technologies such as perception, localization, and path planning. This platform provides a seamless transition for algorithms and tools created and tested on the development platform onto products that would demand the quality and safety certification supplied by our Tier 1 partners.

We will be covering the advancements in hardware which facilitate optimized computation for self-driving tasks, including the detection of objects/obstacles around the vehicle. Until recently, the perception of the world around the vehicle was primarily derived from hand-crafted computer vision algorithms. While these handcrafted algorithms were adequate for basic ADAS, it is simply impossible to manually write code for every possible scenario an autonomous vehicle (AV) might encounter. AV requires a new computing model which is deep learning. Deep learning algorithms help address the issues of robustness, accuracy, and scalability, and they have become more relevant through the advancements in the availability of big data, compute power, and accelerated frameworks.

The goal of this tutorial is to provide an overview of the autonomous vehicle landscape through NVIDIA’s platform and to highlight how deep neural networks are changing the autonomous vehicle landscape.
</td>
</tr>
<tr >

<td >1:35 PM
</td>

<td >T2
</td>

<td >[An Overview of NVIDIA’s Autonomous Vehicles Platform](/wp-content/uploads/hc_archives/hc29/HC29.20-Tutorials-Pub/HC29.20.2-Autonomous-Pub/HC29.20.220.Deep Neural Networks Autonomous Vehicle Landscape - NVIDIA - final.pdf)
</td>

<td >Pradeep Kumar Gupta
</td>

<td >NVIDIA
</td>
</tr>
<tr >

<td >2:50 PM
</td>

<td >Break
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
<tr >

<td >3:15 PM
</td>

<td >T2
</td>

<td >[Deep Neural Networks – Changing the Autonomous Vehicles Landscape](/wp-content/uploads/hc_archives/hc29/HC29.20-Tutorials-Pub/HC29.20.2-Autonomous-Pub/HC29.20.210.An Overview of NVIDIAs Autonomous Vehicles Platform-v2.pdf)
</td>

<td >Dennis Lui
</td>

<td >NVIDIA
</td>
</tr>
<tr >

<td >4:30 PM
</td>

<td >Reception
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
<tr >

<td >6:00 PM
</td>

<td >End of Reception
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
</tbody>
</table>
[/tab]
[tab title="Conf. Day1"]


# Conference Day1


<table > 
<tbody >
<tr >

<td >**Mon 8/21**
</td>

<td >**Session**
</td>

<td >**Title**
</td>

<td >**Presenter**
</td>

<td >**Affiliation**
</td>
</tr>
<tr >

<td >7:30 AM
</td>

<td >Breakfast
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
<tr >

<td >9:15 AM
</td>

<td >Introduction
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
<tr >

<td >9:30 AM
</td>

<td >GPU and Gaming
</td>

<td >[The Xbox One X Scorpio Engine](/wp-content/uploads/hc_archives/hc29/HC29.21-Monday-Pub/HC29.21.10-GPU-Gaming-Pub/HC29.21.110-Xbox-Sell-Microsoft.pdf)
</td>

<td >John Sell
</td>

<td >Microsoft
</td>
</tr>
<tr >

<td >10:00 AM
</td>

<td >Eclipse Viewing Break
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
<tr >

<td >10:30 AM
</td>

<td >GPU and Gaming (cont)
</td>

<td >[AMD's Radeon Next Generation GPU](/wp-content/uploads/hc_archives/hc29/HC29.21-Monday-Pub/HC29.21.10-GPU-Gaming-Pub/HC29.21.120-Radeon-Vega10-Mantor-AMD-f1.pdf)
</td>

<td >Michael Mantor & Ben Sander
</td>

<td >AMD
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td >[NVIDIA's Volta GPU: Programmability and Performance for GPU Computing](/wp-content/uploads/hc_archives/hc29/HC29.21-Monday-Pub/HC29.21.10-GPU-Gaming-Pub/HC29.21.132-Volta-Choquette-NVIDIA-Final3.pdf)
</td>

<td >Jack Choquette
</td>

<td >NVIDIA
</td>
</tr>
<tr >

<td >11:30 AM
</td>

<td >IOT/Embedded
</td>

<td >[SiFive Freedom SoCs: Industry's First Open-Source RISC-V Chips](/wp-content/uploads/hc_archives/hc29/HC29.21-Monday-Pub/HC29.21.20-IOT-Embedded-Pub/HC29.21.210-Freedom-SoCs-Lee-SiFive-v2.pdf)
</td>

<td >Yunsup Lee
</td>

<td >SiFive
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td >[Self-timed ARM M3 Microcontroller for Energy Harvested Applications](/wp-content/uploads/hc_archives/hc29/HC29.21-Monday-Pub/HC29.21.20-IOT-Embedded-Pub/HC29.21.220-ARM-M3-Baker-etacmpute-20JULY2017A.pdf)
</td>

<td >David Baker
</td>

<td >ETA Compute
</td>
</tr>
<tr >

<td >12:30 PM
</td>

<td >Lunch
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
<tr >

<td >1:45 PM
</td>

<td >Keynote 1
</td>

<td >The Direct Human/Machine Interface and hints of a General Artificial Intelligence
</td>

<td >Dr. Phillip Alvelda
</td>

<td >Wiseteachers.com, Former DARPA PM
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td colspan="3" >Abstract: Dr. Alvelda will speak about the latest and future developments in Brain-Machine Interface, and how new discoveries and interdisciplinary work in neuroscience are driving new extensions to information theory and computing architectures.
</td>
</tr>
<tr >

<td >2:45 PM
</td>

<td >Automotive
</td>

<td >[R-Car Gen3: Computing Platform for Autonomous Driving Era](/wp-content/uploads/hc_archives/hc29/HC29.21-Monday-Pub/HC29.21.30-Automotive-Pub/HC29.21.310-RCarGen3-Igarashi-Renesas-v1d2c.pdf)
</td>

<td >Mitsuhiko Igarashi & Kazuki Fukuoka
</td>

<td >Renesas Electronics Corporation
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td >[Localization for Next Generation Autonomous Vehicles](/wp-content/uploads/hc_archives/hc29/HC29.21-Monday-Pub/HC29.21.30-Automotive-Pub/HC29.21.320-Local-Vehicles-Fergus-SwiftNavigation-3.pdf)
</td>

<td >Fergus Noble
</td>

<td >Swift Navigation
</td>
</tr>
<tr >

<td >3:45 PM
</td>

<td >Break
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
<tr >

<td >4:15 PM
</td>

<td >Processors
</td>

<td >[XPU: A programmable FPGA Accelerator for diverse workloads](/wp-content/uploads/hc_archives/hc29/HC29.21-Monday-Pub/HC29.21.40-Processors-Pub/HC29.21.410-XPU-FPGA-Ouyang-Baidu.pdf)
</td>

<td >Jian Ouyang
</td>

<td >Baidu
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td >[Knights Mill: Intel Xeon Phi Processor for Machine Learning](/wp-content/uploads/hc_archives/hc29/HC29.21-Monday-Pub/HC29.21.40-Processors-Pub/HC29.21.421-Knights-Mill-Bradford-Intel-APPROVED.pdf)
</td>

<td >Jesus Corbal (Lead Presenter), Nawab Ali, Dennis Bradford, Sundaram Chinthamani, Ken Janik, Adhiraj Hassan
</td>

<td >Intel
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td >[Celerity: An Open Source RISC-V Tiered Accelerator Fabric](/wp-content/uploads/hc_archives/hc29/HC29.21-Monday-Pub/HC29.21.40-Processors-Pub/HC29.21.430-Celerity-RISC-V-Davidson-UCSD.pdf)
</td>

<td colspan="2" >Scott Davidson (UC San Diego), Khalid Al-Hawaj (Cornell) and Austin Rovinski ( U. Michigan)
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td >[Graph Streaming Processor (GSP) A Next-Generation Computing Architecture](/wp-content/uploads/hc_archives/hc29/HC29.21-Monday-Pub/HC29.21.40-Processors-Pub/HC29.21.440-Graph-Streaming-Cook-ThinCl-v1.1.pdf)
</td>

<td >Val Cook
</td>

<td >ThinCI
</td>
</tr>
<tr >

<td >6:15 PM
</td>

<td >Reception
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
<tr >

<td >7:15 PM
</td>

<td >End of Reception
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
</tbody>
</table>
[/tab]
[tab title="Conf. Day2"]


# Conference Day2


<table > 
<tbody >
<tr >

<td >**Tue 8/22**
</td>

<td >**Session**
</td>

<td >**Title**
</td>

<td >**Presenter**
</td>

<td >**Affiliation**
</td>
</tr>
<tr >

<td >7:15 AM
</td>

<td >Breakfast
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
<tr >

<td >8:15 AM
</td>

<td >FPGA
</td>

<td >[Xilinx RFSoC: Monolithic Integration of RF Data Converters with All Programmable SoC in 16nm FinFET for Digital-RF Communications](/wp-content/uploads/hc_archives/hc29/HC29.22-Tuesday-Pub/HC29.22.50-FPGA-Pub/HC29.22.511-RFSoC-Farley-Xilinx-Final.pdf)
</td>

<td >Brendan Farley
</td>

<td >Xilinx
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td >[Stratix 10: Intel's 14nm Heterogeneous FPGA System-in-Package (SiP) Platform](/wp-content/uploads/hc_archives/hc29/HC29.22-Tuesday-Pub/HC29.22.50-FPGA-Pub/HC29.22.523-Hetro-Mod-Platform-Shumanrayev-Intel-Final.pdf)
</td>

<td >Sergey Shumarayev
</td>

<td >Altera/Intel
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td >[Xilinx 16nm Datacenter Device Family with In-Package HBM and CCIX Interconnect](/wp-content/uploads/hc_archives/hc29/HC29.22-Tuesday-Pub/HC29.22.50-FPGA-Pub/HC29.22.530-Datacenter-16nm-Singh-Xilinx-VU37p-rev5.pdf)
</td>

<td >Gaurav Singh & Sagheer Ahmad
</td>

<td >Xilinx
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td >[FPGA Accelerated Computing Using AWS F1 Instances](/wp-content/uploads/hc_archives/hc29/HC29.22-Tuesday-Pub/HC29.22.50-FPGA-Pub/HC29.22.544-AWS-F1-Pellerin-Amazon v4.pdf)
</td>

<td >David Pellerin
</td>

<td >Amazon
</td>
</tr>
<tr >

<td >10:15 AM
</td>

<td >Break
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
<tr >

<td >10:45 AM
</td>

<td >Neural Net 1
</td>

<td >[A Dataflow Processing Chip for Training Deep Neural Networks](/wp-content/uploads/hc_archives/hc29/HC29.22-Tuesday-Pub/HC29.22.60-NeuralNet1-Pub/HC29.22.610-Dataflow-Deep-Nicol-Wave-07012017.pdf)
</td>

<td >Chris Nicol
</td>

<td >Wave Computing
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td >[Accelerating Persistent Neural Networks at Datacenter Scale](/wp-content/uploads/hc_archives/hc29/HC29.22-Tuesday-Pub/HC29.22.60-NeuralNet1-Pub/HC29.22,622-Brainwave-Datacenter-Chung-Microsoft-2017_08_11_2017.pdf)
</td>

<td >Eric Chung & Jeremy Fowers
</td>

<td >Microsoft
</td>
</tr>
<tr >

<td >11:45 AM
</td>

<td >Keynote 2
</td>

<td >[Recent Advances in Artificial Intelligence via Machine Learning and the Implications for](/wp-content/uploads/hc_archives/hc29/HC29.22-Tuesday-Pub/HC29.22.69-Key2-AI-ML-Pub/HotChips keynote Jeff Dean - August 2017.pdf)
Computer System Design
</td>

<td >Jeff Dean
</td>

<td >Google
</td>
</tr>
<tr >

<td >12:45 PM
</td>

<td >Lunch
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
<tr >

<td >2:00 PM
</td>

<td >Neural Net 2
</td>

<td >[DNN ENGINE: A 16nm Sub-uJ Deep Neural Network Inference Accelerator for the Embedded Masses](/wp-content/uploads/hc_archives/hc29/HC29.22-Tuesday-Pub/HC29.22.70-NeuralNet2-Pub/HC29.22.711-DNN-Engine-Whatmough-ARM-0.6_clean.pdf)
</td>

<td >Paul Whatmough
</td>

<td >Harvard University/ARM Research
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td >[DNPU: An Energy-Efficient Deep Neural Network Processor with On-Chip Stereo Matching](/wp-content/uploads/hc_archives/hc29/HC29.22-Tuesday-Pub/HC29.22.70-NeuralNet2-Pub/HC29.22.721-DNPU-Shin-KAIST-3rd.pdf)
</td>

<td >Dongjoo Shin & Hoi-Jun Yoo
</td>

<td >KAIST
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td >[Evaluation of the Tensor Processing Unit: A Deep Neural Network Accelerator for the Datacenter](/wp-content/uploads/hc_archives/hc29/HC29.22-Tuesday-Pub/HC29.22.70-NeuralNet2-Pub/HC29.22.730-TensorPU-Young-Google.pdf)
</td>

<td >Cliff Young
</td>

<td >Google
</td>
</tr>
<tr >

<td >3:30 PM
</td>

<td >Architecture
</td>

<td >[A 400Gbps Multi-Core Network Processor](/wp-content/uploads/hc_archives/hc29/HC29.22-Tuesday-Pub/HC29.22.80-Architectdure-Pub/HC29,22,810-400gbs-NPU-Markevitch-Cisco.pdf)
</td>

<td >James Markevitch & Srinivasa Malladi
</td>

<td >Cisco
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td >[ARM DynamIQ: Intelligent Solutions using Cluster Based Multi-Processing](/wp-content/uploads/hc_archives/hc29/HC29.22-Tuesday-Pub/HC29.22.80-Architectdure-Pub/HC29,22,820-DynamiQ-Greenhaigh-ARM.pdf)
</td>

<td >Peter Greenhalgh
</td>

<td >ARM
</td>
</tr>
<tr >

<td >4:30 PM
</td>

<td >Break
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
<tr >

<td >5:00 PM
</td>

<td >Server
</td>

<td >[The Next Generation IBM Z Systems Processor](/wp-content/uploads/hc_archives/hc29/HC29.22-Tuesday-Pub/HC29.22.90-Server-Pub/HC29.22.910-Z14-processor-Jacobi-IBM.pdf)
</td>

<td >Christian Jacobi & Anthony Saporito
</td>

<td >IBM
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td >[The Next Generation AMD Enterprise Server Product Architecture](/wp-content/uploads/hc_archives/hc29/HC29.22-Tuesday-Pub/HC29.22.90-Server-Pub/HC29.22.921-EPYC-Lepak-AMD-v2.pdf)
</td>

<td >Kevin Lepak
</td>

<td >AMD
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td >[The New Intel® Xeon® Processor Scalable Family (Formerly Skylake-SP)](/wp-content/uploads/hc_archives/hc29/HC29.22-Tuesday-Pub/HC29.22.90-Server-Pub/HC29.22.930-Xeon-Skylake-sp-Kumar-Intel.pdf)
</td>

<td >Akhilesh Kumar
</td>

<td >Intel
</td>
</tr>
<tr >

<td >
</td>

<td >
</td>

<td >[Qualcomm Centriq 2400 Processor](/wp-content/uploads/hc_archives/hc29/HC29.22-Tuesday-Pub/HC29.22.90-Server-Pub/HC29.22.942-Centriq-2400-Wolford-Qualcomm Final Submission corrected.pdf)
</td>

<td >Thomas Speier & Barry Wolford
</td>

<td >Qualcomm
</td>
</tr>
<tr >

<td >7:00 PM
</td>

<td >Closing Remarks
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
<tr >

<td >7:15 PM
</td>

<td >End of Conference
</td>

<td >
</td>

<td >
</td>

<td >
</td>
</tr>
</tbody>
</table>
[/tab]
[tab title="Posters"]


# Posters


<table > 
<tbody >
<tr >

<td >**Title**
</td>

<td >**Presenter**
</td>
</tr>
</tbody>
</table>
<table style="width: 584px;" >
<tbody >
<tr >

<td style="width: 277px;" >[Using Texture Compression Hardware for Neural Network Inference](/wp-content/uploads/hc_archives/hc29/HC29.23-Posters-Pub/HC29.23.p10-Texture-Compression-Sharma-GeorgiaTech-v02.pdf)
</td>

<td style="width: 287px;" >Hardik Sharma, Tom Olson and Alex Chalfin (Georgia Institute of Technology and ARM)
</td>
</tr>
<tr >

<td style="width: 277px;" >[SoundTracing: Real-time Sound Propagation Hardware Accelerator](/wp-content/uploads/hc_archives/hc29/HC29.23-Posters-Pub/HC29.23.p20-Sound-Tracing-Hong-SejongUniv-v01.pdf)
</td>

<td style="width: 287px;" >Dukki Hong, Tae-Hyung Lee, Woonam Chung, Jinseok Hur, Yejong Joo, Juwon Yun, Imjae Hwang and Woo-Chan Park (Sejong University)
</td>
</tr>
<tr >

<td style="width: 277px;" >[A Memory-Efficient Persistent Key-value Store on eNVM SSDs](/wp-content/uploads/hc_archives/hc29/HC29.23-Posters-Pub/HC29.23.p30-Key-Value-De-WesternDigital-v01.pdf)
</td>

<td style="width: 287px;" >Arup De and Zvonimir Bandic (Western Digital)
</td>
</tr>
<tr >

<td style="width: 277px;" >[Accelerating Big Data Workloads with FPGAs](/wp-content/uploads/hc_archives/hc29/HC29.23-Posters-Pub/HC29.23.p40-HyperAcclerator-Samynathan-Bigstream-v.1.5.pdf)
</td>

<td style="width: 287px;" >Balavinayagam Samynathan, Shahrzad Mirkhani, Weiwei Chen, John Davis, Maysam Lavasani and Behnam Robatmili (Bigstream)
</td>
</tr>
<tr >

<td style="width: 277px;" >[Loom: A Precision Exploiting Neural Network Accelerator](/wp-content/uploads/hc_archives/hc29/HC29.23-Posters-Pub/HC29.23.p50-Loom.pdf)
</td>

<td style="width: 287px;" >Sayeh Sharify (University of Toronto)
</td>
</tr>
<tr >

<td style="width: 277px;" >[EPIPHANY-V: A TFLOPS scale 16nm 1024-core 64-bit RISC Array Processor](/wp-content/uploads/hc_archives/hc29/HC29.23-Posters-Pub/HC29.23.p60-Adapteva.pdf)
</td>

<td style="width: 287px;" >Andreas Olofsson (Adapteva, Inc.)
</td>
</tr>
<tr >

<td style="width: 277px;" >[Fully-Integrated Surround Vision and Mirror Replacement SoC for ADAS/Automated Driving](/wp-content/uploads/hc_archives/hc29/HC29.23-Posters-Pub/HC29.23.p72-Surround-Vision-Mody-TexasInstruments-v02.pdf)
</td>

<td style="width: 287px;" >Mihir Mody, Piyali Piyali, Rajat Sagar, Gregory Shurtz, Abhinay Armstrong, Yashwant Dutt, Kedar Chitnis, Peter Labaziewicz, Jason Jones and Manoj Koul (Texas Instruments)
</td>
</tr>
<tr >

<td style="width: 277px;" >[GRVI Phalanx On Xilinx Virtex UltraScale+: A 1680-core, 26 MB RISC-V FPGA Parallel Processor Overlay](/wp-content/uploads/hc_archives/hc29/HC29.23-Posters-Pub/HC29.23.p81-GRVI-Phalanx-Gray-GrayReserach-poster=v2.pdf) [[Abstract](/wp-content/uploads/hc_archives/hc29/HC29.23-Posters-Pub/HC29.23.p80-GRVI-Phalanx-Gray-GrayReserach-extd-abs.pdf)]
</td>

<td style="width: 287px;" >Jan Gray (Gray Research LLC)
</td>
</tr>
<tr >

<td style="width: 277px;" >
</td>

<td style="width: 287px;" >
</td>
</tr>
</tbody>
</table>
[/tab]
[/tabs]
[/accordion]		
