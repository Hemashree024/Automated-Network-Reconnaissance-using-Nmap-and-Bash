A modern web application built with Next.js, TypeScript, and Tailwind CSS. This project features a modular component structure, support for server actions, and integrates some AI functionality.

✨ Features

- ⚡️ Built with [Next.js](https://nextjs.org/) and [TypeScript](https://www.typescriptlang.org/)
- 🎨 Styled using [Tailwind CSS](https://tailwindcss.com/)
- 🧠 Includes basic AI utilities (`src/ai/`)
- 📦 Uses modular components for UI (e.g., buttons, dialogs, forms)
- 📁 Organized structure for easy scalability and maintenance

📁 Project Structure

```bash
cyber/
├── src/
│   ├── ai/                 # AI utilities
│   ├── app/                # Application layout and pages
│   ├── components/         # Reusable UI and app components
│   ├── hooks/              # Custom React hooks
│   ├── lib/                # Utility functions
├── public/                 # Static assets
├── .next/                  # Build output (ignored in Git)
├── docs/                   # Documentation and blueprints
├── tailwind.config.ts      # Tailwind configuration
├── next.config.ts          # Next.js configuration
├── tsconfig.json           # TypeScript configuration
├── package.json            # Project dependencies
````
🚀 Getting Started

 Prerequisites

* Node.js (v18 or later)
* npm or yarn

 Installation

```bash
# Clone the repo
git clone https://github.com/your-username/cyber-app.git
cd cyber-app

# Install dependencies
npm install
# or
yarn install
```

 Run the development server

```bash
npm run dev
# or
yarn dev
```

Open your browser at [http://localhost:3000](http://localhost:3000) to see the app in action.

📄 Documentation

See `docs/blueprint.md` for project planning and architecture notes.

🛠 Scripts

```bash
npm run dev       # Start development server
npm run build     # Build the application for production
npm run start     # Start the production server
```

 📌 Notes

* Tailwind CSS is used for UI styling.
* Fonts are loaded using internal Google font modules.
* AI integrations are scaffolded in `src/ai/`, you can extend functionality as needed.

 📄 License

This project is open source and available under the [MIT License](LICENSE).



