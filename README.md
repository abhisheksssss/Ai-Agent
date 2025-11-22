Here is a clean, professional **README.md** for your AI Agent tool 👇
(Everything properly structured and well-described)

---

# 🧠 AI Agent MCP Server

A powerful AI Agent built using **Model Context Protocol (MCP)** that enables real-time tool execution, intelligent prompts, and automation through a server-based AI tool infrastructure.

This project exposes multiple AI-powered tools such as:

* Real-time information retrieval
* Code reviewing
* BMI calculation
* Social posting (e.g., X/Twitter)
* Team greeting automation
* Basic arithmetic operations

It communicates using **SSE (Server-Sent Events)** and provides multi-session support.

---

## 🚀 Features

| Tool / Prompt       | Description                                    |
| ------------------- | ---------------------------------------------- |
| `addTwoNumbers`     | Returns the sum of two numbers                 |
| `createPost`        | Creates a post on X (Twitter)                  |
| `calculate-Bmi`     | Calculates Body Mass Index                     |
| `fetchRealTimeData` | Fetches live information using Tavily API      |
| `review-code`       | Reviews programming code and provides feedback |
| `team-greeting`     | Generates smart greetings with auto-completion |

Additionally:

* Supports multiple concurrent MCP connections
* Built with **Express.js** backend + MCP server
* SSE-based event transport system

---

## 🛠 Tech Stack

* **Node.js** + **Express.js**
* **Model Context Protocol**
* **SSE Transport**
* **Zod** for schema validation
* **Tavily API** for real-time information

-
