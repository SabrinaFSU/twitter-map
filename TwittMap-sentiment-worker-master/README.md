TwittMap-sentiment-worker
=========================


Functionality:

1. Acquire data from AWS SQS queue with topic subscribed
2. Analyze text using sentiment analysis API alchemyapi: positive, neutral, negative
3. Push tweet data with this analysis result to another queue for final display
