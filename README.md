# 🐺 Werrberus — Official Legal & Privacy Documentation Suite

> **Discord Bot Verification & Developer Policy Compliance Portal**  
> **Effective Date:** October 1, 2026 | **Version:** 1.1 Enterprise  
> **Live Site:** [Werrberus Security & Legal Portal](https://lexovian.github.io/Werrberus-ToS-Privacy/)

This directory contains the public **Terms of Service**, **Privacy Policy**, and visual overview pages for **Werrberus**, an autonomous Discord security and anti-raid system.

---

## 🌐 Public Documents & GitHub Pages URLs

When deployed to GitHub Pages, the following URLs provide compliance endpoints for Discord Bot Verification:

| Document | Source File | Live Target URL | Purpose |
| :--- | :--- | :--- | :--- |
| **Security Overview** | [`index.html`](index.html) | `https://lexovian.github.io/Werrberus-ToS-Privacy/` | Public landing page & feature documentation |
| **Terms of Service** | [`terms.html`](terms.html) | `https://lexovian.github.io/Werrberus-ToS-Privacy/terms.html` | Official user agreement & authority scope |
| **Privacy Policy** | [`privacy.html`](privacy.html) | `https://lexovian.github.io/Werrberus-ToS-Privacy/privacy.html` | Zero-Data-Retention & Intent transparency |
| **Design System** | [`style.css`](style.css) | Dark glassmorphism stylesheet | Modern, responsive cybersecurity styling |

---

## 📜 1. Terms of Service Summary

* **Scope:** Real-time, autonomous protection against raids, token grabbers, Web3 wallet drainers, and rogue admin channel nukes.
* **Permissions Justification:** Transparency regarding required moderation permissions (`Ban Members`, `Kick Members`, `Moderate Members`, `Manage Messages`, `Manage Channels`, and `View Audit Log`).
* **Human-in-the-Loop Safeguard:** All automated actions are posted to a private security log channel equipped with persistent **`[ 👁️ Reviewed ]`** and **`[ 🔓 Revert Punishment ]`** buttons, allowing administrators to review and pardon actions at any time without database dependencies.
* **Acceptable Use & Liability:** Standard limitations of liability and disclaimers aligned with Discord Developer Terms of Service.

---

## 🔒 2. Privacy Policy Summary

* **The Zero-Retention Principle:** Werrberus operates on a 100% stateless architecture. No usernames, messages, avatar graphics, or conversation histories are ever logged or written to disk.
* **Volatile Memory (RAM Only):** Real-time mathematical inspection of Discord Snowflake IDs (GAP-0331 Z/9Z ring invariants), message regex patterns, and Shannon entropy (H > 4.70 bits/character). Once evaluated, raw event data is discarded immediately from memory.
* **Persistent Disk Storage:** The **only** file written to disk is `guild_settings.json`, containing numeric server IDs and administrator-configured threshold numbers.
* **Privileged Gateway Intents:** Full transparency for `Server Members Intent` (join-burst monitoring) and `Message Content Intent` (real-time phishing/token grabber mitigation).

---

## 📬 3. Contact & Developer Support

For security disclosures, verification inquiries, or technical support:
* **Discord:** Available via Discord Developer Portal
* **Documentation Portal:** [https://lexovian.github.io/Werrberus-ToS-Privacy/](https://lexovian.github.io/Werrberus-ToS-Privacy/)

