# Hi, I'm Somnath Pandit. 

**Backend Software Engineer | System Architecture | Applied Cryptography & IoT**

I am a Software Engineer focused on designing secure, scalable backend architectures and connected device ecosystems. With a strong foundation in Java (Spring Boot) microservices and professional experience in hardware-level firmware development (C/C++), I build resilient systems that handle real-time data flow from the edge to the cloud. Whether I am implementing mathematically anonymous cryptographic protocols or bridging telemetry data for industrial IoT, I focus on writing clean, secure, and production-ready code.

🟢 I'm currently seeking remote opportunities and roles where I can contribute to challenging backend and IoT problems. Feel free to review my [Resume](./cv_somnath.pdf), connect with me on [LinkedIn](https://www.linkedin.com/in/somnathpandit633/), or reach out directly via [email](mailto:somnathpandit633@gmail.com).

## 🛠️ Skills & Technologies

| Category | Technologies |
| :--- | :--- |
| **Languages** | ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) |
| **Backend & APIs** | ![Spring Boot](https://img.springframework.io/badges/spring-boot-badge.svg) ![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Material UI](https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white) |
| **Hardware & IoT** | ![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=Raspberry%20Pi&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-000000?style=for-the-badge&logo=espressif&logoColor=white) ![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white) |
| **Databases** | ![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white) |

---

## 🚀 Featured Projects

### 📄 CAFVIS: Hybrid Multimodal Research Summarizer (IEEE Internship)
Developed during an internship under the IEEE Computational Intelligence Society (CIS), Kolkata Chapter. [cite_start]CAFVIS is a hybrid AI framework designed to process and summarize complex academic documents by integrating state-of-the-art NLP and Computer Vision[cite: 2753, 2765].
* [cite_start]**Architecture Pipeline:** Designed a robust 4-stage data pipeline[cite: 2865]:
  * [cite_start]*PDF Parsing Unit (PPU):* Extracts structured text using GROBID[cite: 2874].
  * [cite_start]*Image Processing Unit (IPU):* Decodes visual data using PixTral, BLIP-2, and Command-R+[cite: 2884].
  * [cite_start]*Abstract Summary Generator Unit (ASGU):* Generates fact-verified summaries using Pegasus and ROBERTa-MNLI[cite: 2915].
  * [cite_start]*Extract Summary Generator Unit (ESGU):* Utilizes SBERT and RAG for query-focused retrieval[cite: 2932].
* [cite_start]**Research Team:** Co-authored with Sayan Chandra and Soumyajit Mukherjee, under the supervision of Dr. Jyoti Sekhar Banerjee[cite: 2757, 2758, 2762].
* [📄 Read the Full Research Paper (PDF) ➔](https://github.com/somnath503/somnath503/blob/main/CAFVIS.pdf?raw=true)

### 🛡️ ZeroProof (Binary V2 Hackathon)
Co-developed a mathematically anonymous, trustless feedback system within a 4-person team (Team SnackOverflow). The system prevents spam while ensuring the server cannot link authorized users to their responses.
* **Cryptographic Protocol:** Implemented RSA Blind Signatures, exchanging unique invite URLs for unlinkable "voting tickets" to guarantee mathematical anonymity.
* **Architecture:** Built an Admin Web App for organizations to manage contacts and questionnaires, paired with an open-source, auditable client app that generates a visual Security Pattern for respondents.
* [View Repository ➔] (./CAFVIS.pdf *(Add your link here)*

### 🍔 dev.restaurant Ecosystem
A complete, production-ready microservice ecosystem for restaurant management, built across 4 distinct repositories. Orchestrated a highly scalable architecture handling real-time order lifecycles across customer, administrative, and delivery interfaces.
* **Backend:** Built a stateless Spring Boot API utilizing JWT authentication, Role-Based Access Control, Razorpay payment processing, and MessageCentral OTP verification.
* **Admin Dashboard:** Developed a React.js portal featuring POS billing, thermal printer integration, and real-time WebSocket polling.
* [View the Organization & Repositories ➔](https://github.com/dev-restaurant-system)

### 🧬 Encoding-Driven Genetic Optimization
An academic research project introducing a Matrix-Centric approach to complex university scheduling. 
* Developed and implemented a specialized Genetic Algorithm (MR-GA) utilizing a (35,12) NumPy matrix architecture to resolve severe timetable conflicts. 
* Achieved algorithmic convergence at Generation 105, proving the efficiency of multi-dimensional chromosome representations in resource-constrained environments.

### 🚆 Railway Gate Monitor & Audlog Pro
A suite of IoT and embedded systems projects focusing on real-time data telemetry and hardware-software bridging.
* Engineered a CM4 Master Dashboard to monitor multi-node slave data via a Mosquitto MQTT broker for railway safety.
* Designed ESP32 DevKit V1 hardware architectures, ensuring strict 3.3V logic compliance for ultrasonic sensor arrays.

---

## ⚙️ Core Competencies & Technical Highlights

I don't just write code; I architect end-to-end systems. Here is a look at the extended features and methodologies I bring to my projects:

**🔐 Applied Cryptography & Security**
* **Trustless Systems:** Deep understanding of implementing mathematical anonymity using RSA Blind Signatures to solve complex authorization-vs-privacy trade-offs.
* **Stateless Authentication:** Extensive experience implementing custom JWT-based authentication filters and Spring Security Role-Based Access Control (RBAC) to secure sensitive APIs.

**🔌 Hardware-to-Cloud Integration (IoT)**
* **Firmware Engineering:** Professional experience writing bare-metal C/C++ firmware, managing GPIOs, serial communications, and sensor logic in Linux environments.
* **Telemetry & Messaging:** Proficient in bridging low-level hardware with cloud infrastructure using MQTT (Mosquitto) and WebSockets for real-time, low-latency data streaming.

**🧠 Applied AI & Algorithmic Optimization**
* [cite_start]**Retrieval-Augmented Generation (RAG):** Hands-on research experience building multimodal AI summarization pipelines using SBERT, Command-R+, and GROBID for structured document extraction[cite: 2766].
* **Mathematical Modeling:** Strong background in translating complex academic problems into code, such as building matrix-centric Genetic Algorithms (MR-GA) in Python/NumPy for severe constraint-satisfaction problems.
