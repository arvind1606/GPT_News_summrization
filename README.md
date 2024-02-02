# GPT_News_summrization
GPT-4 News Summarization and Categorization


# Overview
This Python script utilizes the GPT-4 language model and Bing News API to perform news summarization and categorization. The script searches for news articles on specified topics, extracts relevant details, and generates summaries, sentiment scores, and categorizes the news based on predefined categories.

# Requirements
Python 3.x
openai, pandas, requests, beautifulsoup4, and dotenv Python libraries
Bing Search API key

# Usage
Install required Python libraries:

bash
Copy code
pip install openai pandas requests beautifulsoup4 python-dotenv
Set up a .env file with your Bing Search API key.

bash
Copy code
BING_SEARCH_V7_SUBSCRIPTION_KEY=your_api_key
BING_SEARCH_V7_ENDPOINT_NEWS=https://api.cognitive.microsoft.com/bing/v7.0/news/search
Run the script:

bash
Copy code
python your_script_name.py
View the generated summaries and categorized news in the pages folder.

# Configuration
Customize the script's behavior by modifying the custom_news_config.ini file. Update the custom_news_topics section with the desired news topics.

# Folder Structure
pages: Contains categorized news articles and summaries for each topic.
pages/current_bing_websearch: Holds the merged news data from various topics.
Feel free to explore and adapt the script for your specific use case.

Note: Ensure compliance with API usage policies and ethical considerations when deploying this script in a production environment.
