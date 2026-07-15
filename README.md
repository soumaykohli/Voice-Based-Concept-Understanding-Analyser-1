# 🎤 Voice-Based Concept Understanding Analyser (VBCUA)

An AI-powered educational web application that evaluates a student's conceptual understanding from spoken explanations using speech recognition, semantic similarity analysis, and audio feature extraction.

---

# 📌 Project Overview

The **Voice-Based Concept Understanding Analyser (VBCUA)** is designed to assess a student's conceptual understanding through spoken explanations rather than written responses.

The application combines **OpenAI Whisper**, **Sentence-BERT**, and **Librosa** to automatically transcribe speech, compare it with a reference concept, analyze communication quality, and generate an intelligent evaluation report.

The system provides an objective assessment by combining semantic understanding and speech characteristics.

---

# ✨ Features

- 🎤 Upload spoken explanations (WAV/MP3)
- 📝 Automatic Speech-to-Text using OpenAI Whisper
- 🧠 Semantic Similarity Evaluation using Sentence-BERT
- 🎯 AI-based Understanding Score
- 📊 Filler Word Detection
- 🔊 Audio Feature Extraction
  - Pause Ratio
  - RMS Energy
  - Speech Duration
- 📈 Audio Waveform Visualization
- 📄 Automatic PDF Report Generation
- 💬 Qualitative Feedback
- 🌐 Responsive Streamlit User Interface
- ⚡ Cached AI Models for Faster Evaluation

---

# 🏗️ System Workflow

```text
Student Uploads Audio
        │
        ▼
Audio Validation
        │
        ▼
Speech-to-Text (Whisper)
        │
        ▼
Transcript Generation
        │
        ▼
Sentence-BERT
Semantic Similarity
        │
        ▼
Audio Feature Extraction
(Librosa)
        │
        ▼
Filler Word Detection
        │
        ▼
Scoring Engine
        │
        ▼
Understanding Classification
        │
        ▼
Waveform Visualization
        │
        ▼
PDF Report Generation
```

---

# 🛠️ Technology Stack

## Programming Language

- Python 3.10+

## Frontend

- Streamlit

## AI / Machine Learning

- OpenAI Whisper
- Sentence-BERT
- Scikit-learn

## Audio Processing

- Librosa
- SoundFile
- NumPy

## Data Visualization

- Matplotlib

## Report Generation

- ReportLab

## Development Environment

- Visual Studio Code

---

# 📂 Project Structure

```text
VBCUA
│
├── uploads/
├── reports/
├── temp/
├── tests/
│
├── app.py
├── model_loader.py
├── speech_to_text.py
├── audio_utils.py
├── semantic_eval.py
├── text_utils.py
├── scoring_engine.py
├── report_generator.py
├── requirements.txt
└── README.md
```

---

# 🚀 Installation

## Clone the Repository

```bash
https://github.com/soumaykohli/Voice-Based-Concept-Understanding-Analyser.git
```

---

## Navigate to the Project

```bash
cd VBCUA
```

---

## Create Virtual Environment

```bash
python -m venv vbcu_env
```

Windows

```bash
vbcu_env\Scripts\activate
```

Linux / macOS

```bash
source vbcu_env/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
streamlit run app.py
```

---

# 📋 Application Workflow

1. Launch the Streamlit application.
2. Enter the reference concept.
3. Upload a student's audio explanation.
4. Convert speech into text using Whisper.
5. Generate sentence embeddings using Sentence-BERT.
6. Compute semantic similarity.
7. Extract audio features using Librosa.
8. Detect filler words.
9. Calculate the understanding score.
10. Generate qualitative feedback.
11. Download the evaluation report as a PDF.

---

# 📊 Evaluation Metrics

The application evaluates spoken explanations using multiple criteria.

| Metric | Description |
|----------|-------------|
| Semantic Similarity | Measures conceptual alignment with the reference answer |
| Filler Word Ratio | Measures unnecessary filler words |
| Pause Ratio | Measures speaking continuity |
| RMS Energy | Estimates speaking confidence |
| Understanding Score | Overall evaluation score |
| Classification | Strong / Moderate / Poor Understanding |

---

# 📄 PDF Report

The generated PDF includes:

- Reference Concept
- Student Transcript
- Waveform Visualization
- Semantic Similarity Score
- Filler Word Ratio
- Pause Ratio
- RMS Energy
- Final Understanding Score
- Qualitative Classification
- Personalized Feedback

---

# 🧪 Testing

The project includes test modules for:

- Whisper Transcription
- Audio Feature Extraction
- Semantic Similarity
- Filler Detection
- Scoring Engine
- PDF Generation

Run individual tests:

```bash
python tests/test_whisper.py
python tests/test_audio.py
python tests/test_semantic.py
python tests/test_text_utils.py
python tests/test_scoring.py
python tests/test_report.py
```

---

# 📈 Performance Optimizations

- Streamlit Resource Caching
- Cached Whisper Model
- Cached Sentence-BERT Model
- Modular Architecture
- Exception Handling
- Input Validation
- Session State Management

---

# 📚 References

- Python
- Streamlit
- OpenAI Whisper
- Sentence-BERT
- Librosa
- ReportLab
- Scikit-learn

---

# 🔮 Future Enhancements

- Real-time microphone recording
- Multi-language speech support
- Advanced pronunciation assessment
- Emotion and sentiment analysis
- Teacher analytics dashboard
- Student performance history
- Cloud deployment
- Database integration
- User authentication

---

# 👨‍💻 Developed By

**Soumay Kohli** 

**Himani Sharma**

B.Tech – Computer Science & Engineering

---

# 📄 License

This project is developed for educational and academic purposes.

---

# 🙏 Acknowledgements

- SmartBridge
- Skill Wallet
- OpenAI
- Streamlit
- Hugging Face
- Python Open Source Community

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
