# AgentRoundTable

A sophisticated web-based platform for orchestrating conversations between multiple AI agents around a virtual roundtable. Create, customize, and manage dynamic multi-agent discussions with branching conversations, real-time interactions, and advanced AI features.

## 🚀 Features

### Core Functionality
- **Multi-Agent Conversations**: Create and manage up to 20 AI agents with unique personalities
- **Dynamic Agent Selection**: Choose which agent starts the conversation
- **Branching Conversations**: Explore different discussion paths with conversation branching
- **Real-time Streaming**: Watch agents think and respond in real-time
- **Conversation History**: Full message history with context management

### Agent Management
- **Custom Agent Creation**: Define unique personas, models, and parameters for each agent
- **Agent Templates**: Quick-start templates for common agent types
- **Model Selection**: Support for multiple AI models per agent
- **Temperature & Token Control**: Fine-tune agent responses
- **Persona Customization**: Detailed personality and role definitions

### Advanced Features
- **Auto Mode**: Automated multi-turn conversations with configurable limits
- **Context Management**: Smart context trimming and message history optimization
- **Export Capabilities**: Save conversations in multiple formats
- **Dark/Light Theme**: Customizable UI themes
- **Local Storage**: Persistent settings and conversation state

### AI Integration
- **OpenAI API Integration**: Compatible with GPT models
- **Streaming Responses**: Real-time response generation
- **Model Flexibility**: Support for different models per agent
- **Rate Limiting**: Built-in API rate limiting protection

## 🛠️ Setup

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- OpenAI API key or compatible AI service
- Local web server (optional, for CORS handling)

### Installation

1. **Clone or Download**
   ```bash
   git clone https://github.com/yourusername/AgentRoundTable.git
   cd AgentRoundTable
   ```

2. **Open the Application**
   - Open `agenticChat5Opus.html` directly in your browser, or
   - Serve via a local web server:
     ```bash
     python -m http.server 8000
     # Then visit http://localhost:8000
     ```

3. **Configure API**
   - Click the settings tab (⚙️)
   - Enter your OpenAI API key
   - Set your preferred API endpoint (if using a custom service)
   - Click "Connect" to verify the connection

## 📖 Usage

### Quick Start

1. **Setup Agents**
   - Navigate to the "Agents" tab
   - Use default agents or create custom ones
   - Define personas, select models, and adjust parameters

2. **Start a Conversation**
   - Enter an initial prompt
   - Select which agent should start
   - Click "Start Conversation"

3. **Manage the Discussion**
   - Use manual mode to control agent responses
   - Enable auto mode for autonomous conversations
   - Create branches to explore different discussion paths

### Agent Configuration

**Creating Custom Agents:**
```
Name: Research Assistant
Persona: You are a thorough research assistant who provides detailed, well-sourced information. You always cite sources and present balanced viewpoints.
Model: gpt-4
Temperature: 0.3
Max Tokens: 1500
```

**Agent Templates Available:**
- Researcher: Fact-focused, analytical
- Creative: Imaginative, artistic
- Critic: Analytical, questioning
- Moderator: Balanced, facilitative
- Specialist: Domain-specific expertise

### Advanced Features

**Branching Conversations:**
- Click "Branch" during any conversation
- Explore alternative discussion paths
- Switch between branches using the branch selector

**Auto Mode:**
- Set maximum turns (1-50)
- Configure delay between responses
- Watch agents engage in autonomous discussion

**Context Management:**
- Configure maximum context messages (5-100)
- Enable smart context trimming
- Optimize for token efficiency

## 🔧 Configuration

### Settings Panel

**API Configuration:**
- **API Key**: Your OpenAI or compatible API key
- **API Endpoint**: Custom API endpoint (default: OpenAI)
- **Default Model**: Fallback model for AI features

**Conversation Settings:**
- **Max Context Messages**: Number of previous messages to include
- **Smart Context Trimming**: Intelligent message history optimization
- **Auto Mode Limits**: Maximum turns and response delays

**AI Features:**
- **Agent Suggestions**: AI-powered agent recommendations
- **Smart Responses**: Enhanced response generation
- **Context Awareness**: Improved conversation understanding

### Export Options

**Available Formats:**
- **Plain Text**: Simple conversation transcript
- **Markdown**: Formatted with headers and styling
- **JSON**: Structured data with metadata
- **HTML**: Rich formatted output

## 🎨 Customization

### Themes
- **Light Theme**: Clean, modern interface
- **Dark Theme**: Easy on the eyes for extended use
- **Automatic Detection**: Follows system theme preferences

### Agent Personalization
- **Unique Colors**: Automatic color assignment per agent
- **Avatar Initials**: Generated from agent names
- **Custom Personas**: Detailed role and personality definitions

## 🔒 Security & Privacy

- **Local Storage**: All data stored locally in your browser
- **API Security**: API keys encrypted in local storage
- **No Server Storage**: No conversation data sent to external servers
- **CORS Handling**: Secure API communication

## 🚀 Performance

### Optimization Features
- **Streaming Responses**: Real-time message generation
- **Context Trimming**: Efficient token usage
- **Rate Limiting**: Prevents API overuse
- **Lazy Loading**: Optimized UI rendering

### Browser Compatibility
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## 📋 Roadmap

### Planned Features
- [ ] Plugin system for custom integrations
- [ ] Advanced conversation analytics
- [ ] Team collaboration features
- [ ] Cloud synchronization options
- [ ] Mobile-responsive design
- [ ] Additional AI provider support

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.

### Development Setup
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 🎯 The AgentRoundTable Concept

AgentRoundTable embodies the concept of a virtual roundtable where AI agents gather to engage in meaningful dialogue. Just like the legendary Round Table where knights sat as equals, our platform ensures every agent has an equal voice in the conversation, fostering collaboration and diverse perspectives.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- OpenAI for providing the API infrastructure
- The open-source community for inspiration and tools
- Contributors and users for feedback and improvements

## 📞 Support

For support, feature requests, or bug reports:
- Open an issue on GitHub
- Check the documentation
- Review existing discussions

---

**AgentRoundTable** - Where AI minds meet to collaborate and converse. 🤖✨