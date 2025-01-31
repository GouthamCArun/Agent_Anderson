# Agent_Anderson

**Agent_Anderson** is a powerful automation tool designed to help you interact with LinkedIn and perform executive search tasks efficiently. It utilizes OpenAI for parsing and generating text, Swarm for agent orchestration, LinkedIn API for profile searches, and Selenium for web automation. The application seamlessly automates the process of sending personalized LinkedIn messages to executives.

## Features

- **Executive Finder**: Finds the name of executives (e.g., CEO, CTO) based on company and position using a custom agent.
- **LinkedIn Profile Finder**: Searches for LinkedIn profiles of executives based on their name.
- **Message Generator**: Creates personalized LinkedIn messages based on the extracted details.
- **LinkedIn Messenger**: Sends the generated message to the LinkedIn profile using the LinkedIn API.
- **AI-Powered Input Parsing**: Extracts company name, position, and message from user input using OpenAI's GPT-4.

## Technologies Used

- **Swarm**: For orchestrating different agents with distinct roles and tasks.
- **OpenAI GPT-4**: For parsing user input and generating messages.
- **LinkedIn API**: For finding LinkedIn profiles and sending messages.
- **Selenium**: For browser automation (used for LinkedIn profile search and message sending).
- **Python**: The core language for the application.
- **Dotenv**: For managing environment variables securely.

## Installation

Follow these steps to set up **Agent_Anderson** on your local machine:

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/Agent_Anderson.git
