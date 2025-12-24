# CodePilot

**CodePilot** is a modern, all-in-one dashboard for developers, designed to streamline project management, learning paths, resources, tasks, and analytics. Built with **React** and **Vite**, and fully optimized for TypeScript, CodePilot provides an intuitive interface to help developers stay organized and focused.

## Table of Contents
- [Features](#features)
- [Architecture](#architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)


## Features

- **Project Management:** Create, track, and organize multiple projects with ease.  
- **Learning Paths:** Curated resources and guided paths to accelerate skill development.  
- **Resource Library:** Centralized collection of tutorials, articles, and documentation.  
- **Task Management:** Manage tasks, deadlines, and priorities with a simple Kanban-style board.  
- **Analytics:** Insights into productivity and progress across projects and learning paths.  
- **Modern Tech Stack:** Built with React, Vite, and TypeScript for speed, scalability, and maintainability.  
- **Responsive Design:** Fully responsive UI for desktop and mobile devices.  


## Architecture

The project is structured for modularity, scalability, and maintainability:

```

codepilot/
├── public/               # Static assets (icons, images, manifest)
├── src/
│   ├── assets/           # Images, icons, fonts
│   ├── components/       # Reusable UI components (Buttons, Cards, Modals)
│   ├── context/          # Global state management using React Context
│   ├── hooks/            # Custom hooks
│   ├── pages/            # Application pages (Dashboard, Projects, Learning, Analytics)
│   ├── services/         # API calls and data services
│   ├── styles/           # Global and component-specific styles
│   ├── utils/            # Utility functions
│   └── App.tsx           # Main application entry
├── .gitignore
├── package.json
├── tsconfig.json
└── vite.config.ts

```


## Installation

1. **Clone the repository**
```bash
git clone https://github.com/Calvorya/CodePilot.git
cd codepilot
```

2. **Install dependencies**

```bash
npm install
```

3. **Start the development server**

```bash
npm run dev
```

4. Open your browser at [http://localhost:5173](http://localhost:5173)

---

## Usage

* Navigate between Dashboard, Projects, Learning Paths, and Analytics.
* Create new projects, add tasks, and track progress.
* Explore learning resources and follow curated learning paths.
* Customize dashboard components as per your workflow.

---

## Contributing

We welcome contributions from the community. To contribute:

1. Fork the repository
2. Create a feature branch:

```bash
git checkout -b feature/your-feature
```

3. Commit your changes:

```bash
git commit -m "Add feature description"
```

4. Push to your branch:

```bash
git push origin feature/your-feature
```

5. Open a Pull Request

---

## License

This project is licensed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for details.

---

**CodePilot** — Empowering developers to organize, learn, and grow efficiently.
