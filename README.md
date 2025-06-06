# 🛡️ Discord Token Type Checker

A simple Flask web app that lets developers check whether a Discord token is a **bot** or a **user** token.

## 🔍 What It Does

- Accepts a Discord token through a web form
- Automatically determines if it's a bot or user token
- Pretty-prints the `/users/@me` API response
- Helpful for debugging or inspecting leaked tokens

## 🛠️ Tech Stack

- Python 3
- Flask
- Requests
- HTML + CSS (Jinja2 templates)

## 🚀 Getting Started

1. Clone the repo:

```bash
git clone https://github.com/discowd-nitwo/discord-token-checker.git
cd discord-token-checker
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the app:
```bash
python app.py
```
4. Open your browser and go to:
```bash
http://localhost:5000
```
## ⚠️ Disclaimer
This tool is for educational and debugging purposes only. Do not use user tokens you don't own. Misuse may violate Discord’s Terms of Service.

>🔒 **Privacy Notice**: This tool intentionally strips out sensitive fields like emails and phone numbers from the output ([Removed due to privacy]). If you fork or reuse this code, please keep that protection in place.
## 📄 License
```
MIT License

Copyright (c) 2025 Avery

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
