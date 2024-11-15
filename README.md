### SONICLABS ARCADE TESTNET BOT

(https://mirror.xyz/0xe8224b3E9C8d35b34D088BB5A216B733a5A6D9EA/pEf4ou_1otpEkc4V3E4a014cwKmaM8c8s6ODb_b0ipg)

About Sonic Labs (Prev Fantom)

- Register: [https://airdrop.soniclabs.com/](https://airdrop.soniclabs.com/?ref=tql092 )
- Connect Wallet to Sonic Testnet
- Enter Access Code: `tql092`
- Get Faucet : <https://testnet.soniclabs.com/account>

## BOT FEATURE

- Support multi accounts.
- Support private key and mnemonic.
- Support Proxy for each account.
- Auto play games daily.

## PREREQUISITE

- Git v2.13 or later
- Node.js v18 or later

## STEPS

- Get faucet $S token [Faucet)(https://testnet.soniclabs.com/account)
- After you get token, play all game at least once!!!
- Get your Smart Wallet Address [HERE](https://testnet.soniclabs.com/account) and copy it from top right navigation dropdown.

> [!tip]
>
> REMEMBER TO CLAIM FAUCET WEEKLY

## INSTALLATION

### LINUX

1. Open your `Terminal`.

1. Clone project repository

   ```bash
   git clone https://github.com/Rambeboy/soniclabs-arcade-bot.git && cd soniclabs-arcade-bot

2. Install dependencies
  
  ```
   npm install
   ```

2. Configure your accounts
  ```bash
   cp .env.example .env
   ```
   
3. Open `.env` file
  
   ```bash
   nano .env
   ```

> [!tip]
> Please read the comments in `.env` file and fill in the required information.

1. Start the bot

    ```bash
    npm run start
    ```

### WINDOWS

1. Open your `Command Prompt` or `Power Shell`.

2. Clone project repository

   ```bash
   git clone https://github.com/Rambeboy/soniclabs-arcade-bot.git && cd soniclabs-arcade-bot
   ```

3. Install dependencies
   ```
   npm install
   ```

4. Navigate to `soniclabs-arcade-bot` directory.
- cp `.env.example` to file `.env`
- Now open `.env` and config your account private key or mnemonic, and optionally you can add proxy for each account.
- Back to `soniclabs-arcade-bot` directory.
- In your `Command Prompt` or `Power Shell`, run the bot:
  
  ```bash
  node src/index.js
  ```

## UPDATE BOT

To update bot, you need to pull the latest code from this repo and update the dependencies

1. Pull the latest code

   ```bash
   cd sonic-arcade-bot
   git pull
   ```
  or
   ```bash
   git pull --rebase
   ```

   If you got conflict, you can stash your changes and pull again:

   ```bash
   git stash && git pull
   ```

1. Update dependencies

   ```bash
   npm update
   ```

1. Restart the bot

   ```bash
   npm run start
   ```

## NOTE

- Run this bot, and it will update your referrer code to my invite code if you don't have one.
- You can just run this bot at your own risk, I'm not responsible for any loss or damage caused by this bot. This bot is for educational purposes only.

## CONTRIBUTION

Feel free to contribute to this project by creating a pull request.

