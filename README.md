# Content Curator
This project uses web scraping techniques to search the internet for niche content and curates a Twitter feed using the twitter.js library.

## Prerequisites
Node.js
npm (included with Node.js)
A Twitter developer account and API keys
## Installation
Clone the repository to your local machine
Navigate to the project directory in your terminal
Run npm install to install the required dependencies
Create a file called config.json in the root directory of the project and add your Twitter API keys in the following format:
```
  {
    "CONSUMER_KEY": "your_consumer_key",
    "CONSUMER_SECRET": "your_consumer_secret",
    "ACCESS_TOKEN_KEY": "your_access_token_key",
    "ACCESS_TOKEN_SECRET": "your_access_token_secret"
  }
```
## Usage
Run the script using node main.js
The script will search the internet for niche content and post the results to your Twitter feed
Customization
You can customize the search terms and frequency of the script by modifying the relevant variables in the main.js file.

## Disclaimer
This project is for educational purposes only. Use at your own risk and ensure that you are in compliance with the terms of service of any websites you are scraping.
