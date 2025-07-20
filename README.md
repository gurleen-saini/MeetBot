# 🧠 MeetBot – PDF-Based Contextual Question Answering System

## Project Title / Headline
**Meeting QA Bot: LLM-Powered Contextual Q&A from Institutional Meeting Documents**  
A natural language interface built to understand and answer questions from PDF-based meeting records using transformer-based models.

## 📌 Short Description / Purpose
This project empowers users to query unstructured meeting documents in PDF format and receive contextually accurate answers. The system extracts, preprocesses, and analyzes meeting discussions using NLP and transformer pipelines to generate relevant answers and evaluate answer reliability.

## 🧰 Tech Stack
The system utilizes the following technologies:

- 🐍 **Python 3.11+** – Core scripting and processing logic
- 📄 **PDFMiner** – Extract text from meeting PDFs
- 🤗 **Transformers (HuggingFace)** – Pretrained LLM pipelines (e.g., `roberta-large-mnli` for entailment)
- 🧪 **python-dotenv** – Manage environment variables
- ⚙️ **Custom Pipelines** – Chunking, context retrieval, and confidence scoring

## 📂 Data Source
- 📘 **Input**: PDF files of institutional meeting records (e.g., university announcements, reports)
- 🔍 **Output**: Extracted answers along with label (`ENTAILMENT`, `NEUTRAL`, `CONTRADICTION`) and confidence scores

## ✨ Features / Highlights

### Business Problem
Institutions often generate lengthy, unstructured meeting documents that are difficult to search and understand. This system aims to create an efficient Q&A assistant that can instantly surface relevant decisions, announcements, or summaries.

### Core Features
- 🧾 **PDF Text Extraction**: Converts scanned or digital PDFs into raw text.
- 🔍 **Context Chunking**: Splits text into manageable segments for better embedding and retrieval.
- ❓ **Answer Extraction**: Uses NLP techniques to select relevant answer from context.
- ✅ **Answer Confidence Scoring**: Utilizes `roberta-large-mnli` to verify if the answer is entailed by the context.

### Sample Question
> **Question**: What awards were announced in the meeting?  
> **Answer**:  
> The Vice Chancellor announced that the following awards had been announced:  
> - Best Faculty: Dr. Shashi K. Gupta, Department of Computer Science  
> - Best Teacher: Dr. Rajeev Kumar, Department of Chemistry  
> - Best Student: Ms. Kritika Gupta, Department of Mathematics  
> - Best Project: Ms. Kritika Gupta and Ms. Prachi Aggarwal, Department of Mathematics  
> - Best Paper: Mr. Aman Bhalla, Department of Physics

## 📈 Business Impact & Use Cases
- 🏛️ **Universities / Institutions**: Summarize important decisions from multiple meetings.
- 📚 **Researchers**: Track trends in academic outcomes or funding allocations.
- 🧑‍💼 **Executives**: Quickly access strategic decisions without manually reading entire PDFs.

## 📌 About
A smart document QA assistant designed to turn institutional records into actionable knowledge using NLP.

## 🛠️ Future Improvements
- Add UI for user interaction
- Fine-tune QA model on meeting-specific dataset
- Enable voice-based question interface

© 2025 | Gurleen Saini 
