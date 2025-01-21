# Gaianet-Node-Run-Full-Guide

## Need Some Software Requirements for PC Users

1. For Windows Install WSL - https://learn.microsoft.com/en-us/windows/wsl/install#install-wsl-command

2. For Windows Install Ubuntu after Installing WSL - https://apps.microsoft.com/detail/9PDXGNCFSCZV?hl=en-us&gl=IN&ocid=pdpshare

3. For macOS If you have Installed Homebrew (https://brew.sh/) to manage packages on OS X,
run this command to install Git.
```
brew install git
```

## Need Some Hardware Requirements [Check Out](system-requirements.md)

1️⃣ Dependencies for WINDOWS & LINUX & VPS
```
sudo apt update
sudo apt upgrade -y
```

For VPS Only
```
apt install screen -y
```

2️⃣ Download Some Files
```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```
```
source /root/.bashrc
```
```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/refs/heads/main/llama-3.2-3b-instruct/config.json
```

For VPS Only
```
screen -S t3rn
```

3️⃣ Start Node & Stop Node
```
gaianet start
```
```
gaianet stop
```

For VPS Only
```
PRESS CTRL+A+D (to run ur miner continuously)
```

4️⃣ Check Your Node ID & Device ID
```
gaianet info
```

5️⃣ Check Your Points [Full Details](register.md)
Go:- https://tinyurl.com/ycyaxm7w

Refer Code:- RpwysF

## 🔶For Next Day Run This Command (Windows)

#1 Open WSL and Put this Command 
```
gaianet start
```
