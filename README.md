# Twitter_sentiment_analysis
Automation of twitter data collection through utilization of TAGS and Google Drive

This script allows you to use a simple process:
1. Use TAGS to collect data from Twitter. You can set TAGS to collect data hourly.
2. Use Pythonanywhere to pull data directly from your TAGS Google Sheet
3. Use Pythonanywhere to process the data for sentiment analysis purposes, and write this as three output files
4. Use Pythonanywhere to send send data to Google Drive destination folder. This can be set as a scheduled task that runs in the background.

Prerequisites:
- You need to enable Google Drive API in Google Cloud and create credentials for this API.
- You need to have settings.yaml configured according to the above mentioned Google Cloud credentials, and copied to your working directory.
- You need to run the script once in your own computer to generate the required credentials.json file (by above settings.yaml), and to authorize things properly. Pythonanywhere will not allow you to do this.

Pythonanywhere is mentioned above because that is what was used by me. You can of course use any other similar service for this.
