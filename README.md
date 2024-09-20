# Vite React TypeScript shadcn/ui Setup Script

This repository contains a PowerShell script that automates the setup of a React project using Vite, TypeScript, and shadcn/ui. It streamlines the process of creating a new project with these technologies, saving developers time and ensuring a consistent setup.

## ✨ Features
- Creates a new Vite project with React and TypeScript
- Installs and configures shadcn/ui components
- Sets up Tailwind CSS with the necessary configurations
- Installs additional useful packages like `class-variance-authority`, `clsx`, and `tailwind-merge`
- Configures path aliases for easier imports
- Creates a basic button component as an example
- Sets up a sample `App.tsx` file demonstrating the use of the button component

## 📋 Prerequisites
- Node.js and npm (Node Package Manager)
- PowerShell (Windows)
- Git (optional, for cloning the repository)

## 🚀 Usage
1. Clone this repository or download the script file:
   ```
   git clone https://github.com/NunoTeixeiraMota/vite-react-ts-shadcn-setup.git
   ```

2. Open PowerShell as an administrator.

3. Navigate to the directory containing the script:
   ```
   cd path/to/script/directory
   ```

4. If you haven't already, you may need to set the execution policy to allow running scripts:
   ```
   Set-ExecutionPolicy RemoteSigned
   ```

5. Run the script:
   ```
   .\create-react-vite-shadcn-project.ps1
   ```

6. Follow the prompts to enter your project name.

7. Once the script completes, navigate to your new project directory and start the development server:
   ```
   cd your-project-name
   pnpm run dev
   ```

## 🛠️ What the Script Does
1. Checks for and installs pnpm if not present
2. Creates a new Vite project with React and TypeScript
3. Installs necessary dependencies including shadcn/ui and its prerequisites
4. Sets up Tailwind CSS configuration
5. Creates the `components.json` file for shadcn/ui
6. Sets up the base styles in `src/index.css`
7. Creates a utility function for merging Tailwind classes
8. Creates a basic button component using shadcn/ui
9. Updates `App.tsx` to use the new button component
10. Configures path aliases for easier imports

## 🔧 Customization
Feel free to modify the script to suit your specific needs. You can add or remove dependencies, change configurations, or add more components as needed.

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 🙏 Acknowledgements
- [Vite](https://vitejs.dev/)
- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [shadcn/ui](https://ui.shadcn.com/)
- [Tailwind CSS](https://tailwindcss.com/)
