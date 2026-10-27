# Asma Rizwan Rao
**Systems Architect | Founder of A818 Research**

Independent researcher and systems architect operating from Lahore, Pakistan. My work focuses on the architectural intersection of advanced artificial intelligence, neurotechnology (BCI), and electromagnetic threat analysis. I engineer systems from first principles, utilizing custom pipelines and public datasets to deploy production-grade applications.

## Active Systems

### A818_NF (NeuroFlow) — Neurotechnology
A software-first Brain-Computer Interface designed to decode motor intent from raw electroencephalogram (EEG) signals.
*   **Methodology:** Implements a custom EEGNet CNN architecture and Common Spatial Patterns (CSP) for feature extraction. Data processing pipeline includes 50 Hz notch filtering, 8–30 Hz bandpass filtering, and per-channel z-score normalization.
*   **Performance:** 91% accuracy on 3-class intent classification; 78% on 5-class with per-subject calibration.
*   **Status:** Software infrastructure is complete, fully open-source, and deployed live. Hardware integration (EEG headband) is in active development via custom-sourced components.
*   **Deployment:** [a818-nf.streamlit.app](https://a818-nf.streamlit.app)

### A818_SK (Sky Net) — Electromagnetic & Threat Analysis
A real-time drone detection and EMP effects analysis platform integrating computer vision and geospatial tracking.
*   **Methodology:** Utilizes YOLOv8 (Ultralytics) for target detection, Tkinter for GUI, and OpenCV for real-time video processing. The EMP physics engine calculates standardized HEMP geometry, geometric spreading attenuation, and Poynting vector energy density.
*   **Architecture:** Includes a hardware interface abstraction layer using `pyserial` with built-in safety interlocks, auto-disarm protocols, and state-machine logic.
*   **Status:** 60% complete. Current focus: Training YOLOv8 on the 9.14 GB Seraphim drone dataset to transition from COCO (80 classes) to drone-specific (1 class) detection.

### A818_K — Software Architecture
Legacy code mapping and governance architecture. (Scheduled for deployment upon A818_SK completion).

## Technical Competencies

**Artificial Intelligence & Machine Learning**
`PyTorch` `scikit-learn` `OpenCV` `Ultralytics (YOLOv8)` `Convolutional Neural Networks (CNN)` `Reinforcement Learning`

**Signal Processing & Neurotechnology**
`MNE-Python` `EEGNet` `Common Spatial Patterns (CSP)` `EDF Parsing` `Notch/Bandpass Filtering` `ERD/ERS Analysis` `LOSO Validation`

**Software Engineering & Automation**
`Python` `C` `SQL` `JavaScript` `FastAPI` `Streamlit` `LangChain` `LangGraph` `n8n` `Agentic AI Orchestration` `CRM Integration`

**Environment & Deployment**
`Git/GitHub` `Linux` `Google Colab (T4 GPU)` `Kaggle` `Streamlit Cloud` `Cloudflare Tunnel`

## Verification & Links

*   **Official Website:** [sites.google.com/view/asma-rizwan-rao-/home](https://sites.google.com/view/asma-rizwan-rao-/home)
*   **Research Identity (ORCID):** [0009-0009-8429-9348](https://orcid.org/0009-0009-8429-9348)
*   **Professional Network:** [linkedin.com/in/asma-rizwan-rao](https://www.linkedin.com/in/asma-rizwan-rao)
*   **Direct Contact:** asma.rizwanrao7@gmail.com
