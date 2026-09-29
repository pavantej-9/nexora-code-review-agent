Nexora – AI Code Review Agent

Nexora is an intelligent code review assistant designed to analyze code for security vulnerabilities, performance bottlenecks, and bugs while respecting your persistent development environment settings.

Built For HackwithHyderabad 3.0
This project integrates Hindsight memory to allow the AI agent to remember project environments, configuration details, and past feedback over time.

Tech Stack & Architecture
* Frontend:HTML5, CSS3, Modern JavaScript (Single-file architecture)
* Backend / Storage: Firebase (Auth & Firestore) / Local Storage fallback
* Memory Layer:Hindsight (for persistent agent memory and contextual continuity)

 Features
* Environment-Aware Reviews: Stores your specific IDE, language version, frameworks, and database preferences so the agent never guesses your tech stack.
* Targeted Analysis: Switch between Full Review, Security, Performance, and Bug detection modes.
* Persistent Reports: Automatically saves past code reviews and findings for easy reference.

How to Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/nexora-code-review-agent.git](https://github.com/your-pavantej-9/nexora-code-review-agent.git)
