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
   git clone https://github.com/yourusername/website-status-checker.git
   cd website-status-checker

2. chmod +x check_websites.sh
3. ./check_websites.sh


🛠️ Requirements

  sudo apt install curl   # Debian/Ubuntu
  sudo dnf install curl   # Fedora
  brew install curl       # macOS
