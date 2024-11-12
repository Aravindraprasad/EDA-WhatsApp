# WhatsApp Chat Analyzer

This project is a web-based application for exploring and analyzing WhatsApp chat data, built using Python, Streamlit, and several data visualization libraries. The application provides insightful statistics and visualizations of WhatsApp conversations to help users better understand messaging patterns, activity levels, common words, and emoji usage.

### Result
![alt text](https://github.com/Aravindraprasad/EDA-WhatsApp/blob/main/screenshots/1.jpg)

![alt text](https://github.com/Aravindraprasad/EDA-WhatsApp/blob/main/screenshots/2.jpg)

![alt text](https://github.com/Aravindraprasad/EDA-WhatsApp/blob/main/screenshots/3.jpg)

![alt text](https://github.com/Aravindraprasad/EDA-WhatsApp/blob/main/screenshots/4.jpg)

![alt text](https://github.com/Aravindraprasad/EDA-WhatsApp/blob/main/screenshots/5.jpg)


### Features

- Top Statistics: Summary of key statistics such as total messages, word count, media shared, and links shared.
Monthly and Daily Timelines: Visualizes the number of messages over time, both on a daily and monthly basis.
- Activity Maps: Shows the busiest days of the week and months of the year.
- Weekly Activity Heatmap: Displays a heatmap showing the intensity of messages across different times of the day and days of the week.
- Most Active Users: Lists the users who contributed the most to the chat in group conversations.
- Word Cloud: Generates a word cloud of the most commonly used words.
-  Most Common Words: Lists the top 20 most frequently used words.
- Emoji Analysis: Provides insights into the most commonly used emojis in the chat.

## Usage

- Load the Data: The script automatically fetches the dataset from the UCI repository.
- Run EDA: Visualize and analyze feature distributions and correlations.
- Train the Model: Fit a Logistic Regression model on the dataset and evaluate its performance.
- Predict on Custom Input: Use the model to predict species from user-defined measurements.



## Installation

To run this application locally, follow these steps:

```bash
  git clone https://github.com/your-username/whatsapp-chat-analyzer.git
```

```bash
cd whatsapp-chat-analyzer
```

```bash
pip install -r requirements.txt

```

```bash
streamlit run app.py

``` 

### How to Export WhatsApp Chat Data
To export your WhatsApp chat for analysis:

- Open the chat on WhatsApp.
- Go to "More Options" > "More" > "Export Chat".
- Choose "Without Media" to focus on text analysis.
- Save the exported .txt file to upload in the app.

