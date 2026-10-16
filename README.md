<div align="center">

# 👋 Durga Prasad Puli

### 🤖 AI / Machine Learning Engineer · Generative AI, LLMs & Applied Robotics

📍 Hannover, Germany &nbsp;·&nbsp; 🎓 Dual-degree M.Sc. Applied Computer Science & Mechatronics and Robotics (in progress)

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-durgaprasadpuli.vercel.app-0F172A?style=for-the-badge)](https://durgaprasadpuli.vercel.app)
[![LinkedIn](https://img.shields.io/badge/💼_LinkedIn-durgaprasadpuli-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/durgaprasadpuli)
[![Email](https://img.shields.io/badge/📧_Email-durgadp.ml@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:durgadp.ml@gmail.com)

</div>

---

## 👤 Profile

AI and Machine Learning Engineer with **1+ years** of hands-on experience across research, academic projects, and industry. I build data-driven solutions with machine learning, LLMs, prompt engineering, and speech AI, and I apply AI in robotics and well-tested production applications. Currently pursuing a dual-degree M.Sc. in Applied Computer Science and Mechatronics & Robotics in Germany.

---

## 🔭 Currently

| | Focus | Details |
|:-:|:--|:--|
| 🧬 | **Research Assistant (AI)**, Hannover Medical School | Microbiome and clinical ML for bronchiectasis (Master's thesis) |
| 🚁 | **SkyDive Voice**, Master's thesis | Amphibious voice-controlled drone on Jetson Orin Nano, ROS 2, and PX4 |
| 💼 | **Full-Stack Developer**, MietoDev | Rental marketplace platform (FastAPI, PostgreSQL, React) |

---

## 🎓 Education

| Institution | Program | Period |
|:--|:--|:-:|
| 🏛️ Schmalkalden University of Applied Sciences | M.Sc. Applied Computer Science | Oct 2025 – Present |
| 🏛️ Schmalkalden University of Applied Sciences | M.Sc. Mechatronics and Robotics | Oct 2023 – Present |
| 🏛️ CVR College of Engineering, Hyderabad | B.Tech. Mechanical Engineering | Aug 2016 – Jul 2020 |

> 🔁 Pursuing both M.Sc. programs concurrently as a dual-degree course of study.

---

## 💼 Experience

**🧬 Student Research Assistant (AI), Master's Thesis** · *Hannover Medical School (MHH)* · Oct 2026 – Present
- 🧫 Profiled sputum shotgun metagenomes from 150 bronchiectasis patients (PROGNOSIS cohort, Illumina NovaSeq X Plus) to species level using the Wochenende alignment pipeline and KrakenUniq.
- 📈 Integrated microbial profiles with serum inflammatory markers and clinical data, applying hierarchical clustering, PCA, and Random Forest to identify endotypes linked to Bronchiectasis Severity Index and exacerbation rate.
- 🌍 Benchmarked the German cohort against 100 Scottish EMBARC metagenomes and healthy controls, delivering a versioned, documented pipeline with an automated clinician-readable report.

**🧑‍💻 Full-Stack Developer** · *MietoDev, Rental Marketplace Platform (mieto.space)* · Jul 2026 – Oct 2026 · *Remote*
- 🔍 Built PostgreSQL full-text search for a FastAPI/SQLAlchemy API: generated `tsvector` column, GIN indexing, German-stemmed weighted ranking, and availability-aware date-range filtering, covered by 335+ lines of tests.
- 🛡️ Diagnosed and fixed a critical transaction-integrity bug, isolating operations with scoped savepoints to prevent silent data loss in production.
- 🚀 Delivered end-to-end features: a notification-preferences system (optimistic UI, REST API, schema), bulk listing management, database migrations, and bilingual (EN/DE) localization.

---

## 🚀 Projects

### 🚁 Master's Thesis: SkyDive Voice · Amphibious Voice-Controlled Drone
![Jetson](https://img.shields.io/badge/Jetson_Orin_Nano-76B900?style=flat-square&logo=nvidia&logoColor=white) ![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white) ![PX4](https://img.shields.io/badge/PX4-E62A2A?style=flat-square) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
- 🎙️ On-device voice pipeline using **openWakeWord** for wake-word detection and **faster-whisper** for real-time speech-to-text, with no cloud dependency.
- 🧭 Modular **ROS 2 Jazzy** architecture mapping voice commands to PX4 surface and dive modes over **MAVLink**, with a UART-connected acoustic modem relaying commands underwater.

### 🤖 Self-Balancing Robot with Voice and Vision Control
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi_5-A22846?style=flat-square&logo=raspberrypi&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI_GPT--4o-412991?style=flat-square&logo=openai&logoColor=white) ![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat-square) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
- 🗣️ Real-time voice-controlled robot integrating speech recognition, GPT-4o-mini inference, and ElevenLabs text-to-speech, with a measured **2.4 s** average end-to-end latency.
- 👁️ Scene understanding with Picamera2 and GPT-4o vision, using a 1-second stabilization delay to reduce motion blur. Audio, vision, and motor control run as isolated, thread-safe, queue-based pipelines.

### 🔐 Post-Quantum Key Exchange for IoT Devices
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![CoAP](https://img.shields.io/badge/CoAP-0E7C86?style=flat-square) ![ML-KEM](https://img.shields.io/badge/ML--KEM_(Kyber)-6A1B9A?style=flat-square)
- 🛰️ Post-quantum secure messaging on **PineCone BL602** microcontrollers using **ML-KEM-512 (Kyber)**, **HKDF-SHA256**, and **AES-128-CCM** over CoAP.
- 🧪 Hardware-tested against passive sniffing, tampering, and man-in-the-middle attacks while keeping handshake latency suitable for embedded deployment.

### 📄 LLM-Based Document Analysis & Micro-Course Preparation Tool
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square) ![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white)
- 🧩 Pipeline for PDF and Word files using OpenCV and NLP to extract text, tables, and figures while preserving reading order.
- 🌐 Local LLM via Ollama in a Streamlit app for summarization, question generation, and translation across **52 languages**, with export to PPTX, HTML, and JSON.

---

## 🛠️ Technical Skills

| Category | Skills |
|:--|:--|
| 💻 **Programming Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![GDScript](https://img.shields.io/badge/GDScript-478CBF?style=flat-square&logo=godotengine&logoColor=white) |
| 🧠 **Generative AI & LLMs** | ![LLMs](https://img.shields.io/badge/LLMs-8B5CF6?style=flat-square) ![RAG](https://img.shields.io/badge/RAG-8B5CF6?style=flat-square) ![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-8B5CF6?style=flat-square) ![OpenAI](https://img.shields.io/badge/OpenAI_GPT--4o-412991?style=flat-square&logo=openai&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square) |
| 🗣️ **NLP & Speech AI** | ![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white) ![NLTK](https://img.shields.io/badge/NLTK-154F3C?style=flat-square) ![Text Embeddings](https://img.shields.io/badge/Text_Embeddings-8B5CF6?style=flat-square) ![Semantic Search](https://img.shields.io/badge/Semantic_Search-8B5CF6?style=flat-square) ![Whisper](https://img.shields.io/badge/Whisper-412991?style=flat-square) ![openWakeWord](https://img.shields.io/badge/openWakeWord-0EA5E9?style=flat-square) ![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat-square) |
| 📊 **Machine & Deep Learning** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square) ![LightGBM](https://img.shields.io/badge/LightGBM-9ACD32?style=flat-square) ![Optuna](https://img.shields.io/badge/Optuna-1E88E5?style=flat-square) |
| 📈 **Data Science & Analysis** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) |
| 👁️ **Computer Vision** | ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![TorchVision](https://img.shields.io/badge/TorchVision-EE4C2C?style=flat-square) ![scikit-image](https://img.shields.io/badge/scikit--image-F7931E?style=flat-square) ![Pillow](https://img.shields.io/badge/Pillow-3776AB?style=flat-square) ![MMCV](https://img.shields.io/badge/MMCV-0D6EFD?style=flat-square) ![Picamera2](https://img.shields.io/badge/Picamera2-A22846?style=flat-square) ![CVAT](https://img.shields.io/badge/CVAT-1A1A1A?style=flat-square) |
| 🤖 **Robotics & Embedded** | ![ROS 2](https://img.shields.io/badge/ROS_2_Jazzy-22314E?style=flat-square&logo=ros&logoColor=white) ![PX4](https://img.shields.io/badge/PX4-E62A2A?style=flat-square) ![MAVLink](https://img.shields.io/badge/MAVLink-0F172A?style=flat-square) ![Jetson](https://img.shields.io/badge/Jetson_Orin_Nano-76B900?style=flat-square&logo=nvidia&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi_5-A22846?style=flat-square&logo=raspberrypi&logoColor=white) ![BL602](https://img.shields.io/badge/PineCone_BL602-6B7280?style=flat-square) ![UART](https://img.shields.io/badge/UART-6B7280?style=flat-square) ![CoAP](https://img.shields.io/badge/CoAP-0E7C86?style=flat-square) ![ML-KEM](https://img.shields.io/badge/ML--KEM_(Kyber)-6A1B9A?style=flat-square) ![AES-CCM](https://img.shields.io/badge/AES--CCM-6A1B9A?style=flat-square) |
| 🧩 **Backend & Full-Stack** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square) ![Alembic](https://img.shields.io/badge/Alembic-6BA81E?style=flat-square) ![REST APIs](https://img.shields.io/badge/REST_APIs-009688?style=flat-square) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) |
| ☁️ **MLOps, Cloud & DevOps** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS_(Lambda,_RDS)-232F3E?style=flat-square&logo=amazonaws&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) ![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square) ![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white) ![Microservices](https://img.shields.io/badge/Microservices-0F172A?style=flat-square) |
| 🗄️ **Databases & Tools** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white) |

---

## 🏆 Certifications

| 🎖️ | Certification | Issuer | Year |
|:-:|:--|:--|:-:|
| 🥇 | Artificial Intelligence Engineer (Master's Program) | IBM + Simplilearn | 2024 |
| 🥇 | Data Scientist (Master's Program) | IBM + Simplilearn | 2024 |
| 🥇 | Data Analyst (Master's Program) | IBM + Simplilearn | 2024 |
| 🧠 | Advanced Deep Learning and Computer Vision | Simplilearn | 2024 |
| 🧠 | Natural Language Processing | Simplilearn | 2024 |
| 📘 | Machine Learning | Simplilearn | 2023 |
| 🏅 | Machine Learning A-Z: AI, Python & R + ChatGPT Prize | Udemy | 2024 |

---

## 🌍 Languages

| Language | Level |
|:--|:--|
| 🇬🇧 English | **C2** (Proficient) |
| 🇩🇪 German | **B1–B2** (Upper Intermediate) |
| 🇮🇳 Telugu | **C2** (Native-level) |

---

<div align="center">

### 📫 Let's Connect

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-durgaprasadpuli.vercel.app-0F172A?style=for-the-badge)](https://durgaprasadpuli.vercel.app)
[![LinkedIn](https://img.shields.io/badge/💼_LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/durgaprasadpuli)
[![Email](https://img.shields.io/badge/📧_Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:durgadp.ml@gmail.com)
[![GitHub](https://img.shields.io/badge/🐙_GitHub-DurgaPrasadPuli-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DurgaPrasadPuli)

</div>


