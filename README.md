# React + TypeScript Project with CI/CD

### 🚀 Project Overview

Modern React + TypeScript project with comprehensive development setup including ESLint, SASS, CI/CD, and VS Code configuration.

### 📁 Project Structure

```
test_cursor/
├── .github/workflows/     # CI/CD configuration
├── .vscode/              # VS Code settings
├── src/                  # Source code
│   ├── App.tsx          # Main component
│   ├── main.tsx         # Entry point
│   ├── App.scss         # Component styles
│   └── index.scss       # Global styles
├── public/              # Static assets
├── dist/                # Build output (auto-generated)
├── package.json         # Dependencies and scripts
├── eslint.config.js     # ESLint configuration
├── tsconfig.json        # TypeScript configuration
├── vite.config.ts       # Vite configuration
└── README.md           # This file
```

### 🛠️ Setup Instructions

#### 1. Prerequisites
- Node.js 18+ 
- Git
- VS Code (recommended)

#### 2. Clone and Install
```bash
git clone git@github.com:Tsekhmister/test_cursor.git
cd test_cursor
npm install
```

#### 3. Development
```bash
# Start development server
npm run dev

# Run all checks
npm run check

# Run checks with auto-fix
npm run check:fix

# Build for production
npm run build
```

### 🔧 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run lint` | Run ESLint |
| `npm run lint:fix` | Run ESLint with auto-fix |
| `npm run type-check` | TypeScript type checking |
| `npm run check` | Run all validations |
| `npm run check:fix` | Run all validations with auto-fix |
| `npm run preview` | Preview production build |

### 🎯 Features

- ✅ **React 19** with TypeScript
- ✅ **Vite** for fast development
- ✅ **ESLint** with modern configuration
- ✅ **SASS** for advanced styling
- ✅ **CI/CD** with GitHub Actions
- ✅ **VS Code** auto-save and formatting
- ✅ **Git hooks** ready
- ✅ **Modern Git workflow**

### 🔄 CI/CD Pipeline

The project includes automated CI/CD with GitHub Actions:

**Triggers:**
- Push to `main` or `develop` branches
- Pull requests to `main` or `develop`

**Checks:**
- ESLint validation
- TypeScript compilation
- Build verification
- Node.js 18.x and 20.x compatibility

**View CI/CD:**
- Go to GitHub repository
- Click "Actions" tab
- See workflow runs and status

### 🎨 Development Workflow

1. **Create feature branch:**
   ```bash
   git checkout -b feature/your-feature
   ```

2. **Develop with auto-save:**
   - VS Code auto-saves every 15 seconds
   - ESLint shows errors in real-time
   - Auto-formatting on save

3. **Check before commit:**
   ```bash
   npm run check:fix
   ```

4. **Commit and push:**
   ```bash
   git add .
   git commit -m "feat: your feature description"
   git push origin feature/your-feature
   ```

5. **Create Pull Request:**
   - Go to GitHub
   - Create PR from feature branch to main
   - CI/CD automatically runs
   - Merge after approval

### 🛠️ VS Code Setup

The project includes optimized VS Code settings:

- **Auto-save:** Every 15 seconds
- **Format on save:** Enabled
- **ESLint auto-fix:** On save
- **TypeScript support:** Full

### 📦 Dependencies

**Production:**
- React 19
- TypeScript
- Vite

**Development:**
- ESLint with modern plugins
- SASS
- Various TypeScript tools



## 🚀 Quick Start

```bash
# Clone and setup
git clone git@github.com:Tsekhmister/test_cursor.git
cd test_cursor
npm install

# Start development
npm run dev

# Check everything works
npm run check
```

**Happy coding! 🎉**
