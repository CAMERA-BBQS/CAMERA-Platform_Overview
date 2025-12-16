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

[NIH Project Details](https://reporter.nih.gov/project-details/10801782)

For more informations, please contact Dr. Brett E. Youngerman

![CAMERA Architecture](images/architecture.png "CAMERA Architecture Diagram")

## Funding
This NIH-funded project is being developed in a phased R61/R33 framework.

## System Configuration

### Hardware Requirements
- **iPad**  
  - iPadOS XX or later  
  - Tested on: iPad Pro (M1/M2)

- **Host Computer**  
  - macOS / Windows  
  - Used for experiment control and data synchronization

- **EEG System**  
  - Natus

- **Networking**  
  - Local Wi-Fi router (no internet required)
- 
### Software Requirements
- [BCI2000](https://www.bci2000.org/mediawiki/index.php/Contributions:NatusADC)

### Tested/Verified Configuration
- iPad Pro (M1), iPadOS 17
- Unity 2021.3 LTS
- Python 3.10
- BCI2000


## Repositories
| Component | Repository | Description |
|---------|------------|-------------|
| Python Controller Hub | [`PyUnityLink`](https://github.com/CAMERA-BBQS/PyUnityLink) | Orchestrates sessions, triggers events, and synchronizes data |
| iPad Client | `TH-ipad` | Unity-based experimental task running on iPad |

## Contributors

- PI: Dr. Brett E. Youngerman, Dr. Joshua Jacobs, Dr. Jorge Jose Ortiz, Dr. Alik S. Widge
- Core Development:
- Collaborating Labs:
