🕵️ BaziGarr OSINT Tool

<p align="center">Advanced Mobile Number Information Lookup Tool

Developed & Maintained by BaziGarr

"Python" (https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
"Platform" (https://img.shields.io/badge/Platform-Termux%20%7C%20Kali%20Linux-green?style=for-the-badge)
"API" (https://img.shields.io/badge/API-Integrated-red?style=for-the-badge)
"License" (https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</p>---

⚡ About

BaziGarr OSINT Tool is a Python-based mobile number information lookup utility designed with a terminal-based interface.

The tool sends a mobile number to a configured API endpoint and displays the returned information in a structured and readable format.

It features a custom terminal banner, animated loading progress, colored output, and Base64-protected source code.

Built for educational purposes and authorized OSINT research.

✨ Features

- 🔍 Mobile Number Information Lookup
- 🌐 API-Based Information Retrieval
- 🎨 Colored Terminal Interface
- ⚡ Animated Loading Progress Bar
- 📊 Structured Search Results
- 🔐 Base64-Protected Source Code
- 🖥️ Custom BaziGarr Terminal Banner
- 🐍 Python-Based Implementation
- 📱 Termux & Kali Linux Compatibility

📸 Tool Preview

=========================================
        BAZIGARR OSINT TOOL
=========================================

[+] Enter Number - 10 Digit:

[>] Initializing OSINT Engine...
[>>>>>>>>>>>>>>>>>>>>>>>>>] 100% ✔

[+] Result Found!

--- Result 1 ---
Name: Example
Number: XXXXXXXX
Information: API Returned Data

=========================================
        Powered By BaziGarr
=========================================

Preview is illustrative. Actual results depend on the configured API.

🛠️ Requirements

- Python 3.x
- Requests library
- Active API endpoint
- Internet connection

🚀 Installation

Step 1 — Clone Repository

git clone YOUR_GITHUB_REPOSITORY_URL

Step 2 — Navigate to Project

cd YOUR_REPOSITORY_NAME

Step 3 — Install Dependencies

pip install requests

Step 4 — Run the Tool

python3 main.py

«Replace "main.py" with the actual Python filename in your repository.»

⚙️ API Configuration

The tool communicates with a configured API endpoint to retrieve information.

Before running the tool, configure your own authorized API credentials.

Find the API configuration section in the source code:

api_key = "YOUR_API_KEY"

base_url = "YOUR_API_ENDPOINT"

Important: Never publish your real API key in a public GitHub repository.

For production use, store API credentials in environment variables instead of hardcoding them.

🔐 Source Code Protection

The source code is stored in Base64-encoded format and decoded at runtime using Python's built-in "base64" module.

decoded = base64.b64decode(_payload).decode("utf-8")
exec(decoded, globals())

Note: Base64 is an encoding mechanism, not encryption. Anyone with access to the payload can decode it. Do not use it to protect API keys or sensitive credentials.

📱 Supported Platforms

Platform| Support
Android Termux| ✅
Kali Linux| ✅
Debian Linux| ✅
Ubuntu| ✅
Windows| ✅ (Python required)

⚠️ Disclaimer

This project is intended strictly for educational purposes, authorized OSINT research, and legitimate information lookup.

- Use the tool only with proper authorization.
- Do not use it to invade anyone's privacy.
- Do not use it for harassment, stalking, or illegal activities.
- API responses depend entirely on the third-party service.
- The developer is not responsible for misuse of this tool.

Respect privacy. Follow applicable laws. Use responsibly.

👨‍💻 Developer

<p align="center">BAZIGARR

OSINT | Python | Cybersecurity | Linux

GitHub: "@csrb4zzigar-07" (https://github.com/csrb4zzigar-07)

</p>---

<p align="center">⚡ POWERED BY BAZIGARR ⚡

Think Smart. Explore Responsibly.

</p>
