# endodork
endodork
🔹 Description (short summary for GitHub):

    A Bash-based advanced Google & GitHub dork generator for OSINT and bug bounty hunting.

📄 README.md for EndoDork

# 🔍 EndoDork – Dork Generator for OSINT & Bug Bounty

**EndoDork** is a smart and fast Google/GitHub dork generator written in Bash by **Inayat Hussain**. It’s designed for bug bounty hunters, OSINT professionals, and ethical hackers who need quick access to sensitive search queries.

## 🎯 Key Features

- Google, GitHub, and other dork types
- Smart keyword targeting (like `site:`, `inurl:`, `intitle:`)
- Helps find:
  - Exposed credentials
  - Sensitive directories
  - Public config files
  - Backup files
  - GitHub leaks
- Lightweight and fast — works on 4GB RAM laptops and cloud platforms (like Replit)

## ⚙️ Usage

```bash
chmod +x endodork.sh
./endodork.sh

    Enter your keyword (e.g. domain, app name, tech)

    Choose type of dorking (Google, GitHub, mixed)

    Output will be printed and saved in results/ directory

🛠️ Example Output

site:example.com intitle:"index of"
site:example.com ext:env | ext:sql | ext:log
github.com/example api_key OR password

You can copy-paste these into Google or GitHub search bars directly.
👤 Author

Inayat Hussain (Inayat Raj Chohan)
Bug bounty hunter | OSINT explorer | Bash scripter
🌐 LinkedIn
📘 Facebook: Inayat Raj Chohan
⚠️ Disclaimer

This tool is for educational and ethical purposes only. Do not misuse it on systems you don't have permission to test.
🙏 Support My Journey

I come from a village with no electricity, building tools on a 4GB laptop to help other learners worldwide. If you find value in this, please ⭐️ the repo or share it.


---

### 📁 Rename Your File
Rename the script file to:

endodork.sh
