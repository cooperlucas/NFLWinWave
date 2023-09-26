# NFLWinWave
A twitter bot that automatically tweets every game changing moment in every NFL game

## Overview

The NFL Win Probability Twitter Bot is a Python program designed to monitor live NFL games, calculate win probabilities, and post updates and win probability graphs on Twitter. It utilizes data from ESPN's API to track real-time game scores, play-by-play information, and win probabilities, and it can be configured to post tweets for specific game events.

The program has several features, including:

Monitoring active NFL games.
Calculating and analyzing win probabilities during games.
Posting updates and win probability graphs on Twitter.
Handling different game events, including touchdowns, field goals, turnovers, and more.
Prerequisites

Before running the program, make sure you have the following prerequisites installed:

Python 3.x
Required Python libraries (requests, pandas, matplotlib, tweepy)
API access to ESPN's data (for live game information)
Twitter API access (for tweeting game updates)
Optional: Twilio API access (for SMS notifications)
Configuration

To configure the program, follow these steps:

Obtain API access:
Obtain access to ESPN's API for live game data. You may need to register and obtain an API key.
Obtain access to the Twitter API to post tweets. Create a Twitter Developer account and get API keys and access tokens.
Optional: Obtain Twilio API credentials if you want to enable SMS notifications.
Configure API credentials:
Update the program with your ESPN API key and Twitter API credentials.
Optionally, add Twilio credentials if you want to enable SMS notifications.
Customize behavior:
Adjust the program's behavior by modifying functions like is_win_wave, tweet_play, and tweet_scorecard to suit your tweeting criteria.
Set game monitoring:
Specify the games you want to monitor by updating the update_current_week_games function to filter games based on your preferences (e.g., teams, start times).
Run the program:
Execute the program by running the main function.
Usage

Here's how the program works:

The program continuously monitors active NFL games and calculates win probabilities.
It checks for specific game events and posts updates and win probability graphs to Twitter when criteria are met.
You can customize which game events trigger tweets and adjust the tweet content as needed.
Additional Notes

The program is designed for live game monitoring during NFL seasons. Ensure it's running during game times to capture live data.
Be mindful of Twitter's rate limits when posting tweets. Adjust the frequency of tweets accordingly.
Contributors

[Lucas Cooper]
License


Acknowledgments

Thank you to ESPN for providing game data.
Inspired by the Surrender Index twitter bot
