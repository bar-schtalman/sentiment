# Sentiment Analysis Project

## Overview
This project is a sentiment analysis service built using Java Spring Boot. It leverages NLP techniques with stand4nlp to analyze sentences and provide a rating from 1 to 5, indicating the sentiment from very bad to very good. The project also uses pipelines to fetch articles from NewsAPI and sends them to the application via Kafka for analysis.

## Features
- **Sentiment Analysis**: Analyzes sentences and rates them from 1 (very bad) to 5 (very good).
- **Article Fetching**: Uses pipelines to fetch articles from NewsAPI.
- **Kafka Integration**: Sends articles to the application via Kafka for sentiment analysis.

## Tech Stack
- **Java Spring Boot**
- **stand4nlp**: For natural language processing and sentiment analysis.
- **NewsAPI**: For fetching articles.
- **Kafka**: For message queuing and sending articles to the application.

## Usage
- **Analyze Sentiment**: 
  - Start stream
  GET http://localhost:8080/sentiment?text=[text_to_sentiment]
  if no input is provided, it defaults to searching “obama”.
  - Stop Stream:
  GET http://localhost:8080/stopTwitter/

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.


Feel free to copy and paste this into your README file. If you need any more adjustments, just let me know!
