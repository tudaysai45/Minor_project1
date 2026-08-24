# Minor_project1
Group DNA Analysis
# 🧬 GroupDNA WhatsApp Analyzer

## 📌 Project Overview

**GroupDNA WhatsApp Analyzer** is a Data Analytics and Data Science mini project that analyzes WhatsApp group chat data and discovers the group's communication patterns.

The project reads a WhatsApp chat dataset in CSV format and performs different analyses such as participant activity, message frequency, busiest days and hours, word usage, response speed, silent streaks, and personality-based group archetypes.

---

## 🎯 Objectives

* Analyze WhatsApp group communication data.
* Identify active participants and top contributors.
* Find the busiest day and busiest hour.
* Analyze hourly activity patterns.
* Create a NumPy-based activity matrix.
* Display an activity heatmap using text symbols.
* Find the most frequently used words.
* Calculate average response time.
* Identify the longest silent streak of each participant.
* Assign personality archetypes based on chat behavior.
* Generate a final GroupDNA report.

---

## ✨ Features

### 👥 Participant Analysis

Counts the total number of participants and ranks them based on the number of messages sent.

### 📅 Date Analysis

Finds:

* First date of the chat
* Last date of the chat
* Total number of days
* Busiest day
* Number of messages on the busiest day

### ⏰ Hourly Activity Analysis

Analyzes messages sent during each hour of the day and identifies the busiest hour.

### 📊 NumPy Activity Matrix

Creates a matrix where:

* Rows represent participants
* Columns represent 24 hours of the day
* Values represent the number of messages sent

### 🔥 Text-Based Activity Heatmap

Displays participant activity using symbols:

| Symbol | Activity Level  |
| ------ | --------------- |
| `.`    | No activity     |
| `░`    | Low activity    |
| `▒`    | Medium activity |
| `█`    | High activity   |

### 💬 Top 10 Words

Removes common stop words and identifies the most frequently used words in the group chat.

### ⚡ Response Speed

Calculates the average response time for each participant when the sender changes.

### 👻 Longest Silent Streak

Finds the maximum number of consecutive days during which each participant was inactive.

### 🎭 Group Personality Archetypes

The project analyzes chat behavior and assigns archetypes such as:

* 👻 **THE GHOST**
* 😂 **THE ENTERTAINER**
* 🎭 **THE DRAMA QUEEN**
* 🦉 **THE NIGHT OWL**
* 📖 **THE STORYTELLER**

### 📋 Final Report

Displays a complete summary containing:

* Total messages
* Number of participants
* Date range
* Busiest day and hour
* Top contributors
* Top words
* Participant personality/archetype results

---

## 🛠️ Technologies Used

* **Python**
* **NumPy**
* **datetime**
* **Google Colab**
* **CSV Data Processing**

---

## 📂 Project Structure

```text
Minor_project1/
│
├── minorproject1da_ds.ipynb
├── whatsappchat.csv
└── README.md
```

---

## 📄 Dataset Format

The WhatsApp chat dataset should be stored in CSV format.

Expected structure:

```csv
date,time,sender,text
01/01/2026,10:30,Person1,Hello everyone
01/01/2026,10:35,Person2,Hi
01/01/2026,11:00,Person3,Good morning
```

### Required Columns

* `date` — Date of the message
* `time` — Time of the message
* `sender` — Name of the participant
* `text` — Message content

The project expects the date and time format:

```text
DD/MM/YYYY
HH:MM
```

---

## ▶️ How to Run

### Option 1: Google Colab

Click the badge below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tudaysai45/Minor_project1/blob/main/minorproject1da_ds.ipynb)

Then:

1. Open the notebook in Google Colab.
2. Upload the WhatsApp CSV dataset.
3. Make sure the dataset file path matches the notebook configuration.
4. Run all cells from top to bottom.
5. View the analysis and final GroupDNA report.

### Option 2: Run Locally

Install the required dependency:

```bash
pip install numpy
```

Then open and run the Jupyter Notebook:

```text
minorproject1da_ds.ipynb
```

---

## 📈 Sample Analyses Performed

```text
PARTICIPANTS
Person1 : 120 messages
Person2 : 95 messages
Person3 : 76 messages
```

```text
DATE ANALYSIS
First Date  : 2026-01-01
Last Date   : 2026-01-31
Total Days  : 31
Busiest Day : 2026-01-15
```

```text
HOURLY ACTIVITY
09:00 - 25 messages
10:00 - 42 messages
11:00 - 38 messages

Busiest Hour: 10:00
```

---

## 🧠 Project Workflow

```text
WhatsApp CSV Dataset
        ↓
File Loading
        ↓
Data Parsing
        ↓
Date & Time Validation
        ↓
Participant Analysis
        ↓
Date & Hour Analysis
        ↓
NumPy Activity Matrix
        ↓
Word Frequency Analysis
        ↓
Response Speed Analysis
        ↓
Silent Streak Analysis
        ↓
Personality Archetypes
        ↓
Final GroupDNA Report
```

---

## 📊 Output

The program produces a detailed terminal/notebook output containing:

* Group overview
* Participant rankings
* Date analysis
* Hourly activity
* NumPy activity matrix
* Activity heatmap
* Top 10 words
* Response speed
* Silent streak analysis
* Personality archetypes
* Final GroupDNA report

---

## 👨‍💻 Author

**Udaysai**

GitHub: [@tudaysai45](https://github.com/tudaysai45)

---

## 🎓 Academic Purpose

This project was developed as a **Data Analytics and Data Science Mini Project** to demonstrate practical usage of:

* Python programming
* Data processing
* NumPy arrays
* Date and time analysis
* Frequency analysis
* Pattern detection
* Behavioral data analysis

---
