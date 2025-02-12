# NodeGo VOT
NodeGo VOT

- Register Here : [NodeGo](https://app.nodego.ai/r/NODEF83C1F837A09)
- Use Code : NODEF83C1F837A09

## Features

  - Auto Get Account Information
  - Auto Run With [Monosans](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt) Proxy - Choose 1
  - Auto Run With Private Proxy - Choose 2
  - Auto Run Without Proxy - Choose 3
  - Auto Added Node & Send Ping Every 1 Minutes
  - Supports Multi Nodes For Each Account
  - Multi Accounts With Threads

Note: 
1. Only running 1 node if run without proxy.
2. Some features will be available soon.
3. If there is an error. Please first find out the meaning of the error with the status code displayed. if the error is with status code 500 or higher. The problem is on the project server. Some of you opened an issue and complained that there was an error with status code 502 and told me to update the bot. Hey sir, are you kidding me?

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.

## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/xmandirigma/NodeGo-VOT.git
   ```
   ```bash
   cd NodeGo-VOT
   ```

2. **Install Requirements:**
   ```bash
   pip3 install -r requirements.txt
   ```

## Configuration

- **tokens.txt:** You will find the file `tokens.txt` inside the project directory. Make sure `tokens.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
  nano tokens.txt
  ```

- **proxy.txt:** You will find the file `proxy.txt` inside the project directory. Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
  nano proxy.txt
  ```

## Run

```bash
python3 bot.py
```

