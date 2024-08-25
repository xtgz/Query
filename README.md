## Install the necessary dependencies by running:
```
npm install
```
#### Edit .env file in the root of the project and add your Telegram API credentials:
```
nano .env
```
> API_ID=your_telegram_api_id

> API_HASH=your_telegram_api_hash

#### Create session folder
```
mkdir session
```
#### Create data folder
```
mkdir data
```
### Usage
#### Run the script:
```
node main.js
```
You will be prompted to choose an option:

1. Create session: Start the process to create a new Telegram session.
2. Get query from session: Retrieve the latest queries from the specified Telegram bot.
