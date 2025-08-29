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

| Tool             | Description                                                                                                                                     | Documentation & Repository                                             | Key Features                                                                                     | License       |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|---------------|
| **PedPy**        | An open-source, MIT-licensed Python library for pedestrian movement analysis. It provides a high-level interface for extracting fundamental measurements from trajectory data, including velocity, flow, and density. | [Documentation](https://pedpy.readthedocs.io/en/stable/), [GitHub](https://github.com/PedestrianDynamics/PedPy) | - Compute fundamental diagrams<br> - Analysis of pedestrian trajectories<br> - Plotting functionalities for visualization | Open-Source   |
| **JuPedSim**     | An open-source framework for simulating and analyzing pedestrian dynamics. It supports a variety of simulation and analysis tools tailored for pedestrian movement.                | [Documentation](https://www.jupedsim.org/stable/), [GitHub](https://github.com/PedestrianDynamics/jupedsim)    | - Simulation of pedestrian dynamics<br> - Analysis tools for trajectory data<br> - Visualizations and fundamental diagram computations | Open-Source   |
| **Vadere**       | An open-source framework for the simulation and analysis of pedestrian dynamics. It offers a variety of models to simulate pedestrian behavior in different environments.              | [Website](https://www.vadere.org/)                                      | - Multiple pedestrian behavior models<br> - Simulation and analysis tools<br> - Extensive visualization capabilities         | Open-Source   |
| **PeTrack**      | A tool for the empirical analysis of pedestrian dynamics. It allows for the tracking and analysis of pedestrian trajectories from video recordings.                               | [Wiki](https://jugit.fz-juelich.de/ped-dyn-emp/petrack/-/wikis/home)    | - Tracking pedestrian movements from videos<br> - Analysis of pedestrian trajectories<br> - Visualization tools              | Open-Source   |
| **UMANS**        | Open-source simulation framework for crowd dynamics and pedestrian behavior.                                                                  | [Project Page](https://project.inria.fr/crowdscience/project/ocsr/umans/) | - Agent-based modeling<br> - Customizable pedestrian behaviors<br> - Integration with other simulation tools                  | Open-Source   |
| **CromoSim**     | A simulation tool for crowd dynamics, focusing on realistic modeling and analysis of pedestrian movements.                                    | [Website](https://www.cromosim.fr/)                                     | - Realistic crowd simulations<br> - Analysis of pedestrian flow and behavior<br> - Visualization tools                          | Open-Source    |
| **CrowNet**      | An open-source tool for simulating and analyzing crowd dynamics using network-based approaches.                                                | [GitHub Repository](https://github.com/roVer-HM/crownet)               | - Network-based simulation models<br> - Analysis tools for crowd movement<br> - Integration with other simulation frameworks   | Open-Source   |
| **SocialForce**  | An open-source Python library for simulating pedestrian dynamics using the social force model.                                                 | [GitHub Repository](https://github.com/svenkreiss/socialforce)         | - Social force model implementation<br> - Simulation of pedestrian interactions<br> - Visualization tools                       | Open-Source   |
| **JPSreport**    | An open-source tool for analyzing pedestrian trajectories and generating reports on pedestrian dynamics.                                       | [Website](https://jupedsim.github.io/jpsreport/)                       | - Analysis of pedestrian trajectories<br> - Reporting tools for pedestrian dynamics<br> - Integration with JuPedSim            | Open-Source   |
| **PySocialForce**| An open-source Python library for simulating pedestrian dynamics using the social force model.                                                 | [GitHub Repository](https://github.com/yuxiang-gao/PySocialForce)      | - Social force model implementation<br> - Simulation and analysis tools<br> - Visualization capabilities                       | Open-Source   |
| **Crowd Evacuation Simulation** | An open-source tool for simulating crowd evacuation dynamics.                                                                                   | [GitHub Repository](https://github.com/shingkid/crowd-evacuation-simulation) | - Simulation of crowd evacuation<br> - Analysis tools<br> - Visualization capabilities                                           | Open-Source   |
| **Crowd Evacuation Simulation** | An open-source tool for simulating crowd evacuation dynamics.                                                                                   | [GitHub Repository](https://github.com/JR-Morgan/Crowd-Evacuation-Simulation/tree/master) | - Simulation of crowd evacuation<br> - Analysis tools<br> - Visualization capabilities                                           | Open-Source   |


## Datasets

| Dataset                                        | Description                                                                                                             | Access Link                                                                                   | Key Features                                                         | Usage Instructions                                      |
|------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|----------------------------------------------------------------------|----------------------------------------------------------|
| **Jülich Pedestrian Data Archive**             | A comprehensive data archive containing pedestrian trajectory data from various experiments.                            | [Access Link](https://ped.fz-juelich.de/da/doku.php?id=start#data_section)                    | - High-quality trajectory data<br> - Multiple experimental setups<br> - Detailed metadata and documentation | Visit the access link and follow the provided instructions to download and use the datasets. |
| **External Database of Pedestrian Dynamics**   | An extensive collection of external datasets related to pedestrian dynamics, available for research purposes.            | [Access Link](https://ped.fz-juelich.de/da/doku.php?id=extdb)                                 | - Diverse datasets from different sources<br> - Ready-to-use formats<br> - Documentation and usage examples  | Visit the access link and follow the provided instructions to download and use the datasets. |
| **Dense Crowd Dynamics and Pedestrian Trajectories: A Multiscale Field Dataset from the Festival of Lights in Lyon**   | The datasets referenced in this study in relation to dense pedestrian dynamics during the 2022 Festival of Lights in Lyon, France | [Access Link](https://doi.org/10.1038/s41597-025-04732-3)                                 | - Study, dashboard and Analysis Code are accessible  | Visit the access link to access the paper, description of the data and analysis code |



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
