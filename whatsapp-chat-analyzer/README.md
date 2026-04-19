# 💬 WhatsApp Chat Analysis Dashboard

Interactive dashboard built with Python and Streamlit to analyze WhatsApp chat patterns and extract insights from conversation data.

## ✨ Features

- 📊 Total messages, words, media & links count
- 📅 Monthly and daily activity timelines
- 🔥 Activity heatmap (day vs time)
- 👥 Busiest users and ghost user detection
- ☁️ Word cloud, top words, and emoji analysis

## 🚀 Installation

```bash
git clone https://github.com/yourusername/whatsapp-chat-analyzer.git](https://github.com/Manav-020/Projects/tree/094c33811b3b2f3b44ce7302b2eb416cb45b054d/whatsapp-chat-analyzer)
cd whatsapp-chat-analyzer
pip install -r requirements.txt
```

## 📖 Usage

**1. Export WhatsApp Chat:**
- Open WhatsApp → Chat → Three dots → More → Export chat → Without Media
- Save the `.txt` file

**2. Run the app:**
```bash
streamlit run app.py
```

**3. Analyze:**
- 📤 Upload your exported `.txt` file
- 🎯 Select "Overall" or specific user
- 📈 Explore the visualizations

## 🛠️ Tech Stack

Python • Streamlit • Pandas • Matplotlib • Seaborn • WordCloud

## 📦 requirements.txt

```txt
streamlit
pandas
matplotlib
seaborn
wordcloud
emoji
urlextract
```
