# WorkStyle Profiling
This interactive tool simulates an assessment inspired by a structured workstyle evaluation. It presents workplace scenarios and uses AI (IBM's Granite-3B Instruct model) to evaluate your responses in terms of leadership principles.

## 🔍 Overview

This tool presents multiple-choice questions to users, professional assessment approach. Each response is mapped to a core leadership principle such as Customer Obsession, Bias for Action, or Deliver Results.

After completing the quiz, the model provides a summary of your work style and strengths using AI-driven natural language generation.

## 🚀 Features

✅ Interactive question-answer interface via widgets

🤖 AI-generated summary of dominant leadership principles

📊 Visual mapping of responses to values

🧩 Uses IBM's Granite 3B open-source language model

## 🛠️ Installation

Before running the tool, make sure to install the required dependencies:

```bash
pip install transformers torch accelerate ipywidgets pandas
```

## 📦 Model Used

Model: ibm-granite/granite-3.0-3b-a800m-instruct

Framework: HuggingFace Transformers

Precision: bfloat16 (optimized for newer GPUs)

## 🧪 How to Use

1. Clone this or open the notebook in Colab <a href="https://colab.research.google.com/drive/1F2NKnCrIwwZTLUCxfksP8u-lLo91GmFZ?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>
2. Run all cells.
3. Answer each of the 10 prompted questions.
4. View your selected leadership principles.
5. Read the AI-generated insight summarizing your work style.

## 📋 Example Output

```bash
Q: How do you approach learning something new on the job?
A: I take the initiative to teach myself


🧾 Summary of Leadership Principles:
- Learn and Be Curious: selected 4 time(s)
- Earn Trust: selected 1 time(s)
- Dive Deep: selected 1 time(s)
- Ownership: selected 1 time(s)
- Deliver Results: selected 1 time(s)
- Customer Obsession: selected 1 time(s)
- Invent and Simplify: selected 1 time(s)

⏳ Generating AI insight using Granite...

🧠 AI Personality Insight:

Based on this , write a short paragraph summarizing their likely work style and strengths.

The candidate is likely to be a curious and learning-focused individual who values trust, ownership, and results. They may be detail-oriented and prioritize customer satisfaction. They might also be innovative and enjoy simplifying complex problems. Their work style appears to be driven by a strong customer-centric approach and a desire to constantly improve and simplify processes.
```

## 🧭 Leadership Principles Referenced

The following leadership principles are inspired by Amazon’s publicly documented values:

- Customer Obsession
- Ownership
- Invent and Simplify
- Are Right, A Lot
- Learn and Be Curious
- Hire and Develop the Best
- Insist on the Highest Standards
- Think Big
- Bias for Action
- Frugality
- Earn Trust
- Dive Deep
- Have Backbone; Disagree and Commit
- Deliver Results
