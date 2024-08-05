# Awesome Crowd Dynamics Hub

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repository is dedicated to providing a curated collection of open-source tools and resources for the study and analysis of crowd dynamics, pedestrian flow, and evacuation strategies.

## Table of Contents

- [Introduction](#introduction)
- [Tools](#tools)
- [Datasets](#datasets)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Understanding crowd dynamics and pedestrian behavior is crucial for ensuring safety and efficiency in various environments, from urban planning to emergency evacuation. This repository aims to gather the best open-source tools and resources available for researchers, practitioners, and enthusiasts in the field.

## Tools

| Tool                                        | Description                                                                                                             | Documentation & Repository                                                                                  | Key Features                                                         | Programming Language                             |
|---------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------|--------------------------------------------------|
| **PedPy**                                   | A Python library for pedestrian movement analysis, providing methods for extracting fundamental measurements from trajectory data, including velocity, flow, and density. | [Documentation](https://pedpy.readthedocs.io/en/stable/), [GitHub](https://github.com/PedestrianDynamics/PedPy)                  | Compute fundamental diagrams, analysis of pedestrian trajectories, plotting functionalities for visualization | Python                                           |
| **JuPedSim**                                | An open-source framework for simulating pedestrian dynamics. It emphasizes flexibility and prototyping of models on the tactical and strategical levels. | [Documentation](https://www.jupedsim.org/stable/), [GitHub](https://github.com/PedestrianDynamics/jupedsim) | Several operational models, C-API for coupling with other software like [SUMO](https://sumo.dlr.de/docs/Simulation/Pedestrians.html#model_jupedsim), Basic visualization tool| C++, Python                                      |
| **Vadere**                                  | An open-source framework for the simulation and analysis of pedestrian dynamics, offering various models to simulate pedestrian behavior in different environments. | [Website](https://www.vadere.org/)                                                                                              | Multiple pedestrian behavior models, simulation and analysis tools, extensive visualization capabilities | Java                                             |
| **PeTrack**                                 | A tool for the empirical analysis of pedestrian dynamics, allowing for tracking and analysis of pedestrian trajectories from video recordings.           | [Wiki](https://jugit.fz-juelich.de/ped-dyn-emp/petrack/-/wikis/home)                                                             | Tracking pedestrian movements from videos, analysis of pedestrian trajectories, visualization tools | Python, C++                                      |
| **UMANS**                                   | A crowd-simulation framework that can reproduce many different algorithms for local collision avoidance and pedestrian behavior.                        | [Project Page](https://project.inria.fr/crowdscience/project/ocsr/umans/)                                                      | Agent-based modeling, customizable pedestrian behaviors, integration with other simulation tools    | C++                                              |
| **CromoSim**                                | A simulation tool for crowd dynamics, focusing on realistic modeling and analysis of pedestrian movements.                                               | [Website](https://www.cromosim.fr/)                                                                                             | Realistic crowd simulations, analysis of pedestrian flow and behavior, visualization tools         | Python                                           |
| **CrowNet**                                 | A simulation framework for the development of new networked mobility concepts and intelligent transportation systems, using network-based approaches.     | [GitHub](https://github.com/roVer-HM/crownet)                                                                                   | Network-based simulation models, analysis tools for crowd movement, integration with other simulation frameworks | Python, C++                                              |
| **SocialForce**                             | A Python library for simulating pedestrian dynamics using the social force model.                                                                         | [GitHub](https://github.com/svenkreiss/socialforce)                                                                             | Social force model implementation, simulation of pedestrian interactions, visualization tools       | Python                                           |
| **JPSreport**                               | A tool for analyzing pedestrian trajectories and generating reports on pedestrian dynamics.                                                               | [Website](https://jupedsim.github.io/jpsreport/)                                                                                | Analysis of pedestrian trajectories, reporting tools for pedestrian dynamics, integration with JuPedSim | Python, C++                                      |
| **PySocialForce**                           | A Python library for simulating pedestrian dynamics using the extended social force model.                                                                | [GitHub](https://github.com/yuxiang-gao/PySocialForce)                                                                          | Social force model implementation, simulation and analysis tools, visualization capabilities        | Python                                           |                                         |
| **Forest-Fire-CNNs**                        | Uses UAV imagery and Convolutional Neural Networks (CNNs) to detect forest fires.                                                                   | [GitHub](https://github.com/LeadingIndiaAI/Forest-Fire-Detection-through-UAV-imagery-using-CNNs)                                | UAV imagery, CNNs, wildfire detection                                                             | Python                                           |
| **Robot-Motion-Planning-in-ROS-Kinetic**    | Implements D* and A* path planning algorithms for TurtleBot-guided crowd evacuation scenarios.                                                         | [GitHub](https://github.com/Folk4681/Robot-Motion-Planning-in-ROS-Kinetic)                                                      | D* and A* algorithms, dynamic window approach, ROS integration                                      | C++, Python                                      |
| **MesaFireEvacuation**                      | Agent-based fire evacuation model using Project Mesa.                                                                                                    | [GitHub](https://github.com/chadsr/MesaFireEvacuation)                                                                          | Agent-based modeling, Bresenham's line algorithm, visual and batch runs                            | Python                                           |
| **Louvre_Evacuation**                       | Simulates evacuation scenarios in the Louvre museum.                                                                                                     | [GitHub](https://github.com/izcat/Louvre_Evacuation)                                                                            | Map-based simulation, agent-based modeling                                                         | Python                                           |
| **pedsim**                                  | Pedestrian simulator for robot navigation experiments in crowded scenes.                                                                                 | [GitHub](https://github.com/chgloor/pedsim)                                                                                     | Social force model, group walking, sensor simulation, ROS integration                              | C++                                              |
| **Crowd Evacuation Simulation**             | Simulates crowd evacuation using NetLogo, focusing on human stampede effects.                                                                         | [GitHub](https://github.com/shingkid/crowd-evacuation-simulation)                                                               | Multi-agent systems, panic level simulation, NetLogo model                                         | NetLogo                                          |
| **EvacuationModel**                         | Agent-based evacuation model for city-level scenarios, including tsunamis.                                                                               | [GitHub](https://github.com/armostafizi/EvacuationModel)                                                                        | Horizontal and vertical evacuation, pedestrian and vehicle simulation, NetLogo                     | NetLogo                                          |
| **MCM-ICM-2019**                            | Code and report for MCM/ICM 2019 competition.                                                                                                            | [GitHub](https://github.com/icepear-jzx/MCM-ICM-2019)                                                                           | Various models and simulations                                                                     | Python                                           |
| **Evacuation-Simulator**                    | Simulates evacuation scenarios with a focus on pedestrian behavior.                                                                                      | [GitHub](https://github.com/gia-urjc/Evacuation-Simulator)                                                                      | Pedestrian behavior modeling, evacuation routes                                                    | Python                                           |
| **mistral-evacuate**                        | Automatic evacuation for VMs in OpenStack cloud using Mistral.                                                                                           | [GitHub](https://github.com/gryf/mistral-evacuate)                                                                              | VM evacuation, OpenStack integration                                                               | Python                                           |
| **Evacuation-Bottleneck**                   | Models crowd behavior in panic situations.                                                                                                               | [GitHub](https://github.com/fschur/Evacuation-Bottleneck)                                                                       | Crowd behavior modeling, bottleneck analysis                                                       | Python                                           |
| **aamks**                                   | Probabilistic fire risk assessment framework.                                                                                                            | [GitHub](https://github.com/aamks/aamks)                                                                                        | Monte Carlo simulations, fire and evacuation modeling, web-based                                   | Python                                           |
| **Evacuation**                              | Calculates the max flow of people to evacuate in a city.                                                                                                 | [GitHub](https://github.com/labseven/Evacuation)                                                                               | Max flow calculation, city evacuation modeling                                                     | Python                                           |
| **MultiExit-Rainbow**                       | Simulates multi-exit evacuation scenarios.                                                                                                               | [GitHub](https://github.com/XD1227/MultiExit-Rainbow)                                                                          | Multi-exit strategies, evacuation simulation                                                       | Python                                           |
| **fire-evacuation-simulator**               | Simulates fire evacuation in confined spaces.                                                                                                           | [GitHub](https://github.com/aalok-sathe/fire-evacuation-simulator)                                                              | Agent-based modeling, fire spread simulation                                                       | Python                                           |
| **PyroRL**                                  | Reinforcement learning for fire evacuation scenarios.                                                                                                    | [GitHub](https://github.com/sisl/PyroRL)                                                                                        | Reinforcement learning, fire evacuation                                                            | Python                                           |
| **evacuationcenter**                        | Simulates evacuation center management.                                                                                                                  | [GitHub](https://github.com/joserodny/evacuationcenter)                                                                         | Evacuation center management, resource allocation                                                  | Blade, PHP                                           |
| **Emergency-Fire-Evacuation-System**        | Emergency fire evacuation system prototype.                                                                              | [GitHub](https://github.com/52North/Emergency-Fire-Evacuation-System)                                                           | Fire evacuation, emergency response                                                                | Java                                           |
| **ees**                                     | Emergency evacuation simulation tool.                                                                                                                    | [GitHub](https://github.com/agentsoz/ees)                                                                                       | Evacuation simulation, agent-based modeling                                                        | Java, R, Python                                           |
| **themis**                                  | Evacuation simulation for large buildings.                                                                                                               | [GitHub](https://github.com/ljjjustin/themis)                                                                                   | Large building evacuation, simulation modeling                                                     | Go                                           |
| **floor-evacuation-simulator**              | Simulates floor evacuation scenarios.                                                                                                                  | [GitHub](https://github.com/MingkuanXu/floor-evacuation-simulator)                                                              | Floor evacuation, agent-based modeling                                                             | Java                                           |
| **Cellular_Automata_Pedestrians**           | Models pedestrian behavior using cellular automata.                                                                       | [GitHub](https://github.com/Silvia-exe/Cellular_Automata_Pedestrians)                                                           | Cellular automata, pedestrian simulation                                                           | C++, Python                                           |
| **Social-Force-Model-Crowd-Simulation**     | Crowd simulation using the social force model.                                                                             | [GitHub](https://github.com/jwmeindertsma/Social-Force-Model-Crowd-Simulation)                                                  | Social force model, crowd behavior                                                                 | Python                                           |
| **evacuation**                              | Simulates evacuation scenarios in various environments.                                                                                                 | [GitHub](https://github.com/cinemere/evacuation)                                                                                | Evacuation modeling, multi-environment simulation                                                  | Python                                           |
| **CalFireAlertChatBot**                     | Chatbot for fire alerts and evacuation guidance.                                                                                                        | [GitHub](https://github.com/amittallapragada/CalFireAlertChatBot)                                                               | Fire alerts, chatbot integration                                                                   | Python                                           |
| **Optimizing-Evac-Routes**                  | Optimizes evacuation routes for emergencies.                                                                                                            | [GitHub](https://github.com/balak4/Optimizing-Evac-Routes)                                                                      | Route optimization, emergency evacuation                                                           | Python                                           |
| **EmergencyEvac**                           | Models and simulates emergency evacuation scenarios.                                                                       | [GitHub](https://github.com/aajayssingh/EmergencyEvacuationModellingAndSimulation)                                              | Evacuation modeling, simulation tools                                                              | Python, HTML, C++                                           |

## Datasets

| Dataset                                        | Description                                                                                                             | Access Link                                                                                   | Key Features                                                         | Usage Instructions                                      |
|------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|----------------------------------------------------------------------|----------------------------------------------------------|
| **Jülich Pedestrian Data Archive**             | A comprehensive data archive containing pedestrian trajectory data from various experiments.                            | [Access Link](https://ped.fz-juelich.de/da/doku.php?id=start#data_section)                    | - High-quality trajectory data<br> - Multiple experimental setups<br> - Detailed metadata and documentation | Visit the access link and follow the provided instructions to download and use the datasets. |
| **External Database of Pedestrian Dynamics**   | An extensive collection of external datasets related to pedestrian dynamics, available for research purposes.            | [Access Link](https://ped.fz-juelich.de/da/doku.php?id=extdb)                                 | - Diverse datasets from different sources<br> - Ready-to-use formats<br> - Documentation and usage examples  | Visit the access link and follow the provided instructions to download and use the datasets. |
| **Decision making of individuals**   | A dataset related to the "[How simple behavioural modifications can influence evacuation efficiency of crowds: Part 1. Decision making of individuals](https://doi.org/10.1016/j.trc.2024.104763)" paper            | [Access Link](https://github.com/Milad-Haghani/Decision-making-of-individuals)                                 | -  | Visit the access link, download and use the datasets. |
| **Physical movement of individuals**   | A dataset related to the "[How simple behavioural modifications can influence evacuation efficiency of crowds: Part 2. Physical movement of individuals](https://doi.org/10.1016/j.trc.2024.104762)" paper            | [Access Link](https://github.com/Milad-Haghani/Physical-movement-of-individuals)                                 | -  | Visit the access link, download and use the datasets. |



## Contributing

We welcome contributions from the community! If you have a tool, dataset, or publication that you believe should be included in this repository, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-new-resource`).
3. Make your changes and commit them (`git commit -m 'Add new resource'`).
4. Push to the branch (`git push origin feature-new-resource`).
5. Create a new Pull Request.

Please ensure your contributions adhere to our [Code of Conduct](CODE_OF_CONDUCT.md).

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

We hope you find these resources helpful! If you have any questions or suggestions, feel free to open an issue or contact us.

Happy researching!
