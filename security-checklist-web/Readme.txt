# Security Checklist Automation — MVP

A **frontend-first MVP** to generate a security checklist from user input and selected checks. This tool simulates common web security checks, allows local project saving, and exports the results as **TXT** or **PDF**.  

> ⚠️ This is a **simulation only**. Replace with real scanner APIs or backend orchestration for production.

---

## Features

- Paste a URL or notes to generate a checklist.
- Select which security checks to simulate:
  - SAST (static analysis)
  - DAST (dynamic/web scan)
  - Dependency scanning
  - Secrets detection
  - Security headers check
  - Container scanning
  - Access control checks
  - OWASP Top 10 quick probe
- Pick a CI provider: **GitHub Actions** or **GitLab CI**.
- Save and refresh projects in **local browser storage**.
- View checklist, updates, and reminders.
- Download the checklist as:
  - **TXT**
  - **PDF**

---

## Getting Started

1. Clone or download the project files.
2. Open `index.html` in your web browser.
3. Enter your URL/notes in the left panel.
4. Select the security checks you want to simulate.
5. Pick a CI provider if needed.
6. Click **Generate** to see the checklist.
7. Use **Download Checklist (TXT/PDF)** to export the results.
8. Use **Save** to save the project locally and **Refresh** to reload saved data.

---

## File Structure

