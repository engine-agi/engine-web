# Engine Web

[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.2.0-blue.svg)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.2.0-blue.svg)](https://www.typescriptlang.org/)

**Engine Framework Web Dashboard** - Modern web interface for the AI Agent Orchestration System.

## 🚀 Features

- **Real-time Dashboard**: Live monitoring of agents, teams, and workflows
- **Interactive Management**: Create and manage agents through web UI
- **Workflow Visualization**: Visual workflow builder and execution monitor
- **Team Coordination**: Manage team hierarchies and coordination strategies
- **Modern UI**: Built with React 18, TypeScript, and Tailwind CSS

## 📦 Installation

### Development Setup

```bash
# Clone the repository
git clone https://github.com/engine-agi/engine-web.git
cd engine-web

# Install dependencies
npm install

# Start development server
npm run dev
```

### Production Build

```bash
# Build for production
npm run build

# Preview production build
npm run preview
```

## 🏗️ Architecture

```
src/
├── components/          # Reusable UI components
│   ├── agents/         # Agent management components
│   ├── teams/          # Team coordination components
│   ├── workflows/      # Workflow visualization
│   ├── tools/          # Tool integration UI
│   └── shared/         # Common components
├── pages/              # Page components
│   ├── dashboard/      # Main dashboard
│   ├── agents/         # Agent management
│   ├── teams/          # Team management
│   └── workflows/      # Workflow management
├── hooks/              # Custom React hooks
├── services/           # API integration
├── types/              # TypeScript type definitions
└── utils/              # Utility functions
```

## 🔧 Usage

### Local Development

```bash
# Start development server
npm run dev

# Open http://localhost:5173 in your browser
```

### API Configuration

Update `src/services/api.ts` with your Engine Core API endpoint:

```typescript
const API_BASE_URL = 'http://localhost:8000/api/v1';
```

## 📚 Key Features

### Agent Management
- Create and configure AI agents
- Monitor agent status and performance
- View agent execution logs
- Manage agent capabilities and tools

### Team Coordination
- Create and manage teams
- Define coordination strategies
- Monitor team performance
- Visualize team hierarchies

### Workflow Orchestration
- Visual workflow builder
- Real-time execution monitoring
- Workflow performance analytics
- Error handling and debugging

## 🛠️ Tech Stack

- **Frontend Framework**: React 18 with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **State Management**: React Query + Context
- **Charts**: Recharts
- **Icons**: Lucide React
- **HTTP Client**: Axios

## 📚 Documentation

- [User Guide](https://engine-agi.github.io/engine-web/user-guide)
- [API Reference](https://engine-agi.github.io/engine-web/api)
- [Contributing](https://engine-agi.github.io/engine-web/contributing)

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for development setup and contribution guidelines.

## 📄 License

MIT License - see [LICENSE](LICENSE) for details.

---

**Part of the Engine Framework** | [engine-agi](https://github.com/engine-agi)