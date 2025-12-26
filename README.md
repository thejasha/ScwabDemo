# ScwabDemo

Current state of the project.

The website is being run in a Docker instance of a Gunicorn Server with a reverse proxy to redirect URL requests to the correct port on the server.

It can be accessed by any device that is on the network. For remote access, must be connected to wireguard VPN.

https://github.com/user-attachments/assets/800cf169-db8e-40e1-aef7-ed89efbd600a


### List of features not included in demo:
* Webscrapper to collect fundamental data on tickers and display graphs of data (Rev, Net Income, etc). (UPDATE: Macrotrends has a pay wall now so this doesn't work)
* Wrapper to self-hosted ollama model to summarize long PDFs (such as a 10-k).
* Working on caching data that is repeatedly fetched, but doesn't change, to stop bottleneck from the Schwab API (Example is fetching the FED fund rate).
* Garch model to forecast future volatility - will be implementing an ML analysis to see if I can optimize some parameters.
* Correlation Matrix calculator on positions.
* Forward Volaility Calculation.


Codebase is in private git.
