# CAMERA-Platform_Overview
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

[NIH Project Details](https://reporter.nih.gov/project-details/11004690)

*For more informations, please contact Dr. Brett E. Youngerman*

![CAMERA Architecture](images/architecture.png "CAMERA Architecture Diagram")

## Funding
This NIH-funded project is being developed in a phased R61/R33 framework.

## Getting Started

### System Configuration

#### Hardware Requirements
- **iPad**
  - iPadOS 12 or later

- **Host Computer**
  - Windows PC

- **EEG System**
  - Natus EEG System

- **Networking**
  - Local Wi-Fi router (no internet required)

- **Wearable Device**
  - Empetica
    
#### Software Requirements
- BCI2000
- PyUnityLink
- EMA iPad client


#### Tested/Verified Configuration
- iPad Pro (11-inch, M2), iPadOS 26.1
- Unity 2022.3 LTS
- Python 3.10


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

## To-do
