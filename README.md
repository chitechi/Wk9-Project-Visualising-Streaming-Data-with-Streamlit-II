# Wk9-Project-Visualising-Streaming-Data-with-Streamlit-II
SBS Data Engineering Project on streaming with Streamlit.

# Telecom Fraud Visualization Dashboard

## Introduction
The Telecom Fraud Visualization Dashboard is a real-time data visualization tool built using Streamlit, Python, and the Reddit API. The goal of this project is to analyze streaming data from Reddit to identify fraud in the telecommunications industry. The dashboard collects real-time posts related to telecom fraud from Reddit, processes the data, and visualizes it in an interactive dashboard.

## Problem Statement
Fraud in the telecommunications industry is a significant problem that costs billions of dollars annually. Telecom companies face the challenge of detecting and preventing fraud in real-time before it causes financial damage. This project aims to develop a real-time data visualization dashboard that monitors Reddit for mentions of telecom fraud and related keywords, analyzes the data for patterns and trends, and provides insights to aid fraud detection and prevention efforts.

## Features
- Collects real-time posts related to telecom fraud from Reddit using the Reddit API
- Processes the collected posts to extract useful information such as post text, user name, subreddit, and date/time
- Performs data analysis to identify patterns and trends related to telecom fraud
- Presents the data in an interactive dashboard using Streamlit
- Visualizes the data with charts and graphs to provide insights into fraud mentions by subreddit and over time

## Technologies Used
- Python
- Streamlit
- PRAW (Python Reddit API Wrapper)
- Pandas
- Matplotlib
- Seaborn

## Getting Started
To get started with the Telecom Fraud Visualization Dashboard, follow these steps:

1. Clone the repository:

2. Install the required Python packages:

3. Set up a Reddit Developer Account and create an app to obtain the API credentials.

4. Update the `client_id`, `client_secret`, and `user_agent` variables in the code with your Reddit API credentials.

5. Run the Streamlit app:

6. Access the dashboard by opening the provided local URL in your web browser.

## Usage
- The dashboard displays real-time information about telecom fraud mentions from Reddit.
- It includes a bar chart showing the number of fraud mentions by subreddit and a line chart showing the frequency of fraud mentions over time.
- Use the interactive controls provided by Streamlit to explore the data and gain insights into fraud patterns and trends.

## Deployment
To deploy the Telecom Fraud Visualization Dashboard to a cloud-based platform such as Heroku or AWS, follow the platform-specific deployment instructions and ensure that the required dependencies are installed.

## Contributing
Contributions to the Telecom Fraud Visualization Dashboard are welcome! If you have any ideas, improvements, or bug fixes, feel free to open an issue or submit a pull request.

