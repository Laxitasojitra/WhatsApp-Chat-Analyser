# WhatsApp Chat Analyzer

## Overview
This project aims to analyze WhatsApp chat data to provide insights such as top statistics, monthly and daily timelines, activity maps, sentiment analysis, emoji analysis, and word frequency by user.

## Features
- **Top Statistics:** Provides the total number of messages, words, media shared, and links shared.
- **Monthly Timeline:** Displays the message count over different months.
- **Daily Timeline:** Shows the message count on a daily basis.
- **Activity Map:** Visualizes the busiest days and months.
- **Most Busy Users:** Identifies the most active users in the group.
- **Wordcloud:** Generates a word cloud based on the most common words used.
- **Most Common Words:** Lists the most frequently used words overall.
- **Sentiment Analysis:** Analyzes the sentiment distribution across users and for each user individually.
- **Emoji Analysis:** Analyzes the distribution of emojis used.
- **Word Frequency by User:** Displays the most frequent words used by each user separately.

## Dependencies
- streamlit
- pandas
- matplotlib
- seaborn
- URLExtract
- WordCloud
- TextBlob

## Additional File: `preprocessor.py`
This file contains a preprocessing function `preprocess(data)` to clean and organize WhatsApp chat data before analysis.
## File Structure
- `app.py`: Main Streamlit application code.
- `preprocessor.py`: Preprocessing functions for WhatsApp chat data.
- `helper.py`: Helper functions for analysis and visualization.
  
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
