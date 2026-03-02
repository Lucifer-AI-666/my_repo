# my_repo

An [Angular](https://angular.io/) web application deployed on [Vercel](https://vercel.com/).

🌐 **Live site:** https://myrepo-neon-iota.vercel.app

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.

## Repository Overview

| Item | Details |
|------|---------|
| **Framework** | Angular 15 |
| **Language** | TypeScript 4.8 |
| **Styling** | CSS |
| **Testing** | Karma + Jasmine |
| **Deployment** | Vercel |

## Project Structure

```
my_repo/
├── src/
│   ├── app/
│   │   ├── app.component.ts        # Root component
│   │   ├── app.component.html      # Root template
│   │   ├── app.component.css       # Root styles
│   │   ├── app.component.spec.ts   # Unit tests
│   │   ├── app.module.ts           # App module
│   │   └── app-routing.module.ts   # Routing
│   ├── assets/                     # Static assets
│   ├── index.html                  # Entry HTML
│   ├── main.ts                     # Bootstrap
│   └── styles.css                  # Global styles
├── angular.json                    # Angular CLI config
├── package.json                    # Dependencies & scripts
├── tsconfig.json                   # TypeScript config
└── README.md
```

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Start the development server at `http://localhost:4200` |
| `npm run build` | Build for production (output to `dist/`) |
| `npm test` | Run unit tests via Karma |
| `npm run watch` | Build in watch mode for development |

## Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm start
```

Navigate to `http://localhost:4200/`. The app reloads automatically when source files change.

## Code Scaffolding

```bash
# Generate a new component
ng generate component component-name

# Other generators: directive, pipe, service, class, guard, interface, enum, module
```

## Build

```bash
ng build
```

Build artifacts are stored in the `dist/` directory.

## Running Tests

```bash
ng test
```

Runs unit tests via [Karma](https://karma-runner.github.io).

## Deployment

This app is automatically deployed to Vercel on every push to `main`.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/vercel/tree/main/examples/angular&template=angular)

## Further Help

To get more help on the Angular CLI use `ng help` or check out the [Angular CLI Overview and Command Reference](https://angular.io/cli).
