# Meowsic

**Meowsic** is an innovative mobile application designed to revolutionize music theory and piano education using deep learning and intelligent interaction. It combines theory and practice in a single platform, enabling users to read sheet music, train with real instruments, and utilize AI-driven feedback to improve their skills.

> **Important Note:**  
> This project is currently supported by **TÜBİTAK 2209-A – University Students Research Projects Support Program**.  
> As per ethical and academic responsibility, **the source code of the application is not yet publicly shared** to preserve the integrity of the final project documentation and evaluation process. The repository will be updated following the project’s completion and ethical clearance.

---

## 🎵 Key Features

- **Music Theory Education:** Step-by-step learning of musical notation and theory through an engaging interface.
- **Piano Integration:** Practice on a physical piano or virtual keyboard.
- **Sheet Music Scanner:** Upload sheet music and convert it to playable formats via the PaperAI service.
- **Note Reading Trainer:** Interactive exercises to improve sheet music reading with real-time feedback.
- **AI-powered Audio Recognition:** Real-time note detection using deep learning (Residual Shuffle-Exchange Networks).
- **Progress Tracking:** Profile-based statistics and gamified experience.

---

## 🧠 Technology Stack

- **Frontend:** Swift, MVC Architecture
- **Backend:** Microservices (Python), Firebase Authentication, RabbitMQ Messaging
- **Data Storage:** MongoDB (MusicXML Files), Firebase Cloud
- **AI Models:** TensorFlow Lite, Residual Shuffle-Exchange Networks
- **PDF/Music Processing:** Custom MusicXML Parser
- **DevOps:** Dockerized ML pipelines, message queues, and backend services

---

## 🚀 Getting Started

While the source code is not available yet, here’s a preview of how the system works behind the scenes:

1. Users register/log in via Firebase.
2. They can upload sheet music, which is converted to MusicXML using the PaperAI service.
3. The system triggers a queue through RabbitMQ to notify services and store the converted data.
4. The user trains with the uploaded music using interactive trainers or their own piano.
5. AI models detect and evaluate notes played by the user, providing real-time feedback.

---

## 🛠 Planned Features

- Support for instruments beyond piano (e.g., guitar, violin)
- Ear training modules (note recognition by hearing)
- Internationalization & multilingual UI
- Community leaderboards and progress sharing

---

## 📌 Project Structure

- `mobile/` - Swift (MVC architecture)
- `backend/` - Python microservices, Firebase integrations
- `ai/` - Deep learning models and training scripts
- `paperai/` - MusicXML parsing and conversion tools
- `docs/` - Project planning, research proposal, and diagrams

---

## 📜 Ethical Note

This project is developed under the guidance of **Selçuk University Technology Faculty** and funded by TÜBİTAK. Therefore, **publishing the source code before the project’s official evaluation would be a violation of academic ethics and TÜBİTAK’s guidelines**.

The source code will be made public once the final documentation is approved and all ethical responsibilities are met.

---

## 🧩 Contributors

- **Rabia Doğanay** – Developer & Researcher  
- **Dr. Öğr. Üyesi Sema Servi** – Academic Advisor

---

## 📬 Contact

For any inquiries, collaboration proposals, or access requests after project finalization:

📧 Email: rabia.doganay@outlook.com.tr  
🏫 Institution: Selcuk University – Technology Faculty
