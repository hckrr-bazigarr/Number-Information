<p align="center">
  <img src="assets/bazigarr-logo.jpg" width="500" alt="BAZIGARR Logo">
</p><h1 align="center">🕵️ BaziGarr OSINT Tool</h1><p align="center">
  <b>Advanced Mobile Number Information Lookup Tool</b>
  <br>
  Developed & Maintained by <b>BaziGarr</b>
</p><p align="center">
  <img src="https://img.shields.io/badge/Version-3.0-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Platform-Termux%20%7C%20Kali-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Category-OSINT-black?style=for-the-badge">
</p>---

⚡ About

BaziGarr OSINT Tool is a Python-based mobile number information lookup utility designed with a customized terminal interface.

The tool communicates with a configured API endpoint and displays the returned information in a structured and readable format.

Built with a custom BaziGarr ASCII banner, animated loading progress, colored terminal output, multiple-result handling, and Base64-encoded source code.

Designed for educational purposes and authorized OSINT research.

✨ Features

- 🔍 Mobile Number Information Lookup
- 🌐 API-Based Information Retrieval
- 📊 Multiple Result Handling
- 🎨 Custom Green Terminal Interface
- 🔴 BaziGarr Custom ASCII Banner
- ⚡ Animated Loading Progress Bar
- 📱 10-Digit Mobile Number Validation
- 🗂️ Structured Information Display
- 🔐 Base64-Encoded Source Payload
- 🐍 Python-Based Implementation
- 📟 Termux & Kali Linux Compatibility

📸 Tool Preview

<p align="center">
  <img src="assets/terminal-preview.png" width="700" alt="BaziGarr OSINT Tool Preview">
</p><p align="center">
  <i>BaziGarr OSINT Engine PRO — Terminal Preview</i>
</p>🛠️ Requirements

- Python 3.x
- Requests library
- Active API endpoint
- Valid API credentials
- Internet connection

🚀 Installation

Step 1 — Update Packages

pkg update && pkg upgrade -y

Step 2 — Install Git & Python

pkg install git python -y

Step 3 — Clone Repository

git clone https://github.com/hckrr-bazigarr/Number-Information.git

Step 4 — Navigate to Directory

cd Number-Information

Step 5 — Install Requirements

pip install requests

Step 6 — Run the Tool

python3 main.py

«Replace "main.py" with your actual Python script filename if it is different.»

⚙️ API Configuration

The tool uses an external API endpoint to retrieve information.

Configure your authorized API credentials in the source code or through environment variables.

Example:

api_key = "YOUR_API_KEY"

base_url = "YOUR_API_ENDPOINT"

Important: Never expose real API keys, private credentials, or sensitive endpoints in a public repository.

🔐 Source Code Protection

The project uses Base64 encoding to store its Python source payload.

The encoded payload is decoded and executed at runtime.

Example:

decoded = base64.b64decode(_payload).decode("utf-8")

exec(decoded, globals())

Security Note: Base64 is encoding, not encryption. It does not prevent someone from recovering the original source code.

Never store confidential credentials inside the encoded payload.

📱 Supported Platforms

Platform| Compatibility
Android Termux| ✅
Kali Linux| ✅
Debian Linux| ✅
Ubuntu Linux| ✅
Windows| ✅

🖥️ How It Works

1. Launch the Python script.
2. Enter a valid 10-digit mobile number.
3. The tool validates the input.
4. The OSINT engine sends a request to the configured API.
5. The API response is processed.
6. Available results are displayed in the terminal.

⚠️ Disclaimer

This project is developed strictly for educational purposes and authorized OSINT research.

- Use only with proper authorization.
- Respect individual privacy and applicable data protection laws.
- Do not use this tool for stalking, harassment, or unauthorized surveillance.
- Do not misuse personal or confidential information.
- API results depend on the external service and may be inaccurate or incomplete.

The developer assumes no responsibility for unauthorized or illegal use of this software.

Use responsibly. Respect privacy. Stay ethical.

👨‍💻 Developer

<p align="center">
  <b>BAZIGARR</b>
  <br>
  OSINT | Python | Cybersecurity | Linux
  <br><br>
  GitHub: <a href="https://github.com/hckrr-bazigarr">@hckrr-bazigarr</a>
</p>---

<p align="center">
  <b>⚡ POWERED BY BAZIGARR ⚡</b>
  <br>
  <i>Think Smart. Explore Responsibly.</i>
</p>
