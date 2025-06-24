# Next.js Stack Template

A modern and minimal template built with [Next.js](https://nextjs.org/), [TypeScript](https://www.typescriptlang.org/), and [Tailwind CSS](https://tailwindcss.com/), featuring a pre-configured setup for scalable and maintainable applications. Includes support for [shadcn/ui](https://ui.shadcn.com/) components (manually installed).

## ✨ Features

* ⚡ Next.js 15 with App Router
* 💅 Tailwind CSS 4 for utility-first styling
* 🧹 shadcn/ui components (manually integrated)
* 🧠 TypeScript for static typing
* 🔧 ESLint, Prettier, and lint-staged for code quality
* 📆 Husky for Git hooks and commit linting
* 📑 Conventional Commits with Commitlint
* 🧪 Jest for unit testing
* 📈 Sentry integration for error monitoring

## 📦 Stack

* `next` `15.3.4`
* `react` `^19.0.0`
* `tailwindcss` `^4`
* `shadcn/ui` (installed manually)
* `clsx`, `class-variance-authority`, `tailwind-merge`
* `lucide-react` for icons
* `eslint`, `prettier`, `husky`, `commitlint`

## 🛠️ Scripts

| Script            | Description                          |
| ----------------- | ------------------------------------ |
| `yarn dev`        | Start the development server         |
| `yarn build`      | Build for production                 |
| `yarn start`      | Start the production server          |
| `yarn lint`       | Run ESLint                           |
| `yarn format`     | Format code with Prettier            |
| `yarn test`       | Run tests with Jest                  |
| `yarn prepare`    | Set up Git hooks with Husky          |
| `yarn commitlint` | Validate commits against conventions |

## 🧪 Testing

This template uses [Jest](https://jestjs.io/) for unit testing. To run the tests:

```bash
yarn test
```

## ✅ Linting & Formatting

* ESLint is configured with import and prettier plugins
* Prettier is used to ensure consistent formatting
* Husky + lint-staged runs linting and formatting before each commit
* Commitlint ensures all commits follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) standard

## 🚀 Getting Started

```bash
# Install dependencies
yarn

# Start the development server
yarn dev
```

## 📂 Project Structure

```bash
.
├── public/                       # Static assets
├── src/
│   ├── app/                      # Next.js App Router
│   │   ├── api/                  # API routes
│   │   └── sentry-example-page/  # Example page
│   ├── lib/                      # Utilities and instrumentation
│   └── components/               # UI components (shadcn/ui)
├── .env                          # Environment variables
├── package.json
├── tsconfig.json
├── tailwind.config.ts
├── postcss.config.mjs
├── next.config.ts
├── eslint.config.js
├── README.md
```

## 🧹 About shadcn/ui

Although `shadcn/ui` is not listed in the `package.json`, components from the library have been installed manually. Learn more and customize your components at [ui.shadcn.com](https://ui.shadcn.com).

## 📋 License

This project is licensed under the MIT License.