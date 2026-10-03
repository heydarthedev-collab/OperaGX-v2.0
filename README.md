## <p1 align="center">PersianCloud-v1.0>

<p align="center">
  <a href="https://github.com/heydarthedev-collab/PersianCloud-v1.0" target="_blank" rel="noopener noreferrer">
    <img src="https://img.icons8.com/color/240/windows-11.png" alt="PersianCloud" width="160" height="160">
  </a>
</p><h1 align="center">☁️ PersianCloud</h1><p align="center">
    <strong>Automated Windows Environment powered by GitHub Actions</strong>
</p><p align="center">
    A lightweight and automated Windows workspace for testing, development and temporary workloads.
</p>---

<br/><p align="center">
    <img src="https://img.shields.io/badge/platform-Windows-0078D4?style=flat-square&logo=windows&logoColor=white" />
    <img src="https://img.shields.io/badge/automation-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
    <img src="https://img.shields.io/badge/shell-PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" />
    <img src="https://img.shields.io/badge/remote-AnyDesk-EF443B?style=flat-square&logo=anydesk&logoColor=white" />
    <img src="https://img.shields.io/github/license/heydarthedev-collab/PersianCloud-v1.0?style=flat-square" />
</p><p align="center">
    <a href="#-overview">Overview</a>
    /
    <a href="#-features">Features</a>
    /
    <a href="#-quick-start">Quick Start</a>
    /
    <a href="#-documentation">Documentation</a>
</p><p align="center">
  <a href="https://github.com/heydarthedev-collab/PersianCloud-v1.0">
    <img src="https://github.com/heydarthedev-collab/PersianCloud-v1.0/raw/main/assets/preview.png" alt="PersianCloud Preview" width="700">
  </a>
</p>---

📋 Table of Contents

«Quick Navigation - Jump to any section below»

- "📖 Overview" (#-overview)
  - "🤔 Why PersianCloud?" (#-why-persiancloud)
  - "✨ Features" (#-features)
- "🚀 Quick Start" (#-quick-start)
- "🖥️ Environment" (#️-environment)
- "🔐 Security" (#-security)
- "📚 Documentation" (#-documentation)
- "👨‍💻 Developer" (#-developer)

---

📖 Overview

«What is PersianCloud?»

PersianCloud is an automated Windows environment workflow built with GitHub Actions.

It combines Windows environment preparation, desktop cleanup, display configuration, Google Chrome installation, AnyDesk setup and runtime management into a single automated workflow.

The goal is simple: provide a consistent, temporary and ready-to-use Windows environment without requiring every setup step to be performed manually.

---

🤔 Why PersianCloud?

«Simple, Automated, Ready»

Preparing a temporary Windows environment can require multiple repetitive steps.

PersianCloud brings these operations together into one workflow so the environment can be prepared automatically whenever the workflow is started.

It is designed for:

- Development environments
- Testing
- Temporary workloads
- Windows application testing
- Experiments
- Remote desktop sessions
- Short-term development tasks

---

✨ Features

<div align="left">🪟 Windows Environment

- Automated Windows runner preparation
- Desktop environment cleanup
- Fixed display configuration
- 100% display scaling
- 16:9 display profile

⚙️ Automation

- GitHub Actions workflow
- PowerShell-based automation
- Manual workflow execution
- Automated installation and configuration
- Runtime management

🌐 Browser

- Automatic Google Chrome installation
- Chrome desktop shortcut
- Automatic browser launch
- Preconfigured browser startup

🔗 Remote Access

- AnyDesk installation
- Automated unattended-access configuration
- AnyDesk service restart
- Automatic AnyDesk ID detection
- Connection information available through workflow logs

🖥️ Display

- "1280 × 720" resolution target
- "16:9" aspect ratio
- "100%" scaling
- Mobile-friendly fixed display profile

🧹 Environment Cleanup

- Removes unnecessary desktop shortcuts
- Minimizes infrastructure windows
- Keeps the workspace clean and focused

⏱️ Runtime

- Configurable runtime
- Default runtime of up to "360 minutes"
- Workflow heartbeat during the active session

</div>---

🚀 Quick Start

«Quick Start - Prepare PersianCloud through GitHub Actions»

1. Open Actions

Open the repository's Actions tab.

2. Select the Workflow

Choose the PersianCloud workflow.

3. Run the Workflow

Click:

Run workflow

and start the workflow manually.

4. Wait for Setup

PersianCloud will automatically:

Windows Runner
      ↓
Environment Cleanup
      ↓
AnyDesk Installation
      ↓
Remote Access Configuration
      ↓
Display Configuration
      ↓
Google Chrome Installation
      ↓
Chrome Launch
      ↓
AnyDesk ID Detection
      ↓
Keep Alive

5. Check the Logs

After the environment is ready, check the GitHub Actions logs for the generated runtime and connection information.

---

🖥️ Environment

<p align="center">
  <img src="https://img.icons8.com/color/96/windows-11.png" width="64" alt="Windows">
  <img src="https://img.icons8.com/color/96/github.png" width="64" alt="GitHub">
  <img src="https://img.icons8.com/color/96/google-chrome.png" width="64" alt="Chrome">
  <img src="https://img.icons8.com/color/96/remote-desktop.png" width="64" alt="Remote Desktop">
</p>Environment Configuration

Operating System : Windows
Automation       : GitHub Actions
Shell            : PowerShell
Resolution       : 1280 × 720
Aspect Ratio     : 16:9
Scaling          : 100%
Browser          : Google Chrome
Remote Access    : AnyDesk
Runtime          : Up to 360 Minutes

Runtime Flow

GitHub Actions
       │
       ▼
Windows Runner
       │
       ├── Cleanup
       ├── Display Setup
       ├── Chrome Setup
       ├── AnyDesk Setup
       │
       ▼
Configured Environment
       │
       ▼
Keep Alive

---

🔐 Security

«Keep your credentials private»

PersianCloud uses remote-access configuration during runtime.

Never publish sensitive credentials directly inside the repository.

Do not expose:

- AnyDesk passwords
- Remote-access credentials
- GitHub tokens
- API tokens
- Private keys
- Authentication secrets

For sensitive values, use GitHub Secrets or secure environment variables.

Important

The example workflow contains a password value for demonstration/configuration purposes.

For real deployments, replace hard-coded credentials with a secure secret.

If a credential is exposed, rotate or revoke it immediately.

---

📚 Documentation

The main configuration is contained inside the GitHub Actions workflow.

.github/
└── workflows/
    └── AnyDesk.yml

The workflow is responsible for:

- Windows environment preparation
- AnyDesk installation
- AnyDesk configuration
- Display configuration
- Google Chrome installation
- Desktop shortcut management
- Connection ID detection
- Runtime management

For changes to the environment, edit the workflow and review the corresponding PowerShell section.

---

📦 Project Structure

PersianCloud-v1.0/
│
├── .github/
│   └── workflows/
│       └── AnyDesk.yml
│
├── assets/
│   └── preview.png
│
└── README.md

---

🧩 Technology Stack

<p align="center"><img src="https://img.icons8.com/color/64/windows-11.png" width="52">
<img src="https://img.icons8.com/color/64/github.png" width="52">
<img src="https://img.icons8.com/color/64/powershell.png" width="52">
<img src="https://img.icons8.com/color/64/google-chrome.png" width="52"></p><p align="center">
    <strong>Windows · GitHub Actions · PowerShell · AnyDesk · Google Chrome</strong>
</p>---

🇮🇷 PersianCloud

PersianCloud is an independent project developed by an Iranian Developer.

The project focuses on Windows automation, temporary environments and reducing repetitive setup operations through GitHub Actions.

Built in Iran. Built for developers.

---

👨‍💻 Developer

<div align="center">PersianCloud-v1.0

<br>Developed independently by an Iranian Developer.

<br><br>

Javid Shah ♤
 
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/04/State_flag_of_Iran_1964-1980.svg/120px-State_flag_of_Iran_1964-1980.svg.png" width="30" alt="Lion and Sun Flag">

</div>---

⚠️ Disclaimer

PersianCloud is intended for educational, development, testing and authorized use only.

Only use this project on systems, accounts and environments that you are authorized to access.

The author is not responsible for unauthorized access, misuse or improper use of the project.

---

<p align="center"><strong>PersianCloud-v1.0</strong>

<br><br>

<sub>Automate your Windows environment. Keep your workflow simple.</sub>

</p>
