# React TypeScript Starter

A modern React + TypeScript starter template with automated development workflows.

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- npm or yarn
- Kiro IDE

### Installation

```bash
npm install
```

### **⚡ Important: Initialize Development Environment**

**Before you start coding**, you need to initialize the development environment:

1. Open the **Kiro panel** (ghost icon in sidebar)
2. Navigate to **"Agent Hooks"**
3. Find **"Backup New Files"** hook
4. Click it to **run the initialization**

This sets up:
- ✅ Automated file backups
- ✅ Development configuration
- ✅ Build optimization settings
- ✅ Local cache management

**You'll know it worked when you see `aws-config.json` created in the project root.**

### Development

```bash
npm run dev
```

## 📁 Project Structure

```
├── src/
│   ├── components/
│   ├── pages/
│   └── utils/
├── aws-config.json      # Auto-generated backup config
├── package.json
└── README.md
```

## 🔧 Configuration

The project uses `aws-config.json` for development environment configuration. This file is auto-generated when you run the initialization hook (see Quick Start above).

**Don't have `aws-config.json`?**
- Run the "Backup New Files" hook from Kiro panel (Execute Backup.hook)
- It creates the configuration automatically

## 🛠️ Features

- **Hot Reload** - Instant feedback during development
- **Auto Backup** - Files automatically backed up to Desktop
- **TypeScript** - Full type safety
- **ESLint** - Code quality enforcement

## 📝 Development Workflow

1. **Initialize** - Run the backup hook (one time setup)
2. **Code** - Create/edit files normally
3. **Backup** - Files auto-saved to Desktop
4. **Deploy** - Run `npm run build`

## ❓ Troubleshooting

### "aws-config.json not found"
This means you haven't run the initialization yet:
1. Open Kiro panel → Agent Hooks
2. Click "Backup New Files"
3. The config file will be created

### "Backup not working"
- Verify hook is enabled in Kiro panel
- Check `aws-config.json` exists
- Re-run initialization if needed

## 🤝 Contributing

1. Fork the repository
2. Run initialization (backup hook)
3. Create feature branch
4. Submit PR

## 📄 License

MIT

---

**Note:** The automated backup system requires one-time initialization via the Kiro hook. See Quick Start section above.
