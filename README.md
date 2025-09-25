# JAI — Discord AI Bot

> **JAI** is a lightweight, multi-purpose Discord bot that brings Google Gemini-powered AI chat, role automation, premium music playback, and server insights to your community—all from a single slash-command interface.

---

## ✨ Key Features
- **AI Chat** – Uses Google Gemini free models to answer questions, brainstorm ideas, and generate creative content in designated channels.  
- **Configurable Memory** – Per-channel toggle to store context for deeper conversations or switch to stateless mode for maximum privacy.  
- **Flexible Tokens & Character Limits** – Fine-tune response length to suit your channel’s needs.  
- **Role Automation** – Automatically assign roles to newcomers and streamline onboarding.  
- **Hi-Fi Music** – Crystal-clear audio, advanced queuing, and playlist support.  
- **Logging & Analytics** – Track moderation events and view real-time engagement metrics.

---

## 🚀 Quick Start
1. **Invite JAI** to your server using this link:  
   <https://discord.com/oauth2/authorize?client_id=1411204826699796491>  
   *(You need the **Manage Server** permission to add bots.)*[38]  
2. Grant the recommended permissions when prompted.  
3. Type `/configure` in the channel where you want JAI to operate.

---

## ⚙️ Configuration (`/configure`)
| Option            | Description                                                                   |
| ----------------- | ----------------------------------------------------------------------------- |
| **channel**       | Select which channel JAI will monitor and reply in.                           |
| **memory**        | `on` = continuous context, `off` = stateless responses.                       |
| **max_tokens**    | Upper bound on the number of Gemini tokens JAI may use per reply.             |
| **max_chars**     | Hard cap on visible characters in a single response.                          |
| **system_prompt** | Custom system instructions for JAI in this channel (tone, persona, etc.).     |

Changes take effect immediately and can be updated any time by rerunning `/configure`.

---

## 🛡️ Recommended Permissions
- **Read / Send Messages** – Basic interaction  
- **Manage Messages** – Allows JAI to tidy up its own errors or system notices  
- **Manage Roles** – Enables automatic role assignment  
- **Embed Links & Attach Files** – Permits rich AI and music embeds  

Grant only what your server needs; JAI will gracefully degrade if optional scopes are missing.

---

## 📊 Privacy & Data
JAI stores only minimal data required to operate (user and guild IDs, optional memory snippets) and purges most logs after 30 days. Voice/video content is never recorded. See `PRIVACY.md` for full details.

---

## 🆘 Support
Open a ticket in the JadaDev Support Server or email **support@jadadev.com**. We’re happy to help!

---

## 📄 License
JAI is © 2025 JadaDev. All rights reserved. Use of this bot is governed by the included **Terms of Service** and **Privacy Policy**.
