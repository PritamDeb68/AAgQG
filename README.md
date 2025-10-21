# 🧠 Dataset for Automatic Question Generation (AQG)

This repository contains the dataset used in our research study on **Automatic Question Generation (AQG)**.  
The dataset has been carefully constructed to support the generation of high-quality **factual**, **open-ended**, and **binary** questions from textual contexts.

---

## 📂 Dataset Structure

The dataset is organized in a tabular format with three main columns:

| Column Name      | Description                                                                 |
|------------------|------------------------------------------------------------------------------|
| **context**       | Paragraphs or textual passages from which questions are generated.          |
| **question_type** | Specifies the type of question to be generated — *factual*, *open-ended*, or *binary*. |
| **question**      | The corresponding question(s) generated for each context and question type, concatenated using a `<sep>` token if multiple questions exist. |

A **sample subset** of the dataset (`AAgQG_sample.csv`) is provided in this repository to illustrate the data format and structure used in our experiments.

---

## 📘 Example

Below is a small example demonstrating the dataset structure:

| context | question_type | question |
|----------|----------------|----------|
| The Earth revolves around the Sun once every 365 days. | factual | What is the duration of Earth's revolution around the Sun? |
| The process of photosynthesis converts light energy into chemical energy in plants. | open-ended | How does photosynthesis help plants survive? |
| Water boils at 100 degrees Celsius under normal atmospheric pressure. | binary | Does water boil at 100°C under normal pressure? |

---

## 🎯 Purpose

This dataset is designed to facilitate research in **Automatic Question Generation**, **Instruction Tuning**, and **Natural Language Understanding (NLU)** tasks.  
It can be directly used for training and evaluating transformer-based models such as **T5**, **Flan-T5**, or **GPT-like architectures**.

---

## ⚖️ Data Availability & Reproducibility

To maintain ethical use and ensure reproducibility:

- A **sample dataset** is publicly available in this repository for demonstration purposes.  
- The **complete dataset** can be provided **upon request** for **academic and research purposes only**.  
- Interested researchers may contact the corresponding author via the contact details provided in the paper or this repository to request full access.

We encourage use of this dataset for **non-commercial academic research** aimed at advancing NLP and Question Generation studies.

---

## 📨 Requesting Full Dataset

Researchers can request the full dataset by providing:
1. Institutional affiliation  
2. Intended research purpose  
3. Acknowledgment of ethical data use  

Please contact: **[debopamdeycse19@gmail.com]**  
(Replace with your official email or institutional contact form.)

---

