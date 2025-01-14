Cookie Clicker Automation Bot
This project automates the gameplay of the "Cookie Clicker" game using Selenium WebDriver. It is designed to maximize efficiency in purchasing upgrades and improving the game's performance. The bot continuously clicks the cookie, evaluates the in-game currency, identifies affordable upgrades, and purchases the most cost-effective options. After running for 5 minutes, it outputs the cookies-per-second (CPS) performance metric.

Key Features and Techniques Used

Web Scraping and Automation
Utilizes Selenium WebDriver to interact with the game's elements dynamically, simulating user actions such as clicks and data retrieval.
Automates decisions based on real-time game data to maximize cookie production.

Data Extraction and Processing
Extracts upgrade costs and current cookie count from the DOM (Document Object Model).
Processes and cleans data using Python's string manipulation techniques to convert textual data into numerical values.

Decision-Making Logic
Implements algorithms to prioritize the purchase of upgrades based on affordability and efficiency.
Uses dictionaries and list comprehensions for efficient data mapping and decision-making.

Timing and Performance Monitoring
Integrates Python’s time module to control automation intervals and run-time.
Outputs CPS (cookies-per-second), a performance indicator, after completing its run.
