# 🤖 n8nDaddy Agent

> Your conversational AI assistant for creating n8n workflow agents through simple chat interactions

n8nDaddy is an intelligent agent that generates n8n workflow JSON scripts and detailed instructions based on your requirements, gathered through natural conversation via Telegram. No more complex workflow building - just describe what you need, and n8nDaddy delivers ready-to-use n8n agents directly to your inbox.
<img width="90%" height="90%" alt="image" src="https://github.com/user-attachments/assets/0a3465ec-77c2-412f-8655-7528eb40c5cd" />

## ✨ Features

- **Conversational Workflow Creation**: Describe your automation needs in plain language via Telegram
- **Intelligent Agent Generation**: Powered by Gemini 3.5 Turbo LLM for sophisticated understanding and generation
- **Complete Package Delivery**: Receive both JSON workflow files and comprehensive setup instructions via email
- **Zero Technical Barrier**: No need to understand n8n's node structure - just explain what you want to automate
- **Production-Ready Scripts**: Generated workflows are ready to import and use in your n8n instance

## 🚀 How It Works

1. **Chat with n8nDaddy** on Telegram and describe your automation requirements
2. **AI Processing** - Gemini 3.5 Turbo analyzes your needs and designs the optimal workflow
3. **Receive Your Agent** - Get the n8n JSON script and detailed instructions delivered to your email
4. **Import & Deploy** - Simply import the JSON into your n8n instance and start automating

## 🛠️ Technology Stack

- **LLM Model**: Gemini 3.5 Turbo
- **Input Interface**: Telegram Bot API
- **Delivery Method**: Email
- **Output Format**: n8n-compatible JSON workflows + Markdown instructions

## 📋 Prerequisites

- An active Telegram account
- Access to an n8n instance (self-hosted or cloud)
- Email address for receiving generated workflows

## 🎯 Use Cases

- **API Integration Workflows**: Connect multiple services without code
- **Data Processing Pipelines**: Transform and route data between systems
- **Notification Systems**: Set up smart alerts and notifications
- **Business Process Automation**: Automate repetitive business tasks
- **Custom Webhook Handlers**: Build endpoints that process incoming data

## 🔮 Future Roadmap

### Slack Integration (Coming Soon)
- **Workspace Integration**: Create n8n agents directly from Slack conversations
- **Team Collaboration**: Share and refine workflows with your team in channels
- **Instant Deployment**: Generate and deploy workflows without leaving Slack
- **Slash Commands**: Quick workflow generation with simple commands

## 🚦 Getting Started

### Step 1: Connect to n8nDaddy Bot
```
Search for "yourbotname" on Telegram and start a conversation
```

### Step 2: Describe Your Workflow
```
"I need a workflow that monitors my Gmail for attachments and saves them to Google Drive"
```

### Step 3: Receive Your Agent
Check your email for:
- `workflow.json` - Ready-to-import n8n workflow
- `instructions` - Setup guide and configuration details
<img width="75%" height="75%" alt="image" src="https://github.com/user-attachments/assets/262d7ea1-374a-4ccd-a0c9-23bc45ca0373" />
<img width="75%" height="75%" alt="image" src="https://github.com/user-attachments/assets/f2453271-7928-4425-aef3-478e7a6c5419" />



### Step 4: Import to n8n
1. Open your n8n instance
2. Click "Import from File"
3. Upload the received JSON file
4. Follow the setup instructions to configure credentials

## 📖 Example Conversations

**User**: "Create a workflow that posts new Reddit posts from r/technology to my Discord channel"

**n8nDaddy**: "I'll create an n8n workflow that monitors r/technology and posts updates to Discord. What's your preferred check interval - every 5 minutes, hourly, or custom?"

**User**: "Every hour would be perfect"

**n8nDaddy**: "Perfect! I'll generate a workflow with hourly checks. You'll receive the JSON and setup instructions via email shortly."

## 🤝 Contributing

Contributions are welcome! Whether it's:
- Bug reports
- Feature requests
- Documentation improvements
- Code contributions

Please feel free to open an issue or submit a pull request.


## 🙏 Acknowledgments

- Built with [n8n](https://n8n.io/) - The workflow automation platform
- Powered by [Google Gemini](https://deepmind.google/technologies/gemini/) - Advanced AI capabilities
- Interface via [Telegram Bot API](https://core.telegram.org/bots/api)

---

**Made with ❤️ for the automation community**

*Simplifying workflow creation, one conversation at a time.*
