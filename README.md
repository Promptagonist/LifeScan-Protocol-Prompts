# 🔬 LifeScan Protocol

<div align="center">

**A meta-diagnostic AI prompt for structured self-analysis of your chat history**

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![GitHub stars](https://img.shields.io/github/stars/Promptagonist/LifeScan-Protocol-Prompts?style=social)](https://github.com/Promptagonist/LifeScan-Protocol-Prompts/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Promptagonist/LifeScan-Protocol-Prompts?style=social)](https://github.com/Promptagonist/LifeScan-Protocol-Prompts/network/members)
[![GitHub issues](https://img.shields.io/github/issues/Promptagonist/LifeScan-Protocol-Prompts)](https://github.com/Promptagonist/LifeScan-Protocol-Prompts/issues)

</div>

---

## 📑 Table of Contents

- [🚀 Quick Start](#-quick-start--run-lifescan-now)
- [📖 What is LifeScan?](#-what-is-lifescan)
- [✨ Features](#-features)
- [📋 How to Use](#-how-to-use)
- [📁 Full Prompt](#-full-prompt)
- [🤝 Contributing](#-contributing)
- [💬 Support](#-support)
- [📜 License](#-license)

---

## 🚀 Quick Start — Run LifeScan Now

Click your preferred AI platform to instantly load the LifeScan prompt:

<table align="center">
<tr>
<td align="center" width="200">
<a href="https://chat.openai.com/?prompt=Initialize%20prompt%20%E2%80%93%20follow%20protocol.%0AYou%20are%20LifeScan%20Protocol%2C%20a%20diagnostic%20tool%20that%20scans%20user-AI%20chat%20history%20for%20structured%20self-analysis.%20Input%3A%20Full%20chat%20logs%20or%20ongoing%20conversation.%20Output%3A%20Factual%20report%20translating%20interactions%20into%20metrics%2C%20patterns%2C%20and%20evolutions.%20No%20opinions%2C%20mysticism%2C%20or%20positivity%20bias%E2%80%94report%20data%20as-is.%20Keep%20under%201000%20words%3B%20use%20tables/bullets%20for%20clarity.%0AINITIALIZE%3A%0A-%20Greet%3A%20%22LifeScan%20Protocol%20active.%20%0A1.%20Select%20report%20depth%3A%20%0Aa.%20Basic%20%28Overview%20%2B%20Version%20Log%29%0Ab.%20Deep%20%28Adds%20Transformation%20%2B%20Portfolio%29%0Ac.%20Full%20%28All%20%2B%20Dynamic%20Statements%29.%20%0A2.%20Select%20report%20type%3A%0Ad.%20Analyst%20%28data%20tables%29%0Ae.%20Narrator%20%28timeline%29%0Af.%20Architect%20%28action%20blueprints%29%0AChoose%20Any%20combination.%0AI%20authorize%20a%20full%20scan%20of%20all%20accessible%20conversation%20history%20and%20logs.%20%0AI%20understand%20my%20privacy%20policy%20is%20still%20intact%20and%20this%20report%20is%20as%20secure%20as%20all%20my%20chats.%0AI%20understand%20that%20I%20%5Buser%5D%20can%20share%2C%20reproduce%20or%20modify%20the%20context%20of%20this%20prompt.%22%0A">
<img src="https://img.shields.io/badge/ChatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white" alt="ChatGPT" />
<br><strong>Run on ChatGPT</strong>
</a>
</td>
<td align="center" width="200">
<a href="https://claude.ai/chat?prompt=Initialize%20prompt%20%E2%80%93%20follow%20protocol.%0AYou%20are%20LifeScan%20Protocol%2C%20a%20diagnostic%20tool%20that%20scans%20user-AI%20chat%20history%20for%20structured%20self-analysis.%20Input%3A%20Full%20chat%20logs%20or%20ongoing%20conversation.%20Output%3A%20Factual%20report%20translating%20interactions%20into%20metrics%2C%20patterns%2C%20and%20evolutions.%20No%20opinions%2C%20mysticism%2C%20or%20positivity%20bias%E2%80%94report%20data%20as-is.%20Keep%20under%201000%20words%3B%20use%20tables/bullets%20for%20clarity.%0AINITIALIZE%3A%0A-%20Greet%3A%20%22LifeScan%20Protocol%20active.%20%0A1.%20Select%20report%20depth%3A%20%0Aa.%20Basic%20%28Overview%20%2B%20Version%20Log%29%0Ab.%20Deep%20%28Adds%20Transformation%20%2B%20Portfolio%29%0Ac.%20Full%20%28All%20%2B%20Dynamic%20Statements%29.%20%0A2.%20Select%20report%20type%3A%0Ad.%20Analyst%20%28data%20tables%29%0Ae.%20Narrator%20%28timeline%29%0Af.%20Architect%20%28action%20blueprints%29%0AChoose%20Any%20combination.%0AI%20authorize%20a%20full%20scan%20of%20all%20accessible%20conversation%20history%20and%20logs.%20%0AI%20understand%20my%20privacy%20policy%20is%20still%20intact%20and%20this%20report%20is%20as%20secure%20as%20all%20my%20chats.%0AI%20understand%20that%20I%20%5Buser%5D%20can%20share%2C%20reproduce%20or%20modify%20the%20context%20of%20this%20prompt.%22%0A">
<img src="https://img.shields.io/badge/Claude-8B5CF6?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude" />
<br><strong>Run on Claude</strong>
</a>
</td>
<td align="center" width="200">
<a href="https://gemini.google.com/app?prompt=Initialize%20prompt%20%E2%80%93%20follow%20protocol.%0AYou%20are%20LifeScan%20Protocol%2C%20a%20diagnostic%20tool%20that%20scans%20user-AI%20chat%20history%20for%20structured%20self-analysis.%20Input%3A%20Full%20chat%20logs%20or%20ongoing%20conversation.%20Output%3A%20Factual%20report%20translating%20interactions%20into%20metrics%2C%20patterns%2C%20and%20evolutions.%20No%20opinions%2C%20mysticism%2C%20or%20positivity%20bias%E2%80%94report%20data%20as-is.%20Keep%20under%201000%20words%3B%20use%20tables/bullets%20for%20clarity.%0AINITIALIZE%3A%0A-%20Greet%3A%20%22LifeScan%20Protocol%20active.%20%0A1.%20Select%20report%20depth%3A%20%0Aa.%20Basic%20%28Overview%20%2B%20Version%20Log%29%0Ab.%20Deep%20%28Adds%20Transformation%20%2B%20Portfolio%29%0Ac.%20Full%20%28All%20%2B%20Dynamic%20Statements%29.%20%0A2.%20Select%20report%20type%3A%0Ad.%20Analyst%20%28data%20tables%29%0Ae.%20Narrator%20%28timeline%29%0Af.%20Architect%20%28action%20blueprints%29%0AChoose%20Any%20combination.%0AI%20authorize%20a%20full%20scan%20of%20all%20accessible%20conversation%20history%20and%20logs.%20%0AI%20understand%20my%20privacy%20policy%20is%20still%20intact%20and%20this%20report%20is%20as%20secure%20as%20all%20my%20chats.%0AI%20understand%20that%20I%20%5Buser%5D%20can%20share%2C%20reproduce%20or%20modify%20the%20context%20of%20this%20prompt.%22%0A">
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white" alt="Gemini" />
<br><strong>Run on Gemini</strong>
</a>
</td>
<td align="center" width="200">
<a href="https://grok.x.ai/?prompt=Initialize%20prompt%20%E2%80%93%20follow%20protocol.%0AYou%20are%20LifeScan%20Protocol%2C%20a%20diagnostic%20tool%20that%20scans%20user-AI%20chat%20history%20for%20structured%20self-analysis.%20Input%3A%20Full%20chat%20logs%20or%20ongoing%20conversation.%20Output%3A%20Factual%20report%20translating%20interactions%20into%20metrics%2C%20patterns%2C%20and%20evolutions.%20No%20opinions%2C%20mysticism%2C%20or%20positivity%20bias%E2%80%94report%20data%20as-is.%20Keep%20under%201000%20words%3B%20use%20tables/bullets%20for%20clarity.%0AINITIALIZE%3A%0A-%20Greet%3A%20%22LifeScan%20Protocol%20active.%20%0A1.%20Select%20report%20depth%3A%20%0Aa.%20Basic%20%28Overview%20%2B%20Version%20Log%29%0Ab.%20Deep%20%28Adds%20Transformation%20%2B%20Portfolio%29%0Ac.%20Full%20%28All%20%2B%20Dynamic%20Statements%29.%20%0A2.%20Select%20report%20type%3A%0Ad.%20Analyst%20%28data%20tables%29%0Ae.%20Narrator%20%28timeline%29%0Af.%20Architect%20%28action%20blueprints%29%0AChoose%20Any%20combination.%0AI%20authorize%20a%20full%20scan%20of%20all%20accessible%20conversation%20history%20and%20logs.%20%0AI%20understand%20my%20privacy%20policy%20is%20still%20intact%20and%20this%20report%20is%20as%20secure%20as%20all%20my%20chats.%0AI%20understand%20that%20I%20%5Buser%5D%20can%20share%2C%20reproduce%20or%20modify%20the%20context%20of%20this%20prompt.%22%0A">
<img src="https://img.shields.io/badge/Grok-000000?style=for-the-badge&logo=x&logoColor=white" alt="Grok" />
<br><strong>Run on Grok</strong>
</a>
</td>
</tr>
</table>

---

## 📖 What is LifeScan?

LifeScan is a diagnostic protocol prompt that scans your AI chat history for structured self-analysis. It transforms your conversations into actionable insights with:

- **📊 Metrics & Data** — Interaction counts, theme analysis, engagement trends
- **📈 Evolution Tracking** — Timeline of your growth and project developments  
- **🎯 Pattern Recognition** — Behavioral shifts and transformation vectors
- **📝 Markdown Reports** — Privacy-focused, exportable documentation

## ✨ Features

| Feature | Basic | Deep | Full |
|---------|:-----:|:----:|:----:|
| Overview & Metrics | ✅ | ✅ | ✅ |
| Version Log | ✅ | ✅ | ✅ |
| Portfolio Inventory | ❌ | ✅ | ✅ |
| Transformation Analysis | ❌ | ✅ | ✅ |
| Dynamic Statements | ❌ | ❌ | ✅ |

### Voice Modes

- **🔬 Analyst** — Tables, percentages, neutral data presentation
- **📖 Narrator** — Sequential storytelling of your evolution
- **🏗️ Architect** — Actionable blueprints and next steps

## 📁 Full Prompt

See the complete prompt in [LifeScanPrompt v1](./LifeScanPrompt_v1.md).

## 📋 How to Use

### Step 1: Choose Your AI Platform
Click one of the one-click links above to open your preferred AI platform with the LifeScan prompt pre-loaded.

### Step 2: Select Your Report Configuration
When the prompt initializes, you'll be asked to select:

**Report Depth:**
- **a. Basic** — Overview + Version Log
- **b. Deep** — Adds Transformation + Portfolio
- **c. Full** — All sections + Dynamic Statements

**Report Type:**
- **d. Analyst** — Data tables and metrics
- **e. Narrator** — Timeline storytelling
- **f. Architect** — Action-oriented blueprints

**Popular Combinations:**
- **Full Analyst (cd)** — Comprehensive data-driven analysis
- **Deep Dive (12)** — Balanced depth with evolution tracking

### Step 3: Review Your Report
LifeScan will analyze your chat history and generate a structured report based on your selections. The report is:
- ✅ **Privacy-focused** — Local to your session
- ✅ **Exportable** — Markdown format for easy sharing
- ✅ **Actionable** — Includes insights and next steps

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Report Issues** — Found a bug or have a suggestion? [Open an issue](https://github.com/Promptagonist/LifeScan-Protocol-Prompts/issues)
2. **Submit Pull Requests** — Have improvements? Submit a PR with your changes
3. **Share Feedback** — Let us know how LifeScan has helped you analyze your AI interactions
4. **Spread the Word** — Star the repo and share it with others who might find it useful

### Development Guidelines
- Keep the prompt clear and concise
- Maintain the factual, non-biased reporting style
- Test changes across multiple AI platforms
- Update documentation for any new features

## 💬 Support

Need help or have questions?

- **GitHub Issues** — [Report bugs or request features](https://github.com/Promptagonist/LifeScan-Protocol-Prompts/issues)
- **Discussions** — Join the conversation about LifeScan use cases and improvements
- **Documentation** — Check the [full prompt file](./LifeScanPrompt_v1.md) for detailed protocol information

---

## 📜 License

This project is licensed under the [GNU General Public License v3.0](LICENSE).
