# Split Deez 💰

A modern expense tracking application built with a monorepo architecture using Turbo.

## 🎯 What is Split Deez?

Split Deez is an expense tracking application designed to help users manage and split expenses efficiently. Built with a scalable monorepo structure, it provides a clean separation between different parts of the application while maintaining consistency in development workflows.

## 🏗️ Project Structure

```
split-deez/
├── apps/                    # Application packages
│   └── backend/            # Backend API server
│       ├── index.js        # Main server entry point
│       └── package.json    # Backend dependencies
├── packages/                # Shared packages (future use)
├── package.json            # Root workspace configuration
├── turbo.json              # Turbo build system configuration
└── README.md               # This file
```

## 🚧 Current Status

This project is currently in early development. The backend server is set up with Fastify and ready for API development.

## 🚀 Getting Started

### Prerequisites

- **Node.js**: Version 18 or higher
- **npm**: Version 10.8.2 or higher (recommended)

### Installation

1. **Clone the repository**

   ```bash
   git clone <your-repo-url>
   cd split-deez
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the backend development server**
   ```bash
   npm run dev-backend
   ```

## 🛠️ Available Scripts

| Script                | Description                          |
| --------------------- | ------------------------------------ |
| `npm run dev-backend` | Start the backend development server |
| `npm install`         | Install all workspace dependencies   |

## 🏗️ Architecture

### Technology Stack

- **Backend**: Node.js with Fastify framework
- **Build System**: Turbo for efficient monorepo management
- **Package Manager**: npm workspaces

## 📦 Workspaces

### Apps

- **Backend**: Fastify-based API server (currently in development)

### Packages (Future)

- Shared utilities, components, and configurations will be added here as the project grows.

## 🔧 Development

### Adding New Apps

1. Create a new directory in `apps/`
2. Initialize with `npm init`
3. Add to the root `package.json` workspaces array
4. Configure in `turbo.json` if needed

### Adding New Packages

1. Create a new directory in `packages/`
2. Initialize with `npm init`
3. Add to the root `package.json` workspaces array
4. Configure build tasks in `turbo.json`

## 📄 License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Sumant Katti**

---

Built with ❤️ using Turbo and Fastify
