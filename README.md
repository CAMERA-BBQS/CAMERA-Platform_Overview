# CAMERA Platform
![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)

## Project Description

CAMERA (Context-Aware Multimodal Ecological Research and Assessment) is an NIH(National Institutes of Health)-funded,
open multimodal hardware and software platform designed to measure and model
human brain–behavior relationships in real-world environments. The platform integrates
neural, physiological, behavioral, environmental, and ecological momentary assessment
(EMA) data to enable continuous, high-resolution estimation of internal states such as
anxiety and cognitive performance.

A key innovation of CAMERA is its context-aware and adaptive EMA framework, in which
assessment timing is dynamically informed by a participant’s physiology and behavior.
By leveraging complementary multimodal data sources and interpretable machine learning
methods, CAMERA aims to improve both measurement fidelity and participant compliance
relative to existing approaches.

While initial development focuses on modeling anxiety state and memory performance,
CAMERA is designed as a flexible and extensible platform applicable to a broad range of
research questions involving complex human behavior and cognition.


![CAMERA Architecture](images/architecture.png "CAMERA Architecture Diagram")

[NIH Project Details](https://reporter.nih.gov/project-details/11004690)

*For more informations, please contact Dr. Brett E. Youngerman*

## Funding
This NIH-funded project is being developed in a phased R61/R33 framework.

## Use Cases
- Clinical EMU deployments
- Long-running BCI experiments
- Synchronized EEG and behavioral data collection

## Getting Started

### System Configuration

#### Hardware Requirements
- **Host Computer - Windows**
  - AMD Ryzen 9 9900X 12-Core (4.4 to 5.6 GHz)
  - 32GB of 6000 MHz DDR5 RAM
  - NVIDIA GeForce RTX 5070 GPU (12GB GDDR7)
  - 2TB M.2 PCIe 4.0 SSD
  - Windows 11 Home

- **iPad**
  - iPadOS 12 or later

- **EEG System**
  - Natus EEG System

- **Networking**
  - TP-Link AXE5400 Tri-Band WiFi 6E Router (Archer AXE75)

- **Camera**
  - Logitech Brio PRO X 4K Webcam
  - Mevo Core UHD 4K Mirrorless Streaming Camera paired with an Olympus 14–42mm lens
    
- **Microphone**
  - RØDE NT55 Compact Condenser Microphone with Interchangeable Capsules

- **Speaker**
  - XKX Single USB Computer Speakers

- **Wearable Device**
  - [Empetica Embrace Plus](https://www.empatica.com/embraceplus/)
    
#### Software Requirements
- [BCI2000](https://www.bci2000.org/mediawiki/index.php/Main_Page)
- [PyUnityLink](https://github.com/CAMERA-BBQS/PyUnityLink)
- EMA iPad client
- [Empatica Care lab](https://apps.apple.com/us/app/empatica-care-lab/id6443699123)
- [Ksana Health - Effortless Assessment Research System (EARS)](https://ksanahealth.com/ears/)


#### Tested/Verified Configuration
- [Windows PC](https://www.bhphotovideo.com/c/product/1885882-REG/cyberpowerpc_slcai7400cpgv2_gamer_supreme_liquid_cool.html/specs)
- [iPad Pro (11-inch, M2)](https://support.apple.com/en-us/118452), iPadOS 26.1
- [Unity 2022.3 LTS](https://unity.com/releases/editor/archive)
- [Python 3.9](https://www.python.org/downloads/release/python-390/)


### Setup
- [BCI2000](https://www.bci2000.org/mediawiki/index.php/Contributions:NatusADC)
- 
### Running the System



## Repositories
| Component | Repository | Description |
|---------|------------|-------------|
| Python Controller Hub | [`PyUnityLink`](https://github.com/CAMERA-BBQS/PyUnityLink) | Orchestrates sessions, triggers events, and synchronizes data |
| iPad Client | `TH-ipad` | Unity-based experimental task running on iPad |

## Contributors

### Principal Investigators
- Dr. Brett E. Youngerman
- Dr. Joshua Jacobs
- Dr. Jorge Jose Ortiz
- Dr. Alik S. Widge

### System Development & Data Analysis
- Ehsan, Taqiya, MS — Audio data processing and multimodal predictive modeling
- Li, Yangjia (Francis), MS - System architecture design and development
- Xia, Shuren, MS — Video data processing and multimodal predictive modeling
- Han, Zhixian (Claire), MS — Spatial navigation and memory data analysis
- Wang, Linda, MD — STAI-6 (Spielberger State-Trait Anxiety Inventory) data analysis
- Zhao, Chongkun, MS — Empatica & Kasana data analysis and linguistic feature engineering
- Zhu, Hongkun, PhD — Data preprocessing, multimodal synchronization, and biomarker discovery

## License
Unless otherwise noted, repositories under this organization are released under the Apache License, Version 2.0.
Individual repositories may include additional licensing terms; please refer to each repository's LICENSE file.

## To-do

## About

This repository contains a simplified, public-facing iPad Unity client derived from the
CAMERA platform. It is intended for educational and demonstration purposes and does not
include clinical, medical, or research deployment functionality.

This repository is part of the CAMERA Platform.
See the main guide here: 
