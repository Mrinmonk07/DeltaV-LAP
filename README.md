# ΔV-LAP (Locomotor Analysis Platform) 🐀🔬

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Python 3.9+](https://img.shields.io/badge/Python-3.9%2B-green.svg)
![React](https://img.shields.io/badge/React-18.x-61dafb.svg)

**ΔV-LAP** is an open-source, high-performance software platform designed for the advanced extraction, visualization, and AI-assisted interpretation of continuous rodent wheel-running data.

It features a decoupled architecture with a Python/FastAPI mathematical engine and a React-based "Liquid Glass" interactive visualizer. 

## ✨ Key Features
* **Hardware-Agnostic Dynamic Polling:** Automatically detects hardware sampling rates to calculate absolute distance and mean velocity without hardcoding.
* **Cumulative-Start Correction:** Forces zero-state initializations to prevent artificial velocity anomalies.
* **Calendar-Chunking Validation:** Prevents partial-day misinterpretation using intelligent nocturnal-overlap detection.
* **AI Behavioral Summarization:** Integrates Google's Gemini LLM to generate automated, cross-subject comparative analyses.

## 🏗️ System Architecture
* **Backend:** Python, FastAPI, Pandas, Google GenAI SDK.
* **Frontend:** React, Vite, Recharts.

---

## 🚀 Installation & Setup

### Prerequisites
You will need [Node.js](https://nodejs.org/) and [Python 3.9+](https://www.python.org/) installed on your machine.

### 1. Clone the Repository
```bash
git clone [https://github.com/YOUR-USERNAME/DeltaV-LAP.git](https://github.com/YOUR-USERNAME/DeltaV-LAP.git)
cd DeltaV-LAP