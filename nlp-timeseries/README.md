# Market Mood vs Market Move
(Giggling at the title right now)

## Objective:
- Use the financial-news dataset (headlines/events) to build a “market mood” signal (via NLP: sentiment, emotion, topics).
- Collect matching market-movement/time-series data (e.g., index returns, stock returns, volatility) aligned by date/time.
- Analyse the relationship: does mood precede / accompany / follow market moves? Can mood improve prediction of short-term or medium-term market moves?

### Key questions to answer:
- How to define “mood” from news: overall sentiment, topics, intensity.
- What “move” means: index return next day, intraday return, volatility jump, volume spike.
- What time-horizon makes sense (e.g., daily, hourly) given the dataset.
- Can mood add explanatory/predictive power beyond standard market predictors.
