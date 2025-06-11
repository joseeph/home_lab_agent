# home_lab_agent

A visual and interactive platform for deploying and managing AI agents locally. This project aims to provide a private, secure, and cost-effective solution for running AI agents on your local machine.

## Features

- 🎮 Game-like visual interface for agent management
- 🔒 Local deployment ensuring data privacy
- 💻 Cross-platform support
- 🤖 Multiple agent types support
- 📊 Real-time agent status monitoring
- 💬 Interactive chat interface
- 🛠️ Extensible architecture

## Tech Stack

- Frontend: React + PixiJS
- Backend: Python FastAPI
- AI: Local LLM (0.5-8B parameters)
- Deployment: CPU ARM architecture support

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- Python 3.8+
- Local LLM model

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/local-ai-agent-lab.git
cd local-ai-agent-lab
```

2. Install frontend dependencies:
```bash
npm install
```

3. Install backend dependencies:
```bash
pip install -r requirements.txt
```

4. Start the development servers:
```bash
# Start frontend
npm run dev

# Start backend
python main.py
```

## Project Structure

```
local-ai-agent-lab/
├── src/
│   ├── Agent/           # Agent-related components
│   ├── LabEnvironment/  # Main environment components
│   └── systemSetting/   # System configurations
├── main.py             # FastAPI backend
└── requirements.txt    # Python dependencies
```

## Contributing

We welcome contributions! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to all contributors and the open-source community
- Special thanks to the PixiJS team for the amazing graphics library

