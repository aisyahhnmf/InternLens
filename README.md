# 🚩 InternLens

### See Beyond the Job Description

InternLens is an AI-powered internship analysis chatbot built
using Python and the Groq API.

The chatbot helps students and internship seekers analyze
internship/job descriptions by identifying unclear information,
potential concerns, skill matches, and questions to ask recruiters.

---

## 🎯 Problem

Students often encounter internship descriptions with broad
responsibilities, unclear requirements, incomplete compensation
information, or ambiguous working arrangements.

InternLens helps users understand the information provided in
an internship description before applying.

---

## 💡 Solution

InternLens uses a Large Language Model (LLM) through the Groq API
to analyze the job description provided by the user.

The chatbot focuses on:

- Clear information
- Missing or unclear information
- Potential concerns
- Skill matching
- Questions to ask recruiters

InternLens does not determine whether a company is safe,
fraudulent, or trustworthy. The analysis is based only on the
information provided by the user.

---

## ✨ Features

### 🚩 Internship Analysis

Analyzes:

- Role clarity
- Job scope
- Requirements
- Compensation information
- Working arrangement
- Working hours
- Recruitment process
- Potential concerns

### 🎯 Skill Match

Compares the user's skills with the requirements in the
internship description.

Categories:

- Strong Match
- Partial Match
- Skill Gap
- Need Clarification

### ❓ Questions for Recruiter

Generates relevant questions based on information that is
missing or unclear in the job description.

### 💬 Conversation History

InternLens remembers previous messages during the same session,
allowing the user to provide their profile before sending a job
description.

### ⚡ Streaming Response

Responses are displayed progressively using Groq API streaming.

### 💾 Save & Load History

Conversation history can be saved and loaded using JSON files.

---

## 🛠️ Technologies

- Python
- Groq API
- Large Language Model (LLM)
- Google Colab
- JSON

---

## 📋 Requirements

- Python 3.x
- Groq API key
- Internet connection

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone <REPOSITORY_URL>
cd InternLens