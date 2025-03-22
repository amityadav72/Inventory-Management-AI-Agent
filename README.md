# Inventory Management AI Agent

## Overview
This project is an AI-powered Inventory Management Agent built using **n8n** and the **OpenAI API**. The agent streamlines inventory operations by providing intelligent insights, automating workflows, and enabling a chatbot for user interaction.

## Features
- AI-driven inventory tracking and insights
- Automated inventory workflows using **n8n**
- Chatbot for inventory queries
- Integration with external data sources
- OpenAI-powered natural language processing

## Tech Stack
- **n8n** (Workflow Automation)
- **OpenAI API** (AI-based responses)
- **Database** (Inventory Dataset)

## Dataset
The project uses an inventory dataset containing product details, stock levels, and transaction history. 

[Download Dataset](https://docs.google.com/spreadsheets/d/1JmewmWrynW6dnfrWXCbcR1u9uTx0joukYqmz4wjzpe0/edit?usp=sharing) 

## AI Agent Chatbot
The AI chatbot allows users to query inventory details, check stock levels, and receive automated responses.

[Try the Chatbot](https://amityadav72.app.n8n.cloud/webhook/fdefbe82-be2e-49d8-9899-d22d051f8e6b/chat) 

## Workflow
Below is the n8n workflow used to automate the AI-driven inventory management process.
![Screenshot 2025-03-22 100305](https://github.com/user-attachments/assets/26ad4dd4-6a0f-4f00-b0b3-cca38cf255dd)



## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/amityadav72/Inventory-Management-AI-Agent
   ```
2. Install dependencies:
   ```bash
   cd inventory-ai-agent
   npm install
   ```
3. Configure API keys:
   - Add your **OpenAI API key** in the environment variables.
   - Set up **n8n** with the workflow provided.
4. Run the n8n server:
   ```bash
   npx n8n start
   ```
5. Access the chatbot and inventory dashboard.

## Usage
- Query inventory details via the chatbot.
- Automate stock alerts and reordering.
- Generate AI-based insights on inventory trends.

## License
This project is licensed under the MIT License.

## Contact
For queries or contributions, feel free to reach out!

📧 **Email:** your.email@example.com

🌐 **Website:** [your-website.com](#)
