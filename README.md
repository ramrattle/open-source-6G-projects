# Open-source 6G projects

A curated index of open-source software, datasets, testbeds, and reproducible
research for 6G. This is the 6G companion to the
[100 open-source 5G projects](https://github.com/ramrattle/100-opensource-5G-projects)
list.

**Last reviewed:** 11 August 2026

> [!NOTE]
> 6G is still a research field rather than a deployed standard. Inclusion here
> means that a project explicitly targets 6G research; it does not imply 3GPP
> compliance, production readiness, or endorsement.

## What's new

- Added the ETSI OpenOP Release 1 operator-platform project.
- Added the DeepVerse 6G and BUPTCMCC-6G-DataAI+ multimodal/channel datasets.
- Added NVIDIA's Aerial Omniverse Digital Twin and the 6G-SANDBOX testbed
  ecosystem.
- Added VOTA, a reproducible framework for parallel virtualized OTA experiments.

## Platforms and testbeds

| Project | Focus | Resources |
| --- | --- | --- |
| **ETSI OpenOP** | Operator platform for telco-cloud federation and 6G experimentation. Release 1 was announced on 18 March 2026; code is Apache-licensed. | [Project](https://oop.etsi.org/) · [Release 1](https://oop.etsi.org/news/release-1/) · [License](https://oop.etsi.org/legal/code-license/) |
| **6G-SANDBOX** | European experimentation platform for validating 6G technology across distributed testbeds. | [Project](https://6g-sandbox.eu/) · [GitHub organization](https://github.com/6G-SANDBOX) |
| **OpenAirTwin** | Open-source digital twin for experimenting with wireless systems. | [Code](https://github.com/HKUOpenSource/OpenAirTwin) |
| **6G Testbeds directory** | Community-maintained directory of 6G experimental facilities. | [Code/site](https://github.com/6G-RF/6G-Testbeds.github.io) |
| **OCUDU** | Linux Foundation open-source RAN software and community. | [Project](https://ocudu.org/) |

## Datasets and channel models

| Project | Focus | Resources |
| --- | --- | --- |
| **DeepVerse 6G** | Digital replicas of DeepSense 6G scenarios, combining synchronized vision, LiDAR, radar, positioning, and wireless data. | [Dataset](https://deepverse6g.net/) |
| **BUPTCMCC-6G-DataAI+** | Generative channel data for AI-native air-interface research, spanning mid-band, mmWave, THz, XL-MIMO, RIS, and industrial-IoT scenarios. | [Paper](https://arxiv.org/abs/2410.10839) |
| **DeepMIMO** | Ray-tracing-based channel dataset generator for machine-learning research in wireless communications. | [Code](https://github.com/DeepMIMO/DeepMIMO) |
| **6G Channel Estimation Dataset** | Synthetic channel-estimation dataset and experiments. | [Code](https://github.com/ocatak/6g-channel-estimation-dataset) |

## Toolkits and digital twins

| Project | Focus | Resources |
| --- | --- | --- |
| **Sionna** | GPU-accelerated, differentiable link-level simulation, ray tracing, and system-level wireless research. | [Code](https://github.com/NVlabs/sionna) · [Documentation](https://nvlabs.github.io/sionna/) |
| **Sionna Research Kit** | Tutorials and reference workflows for AI-RAN prototyping with software-defined radios. | [Code](https://github.com/NVlabs/sionna-rk) · [Documentation](https://nvlabs.github.io/sionna/rk/) · [Tutorials](https://nvlabs.github.io/sionna/rk/tutorials/) |
| **Aerial CUDA-Accelerated RAN** | GPU-accelerated 5G/6G physical-layer building blocks. | [Code](https://github.com/NVIDIA/aerial-cuda-accelerated-ran) |
| **Aerial Framework** | Components and examples for accelerated RAN development. | [Code](https://github.com/NVIDIA/aerial-framework) |
| **Aerial Omniverse Digital Twin** | Site-specific digital-twin workflows for 6G and AI-RAN simulation. | [Code](https://github.com/NVIDIA/aerial-omniverse-digital-twin) |
| **6G-Bench** | Benchmark collection for evaluating AI-enabled 6G use cases. | [Code](https://github.com/maferrag/6G-Bench) |

## Research implementations

| Project | Focus | Resources |
| --- | --- | --- |
| **Open Cloud Semantic RAN** | Cloud-native semantic communications for radio access networks. | [Code](https://github.com/6G-Cloud-RnE-Open-Hub/open-cloud-semantic-ran) |
| **EdgeGO** | Simulation and deployment code for resource sharing in massive-IoT edge computing. | [Code](https://github.com/mobinets/6G-Edge-Computing-Simulation-Deployment) · [Paper](https://ieeexplore.ieee.org/document/9375469/) |
| **6G Security** | Machine-learning experiments for wireless attack detection. | [Code](https://github.com/ocatak/6g_security) |
| **Radio Localization** | Learning-based localization for mmWave and THz systems. | [Code](https://github.com/chenhui07c8/Radio_Localization) |
| **End-to-End 6G Terahertz Networks** | Full-stack simulation artifacts for terahertz networking. | [Code](https://github.com/mychele/toward-e2e-6g-terahertz-networks) · [Paper](https://arxiv.org/abs/2005.07989) |
| **MEC-enabled UAV with IRS-assisted 6G THz Networks** | Optimization code for UAV, intelligent-reflecting-surface, and edge-computing scenarios. | [Code](https://github.com/IntelligentNetworkingLAB/MEC-enabled-UAV-with-IRS-assisted-6G-THz-Networks) |
| **LEO Satellite Coverage Maximization** | MAPPO-based deep reinforcement learning for LEO coverage in sub-THz networks. | [Code](https://github.com/IntelligentNetworkingLAB/LEO-Satellite-Coverage-Maximization-in-6G-Sub-THz-Networks-by-MAPPO-DRL) |
| **Radar-aided 6G Beam Prediction** | Radar-assisted beam prediction algorithms and real-world demonstrations. | [Code](https://github.com/umut-demirhan/Radar-aided-beam-prediction) · [Paper](https://arxiv.org/abs/2111.09676) |
| **CommLLM** | LLM-enhanced multi-agent systems for wireless communications. | [Code](https://github.com/jiangfeibo/CommLLM) · [Paper](https://arxiv.org/abs/2312.07850) |
| **LAM4PHY 6G** | Large AI models for physical-layer tasks. | [Code](https://github.com/AI4Wireless/LAM4PHY_6G) |
| **GenSC-6G** | Generative semantic communication research. | [Code](https://github.com/CQILAB-Official/GenSC-6G) |
| **VOTA** | Parallel 6G-RAN experimentation with virtualized over-the-air workloads. | [Code](https://github.com/cl0713/vota) · [Paper](https://arxiv.org/abs/2509.00130) |

## Contributing

Pull requests are welcome. Please include:

1. a stable project, code, or dataset URL;
2. a one-sentence description of its 6G relevance;
3. a paper or official project page when one is available; and
4. enough license information to establish that the artifact is open source or
   openly available.

Projects that only mention “6G” without publishing a reusable artifact may be
declined. Please update the **Last reviewed** date when performing a full link
and metadata audit.
