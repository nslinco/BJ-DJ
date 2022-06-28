# The BJ DJ
A Python auto-clicker for exploiting blackjack bots on Discord

## Motivation
A one-night challenge to exploit a 10.1% player advantage (for the form of blackjack where the dealer exposes both cards and ties push) to become the richest player on a Discord game.

## Summary
The BJ DJ is a small python script that autonomously monitors a user's Discord and optimally responds to blackjack hands according to strategy spreadsheets stored on Google Drive.

## Stack
-     Software: Python
      - requests: Call the Discord API using authenticated requests to listen for new hands
      - gspread: Get the optimal action for a blackjack hand according to a strategy spreadsheet on Google Drive
      - pyautogui: Click the corresponding action on Discord
-     Storage: Google Drive

## Next Steps
Create a web scraper to find online casinos that offer player-advantage blackjack tables and play them according to their respective strategy sheets (within the Terms of Service, of course)

## Comments? Questions? Concerns? Just want to chat?
My inbox is always open and I'd love to hear your thoughts. You can find my email [on my profile](https://github.com/nslinco).
