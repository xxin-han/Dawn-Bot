# Dawn Validator BOT

**DAWN** is a decentralized broadband wireless network protocol built on the Solana blockchain. Its core mission is to democratize internet access by enabling individuals to become local internet service providers within their communities.

## Features

  - Auto Get Account Information
  - Auto Run With Public Proxy - Choose 1
  - Auto Run With Private Proxy - Choose 2 [**GET PROXY**](https://dashboard.proxyscrape.com/)
  - Auto Run Without Proxy - Choose 3
  - Auto Send Keep-Alive Every 5 Minutes
  - Multi Accounts With Threads


## Installation

1. Download Extension Here : [Dawn Validator](https://chromewebstore.google.com/detail/dawn-validator-chrome-ext/fpdkjdnhkakefebpekbdhillbhonfjjp?hl=en)

2. Install tools

   ```bash
   sudo apt update
   ```
   ```bash
   wget https://github.com/xxin-han/setup/raw/main/setup.sh -O setup.sh && chmod +x setup.sh && ./setup.sh
   ```
   ```bash
   pip install -r requirements.txt
   ```

2. Clone Repository
   ```bash
   git clone https://github.com/xxin-han/Dawn-Bot.git
   ```
   ```bash
   cd Dawn-Bot
   ```

3. Getting Token
- Open ``The DAWN Extension`` in your browser and login
- Press F12 or CTRL+SHIFT+I and Select Network
- Look for ``getpoint?appid=``
- Insert your account details in ``accounts.json``, with each line in the format for each account, 

4. Fill the Gmail & Token list on accounts.json then save it ctrl + x + y + enter
```bash
nano accounts.json
```
5. If using Proxy list then save it ctrl + x + y + enter
```bash
 nano proxy.txt
```

6. Run Command

```bash
python bot.py #or python3 bot.py
```
6. Stop Command

    ```CTRL + C ```