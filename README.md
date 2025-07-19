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

Alright, here’s how you can get started with the Tesnet 2 & 3 task

1. **Open your terminal** using one of these methods (see 'How to Get Started' above):
   - **Gitpod**: Open a terminal in your Gitpod workspace.
   - **GitHub Codespace**: Open a terminal in your Codespace.
   - **WSL (Windows Subsystem for Linux)**: Open your WSL terminal on Windows.

2. Run these commands one by one:

```bash
git clone https://github.com/octra-labs/octra_pre_client.git
cd octra_pre_client
python3 -m venv venv
```

3. **Activate your virtual environment:**
- On **Linux/Mac**:
  ```bash
  source venv/bin/activate
  ```
- On **Windows**:
  ```bash
  venv\Scripts\activate
  ```

4. Install the requirements:
```bash
pip install -r requirements.txt
```

5. Copy the example wallet config:
```bash
cp wallet.json.example wallet.json
```

6. Open `wallet.json` in your favorite text editor and update it with your wallet info. It should look like this:
```json
{
  "priv": "private-key-here",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
```

7. Now, to run the client:
- On **Linux/Mac**:
  ```bash
  ./run.sh
  ```
- On **Windows**:
  ```bash
  run.bat
  ```

And that’s it! You’re all set. If you get stuck, just ask for help. Good luck and have fun!

---

Drop your feedback or questions on Twitter
