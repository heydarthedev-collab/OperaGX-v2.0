## PersianCloud-v1.0

<div align="center"><img src="https://img.icons8.com/color/96/windows-11.png" width="72" alt="Windows">PersianCloud

Automated Windows Environment Infrastructure

A lightweight Windows environment powered by GitHub Actions

<br><img src="https://img.shields.io/badge/Platform-Windows-0078D4?style=flat-square&logo=windows&logoColor=white">
<img src="https://img.shields.io/badge/Automation-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
<img src="https://img.shields.io/badge/Runtime-360%20Minutes-6C63FF?style=flat-square">
<img src="https://img.shields.io/badge/Remote%20Access-AnyDesk-EF443B?style=flat-square&logo=anydesk&logoColor=white"></div>---

Overview

PersianCloud-v1.0 is an automated Windows environment project designed around GitHub Actions.

The project provisions and configures a temporary Windows runner with a predefined desktop environment, display configuration, browser installation, and remote-access capabilities.

PersianCloud is designed to reduce repetitive setup tasks and provide a consistent environment for testing, development, experimentation, and temporary workloads.

---

Architecture

GitHub Actions
      │
      ▼
Windows Runner
      │
      ├── Environment Configuration
      ├── Display Configuration
      ├── Desktop Cleanup
      ├── Google Chrome
      ├── AnyDesk
      │
      ▼
Configured Windows Environment
      │
      ▼
Temporary Remote Workspace

---

Core Capabilities

Windows Environment

Automatically prepares the Windows runner and applies the required environment configuration.

Automated Provisioning

The complete setup process is executed through a GitHub Actions workflow without requiring manual configuration for each step.

Remote Access

Installs and configures AnyDesk to provide remote access to the prepared environment.

Browser Environment

Automatically installs Google Chrome and prepares it for immediate use.

Display Configuration

The environment is configured with a fixed display profile:

Resolution       1280 × 720
Aspect Ratio     16:9
Display Scaling  100%

Workspace Cleanup

Removes unnecessary desktop shortcuts and keeps the environment focused on the required tools.

Runtime Management

The workflow maintains the environment for a configured runtime of up to 360 minutes.

---

Environment Profile

Component| Configuration
Operating System| Windows
Automation| GitHub Actions
Shell| PowerShell
Display| 1280 × 720
Aspect Ratio| 16:9
Scaling| 100%
Browser| Google Chrome
Remote Access| AnyDesk
Maximum Runtime| 360 minutes

---

Getting Started

01. Open Actions

Navigate to the repository's Actions section.

02. Select PersianCloud

Select the PersianCloud-v1.0 workflow.

03. Start the Workflow

Select Run workflow and start the execution.

04. Wait for Provisioning

The workflow automatically performs the environment preparation and configuration stages.

05. Review the Logs

After the environment has been initialized, review the workflow logs for the generated runtime and connection information.

---

فارسی

معرفی

PersianCloud-v1.0 یک پروژه اتوماسیون برای آماده‌سازی یک محیط موقت Windows بر پایه‌ی GitHub Actions است.

این پروژه با هدف کاهش مراحل تکراری Setup، یک محیط Windows را با تنظیمات مشخص آماده می‌کند و بخش‌هایی مانند تنظیم نمایشگر، نصب مرورگر، پاک‌سازی محیط و آماده‌سازی دسترسی ریموت را به‌صورت خودکار انجام می‌دهد.

PersianCloud برای تست، توسعه، آزمایش و استفاده‌های موقت طراحی شده است.

---

ساختار عملکرد

GitHub Actions
      │
      ▼
Windows Runner
      │
      ├── آماده‌سازی محیط
      ├── تنظیم نمایشگر
      ├── پاک‌سازی Desktop
      ├── نصب Google Chrome
      ├── آماده‌سازی AnyDesk
      │
      ▼
محیط Windows آماده
      │
      ▼
Workspace موقت

---

قابلیت‌های اصلی

محیط Windows
آماده‌سازی خودکار Windows Runner و اعمال تنظیمات موردنیاز.

اتوماسیون Setup
اجرای مراحل اصلی آماده‌سازی از طریق GitHub Actions.

دسترسی ریموت
نصب و آماده‌سازی AnyDesk برای دسترسی از راه دور.

Google Chrome
نصب و اجرای خودکار مرورگر Google Chrome.

تنظیمات نمایشگر
محیط با مشخصات ثابت زیر آماده می‌شود:

Resolution       1280 × 720
Aspect Ratio     16:9
Display Scaling  100%

پاک‌سازی محیط
حذف Shortcutهای غیرضروری برای ایجاد یک Workspace مرتب‌تر.

مدیریت زمان اجرا
محیط برای حداکثر ۳۶۰ دقیقه قابل نگه‌داری است.

---

مشخصات

بخش| مقدار
سیستم‌عامل| Windows
سیستم اتوماسیون| GitHub Actions
Shell| PowerShell
رزولوشن| 1280 × 720
نسبت تصویر| 16:9
Scaling| 100%
مرورگر| Google Chrome
Remote Access| AnyDesk
حداکثر زمان اجرا| 360 دقیقه

---

نحوه استفاده

۱. ورود به Actions
از بخش Actions مخزن وارد Workflowها شوید.

۲. انتخاب PersianCloud
Workflow مربوط به PersianCloud-v1.0 را انتخاب کنید.

۳. اجرای Workflow
روی Run workflow کلیک کنید.

۴. تکمیل Setup
منتظر بمانید تا مراحل آماده‌سازی به‌صورت خودکار انجام شوند.

۵. بررسی Logs
پس از آماده‌شدن محیط، اطلاعات مربوط به اجرای Workflow و اتصال را از Logs بررسی کنید.

---

Security

«Keep your credentials private.»

اطلاعات حساس نباید در Repository عمومی قرار بگیرند.

هرگز موارد زیر را مستقیماً داخل کد یا README قرار ندهید:

- Passwords
- AnyDesk credentials
- API Tokens
- GitHub Tokens
- Private Keys
- Sensitive connection information

برای اطلاعات حساس از GitHub Secrets و Environment Variables امن استفاده کنید.

در صورت افشای تصادفی یک Credential، آن را فوراً Rotate یا Revoke کنید.

---

Project Status

Version: "v1.0"
Platform: "Windows"
Automation: "GitHub Actions"
Runtime: "Up to 360 Minutes"

---

Developer

PersianCloud is an independent project developed by an Iranian Developer, with a focus on automation, Windows environments, and practical development workflows.

---

Disclaimer

PersianCloud is intended for educational, development, testing, and authorized use only.

Only use the project on systems, accounts, and environments for which you have explicit authorization.

The project must not be used for unauthorized access or activity.

---

<div align="center">PersianCloud-v1.0

<br>Built with Windows · GitHub Actions · PowerShell

<br><br>

Javid Shah ♤
 
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/04/State_flag_of_Iran_1964-1980.svg/120px-State_flag_of_Iran_1964-1980.svg.png" width="30" alt="Lion and Sun Flag">

</div>
