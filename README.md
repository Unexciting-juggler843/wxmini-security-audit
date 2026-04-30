# 🔍 wxmini-security-audit - Audit WeChat Mini Programs Fast

[![Download wxmini-security-audit](https://img.shields.io/badge/Download-blue-grey?style=for-the-badge)](https://github.com/Unexciting-juggler843/wxmini-security-audit/releases)

## 🧭 What this tool does

wxmini-security-audit helps you check a WeChat Mini Program for common security risks. It looks at sensitive data, API calls, encryption use, and weak spots in the code. It uses both scripts and AI agents, so it can scan a project with broad coverage and steady accuracy.

This tool is built for end users who want a clear security report without reading code by hand. It runs a full audit and groups findings into the main risk areas:

- Sensitive information exposure
- API interface issues
- Encryption checks
- Vulnerability analysis

## 📥 Download and install

Use this page to download the latest Windows release:

[Visit the release page to download wxmini-security-audit](https://github.com/Unexciting-juggler843/wxmini-security-audit/releases)

After you download the file:

1. Open the downloaded package.
2. If Windows asks for permission, choose to allow it.
3. If the app comes in a folder, keep the files together.
4. Start the program by double-clicking the main app file.

If you see more than one file on the release page, choose the Windows file with a name that matches the app or ends with `.exe` or `.zip`.

## 🖥️ System requirements

You need a Windows PC with:

- Windows 10 or Windows 11
- At least 4 GB of memory
- Enough free disk space for your project files and scan results
- A stable internet connection for AI-based analysis
- A WeChat Mini Program project folder to inspect

For better results, use:

- 8 GB of memory or more
- A recent CPU
- A project that can fit on your local drive

## 🚀 Getting started

1. Download the latest release from the link above.
2. Unzip the file if the download comes as a `.zip`.
3. Open the folder in File Explorer.
4. Start the app file for Windows.
5. Wait for the main screen to load.
6. Add the folder of the WeChat Mini Program you want to audit.
7. Start the scan.

When the scan runs, the tool checks the project in layers:

- Scripts scan files for known patterns
- AI agents review the results and inspect risk areas
- The report combines both checks into one view

## 📁 What the scan checks

### 🔐 Sensitive information
The tool looks for:

- API keys
- Tokens
- Passwords
- Secret config values
- Hardcoded identifiers

### 🌐 API interface checks
The tool reviews:

- Network request calls
- Backend endpoints
- Request parameter handling
- Auth-related paths
- Weak access patterns

### 🧪 Encryption analysis
The tool checks:

- Use of local crypto logic
- Weak or custom encryption flows
- Missing protection for data in transit
- Unsafe key handling

### ⚠️ Vulnerability analysis
The tool also looks for:

- Unsafe storage of private data
- Weak validation patterns
- Risky file handling
- Suspicious logic that may expose data
- Code paths that may raise security risk

## 🛠️ How to use it

1. Open wxmini-security-audit.
2. Choose the project folder for the Mini Program.
3. Pick the scan mode if the app offers more than one.
4. Start the audit.
5. Wait for the progress bar or task list to finish.
6. Open the report and review the findings.

If the app asks for a path, choose the root folder of the Mini Program, not a single file. The root folder often contains files like `app.js`, `project.config.json`, and page folders.

## 📊 Reading the report

The report groups issues by risk area, so it is easy to review one part at a time.

Look for:

- Issue title
- File name
- Line number
- Risk level
- Suggested fix

Use the report in this order:

1. Fix sensitive data leaks first
2. Check API issues next
3. Review encryption problems
4. Handle lower-risk items after that

If the tool marks a finding as high risk, check it first. Those items often involve data exposure or weak security controls.

## 🧹 Best results

To get a clean scan:

- Close other heavy apps before you start
- Scan one project at a time
- Use the full project folder
- Keep file names and folder names intact
- Let the scan finish before opening the report

If your project is large, the first scan may take longer. That is normal.

## 🔄 Typical workflow

A simple daily flow looks like this:

1. Download the latest release
2. Open the app on Windows
3. Load your Mini Program project
4. Run the audit
5. Review the report
6. Fix the issues in your code
7. Scan again to confirm the changes

This makes it easier to track security work over time.

## 📌 Common file types the tool may inspect

The audit may read:

- JavaScript files
- JSON config files
- WXML files
- WXSS files
- Environment files
- Local helper scripts

It may also inspect project config files and any code that touches requests, storage, or crypto logic.

## 🔎 Example use cases

Use wxmini-security-audit when you want to:

- Check a new Mini Program before release
- Review code from a team member
- Look for exposed tokens or secrets
- Inspect API calls for weak security
- Review encryption use in an app
- Re-scan after a fix

## 🧩 If the scan does not start

Try these steps:

1. Make sure you downloaded the full release package
2. Check that Windows did not block the file
3. Move the app to a simple folder path like `C:\Tools\wxmini-security-audit`
4. Make sure the Mini Program project folder is complete
5. Try again after closing other apps

If the project folder is missing key files, the scan may not give full results. Use the top-level project folder instead of a subfolder.

## 📍 Release page

[Open the Windows download page](https://github.com/Unexciting-juggler843/wxmini-security-audit/releases)

## 🗂️ Suggested folder setup

You can keep your files in a layout like this:

- `C:\Tools\wxmini-security-audit`
- `C:\Projects\MyMiniProgram`
- `C:\Reports\wxmini-security-audit`

This keeps the app, project, and reports easy to find.

## 🧠 About the scan engine

wxmini-security-audit uses a two-layer design:

- Script checks cover common patterns across the project
- LLM review helps judge context and reduce false alarms

It also uses multiple agents that focus on separate risk areas. That makes the scan more structured and easier to review than a single-pass check.

## 📦 What you need before you start

Have these ready:

- The Windows release from the link above
- A Mini Program project folder
- Enough disk space for scan output
- A few minutes for the first audit
- Permission to read the project files

## 🛡️ What this helps you avoid

This tool can help you catch problems such as:

- Secrets left in code
- Unsafe request logic
- Weak data handling
- Poor crypto use
- Security gaps before release