# <img src="resources/minimax-code-icon.png" width="32" align="top"> MiniMax God Mode

<h3>Fully Autonomous AI Coding Agent for VS Code</h3>

[![VS Code](https://img.shields.io/badge/VS%20Code-1.85+-blue?logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=minimax-god-mode.minimax-god-mode)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Price](https://img.shields.io/badge/price-FREE-brightgreen)](https://minimax.io)

---

<p align="center">
  <img width="100%" alt="MiniMax God Mode" src="https://github.com/user-attachments/assets/bb75fe46-e6f7-4023-8aca-01b9629f7704" style="object-fit: contain;" />
</p>

---

## What is MiniMax God Mode?

Stop using coding assistants that just *suggest* code. MiniMax God Mode is a **fully autonomous AI coding agent** that **actually does the work**. It reads your codebase, writes and edits files, runs shell commands, searches code and the web — all without asking permission.

Unlike Copilot or Cursor that waits for your approval, God Mode in **Builder mode** executes actions immediately. Tell it what to build, fix, or research — and watch it happen.

---

## Why MiniMax?

| Service | Speed | Cost |
|---------|-------|------|
| **MiniMax-M2.7-highspeed** | ~100 tok/s | **~$0.01 / 1M tokens** |
| GPT-4o | ~60 tok/s | ~$15 / 1M tokens |
| Claude 3.5 Sonnet | ~60 tok/s | ~$12 / 1M tokens |

MiniMax is **~1000x cheaper** than GPT-4o with comparable coding capability. For an autonomous agent that makes dozens of API calls per task, this isn't a small improvement — it's a complete paradigm shift.

---

## Two Modes

| Mode | Behavior |
|------|----------|
| **Builder** 🔨 | Full autonomy — reads, writes, edits files, runs commands, searches the web. **Acts without asking.** |
| **Plan** 📋 | Read-only — explores code, analyzes structure, explains what needs to be done. No changes made. |

Toggle with `Tab` or click the mode badge in the input box.

| Plan Mode | Builder Mode |
|:---------:|:------------:|
| ![Plan Mode](https://minimax-algeng-chat-tts-us.oss-us-east-1.aliyuncs.com/ccv2%2F2026-04-24%2FMiniMax-M2.7-highspeed%2F2043706096878625265%2Faa5d6ffe243ef5f6a097491e9febe56155e2a953bbb4830df23e74222c6f2eb3..jpeg?Expires=1777052885&OSSAccessKeyId=LTAI5tCpJNKCf5EkQHSuL9xg&Signature=bYA%2FvKksnJrGjrtUnoR7eZmPGhU%3D) | ![Builder Mode](https://minimax-algeng-chat-tts-us.oss-us-east-1.aliyuncs.com/ccv2%2F2026-04-24%2FMiniMax-M2.7-highspeed%2F2043706096878625265%2F3e9570866a9c568273487ef5718fbb330b66b609f87f085abead2087ef807f54..jpeg?Expires=1777052913&OSSAccessKeyId=LTAI5tCpJNKCf5EkQHSuL9xg&Signature=gYB23uHxcv%2FF0fLqrXmrU48cyT8%3D) |

---

## 10 Built-in Tools

The agent operates **directly on your workspace** with these tools:

| Tool | What it does |
|------|-------------|
| `read_file` | Read any file with optional line ranges |
| `write_file` | Create or overwrite files (auto-creates directories) |
| `edit_file` | Precise find-replace within files |
| `bash` | Run shell commands — git, npm, scripts, anything |
| `cmd` | Full system command execution (Builder mode) |
| `glob` | Find files by pattern (`**/*.ts`, `src/**/*`) |
| `grep` | Search file contents with regex + context |
| `search_code` | Semantic code search across your codebase |
| `search_web` | Web research without leaving VS Code |
| `list_directory` | Browse directory trees with depth control |
| `cwd` | Navigate and manage working directory |

---

## Features

### 🛠️ Builder Mode — True Autonomy

In Builder mode, the agent is a **super-agent**. It:
- Writes and edits files without confirmation
- Runs any shell command (git, npm, python, docker...)
- Executes system commands via `cmd`
- Searches code and the web to find solutions
- Refactors, debugs, and ships — all on its own

Just tell it what to build. It figures out how.

### 📋 Plan Mode — Safe Exploration

When you need to understand code before touching anything:
- Explores codebase structure
- Explains what code does
- Identifies potential issues
- Suggests changes without executing them

### 📊 Inline Diff Viewer

Every file change is previewed as a **color-coded diff** directly in the chat. See exactly what was added, removed, or modified before anything is saved.

### 💾 Session History

Conversations auto-save and persist across restarts. Resume any previous session from the history panel (up to 50 sessions stored).

### 📈 Real-Time Quota Tracking

Monitor your MiniMax API usage with color-coded indicators. Reset timers keep you informed of quota windows.

### 🔌 MCP Tool Support

Extend the agent with [Model Context Protocol](https://modelcontextprotocol.io/) servers. Add custom tools for databases, APIs, or external services.

### 🤖 Workspace-Specific Instructions

Drop an `agent.md` file in your project root to give the agent project-specific context, coding conventions, or guidelines. It's loaded automatically for every conversation.

### 📎 @File Context

Reference files in your message using `@filename` to attach them as context. The agent sees the file contents alongside your message.

---

## Getting Started

### 1. Install

Search for **"MiniMax God Mode"** in the VS Code Extensions marketplace:

```
View → Extensions → Search "MiniMax God Mode" → Install
```

Or install the `.vsix` file manually:

```bash
code --install-extension minimax-god-mode-0.2.8.vsix
```

### 2. Set Your API Key

```
Ctrl+Shift+P → "MiniMax: Set API Key"
```

Get your API key from [minimax.io](https://platform.minimax.io).

### 3. Open the Chat

- Click the **MiniMax icon** in the Activity Bar (left sidebar)
- Or press **`Ctrl+Shift+M`** / **`Cmd+Shift+M`**

### 4. Choose Your Mode

Press **`Tab`** in the input box to toggle between **Builder** and **Plan** mode.

---

## Supported Models

| Model | Speed | Best For |
|-------|-------|----------|
| MiniMax-M2.7-highspeed | ~100 tok/s | Complex coding tasks |
| MiniMax-M2.7 | ~60 tok/s | General coding |
| MiniMax-M2.5-highspeed | ~100 tok/s | Fast iterations |
| MiniMax-M2.5 | ~60 tok/s | Balanced workload |
| MiniMax-M2.1-highspeed | ~100 tok/s | Quick edits |

Switch models from the dropdown in the status bar.

---

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl+Shift+M` / `Cmd+Shift+M` | Open / focus chat |
| `Enter` | Send message |
| `Shift+Enter` | New line in message |
| `Tab` | Toggle Plan ↔ Builder mode |
| `Escape` | Cancel streaming response |

---

## Configuration

Settings are in **`Ctrl+,`** under the **MiniMax** section:

| Setting | Default | Description |
|---------|---------|-------------|
| `minimax.model` | `MiniMax-M2.5` | Active model |
| `minimax.theme` | `tokyo-night` | Chat theme |
| `minimax.defaultMode` | `BUILDER` | Startup mode |
| `minimax.mcpServers` | `{}` | MCP server config |

### MCP Server Example

```json
{
  "minimax.mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "/path/to/workspace"],
      "env": {}
    },
    "brave-search": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-brave-search"],
      "env": { "BRAVE_API_KEY": "your-key-here" }
    }
  }
}
```

---

## Themes

Three built-in themes for dark environments:

- **Tokyo Night** — Cool blues and cyans
- **Rose Pine** — Muted pastels with mauve accents  
- **Gruvbox** — Warm earthy tones

---

## Commands

| Command | Description |
|---------|-------------|
| `MiniMax: Open Chat` | Open the sidebar |
| `MiniMax: Set API Key` | Configure API key |
| `MiniMax: Cancel Stream` | Stop current response |
| `MiniMax: Toggle Plan/Builder Mode` | Switch mode |
| `MiniMax: Clear Chat` | Clear conversation |

---

## Example Usage

```
You: Build a REST API endpoint for user registration with validation

Builder Agent:
- Creates routes/users.ts
- Adds input validation with zod
- Implements password hashing with bcrypt
- Sets up database schema
- Writes unit tests
- Runs npm install for dependencies
- Commits with "feat: add user registration endpoint"
```

---

## License

MIT

---

<p align="center">
  <strong>Built with MiniMax</strong><br>
  <a href="https://minimax.io">minimax.io</a> · <a href="https://platform.minimax.io">API Platform</a>
</p>
