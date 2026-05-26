# Sared AI: Empowering Local Egyptian Dialects & Heritage through GenAI

### ⚠️ PROPRIETARY & PUBLIC PROTOTYPE NOTICE
> **Important:** This public repository contains only the initial open-source prototype and Minimum Viable Product (MVP) architecture of **Sared AI**. The core production engines, proprietary datasets, and commercial fine-tuning pipelines remain hosted in a secured, private repository. 

---

**Sared AI** (سَارد) is an innovative, localized Generative AI ecosystem designed specifically for the Egyptian market. Built as a scalable SaaS framework, Sared bridges the gap between state-of-the-art Large Language Models (LLMs) and rich cultural nuances. It provides on-demand custom AI assistants, cultural mapping, and location-based interactive experiences.

---

## 🚀 Core Features (Public MVP Scope)

### 1. On-Demand Custom AI Assistants (B2B & B2C)
* **Hyper-Localized LLMs:** Fine-tuned open-source models (such as Llama 3/Mistral) designed to perfectly comprehend and generate everyday Egyptian Arabic (Cairene, Upper Egyptian/Sa'idi, coastal, and rural dialects).
* **Enterprise-Ready:** Tailored, domain-specific assistants trained on proprietary business data for customer service, legal, or medical support.

### 2. Kemet Maps (Ancient Egyptian Chrono-Mapping)
* **Time-Slice Navigation:** An interactive map interface transforming modern Egyptian geography into Ancient Egyptian provinces (The 42 Nomes).
* **AI Historical Guides:** Context-aware, generative historical personas acting as real-time tour guides using GPS coordinates.

### 3. The Sa'idi Dialect Identifier & Companion
* **Dialect Classifier:** Advanced audio and text analysis capable of pinpointing the specific Upper Egyptian governorate or city of origin (e.g., Luxor, Qena, Asyut) based on phonetics and vocabulary.
* **Cultural Persona:** A wise, witty assistant built with a native Sa'idi persona to offer localized advice, cultural folklore translation, and regional storytelling.

### 4. "Souls of the South" (Location-Based AR Game)
* **Real-World Geography:** An interactive, augmented reality (AR) gamification layer mapping historical quests onto the main streets of Southern Egyptian cities (e.g., Minya, Sohag, Aswan).
* **Generative NPCs:** Real-world street navigation triggers interactions with historical AR characters powered by Sared's localized LLM. Players must converse, negotiate, and solve riddles using regional dialects to unlock rewards.

---

## 🛠️ The Tech Stack

### Machine Learning & LLM Fine-Tuning
* **Base Models:** Llama-3-8B, Mistral-7B, Gemma
* **Optimization Libraries:** `Unsloth`, `PEFT`, `LoRA` (Low-Rank Adaptation)
* **Audio Processing:** `OpenAI Whisper` (for Dialect transcription), `Demucs` (for audio source separation)
* **Frameworks:** PyTorch, Hugging Face Transformers

### Application & Geospatial Layer
* **Frontend/Mobile:** Flutter (Cross-platform iOS/Android)
* **Game Engine:** Unity + AR Foundation
* **Mapping Data:** OpenStreetMap (OSM) API 
* **Backend:** FastAPI, Python

---

## 📂 Project Structure (Public Prototype Layout)

```text
├── data_pipeline/         # Basic scripts for audio scraping and Whisper transcription tests
├── fine_tuning/           # Public training configurations and Unsloth optimization templates
├── datasets/              # Non-proprietary sample JSON datasets for dialect testing
├── geo_engine/            # OpenStreetMap data parsers and public historical coordinates
├── mobile_app/            # Prototype frontend code for Sared interface
└── README.md              # Project documentation
