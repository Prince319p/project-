# 🌟 Emily's Wellness Dashboard & Universal AI Health Coach

A production-grade, single-file interactive web application built as part of the Generative AI Gen AI Project (PJ2). This dashboard serves as both a personalized health/fitness tracking interface for **Emily Park (Age 35)** and a universal multilingual AI health assistant.

---

## 🚀 Key Features & Core Components

1. **Universal Gemini AI Health & Diet Assistant**:
   * Fully functional AI chatbot capable of answering **ANY general health, diet, weight loss, protein, workout routines, sleep science, or wellness question**.
   * Automatically detects language and responds in **Hindi / Hinglish**, **English**, **Spanish**, **French**, or **German** with structured bullet points and actionable advice.

2. **Language-Aware Dynamic Audio (TTS)**:
   * Built-in browser Speech Synthesis integration.
   * Automatically adapts its audio voice profile to the user's selected language (**Hindi `hi-IN`** when Hindi is chosen, **English `en-US`** when English is chosen).

3. **Touch-Interactive Bilingual Modals**:
   * Tapping or clicking on **ANY** metric card (Sleep, Stress, Steps, Exercise), chart, benchmark comparison, or coaching tip instantly opens a deep-dive modal drawer.
   * Provides detailed breakdowns in **both English and Hindi (हिन्दी / Hinglish)**.

4. **5 High-Contrast WCAG-Compliant Themes**:
   * Instantly switch between 5 professionally designed visual themes:
     * 🌙 **Midnight Cyberpunk** (Dark Mode)
     * ☀️ **Clean Light Mode** (High-Contrast Light)
     * 🌅 **Sunset Neon**
     * 🌲 **Deep Emerald Forest**
     * 🌊 **Ocean Blue**
   * Chart.js colors automatically adapt in real-time based on the active theme.

5. **Multilingual UI Switcher**:
   * Seamlessly toggle the entire interface between **English**, **Hindi**, **Spanish**, **French**, and **German**.

6. **PJ2 Core Requirements Met**:
   * **Weekly Numbers Snapshot**: 7-day trailing average metrics (Sleep: 6.4h, Stress: 4.6/10, Steps: 7,654, Exercise: 62 min).
   * **3 Interactive Chart.js Graphs**: Visualizing Sleep trends, Steps vs Workout distribution, and Stress vs Mood correlation with plain-English takeaway notes.
   * **National Health Benchmarks**: Cited Nature / NIH baseline comparison (~7.0h sleep target).
   * **Coaching Messages**: 4 warm, non-diagnostic lifestyle coaching recommendations.

---

## 🛠️ Tech Stack

* **Frontend**: Single-file HTML (`index.html`) using semantic HTML5 and responsive CSS.
* **Styling**: Tailwind CSS via CDN + Custom CSS Variables for themes.
* **Charts**: Chart.js for responsive data visualization.
* **Speech**: Browser Web Speech API (`speechSynthesis`).
* **AI Logic**: Universal conversational health intelligence script.

---

## 📦 Project Directory Structure

```text
Emily-Wellness-Dashboard/
│
├── index.html                 # Main single-file web application
├── PJ2_data_dictionary.txt    # Data dictionary explaining variables
├── PJ2_Emily_Park_wellness_2025.csv # Raw wellness dataset (2025)
├── README.md                  # Project documentation & user guide