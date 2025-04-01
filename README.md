# Workflow Provenance for AI-HPC Integration with FlowCept: Analyzing Tradeoffs Between Model Design Choices, Accuracy, and Resource Consumption

## Abstract

Developing large and complex AI models involving HPC systems is a challenging human-driven process. AI scientists must balance model accuracy and resource efficiency while navigating a vast design space where minor adjustments to model architecture, hyperparameters, or datasets can marginally improve accuracy but significantly impact computational costs. This decision-making process is further complicated by the need to integrate and analyze multiple interconnected workflows (e.g., for data preparation and model training, or multi-model pipelines).

To support scientists, we present a workflow provenance data-centric framework that provides a seamless and context-aware integration of multiple workflows in large-scale HPC training at runtime. Our system is composable and loosely coupled to the used tools, provides adapters to multiple systems such as Dask and MLFlow, and collects telemetry from both Nvidia and AMD GPUs alongside CPUs, memory, and storage. Using FlowCept, our in-house developed system that implements this framework, we help AI scientists navigate a vast design space whil



# Flowcept GitHub Repo

https://github.com/ornl/flowcept

# Recorded Demo

[Link](https://drive.google.com/file/d/1OX6wYAc83ca3EEscLdpBoR4CZPRkf-Kg/view?usp=sharing)

# References

### Multi-workflow provenance using Data Observability
[pdf](https://arxiv.org/pdf/2308.09004.pdf) Towards Lightweight Data Integration using Multi-workflow Provenance and Data Observability
R. Souza, T. Skluzacek, S. Wilkinson, M. Ziatdinov, and R. da Silva
IEEE International Conference on e-Science, 2023. 

### Vision Paper
[pdf](https://www.osti.gov/servlets/purl/2478344) Workflow Provenance in the Computing Continuum for Responsible, Trustworthy, and Energy-Efficient AI
R. Souza, S. Caino-Lores, M. Coletti, T. Skluzacek, A. Costan, F. Suter, M. Mattoso, and R. Silva
IEEE International Conference on e-Science, 2024. 

### Related Work

A. Gueroudji et al., "Performance Characterization and Provenance of Distributed Task-based Workflows on HPC Platforms," SC24-W: Workshops of the International Conference for High Performance Computing, Networking, Storage and Analysis, Atlanta, GA, USA, 2024, pp. 2032-2039, doi: 10.1109/SCW63240.2024.00254.

### Mofka

http://mofka.readthedocs.io/

### OLCF Frontier

https://www.olcf.ornl.gov/frontier/

# Team

- [Renan Souza](https://renansouza.org), Oak Ridge National Lab, Researcher and Lead developer
- [Rafael Ferreira da Silva](https://rafaelsilva.com/), Oak Ridge National Lab, Senior Researcher, Group Leader
- [Daniel Rosendo](https://www.ornl.gov/staff-profile/daniel-rosendo), Oak Ridge National Lab, Researcher, Developer
- [Amal Gueroudji](https://www.anl.gov/profile/amal-gueroudji), Argonne National Lab, Researcher, Developer
- [Seth Ockerman](https://ockermansethgvsu.github.io/), Argonne National Lab & University of Wisconsin-Madison, Researcher, Developer

### Collaborators

Matthieu Dorier, Mark Coletti, Frederic Suter, Tayler Skluzacek, Ketan Maheshwari, Gavin Wiggins, Silvina Caino-Lores, Mallikarjun (Arjun) Shankar, Sarp Oral, Marta Mattoso, Alexandru Costan





