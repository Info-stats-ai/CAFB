

# AI Challenge Project 🚀

## 📌 Overview

This project is a **multi-modal AI system** that processes data of many different types and converts them into usable formats such as **text, audio, and video**. The system combines **fine-tuned models, Retrieval-Augmented Generation (RAG), and blending techniques** to provide a unified pipeline for handling structured and unstructured data.

The project demonstrates:

* 📂 Handling **multiple input formats** – images, PDFs, CSVs, PPTs, plain text, and templates.
* 🔍 Using **RAG pipelines** to fetch and ground information.
* 🧩 Applying **blend filtering + fine-tuning** to improve accuracy.
* 🔄 Converting inputs into **different outputs** – text, audio, video.
* 🤖 A deployable **agent (`agent_to_run.py`)** to automate the process.
* 📝 A **Jupyter Notebook (`AI_challenge.ipynb`)** for exploration, experimentation, and training.

---

## 📂 Project Structure

```
.
├── AI_challenge.ipynb   # Jupyter Notebook: training, fine-tuning, multimodal experiments
├── agent_to_run.py      # Agent script for automated execution
├── data/                # (Optional) folder for input files (pdf, csv, images, etc.)
├── outputs/             # (Optional) folder for generated txt/audio/video outputs
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---

## ⚙️ Key Features

✅ **Multi-modal Input Support**: Handles PDFs, images, CSVs, PPTs, raw text, and structured templates.
✅ **Fine-tuned & Blended Models**: Used blend filtering + fine-tuning to improve response quality.
✅ **RAG Pipeline**: Retrieves relevant context from stored knowledge before generating outputs.
✅ **Format Conversion**: Converts input files into multiple formats – **text, audio, video**.
✅ **Automation**: The `agent_to_run.py` script runs the pipeline end-to-end.

---

## ⚙️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/AI_challenge.git
   cd AI_challenge
   ```

2. Create a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate   # Mac/Linux
   venv\Scripts\activate      # Windows
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Usage

### Run Notebook (Training & Experiments)

```bash
jupyter notebook AI_challenge.ipynb
```

* Explore multimodal data processing.
* Train/fine-tune models.
* Run RAG pipelines with blended filtering.

### Run Agent (Automation)

```bash
python agent_to_run.py
```

* Takes multimodal inputs (pdf, csv, images, ppt, etc.).
* Processes them through the pipeline.
* Outputs converted results (txt, audio, video).

---

## 📊 Example Workflow

1. Input: A PDF, image, or CSV file.
2. Pipeline: Preprocessing → RAG retrieval → Fine-tuned model inference → Format conversion.
3. Output:

   * Text transcript (`.txt`)
   * Audio narration (`.mp3/.wav`)
   * Video with captions (`.mp4`)

---

## 🤝 Contributing

Contributions are welcome! Fork the repo and submit a pull request.

