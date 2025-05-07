# Microsoft Copilot AI Coaching Assistant

## 🔍 Overview
This project implements a Microsoft Copilot-based AI Coaching Assistant that engages users in dynamic, topic-based coaching conversations using Azure OpenAI and Power Platform.

The assistant is deployed using GitHub Actions and includes a Power Automate flow and a Copilot agent (bot), both integrated into a Power Platform solution.

---

## ⚙️ Tech Stack

| Component              | Technology                         |
|------------------------|-------------------------------------|
| Bot Platform           | Microsoft Copilot Studio            |
| Backend Flow Logic     | Power Automate                      |
| AI Model               | Azure OpenAI (GPT-4 / GPT-3.5)      |
| Knowledge Base         | (Optional) SharePoint / Excel       |
| CI/CD                  | GitHub Actions + Power Platform CLI |
| Source Control         | GitHub                              |

---

## How It Works

1. User starts a coaching conversation in Microsoft Teams or web chat
2. Copilot collects the topic and sends it to Power Automate
3. Power Automate calls Azure OpenAI with a coaching prompt
4. The assistant responds with smart, guided coaching questions

Developed by **Lubabalo Lalapi**
