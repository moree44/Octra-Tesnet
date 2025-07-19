# Octra-Tesnet

Hey frens 0$ Cost for Octra Tesnet Guide

## What’s This?
0$ Cost for Octra Tesnet Guide

## How to Get Started
You’ll need one of these:
- **Gitpod** ([link](https://www.gitpod.io/)) – Log in with GitHub, open a terminal, you’re set.
- **GitHub Codespace** ([link](https://github.com/codespaces)) – Log in with GitHub (recommended, it’s fast!).
- **WSL (Windows Subsystem for Linux)** – For Windows users.


## Quick Start
Copy-paste this in your terminal:

```bash
git clone https://github.com/octra-labs/wallet-gen.git
cd wallet-gen
unzip example.zip
chmod +x ./wallet-generator.sh
./wallet-generator.sh
```

## Tesnet 2&3 Task

### How to install and run (super chill guide)

1. **Pop open your terminal**

2. Copy-paste these commands, one by one:

```bash
git clone https://github.com/octra-labs/octra_pre_client.git
cd octra_pre_client
python3 -m venv venv
source venv/bin/activate   # on Windows: venv\Scripts\activate
pip install -r requirements.txt
cp wallet.json.example wallet.json
```

3. **Edit your `wallet.json`**
Swap in your wallet deets:
```json
{
  "priv": "your-private-key",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
```

4. **Run it!**
- On Mac/Linux:
  ```bash
  ./run.sh
  ```
- On Windows:
  ```bash
  run.bat
  ```

That’s you're good to go, Send some public Transaction or Private Transaction to other

---

Drop your feedback or if you facing issue with faucet reply on my X with your Octra Address
