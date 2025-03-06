# AI-Powered Quiz Generator

An AI-powered web application that extracts text from PDFs or accepts raw text and generates multiple-choice questions (MCQs) based on the provided content. The app uses NLP and AI models to generate MCQs for educational and testing purposes.

## Features

- **Text-based MCQ Generation**: Users can input raw text to generate MCQs.
- **PDF Support**: Users can upload a PDF file, and the app extracts text from it to generate questions.
- **AI-powered Question Generation**: Utilizes named entity recognition (NER) to generate MCQs based on extracted entities from the text.
- **Multiple Difficulty Levels**: Customize the difficulty level of the generated questions.
- **Download Quiz**: After generating MCQs, users can download the quiz in PDF format.

## Technologies Used

- **Frontend**: [Streamlit](https://streamlit.io/) for the user interface.
- **Backend**: [FastAPI](https://fastapi.tiangolo.com/) for building the API.
- **NLP Libraries**: 
  - [spaCy](https://spacy.io/) for Named Entity Recognition (NER).
  - [Hugging Face Transformers](https://huggingface.co/) for text generation.
- **PDF Extraction**: [PyMuPDF](https://pypi.org/project/PyMuPDF/) for extracting text from PDF files.
- **PDF Generation**: [FPDF](https://pyfpdf.github.io/fpdf2/) for generating downloadable PDF quizzes.

## Setup Instructions

### 1. Clone the Repository
Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/ai-quiz-generator.git
