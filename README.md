

# WhatsApp Chat Analyzer with Sentiment Analysis

This project is a WhatsApp chat analysis tool that provides insights and sentiment analysis of chat messages. The tool preprocesses chat data, analyzes common emojis, and performs sentiment analysis using various NLP techniques.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [File Descriptions](#file-descriptions)
  - [preprocess.py](#preprocesspy)
  - [helper.py](#helperpy)
  - [app.py](#apppy)
- [Screenshots](#screenshots)
- [License](#license)


## Installation

To use this project, you need to have Python installed on your machine. You can install the necessary dependencies using `pip`:

```bash
pip install -r requirements.txt
```

Create a `requirements.txt` file with the following content:

```
streamlit
pandas
emoji
nltk
wordcloud
matplotlib
seaborn
urlextract
```


## Usage

1. Clone this repository to your local machine.

```bash
git clone https://github.com/ammaarKhan13/Whatsapp-Chat-Analyzer-with-Sentiment-Analysis
cd Whatsapp-Chat-Analyzer-with-Sentiment-Analysis
```

2. Install the required Python packages.

```bash
pip install -r requirements.txt
```

3. Run the Streamlit app.

```bash
streamlit run app.py
```

4. Upload your WhatsApp chat export file (in `.txt` format) through the Streamlit interface and explore the analysis.


## Features

- **Message Statistics**: Provides statistics such as the total number of messages, words, media messages, and links shared.
- **Most Busy Users**: Identifies the most active users in the chat.
- **Monthly and Daily Timeline**: Visualizes the number of messages over time.
- **Activity Map**: Shows activity distribution by day of the week and by month.
- **Word Cloud**: Generates a word cloud of the most common words used in the chat.
- **Most Common Words**: Displays a bar chart of the most common words.
- **Emoji Analysis**: Analyzes the frequency and types of emojis used.
- **Sentiment Analysis**: Analyzes the sentiment of messages using the VADER sentiment analysis tool.


## File Descriptions

### preprocess.py

This script preprocesses the WhatsApp chat data. It extracts the date, time, user, and message content, and creates a pandas DataFrame with additional columns for analysis.


### helper.py

This script contains helper functions for performing various analyses on the chat data, such as fetching statistics, generating word clouds, and performing sentiment analysis.


### app.py

This is the main script that runs the Streamlit app. It handles the file upload, preprocessing, and visualization of various chat statistics and sentiment analysis.


## Screenshots

![image](https://github.com/ammaarKhan13/Whatsapp-Chat-Analyzer-with-Sentiment-Analysis/assets/147348966/2d359924-6f59-40ee-a1f8-c833ea58a559)
![image](https://github.com/ammaarKhan13/Whatsapp-Chat-Analyzer-with-Sentiment-Analysis/assets/147348966/6d6c9e7a-3483-469d-b73d-025ccda3325e)
![image](https://github.com/ammaarKhan13/Whatsapp-Chat-Analyzer-with-Sentiment-Analysis/assets/147348966/82e7e2fe-f498-4a8d-bf79-f85cd31eaea9)


## License

This project is licensed under the MIT License.


