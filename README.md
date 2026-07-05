# 🧬 GroupDNA - WhatsApp Chat Analyzer

> Analyze WhatsApp group chats to uncover participation patterns, activity trends, media usage, and communication insights using Python.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview

**GroupDNA** is a Python-based WhatsApp Chat Analyzer that transforms exported WhatsApp chat files into meaningful analytics.

The project parses WhatsApp chat history and generates detailed statistics about:

- 👥 Group participation
- 💬 Message distribution
- 📅 Activity over time
- 📈 User engagement
- 📷 Media sharing
- ❌ Deleted messages
- 📊 Overall chat insights

It demonstrates practical applications of **Python programming**, **data processing**, and **text analytics**.

---

## ✨ Features

### 📂 Chat Parsing
- Reads exported WhatsApp chat (.txt) files
- Supports multiline messages
- Detects system-generated messages
- Separates sender, timestamp, and message

### 👥 Group Overview
- Total messages
- Number of participants
- Member list
- Chat duration
- Date range

### 📊 Message Statistics
- Messages per participant
- Percentage contribution
- Most active members
- Total conversation count

### 📷 Media Analysis
- Count of media messages
- Deleted message detection
- System message statistics

### 📅 Time Analysis
- Chat start date
- Chat end date
- Total number of days
- Conversation period

---

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- NumPy
- datetime module

---

## 📁 Project Structure

```
GroupDNA/
│
├── PRAJITHA_MARY_MINOR_PROJECT_1.ipynb
├── sample_chat.txt
├── README.md
└── images/
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/GroupDNA.git
```

### 2. Navigate to the project

```bash
cd GroupDNA
```

### 3. Install dependencies

```bash
pip install numpy
```

### 4. Export a WhatsApp Chat

WhatsApp

→ Open Chat

→ More

→ Export Chat

→ Without Media

Save the exported `.txt` file in the project directory.

### 5. Update the filename

```python
filename = "your_chat.txt"
```

### 6. Run the notebook

Open

```
PRAJITHA_MARY_MINOR_PROJECT_1.ipynb
```

using Jupyter Notebook or Google Colab.

---

## 📊 Example Output

The analyzer provides insights such as:

- Total Messages
- Participants
- Chat Duration
- Message Percentage
- Messages Per User
- Media Count
- Deleted Messages
- Activity Summary

Example:

```
==========================================
GROUP OVERVIEW
==========================================

Group Name : Hostel Bois 4ever

Total Messages : 12,584

Participants : 16

Total Days : 425

Most Active Member : John
```

---

## 🎯 Learning Outcomes

This project demonstrates:

- Text Parsing
- Data Cleaning
- File Handling
- Dictionaries & Lists
- Date-Time Processing
- Python Programming
- Data Analysis
- Problem Solving

---

## 🌟 Future Improvements

- Interactive dashboard
- Word cloud generation
- Emoji analysis
- Sentiment analysis
- Reply network visualization
- Message timeline graphs
- Export analytics as PDF
- Streamlit Web App
- Group comparison
- Monthly activity charts

---

## 🤝 Contributing

Contributions are welcome!

Feel free to:

- Fork the repository
- Create a new branch
- Improve the project
- Submit a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Prajitha Mary**

If you found this project useful, consider giving it a ⭐ on GitHub!

---
