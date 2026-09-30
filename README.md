# 🐺 Werrberus — Official Legal & Privacy Documentation

> **Discord Bot Verification & Compliance Suite**  
> **Effective Date:** September 30, 2026 | **Version:** 1.0  
> **Live Site:** [Werrberus Security Portal](https://lexovian.github.io/Werrberus-ToS-Privacy/)

This repository and directory host the public **Terms of Service**, **Privacy Policy**, and legal documentation for **Werrberus**, an autonomous Discord security and anti-raid system.

---

## 🌐 Live Web Portal (GitHub Pages)

The HTML/CSS files in this directory are hosted via GitHub Pages:

| Document | File | Live Target URL |
| :--- | :--- | :--- |
| **Landing & Overview** | [`index.html`](index.html) | `https://lexovian.github.io/Werrberus-ToS-Privacy/` |
| **Terms of Service** | [`terms.html`](terms.html) | `https://lexovian.github.io/Werrberus-ToS-Privacy/terms.html` |
| **Privacy Policy** | [`privacy.html`](privacy.html) | `https://lexovian.github.io/Werrberus-ToS-Privacy/privacy.html` |
| **Design System** | [`style.css`](style.css) | Dark glassmorphism stylesheet |

---

## 📜 1. Terms of Service

### 1.1 Purpose and Service Scope
Werrberus provides real-time, autonomous anti-raid, anti-phishing, anti-nuke, and cyber-security threat mitigation services for Discord communities. The Bot evaluates join events, user interactions, and message structures using purely stateless, in-memory algorithmic models (including Mandelbrot fractal dynamics, modular algebra invariants, and information entropy analysis).

### 1.2 Authority and Permissions
By adding Werrberus to a Discord guild and granting it permissions (`Ban Members`, `Kick Members`, `Moderate Members`, `Manage Messages`, `Manage Channels`, and `View Audit Log`), you expressly authorize Werrberus to execute automated defensive moderation actions according to the security profile selected by guild administrators.

> **Important Notice:** While Werrberus uses advanced deterministic models with high confidence thresholds, automated systems may occasionally flag borderline activity. Administrators retain full supervisory authority via interactive **`[ 👁️ Reviewed ]`** and **`[ 🔓 Revert Punishment ]`** moderator review buttons.

### 1.3 Acceptable Use Policy
You agree not to:
* Attempt to reverse-engineer, exploit, or bypass the Bot's security checks and rate limiters.
* Use the Bot in guilds that violate Discord's [Terms of Service](https://discord.com/terms) or [Community Guidelines](https://discord.com/guidelines).
* Conduct intentional Denial-of-Service (DoS) attacks or command floods against the Bot's infrastructure.
* Misrepresent the Bot's origin, ownership, or authority.

### 1.4 Disclaimers and Limitation of Liability
Werrberus is provided on an **"AS IS"** and **"AS AVAILABLE"** basis without warranties of any kind. While engineered for maximum accuracy and 0ms reflex defense, the developers shall not be liable for any indirect, incidental, or consequential damages resulting from the use or inability to use the Bot, including but not limited to server downtime, unexpected moderation actions, or unmitigated security breaches.

### 1.5 Termination and Removal
Server administrators may terminate this agreement at any time by kicking or banning Werrberus from their guild. Upon eviction, all transient in-memory buffers associated with the guild are immediately purged.

### 1.6 Modifications to Terms
We reserve the right to modify these Terms of Service. Meaningful changes will be notified via our documentation portal and release announcements. Continued use of the Bot following such changes constitutes acceptance of the revised Terms.

---

## 🔒 2. Privacy Policy

### 2.1 The Zero-Retention Principle
> **Guaranteed Stateless Operation:** Werrberus does not store, monetize, track, or profile personal user data. All threat analyses occur strictly in transient RAM using CPU mathematical models. Once an event is analyzed, its raw contents are instantly released from memory.

### 2.2 Information Processed in Real-Time (Volatile RAM Only)
To defend Discord servers against raid swarms, phishing scams, and malicious drainers, Werrberus inspects the following event data in volatile memory (RAM) exclusively during runtime evaluation:
* **Discord Snowflake IDs:** Inspected for GAP-0331 $Z/9Z$ modular residue clustering and creation epoch delta calculations to detect coordinated botnet swarms.
* **Account Metadata:** Account creation timestamp and avatar presence (used to assess account freshness and burst risk).
* **Message Content:** Inspected transiently to detect dangerous URLs, typosquatting domains, crypto drainer patterns, and high-entropy token-stealer payloads.
* **Audit Log Records:** Inspected solely when mass channel or role deletions occur to identify compromised rogue administrative accounts.

### 2.3 Information Stored Persistently
The **only** information stored persistently on disk is guild configuration settings in a local `guild_settings.json` file:
* **Guild ID:** The numerical Discord ID of the server.
* **Configured Log Channel ID:** The channel where security alerts and review cards are dispatched.
* **Operational Thresholds:** The selected security profile (`balanced`, `strict`, or `relaxed`) and user-adjusted numeric limits (join burst threshold, spam limits, feature toggles).

*No usernames, avatar images, messages, IP addresses, or conversation histories are ever written to disk or transferred to third-party databases.*

### 2.4 Third-Party Sharing and Tracking
We do **not** share, sell, rent, or distribute any user or guild data to third parties, advertising networks, or external analytics vendors. Werrberus operates 100% self-contained without external third-party API dependencies or tracking pixels.

### 2.5 Data Subject Rights & Deletion (GDPR / CCPA)
Because Werrberus retains no personal user data, there is no personal database record to query or delete. If a server administrator wishes to remove all persistent guild configuration settings:
1. Run the `/werr reset` slash command to restore all guild settings to default.
2. Remove Werrberus from the server (all active in-memory counters and timers are immediately discarded).

---

## 🚀 3. How to Deploy to GitHub Pages

If you are hosting this documentation on GitHub Pages:

### Step 1: Push to GitHub
If using a dedicated public legal repository (e.g. `werrberus-legal`):
```bash
git init
git add .
git commit -m "feat: Werrberus legal & privacy compliance suite"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

### Step 2: Enable GitHub Pages
1. Go to your repository on GitHub.
2. Navigate to **Settings** $\rightarrow$ **Pages** (under "Code and automation").
3. Under **Build and deployment** $\rightarrow$ **Source**:
   - Select **Deploy from a branch**.
   - Branch: `main` | Folder: `/ (root)` (or `/docs` if pushed from the main repository).
4. Click **Save**.

### Step 3: Configure Discord Developer Portal
Copy your published URLs into the **Discord Developer Portal** $\rightarrow$ **Your Application** $\rightarrow$ **General Information**:
* **Terms of Service URL:** `https://lexovian.github.io/Werrberus-ToS-Privacy/terms.html`
* **Privacy Policy URL:** `https://lexovian.github.io/Werrberus-ToS-Privacy/privacy.html`

---

## 📬 4. Security & Compliance Contact

For security vulnerability disclosures, legal inquiries, or verification reviews:
* **Discord Community:** Available via Discord Developer Portal
* **Project Repository:** [Werrberus Security Core](https://github.com/lexo/werrberus)
