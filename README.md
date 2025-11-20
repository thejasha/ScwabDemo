# ScwabDemo

Current state of application. More features are implemented on the base project, but I am currently working on improving them.

The website is being run in a Docker instance with a reverse proxy to redirect URL requests to the correct port on the server.

https://github.com/user-attachments/assets/c85150eb-fcee-4b4c-9c86-04677993d1b9

### List of features not included in demo:
* Webscrapper to collect fundamental data on tickers and display graphs of data (Rev, Net Income, etc).
* Wrapper to self-hosted ollama model to summarize long PDFs (such as a 10-k).
* News API fetch that sends position news to a Discord channel via webhook.
* Working on caching data that is repeatedly fetched, but doesn't change, to stop the bottleneck from the Schwab API (Example is fetching the FED fund rate)
* Garch model to forecast future volatility - will be implementing an ML analysis to see if I can optimize some parameters.
* Correlation Matrix calculator on positions.
