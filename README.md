# 🧠 Chat Sentiment Analyser
A lightweight, Streamlit-powered web application that helps organizations analyze chat conversations and uncover the emotional dynamics within a group all from a simple exported chat file.

---

## 🚨 Problem Statement

In large-scale group communications whether in social, professional, or investigative settings harmful or suspicious behavior can often remain hidden beneath the surface. Manually monitoring conversations is inefficient and error-prone. Agencies need automated solutions that provide insight into:

- **Who is expressing negative sentiment** most frequently?
- **What is the overall emotional tone** of a group?
- **Is there a pattern of harmful, illegal, or toxic communication?**

**Chat Sentiment Analyser** solves this by transforming raw chat exports into actionable insights through sentiment analysis, keyword frequency, and interactive visualizations.

---
## 🌐 Hosted website
[🔗 Live Demo](https://devpatel43543-chat-sentiment-analyser-analysermyapp-bvwlui.streamlit.app/)
---
## Key Features

- **📂 Chat File Upload**: Supports plain text exports (e.g., WhatsApp, Telegram).
- **📈 Sentiment Analysis**: Classifies each message as Positive, Neutral, or Negative.
- **👤 Individual Sentiment Profiles**: Detects which members are consistently negative or positive.
- **📊 Visual Analytics**: Generates charts for group sentiment, individual contributions, and sentiment over time.
- **🧠 Keyword Extraction**: Displays frequently used words per user and across the group.
- **🔎 Investigation-Oriented Insight**: Useful for agencies identifying suspicious communication patterns.

---

## 🌐 Built With

| Component     | Technology          |
|---------------|---------------------|
| Frontend & UI | [Streamlit](https://streamlit.io/) |
| NLP Engine    | TextBlob / NLTK / spaCy |
| Visualization | Matplotlib / Seaborn / WordCloud |
| File Support  | `.txt` (e.g., WhatsApp exports) |

---

## 🔍 How It Works

1. **Upload** your exported group chat file.
2. The app **parses and processes** each message using NLP techniques.
3. **Sentiment scores** are assigned to every message.
4. Aggregated results show:
   - **Overall sentiment distribution**
   - **Individual sentiment breakdown**
   - **Trending keywords**
   - **Time-series sentiment shifts**
5. **Visual reports** help agencies or organizations derive actionable insights in real time.

---

## 📊 Sample Output

- **Sentiment Pie Chart** (Group-Level)
- **Top Negative / Positive Speakers**
- **Keyword Frequency Heatmap**
- **Time-Series Sentiment Trends**
- **User-specific Word Clouds**

*(Include screenshots or usage GIFs here if available)*

---

## 🛠️ Use Cases

- 👮 **Law Enforcement**: Detect early signs of illegal coordination or harmful behavior.
- 🧠 **Mental Health & Wellness Teams**: Identify individuals showing emotional distress.
- 🏢 **Corporate HR Departments**: Monitor workplace communication culture.
- 📚 **Academic Researchers**: Study group dynamics and communication trends in real-world settings.

---

## 💡 Future Enhancements

- 🔐 Named entity recognition (NER) for identifying topics/entities.
- 🧵 Thread-based sentiment grouping.
- 🌐 Multi-language support for non-English chats.
- 📁 Support for more file types (JSON, Telegram exports, Slack).

---

## 🙌 Contribution

Have ideas to improve the tool? Contributions are welcome! Fork the repository, create a branch, and submit a pull request.

---

## 👋 Contact
📫 Email: [devkumar.patel@dal.ca]  
🔗 LinkedIn: [https://www.linkedin.com/in/devkumar-patel-2190811b6/]  
🌐 Live App: [https://devpatel43543-chat-sentiment-analyser-analysermyapp-bvwlui.streamlit.app/]

