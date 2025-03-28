<div align="center">
<img src="https://raw.githubusercontent.com/bivteam/BBrainAI/main/misc/logo.png" width="350px">
<h2>BrainyAI: a free and open-source browser sidebar plugin that offers a cost-free alternative to products like Sider, Monica, and Merlin. </h2>

[![GitHub license](https://img.shields.io/badge/license-GPL%203.0-blue)](https://github.com/bivteam/BBrainAI/blob/main/LICENSE)

English ｜ [简体中文](README_ZH-CN.md)
<p>
  <a style="font-size: 28px" href="https://chromewebstore.google.com/detail/BrainyAI/jmcllpdchgacpnpgechgncndkfdogdah?utm_source=github&utm_medium=pr&utm_campaign=0614">
  ⏬⏬ Download BrainyAI from Chrome Web Store
</a>
</p>
</div>

<br>

## Introduction

🧠**BrainyAI** is a completely free Chrome browser extension. Users only need to log in once to various AI websites, and then they can bring the capabilities of large models into their daily work habits and scenarios using BrainyAI. With a convenient sidebar, **BrainyAI** offers features such as AI chat aggregation, AI search, AI reading, and enhanced AI web browsing.

When using **BrainyAI**, users don't need to leave their current web page. They can leverage advanced large language models like **GPT-4**, **GPT-4o**, **Claude**, **Gemini**, **Moonshot**, and **LLaMA3** for tasks such as conversation, search, summarizing web pages, and reading files—all completely free. BrainyAI is a free alternative to similar products like **[Sider AI](https://sider.ai)**, **[Monica](https://monica.im)**, **[Merlin](https://www.getmerlin.in)**, and **[MaxAI](https:///www.maxai.me)**. 🌐


<br>


## Key features

- 🤖 Group Chat with Top-Tier AIs at Once, for Free
- 🔍 Multiple Answers from Top-Tier AI Search Engines, for Free
- 📚 Top-Tier AIs to assist with Web/YouTube summaries, for Free
- 💬 Engage in conversations with Top-Tier AIs across documents, for Free


<br>


| Features | Screenshot                                                                                         | 
| -------- |----------------------------------------------------------------------------------------------------| 
| Group Chat     | ![20240614-190440](https://raw.githubusercontent.com/bivteam/BBrainAI/main/misc/group_chat.gif)   | 
| Multiple Answers from Top-Tier AI Search Engines  | ![20240614-191334](https://raw.githubusercontent.com/bivteam/BBrainAI/main/misc/multi_answer.gif) | 
| Web/YouTube summaries     | ![20240614-191334](https://raw.githubusercontent.com/bivteam/BBrainAI/main/misc/summaries.gif)                                       | 





<br>
<br>


## Supported LLMs



| LLMs | Provider | status |
| -------- | -------- | -------- |
| Gpt3.5     | chatgpt.com     | Supported     |
| Gpt4     | chatgpt.com     | Supported     |
| Gpt4o     | chatgpt.com     | Supported     |
| Gpt4     | copilot.microsoft.com     | Supported  |
| Gemini     | gemini.google.com     | Supported     |
| Moonshot     | kimi.moonshot.cn     | Supported     |
| LLama 3    | perplexity.ai     | Supported     |
| Claude 3 haiku     | perplexity.ai     | Supported     |
| Gemma-7b    | perplexity.ai     | Supported     |
| llava-v1.6    | perplexity.ai     | Supported     |
| Mistral-8×22b| perplexity.ai     | Supported     |
| Claude 3     | claude.ai     | Soon     |


More is coming.

<br>

## Privacy

At BrainyAI, we prioritize user privacy and take every measure to safeguard your personal information. We never upload or share any sensitive data, including but not limited to:

- Local cookie information
- Chat session data
- Account information
- Etc.

All chat history, settings, and login data are securely stored locally on your device. We never collect or access this information from our servers.

To enhance your BrainyAI experience, we gather anonymous usage data using GA4 that helps us understand user preferences and optimize our product. This data includes:

- Frequency and duration of AI bot prompts (without capturing prompt content)
- Response length and usage patterns (without capturing response content)

This anonymous usage data is essential for continuous improvement and does not reveal any personally identifiable information.

<br>
<br>


---

## For developers


### Getting started

First, install the dependencies:

```bash
npm install pnpm -g