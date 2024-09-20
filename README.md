# InstaBot - Automating Instagram Tasks with Selenium

## Project Overview

The **InstaBot** project is a two-part automation script designed to help users automate common tasks on Instagram. The bot uses **Selenium** for browser automation and **BeautifulSoup** for web scraping. The primary use case for this bot is to assist users with growing their Instagram presence by automating tasks like following users, liking posts, and more.

### Part 1: Introduction and Basic Automation

In Part 1, we focus on creating the bot's foundation, including automating login, following users, and interacting with posts.

### Part 2: Advanced Features and Analysis

Part 2 builds upon Part 1 by adding more advanced functionalities such as data collection, generating insights using visualizations, and further Instagram interactions.

---

## Features

### Part 1 - Basic Automation
- **Automated Instagram Login**: Automatically logs into Instagram using your credentials.
- **Following Users**: Automates the process of following users based on search results from a hashtag or username.
- **Web Scraping**: Uses **BeautifulSoup** to scrape Instagram profile data when necessary.
  
### Part 2 - Advanced Features
- **Data Collection**: Collects data such as follower counts, recent posts, and interactions.
- **Interaction Automation**: Liking posts and following/unfollowing users based on predefined rules.
- **Data Visualization**: Generates plots and visual insights using **Matplotlib** to analyze Instagram growth and engagement.
  
---

## Requirements

Before running the InstaBot, ensure you have the following tools and libraries installed:

- **Selenium**: For browser automation.
- **BeautifulSoup4**: For web scraping.
- **Pandas**: For handling data.
- **Matplotlib**: For plotting and visual analysis.
- **ChromeDriver**: A driver to enable Selenium to interact with Chrome.

### Install the required libraries:

```bash
pip install selenium beautifulsoup4 pandas matplotlib
```

Download the appropriate **ChromeDriver** version for your system [here](https://sites.google.com/a/chromium.org/chromedriver/downloads), and ensure that it is correctly referenced in your script.

---

## Setup Instructions

1. **Install ChromeDriver**: Download and install the appropriate version of ChromeDriver based on your version of Chrome. Update the path in the script to point to the correct location of the driver:
   
   ```python
   driver = webdriver.Chrome(executable_path='/path/to/chromedriver')
   ```

2. **Clone the repository**:
   ```bash
   git clone https://github.com/RobuRishabh/InstaBot_Coding_Ninjas.git
   cd instabot
   ```

3. **Run the Jupyter Notebook**:
   You can open either `Project_InstaBot_Part_I.ipynb` or `Project_InstaBot_Part_2.ipynb` in Jupyter Notebook or convert them into Python scripts to execute them:
   
   ```bash
   jupyter notebook Project_InstaBot_Part_I.ipynb
   jupyter notebook Project_InstaBot_Part_2.ipynb
   ```

4. **Update Credentials**:
   Update the notebook with your Instagram username and password in the designated sections:
   ```python
   username = 'your_username'
   password = 'your_password'
   ```

---

## How It Works

### Part 1
1. **Login to Instagram**: The bot uses Selenium to navigate to the Instagram login page, enters the credentials, and logs into the account.
2. **Follow Users**: The bot can search for users using hashtags or usernames and follow them automatically.

### Part 2
1. **Advanced Automation**: The bot can like posts, unfollow users, and gather data related to engagement metrics.
2. **Data Analysis**: Using `Pandas` and `Matplotlib`, the collected data can be visualized for insights into follower growth and interaction trends.

---

## Project Structure

- **Part 1**: Focuses on setting up the Instagram bot with basic functionalities (login, follow, scrape).
  - `Project_InstaBot_Part_I.ipynb`: The Jupyter notebook containing the initial automation setup.
  
- **Part 2**: Adds advanced capabilities like data collection, plotting, and additional interaction functionalities.
  - `Project_InstaBot_Part_2.ipynb`: The second notebook that builds upon Part 1, adding advanced features like visualization and extended automation tasks.
  
- **chromedriver**: Place your ChromeDriver executable in the project folder or reference its path in the code.

---
