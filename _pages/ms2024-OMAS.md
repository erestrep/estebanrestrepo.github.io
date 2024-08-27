---
layout: archive
title: "Passivity-aware coordination of open multi-robot systems"
permalink: /ms2024-OMAS/
author_profile: true
---

**Type of position:** Master thesis\
**Team:** [Rainbow](https://team.inria.fr/rainbow/) IRISA/Inria Rennes, France\
**Advised by:** Dr. Esteban Restrepo, Antonio Marino, and Dr. Paolo Robuffo Giordano\
**Contact:** [esteban.restrepo@inria.fr](mailto:esteban.restrepo@inria.fr) – [antonio.marino@irisa.fr](mailto:antonio.marino@irisa.fr) – [prg@irisa.fr](mailto:prg@irisa.fr)\
**How to apply:** [See below](#apply)

________

**Short abstract:** The goal of this Master Thesis is to exploit recent advancements on the topic of open multi-robot systems for the design and experimental validation of a long-term mission with a swarm of aerial robots.

<img src='/images/M2stage.png'>
<span style="font-size:0.8em;">Figure. Snapshots of previous experiments in the team with a fleet of drones.</span>

**Description and motivation:** The deployment of fleets of robotic vehicles has been shown to be effective for a wide range of  applications based on cooperative tasks such as reconnaissance, surveillance, load transportation and imaging. While a fixed number of cooperative robotic agents may be capable of performing “simple” short-term tasks such as, e.g., formation tracking, flocking, or area coverage, it may prove limiting in many practical scenarios. Indeed, as the field advances, applications of multi-robot systems are starting to shift from such relatively simple tasks, to more complex long-term and persistent missions that require the robots to be deployed for longer periods of time, usually surpassing the battery-charge duration of the devices, forcing individual robots to leave the network for recharging and (possibly) returning when fully charged. Moreover, as tasks get more complex and are designed for dynamic and, often, antagonistic environments, failure of individual robots due to malfunctioning or attacks cannot always be prevented. Equivalently, when addressing tasks in uncertain or unknown environments, in order to successfully accomplish the mission, new robots may be required to join the system dynamically as the task specification or the environment evolve. Usually during the development of a mission both the addition and removal of agents are bound to happen, oftentimes, simultaneously.

An Open Multi-Robot System (OMRS) is a system of multiple cooperative robots where agents can be added or removed. Recently, in our team we have started considering the coordination of OMRS in an passivity-aware framework [1] based on the concepts of impulsive switched systems, passivity, and energy-tanks, that allows the OMRS to handle the addition and removal of agents (or groups thereof) autonomously while preserving the passivity of the system.

**General Objectives:** The goal of this Master Thesis is to build upon the passivity-aware coordination framework for OMRS to design a complex and long-term mission on a fleet of quadrotor UAVs, e.g., a long-term surveillance and target-tracking mission, and implement it in simulation and experimentally.

**List of 5 bibliographical references:**

1. E. Restrepo, C. Secchi and P. Robuffo Giordano, “Passivity Preserving Energy-Aware Design for Multi-Dimensional Switched Systems: Application to Open Multi-Robot Systems,” ([hal-04330519](https://hal.science/hal-04330519/document))

1. J. Cortés, M. Egerstedt. Coordinated Control of Multi-Robot Systems: A Survey. SICE Journal of Control, Measurement, and System Integration, vol. 10, no. 6, pp. 495-503, 2017.

1. P. Robuffo Giordano, A. Franchi, C. Secchi, H. H. Bülthoff. A passivity-based decentralized strategy for generalized connectivity maintenance. The International Journal of Robotics Research, vol. 32, no.3, pp. 299-323, 2013.

1. F. Califano, R. Rashad, C. Secchi, S. Stramigioli. On the Use of Energy Tanks for Robotic Systems. In: Borja, P., Della Santina, C., Peternel, L., Torta, E. (eds) Human-Friendly Robotics 2022. Springer Proceedings in Advanced Robotics, vol 26, pp. 174-188, 2022.

1. M. Xue, Y. Tang, W. Ren, F. Qian. Stability of multi-dimensional switched systems with an application to open multi-agent systems. Automatica, vol. 146, 110644, 2022.

**Envisaged Activities:**

1. Literature review of the related works and familiarize with the experimental setup in the team.

1. Design a long-term mission scenario based on the open Multi-agent system framework for a fleet of UAVs.

1. Develop and implement in simulation an algorithm for the proposed mission.

1. Setup the experimental scenario and validate the algorithms on a fleet of Crazyflie drones.

**Requirements:**

- High motivation and interest in the topic

- Good knowledge in control theory and robot modeling

- Good experience using Python/C++, ROS2 and Matlab/Simulink

- Basic knowledge of control and analysis of multi-agent systems is appreciated

- Scientific curiosity


The work will be carried in English at the Centre Inria de l’Université de Rennes research center in Rennes, France.

Financial support offered to the student: gratification de 3,75 € / h

## How to apply: <a name="apply"></a>

Interested candidates are requested to apply via [**this form**](https://forms.gle/nqmRwCzMqTVN41C1A).

The position will remain open until a satisfactory candidate is found.
In case of positive feedback, you will be contacted. If not positive, you won't hear back. 
 
<span style="color:red">Applications sent directly by email and not through the web form will not be considered!!</span>.

**Supervisor(s):** Dr. Esteban Restrepo, Antonio Marino, and Dr. Paolo Robuffo Giordano