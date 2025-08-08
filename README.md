# Website Status Checker (Bash)

This is a simple **Bash script** to check the availability and response time of multiple websites using `curl`.

It can be useful for **monitoring uptime** of a list of domains/subdomains — in this case, EC-Council subdomains — but can be adapted for any list of sites.


## 📌 Features

- Checks if each website is **Up**, **Unreachable**, or has an **Issue**.
- Displays **HTTP status code** and **response time**.
- Works on Linux and macOS with **`curl`** installed.
- Easy to modify for your own list of websites.


## 📂 Usages

1. **Clone the repository** or download the script:
   ```bash
   https://github.com/ifyouknowyou/website-up-down-check.git
   cd website-up-down-check

2. chmod +x website-up-down-check.sh
3. ./website-up-down-check.sh


🛠️ Requirements

  sudo apt install curl   # Debian/Ubuntu
  sudo dnf install curl   # Fedora
  brew install curl       # macOS
