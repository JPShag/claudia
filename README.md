<div align="center">
  <img src="https://github.com/user-attachments/assets/92fd93ed-e71b-4b94-b270-50684323dd00" alt="Claudia Logo" width="120" height="120">

  <a href="https://claudiacode.com"><h1>Claudia</h1></a>
  
  <p>
    <strong>A powerful GUI toolkit for Claude Code</strong>
  </p>
  <p>
    <strong>Create custom agents, manage interactive sessions, run secure background processes, and more.</strong>
  </p>
  
  <p>
    <a href="#features"><img src="https://img.shields.io/badge/Features-✨-blue?style=for-the-badge" alt="Features"></a>
    <a href="#installation"><img src="https://img.shields.io/badge/Install-🚀-green?style=for-the-badge" alt="Installation"></a>
    <a href="#usage"><img src="https://img.shields.io/badge/Usage-📖-purple?style=for-the-badge" alt="Usage"></a>
    <a href="#development"><img src="https://img.shields.io/badge/Develop-🛠️-orange?style=for-the-badge" alt="Development"></a>
  </p>
</div>

![457013521-6133a738-d0cb-4d3e-8746-c6768c82672c](https://github.com/user-attachments/assets/a028de9e-d881-44d8-bae5-7326ab3558b9)

https://github.com/user-attachments/assets/bf0bdf9d-ba91-45af-9ac4-7274f57075cf

> [!TIP]
> **⭐ Star the repo and follow [@getAsterisk](https://x.com/getAsterisk) on X for early access to `asteria-swe-v0`**.

## 🌟 Overview

**Claudia** is a comprehensive desktop application that revolutionizes your Claude Code workflow. Built with Tauri 2, it provides an intuitive GUI for managing Claude Code sessions, creating specialized AI agents, monitoring usage analytics, and seamlessly integrating with your development environment.

Transform your command-line Claude Code experience into a visual, productive workspace where AI-assisted development becomes effortless and organized.

## 📋 Table of Contents

- [🌟 Overview](#-overview)
- [✨ Features](#-features)
  - [🗂️ Project & Session Management](#️-project--session-management)
  - [🤖 Custom AI Agents](#-custom-ai-agents)
  - [📊 Usage Analytics Dashboard](#-usage-analytics-dashboard)
  - [🔌 MCP Server Integration](#-mcp-server-integration)
  - [⏰ Timeline & Checkpoints](#-timeline--checkpoints)
  - [📝 CLAUDE.md Editor](#-claudemd-editor)
- [📖 Usage](#-usage)
- [🚀 Installation](#-installation)
- [🔨 Build from Source](#-build-from-source)
- [🛠️ Development](#️-development)
- [🔒 Security](#-security)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [🙏 Acknowledgments](#-acknowledgments)

## ✨ Features

### 🗂️ **Project & Session Management**
- **Visual Project Browser**: Navigate your entire `~/.claude/projects/` directory with a clean, organized interface
- **Session History**: Access complete session archives with context preservation and metadata
- **Smart Search & Filters**: Find projects and sessions instantly using powerful search algorithms
- **Session Insights**: Preview first messages, timestamps, and execution summaries at a glance
- **Quick Actions**: Resume, duplicate, or create new sessions with one-click simplicity

### 🤖 **Custom AI Agents**
- **Specialized Agent Creation**: Design purpose-built agents with custom system prompts and behavioral configurations
- **Agent Library Management**: Organize and categorize your agent collection for easy access
- **Background Execution**: Run agents asynchronously without blocking your main workflow
- **Execution Monitoring**: Track agent performance, logs, and resource usage in real-time
- **Agent Sharing**: Export and import agent configurations for team collaboration

### 📊 **Usage Analytics Dashboard**
- **Real-Time Cost Tracking**: Monitor Claude API usage and associated costs with live updates
- **Granular Token Analytics**: Detailed breakdowns by model type, project scope, and time periods
- **Interactive Visualizations**: Beautiful charts and graphs showing usage trends and patterns
- **Data Export**: Export comprehensive usage reports for accounting and analysis
- **Budget Alerts**: Set spending thresholds and receive notifications (coming soon)

### 🔌 **MCP Server Integration**
- **Centralized Server Registry**: Manage all Model Context Protocol servers from a unified interface
- **Streamlined Configuration**: Add servers through intuitive UI forms or bulk JSON imports
- **Connection Validation**: Test server connectivity and validate configurations before deployment
- **Claude Desktop Sync**: Import existing server configurations from Claude Desktop seamlessly
- **Health Monitoring**: Track server status and performance metrics

### ⏰ **Timeline & Checkpoints**
- **Session Versioning**: Create snapshots of your coding session at any moment
- **Visual Timeline Navigation**: Browse session history through an interactive, branching timeline
- **One-Click Restoration**: Jump back to any checkpoint instantly without data loss
- **Session Forking**: Create parallel development branches from existing checkpoints
- **Advanced Diff Viewer**: Visualize changes between checkpoints with syntax highlighting

### 📝 **CLAUDE.md Editor**
- **Integrated Markdown Editor**: Edit CLAUDE.md files directly within the application
- **Live Preview Rendering**: See your markdown formatted in real-time as you type
- **Project-Wide Scanner**: Automatically discover and index all CLAUDE.md files across projects
- **Advanced Syntax Support**: Full markdown highlighting with Claude-specific extensions
- **Template System**: Use predefined templates for consistent CLAUDE.md structure

## 📖 Usage

### Getting Started

1. **Launch Claudia**: Open the application after installation
2. **Choose Your Workflow**: Select between CC Agents for automation or CC Projects for session management
3. **Automatic Detection**: Claudia automatically detects your `~/.claude` directory and existing projects

### Managing Projects

Navigate: `CC Projects → Select Project → View Sessions → Resume or Start New`

- Browse all projects with thumbnail previews and metadata
- View session history with searchable filters
- Resume existing sessions with full context restoration
- Create new sessions with customizable templates

### Creating and Managing Agents

Navigate: `CC Agents → Create Agent → Configure → Execute`

1. **Agent Design**: Set name, icon, description, and behavioral parameters
2. **Model Configuration**: Choose from available Claude models with custom settings
3. **Permission Management**: Configure file access, network permissions, and execution limits
4. **Task Execution**: Deploy agents on projects with real-time monitoring

### Monitoring Usage

Navigate: `Menu → Usage Dashboard → View Analytics`

- Real-time cost monitoring with model-specific breakdowns
- Historical usage trends with customizable date ranges
- Project-specific analytics for budget allocation
- Export capabilities for external reporting

### MCP Server Management

Navigate: `Menu → MCP Manager → Add Server → Configure`

- Add servers manually with guided configuration
- Bulk import via JSON configuration files
- Import from existing Claude Desktop setups
- Test connections and validate server health

## 🚀 Installation

### Prerequisites

- **Claude Code CLI**: Install from [Claude's official site](https://claude.ai/code)
- **System Requirements**: Windows 10/11, macOS 11+, or Linux (Ubuntu 20.04+, Fedora 35+)

> **Release Executables Coming Soon** - Pre-built installers for all platforms will be available shortly.

## 🔨 Build from Source

### Prerequisites

#### System Requirements
- **Operating System**: Windows 10/11, macOS 11+, or Linux (Ubuntu 20.04+, Fedora 35+)
- **RAM**: Minimum 4GB (8GB recommended for optimal performance)
- **Storage**: At least 1GB free space for build artifacts

#### Required Tools

**Rust** (1.70.0 or later)
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source ~/.cargo/env
```

**Bun** (latest version)
```bash
curl -fsSL https://bun.sh/install | bash
```

**Git**
```bash
# Usually pre-installed, verify with: git --version
# Ubuntu/Debian: sudo apt install git
# Fedora: sudo dnf install git  
# macOS: brew install git
# Windows: Download from https://git-scm.com
```

**Claude Code CLI**
- Download and install from [Claude's official site](https://claude.ai/code)
- Verify installation: `claude --version`

### Platform-Specific Dependencies

#### Linux (Ubuntu/Debian)
```bash
sudo apt update && sudo apt install -y \
  libwebkit2gtk-4.1-dev \
  libgtk-3-dev \
  libayatana-appindicator3-dev \
  librsvg2-dev \
  patchelf \
  build-essential \
  curl \
  wget \
  file \
  libssl-dev \
  libxdo-dev \
  libsoup-3.0-dev \
  libjavascriptcoregtk-4.1-dev
```

#### Linux (Fedora/RHEL/CentOS)
```bash
sudo dnf update && sudo dnf install -y \
  webkit2gtk4.1-devel \
  gtk3-devel \
  libappindicator-gtk3-devel \
  librsvg2-devel \
  cairo-gobject-devel \
  pango-devel \
  gdk-pixbuf2-devel \
  atk-devel \
  openssl-devel \
  curl \
  wget \
  file \
  libsoup3-devel \
  javascriptcoregtk4.1-devel

# Install development tools
sudo dnf groupinstall "Development Tools" "Development Libraries"
```

#### macOS
```bash
# Install Xcode Command Line Tools
xcode-select --install

# Optional: Install additional dependencies via Homebrew
brew install pkg-config
```

#### Windows
- Install [Microsoft C++ Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/)
- Install [WebView2](https://developer.microsoft.com/microsoft-edge/webview2/) (pre-installed on Windows 11)

### Build Steps

1. **Clone Repository**
   ```bash
   git clone https://github.com/getAsterisk/claudia.git
   cd claudia
   ```

2. **Install Dependencies**
   ```bash
   bun install
   ```

3. **Development Build**
   ```bash
   # Start development server with hot reload
   bun run tauri dev
   ```

4. **Production Build**
   ```bash
   # Create optimized production build
   bun run tauri build
   
   # Executables and installers will be in:
   # src-tauri/target/release/
   ```

### Build Options

**Debug Build** (faster compilation, larger binary)
```bash
bun run tauri build --debug
```

**Universal macOS Binary** (Intel + Apple Silicon)
```bash
bun run tauri build --target universal-apple-darwin
```

### Troubleshooting

#### Common Issues

**"cargo not found"**
- Ensure Rust is installed: `rustc --version`
- Add to PATH: `source ~/.cargo/env`
- Restart terminal after installation

**Linux: "webkit2gtk not found"**
- Install development packages listed above
- For newer Ubuntu: try `libwebkit2gtk-4.0-dev`

**Fedora: PKG_CONFIG_PATH errors**
- Ensure all `-devel` packages are installed
- Run `pkg-config --list-all | grep webkit` to verify

**Windows: "MSVC not found"**
- Install Visual Studio Build Tools with C++ support
- Restart terminal after installation

**"claude command not found"**
- Install Claude Code CLI and ensure it's in PATH
- Test with: `claude --version`

**Memory issues during build**
- Build with fewer parallel jobs: `cargo build -j 2`
- Close other applications to free RAM

#### Verification

Test your build:
```bash
# Run the executable directly
./src-tauri/target/release/claudia         # Linux/macOS
./src-tauri/target/release/claudia.exe     # Windows
```

## 🛠️ Development

### Technology Stack

- **Frontend**: React 18 + TypeScript + Vite 6
- **Backend**: Rust with Tauri 2 framework
- **Styling**: Tailwind CSS v4 + shadcn/ui components
- **Database**: SQLite with rusqlite bindings
- **Package Management**: Bun for fast dependency resolution

### Project Architecture

```
claudia/
├── src/                   # React frontend application
│   ├── components/        # Reusable UI components
│   ├── lib/               # API clients & utility functions
│   ├── hooks/             # Custom React hooks
│   └── assets/            # Static assets and resources
├── src-tauri/             # Rust backend application
│   ├── src/
│   │   ├── commands/      # Tauri command handlers
│   │   ├── checkpoint/    # Session timeline management
│   │   ├── process/       # Background process management
│   │   └── database/      # SQLite operations
│   └── tests/             # Comprehensive test suite
└── public/                # Public web assets
```

### Development Commands

```bash
# Start development environment
bun run tauri dev

# Frontend-only development
bun run dev

# Type checking
bunx tsc --noEmit

# Run Rust tests
cd src-tauri && cargo test

# Code formatting
cd src-tauri && cargo fmt
bunx prettier --write src/

# Linting
bunx eslint src/
cd src-tauri && cargo clippy
```

### Contributing Guidelines

1. **Fork and Clone**: Fork the repository and clone your fork
2. **Branch Strategy**: Create feature branches from `main`
3. **Code Quality**: Follow existing patterns and run linters
4. **Testing**: Add tests for new functionality
5. **Documentation**: Update relevant documentation
6. **Pull Request**: Submit PR with clear description

## 🔒 Security

Claudia implements multiple security layers to protect your data and development environment:

**Process Isolation**: All AI agents execute in sandboxed processes with configurable permissions

**Permission Management**: Granular control over file system access, network permissions, and system resources

**Local-First Architecture**: All data remains on your machine with no external telemetry or tracking

**Open Source Transparency**: Full source code visibility for security auditing and community review

**Secure Communication**: All API communications use encrypted channels with proper credential management

## 🤝 Contributing

We welcome contributions from developers of all skill levels! Here are ways you can help:

### Areas for Contribution

- 🐛 **Bug Fixes**: Help resolve issues and improve stability
- ✨ **New Features**: Implement requested functionality and enhancements  
- 📚 **Documentation**: Improve guides, API docs, and examples
- 🎨 **UI/UX**: Enhance the user interface and experience
- 🧪 **Testing**: Expand test coverage and quality assurance
- 🌐 **Internationalization**: Add support for additional languages
- ⚡ **Performance**: Optimize build times and runtime efficiency

### Getting Started

1. Check our [Issues](https://github.com/getAsterisk/claudia/issues) for good first contributions
2. Read our [Contributing Guide](CONTRIBUTING.md) for detailed guidelines
3. Join our community discussions for support and collaboration

## 📄 License

This project is licensed under the **AGPL License** - see the [LICENSE](LICENSE) file for complete details.

The AGPL license ensures that Claudia remains open source and that any modifications or network-based services using Claudia must also remain open source.

## 🙏 Acknowledgments

**Built With**
- [Tauri](https://tauri.app/) - Secure framework for building desktop applications
- [Claude](https://claude.ai) by Anthropic - AI assistant powering the core functionality
- [React](https://react.dev/) - Frontend user interface framework
- [Rust](https://www.rust-lang.org/) - Systems programming language for performance and safety

**Special Thanks**
- The Tauri team for their excellent documentation and support
- The Anthropic team for Claude Code and continuous API improvements
- Our community contributors who help make Claudia better every day

---

<div align="center">
  <p>
    <strong>Made with ❤️ by the <a href="https://asterisk.so/">Asterisk</a> team</strong>
  </p>
  <p>
    <a href="https://github.com/getAsterisk/claudia/issues">Report Bug</a>
    ·
    <a href="https://github.com/getAsterisk/claudia/issues">Request Feature</a>
    ·
    <a href="https://github.com/getAsterisk/claudia/discussions">Join Discussion</a>
  </p>
</div>

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=getAsterisk/claudia&type=Date)](https://www.star-history.com/#getAsterisk/claudia&Date)
