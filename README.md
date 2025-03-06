# Lightweight-Fine-Tuning-to-a-Foundation-Model

This project implements a lightweight fine-tuning workflow using Parameter-Efficient Fine-Tuning (PEFT) to adapt a pre-trained Hugging Face model (e.g., Gemma-2-2B) for a personalized career assistant. The tool is designed to:

- **Generate concise profile summaries** from detailed professional data.
- **Extract key skills and experiences** from candidate profiles.
- **Provide job matching or resume-tailoring suggestions** based on the candidate's background.

## Overview

By leveraging state-of-the-art transformer models and efficient fine-tuning techniques, this project transforms raw profile data (e.g., from LinkedIn or resumes) into actionable insights. The process involves:

1. **Data Preparation:** Loading and preprocessing a dataset containing professional profile details.
2. **Fine-Tuning:** Using PEFT to efficiently adapt the pre-trained model with minimal additional parameters.
3. **Inference:** Generating clear profile summaries, extracting essential skills and experiences, and setting the foundation for job matching or resume suggestions.
4. **Evaluation:** Comparing the model’s performance before and after fine-tuning.

## Key Features

- **Concise Summaries:** Transform detailed professional information into short, structured summaries.
- **Skill & Experience Extraction:** Automatically highlight the most important skills and achievements.
- **Actionable Recommendations:** Provide insights that can help in resume tailoring and job matching.

## Getting Started

### Prerequisites

- Python 3.8+
- A CUDA-compatible GPU (optional but recommended for training) (Recommended GPT T4 Google Colab)
- Git

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yashnayi234/Lightweight-Fine-Tuning-to-a-Foundation-Model.git
   cd Lightweight-Fine-Tuning-to-a-Foundation-Model

```bash
   pip install -r requirements.txt
