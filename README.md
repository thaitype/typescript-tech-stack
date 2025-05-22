# typescript-tech-stack
TypeScript Tech Stack used and recommended by ThaiType Team

## **🚀 Frontend**

- **astro** — Modern static site builder using islands architecture.
- **Next.js** — Fullstack React framework with SSR, SSG, and API routes.
    - **next-runtime-env** — Load environment variables in the browser at runtime.
- **Material UI** — React components that follow Google’s Material Design.
- **Tailwind CSS** — Utility-first CSS framework for building fast and custom UIs.
- **React Query** — Powerful data fetching and caching solution for React.
- **react-number-format** — Format numbers, currencies, and phone inputs in React.
- **react-hook-form** — Performant form state management using hooks.
- **sonner** — Lightweight toast notification library.
- **vaul** — Accessible and customizable bottom sheet component.
- **usehooks-ts** — Useful and reusable TypeScript hooks for React.
- **zustand** — Simple, scalable, and fast state management.
- **emotion** — CSS-in-JS library for styling components dynamically.
- **signalr** — Real-time web communication library from Microsoft.
- **react router** — Declarative routing for React apps.
- **dnd-kit** — Drag and drop toolkit for React with accessibility focus.
- **tiptap** — Headless rich-text editor built on ProseMirror.
- **ag-grid** — Feature-rich data grid for enterprise-level applications.
- **recharts** — Charting library built with D3 and React.
- **nuqs** — Sync React state with URL query parameters.
- **mantine** — Full-featured React component library with good DX.
- **react-pdf** — Display and render PDFs in React applications.
- **react-icons** — Icon packs wrapped as React components.
- **js-cookie** — Simple JavaScript API for managing cookies.
- **fontsource** — Self-hosted open-source fonts (Google Fonts alternative).
- **lucide-react** — Beautiful, consistent icon library as React components.
- **Fluent UI React** — Microsoft’s React UI framework for enterprise apps.
- **Shadcn** — Beautifully styled Tailwind + Radix UI component set.
- **Radix UI Primitive** — Unstyled, accessible UI primitives for building components.
- **React Aria** — Hooks for building accessible, custom UI components.
- **Better Auth / Auth.js** — Authentication solution for Next.js (formerly NextAuth.js)

## **🛠️ Backend**

- **hono** — Ultra-fast, lightweight web framework for building APIs (similar to Express, but faster).
- **trpc** — End-to-end typesafe API framework for fullstack TypeScript apps.
- **azure functions** — Serverless compute platform from Azure for event-driven apps.
- **mongoose** — ODM (Object Data Modeling) library for MongoDB in Node.js.
- **drizzle** — TypeScript-first, SQL-friendly ORM with zero runtime.
- **prisma** — Next-gen ORM with type-safe query builder and powerful migration system.
- **polars** — Fast DataFrame library (originally Rust/Python), useful for data analytics in Node.js via bindings.
- **grammY** — Framework for building Telegram bots using JavaScript/TypeScript.
- **google-spreadsheet** — Node.js API wrapper to interact with Google Sheets easily.
- **express** — Minimal and flexible web framework for Node.js, great for APIs and web apps.
    - **http-proxy-middleware (express)** — Middleware to proxy requests in Express apps.
- **nestjs** — Scalable, enterprise-grade Node.js framework using TypeScript and decorators.
    - **@anatine/esbuild-decorators** — Enable decorators in NestJS via esbuild without TypeScript compiler.
    - **grpc, @grpc/grpc-js** — High-performance RPC framework; official gRPC client/server implementation for Node.js.

## **⚙️ DevOps**

- **CDKTF** — Infrastructure as Code using TypeScript with Terraform under the hood (by HashiCorp).
- **Terrakit** — Type-safe infrastructure toolkit designed for multi-tenant, modular cloud environments.
- **kubernetes-models** — Auto-generated Kubernetes resource models for writing manifests with full type safety.

## **🧰 General Utilities**

- **axios** — Promise-based HTTP client for browser and Node.js.
- **lodash-es** — Utility library for JavaScript with ES module support.
- **promise-fun** — Async/await utility functions for cleaner async code.
- **filenamify** — Make filenames safe for use across OSes.
- **url-join** — Join URL segments into a properly formatted URL.
- **faker-js** — Generate fake data for testing and prototyping.
- **numbro** — Number formatting and manipulation with localization.
- **dayjs** — Lightweight date library compatible with Moment.js API.
- **grapheme-splitter** — Correctly split strings by visual Unicode characters.
- **node-cron** — Cron-style scheduled task runner for Node.js.

## **🔒 Encoding, Hashing, Config & Env**

- **hash-wasm** — High-performance WebAssembly hash functions.
- **js-base64** — Encode/decode Base64 easily in JavaScript.
- **dotenv** — Load environment variables from .env files.
- **unconfig** — Smart config loader that supports multiple formats.

## **🖼️ CLI & Terminal Helpers**

- **cleye** — Minimal and type-safe CLI argument parser.
- **yargs** — Feature-rich CLI parser for building complex tools.
- **ansis** — Styled terminal output using tagged template literals.
- **clipboardy** — Read/write system clipboard with Node.js.
- **execa** — Modern child_process wrapper for shell commands.

## **🪵 Logging**

- **pino** — Extremely fast, structured logging library for Node.js.
- **@thaitype/core-utils** — Pluggable logger utilities with ILogger interface for consistent, testable logging.

## **🧠 Dependency Injection / IoC**

- **inversify** — IoC container for TypeScript/JavaScript applications.
- **@thaitype/ioctopus** — Type-safe IoC container with zero dependency on reflect-metadata, works in any runtime including edge.

## **📦 File & Data Utilities**

- **globby** — Better glob with advanced file-matching patterns.
- **fs-extra** — Enhanced fs module with extra file system methods.
- **gray-matter** — Parse front-matter from markdown and other content files.
- **@iarna/toml** — Fully spec-compliant TOML parser and serializer.
- **yaml** — Parse and stringify YAML files with full spec compliance.

## **🔍 Search & Viewers**

- **flexsearch** — Ultra-fast, lightweight full-text search engine designed for in-browser use.
- **@thaitype/data-viewer-server** — Dev tool for live-reloading and visualizing structured Node.js data in a dynamic web table.

## **🔎 Module & Env Inspectors**

- **node-modules-inspector** — Tool to check for dual-package hazards (ESM/CJS).

## **🧪 Type-Safe Utilities**

- **@thaitype/core-utils** — Typed error and logger utilities with a shared structure.
- **tiny-invariant** — Small assertion utility for throwing errors with conditions.
- **ts-odata-client** — Type-safe OData client SDK for working with OData APIs.
- **type-fest** — A collection of advanced TypeScript type definitions.
- **zod** — TypeScript-first schema validation and inference library.
    - **zod-validation-error** — User-friendly error formatter for Zod schemas.
- **hotscript** — Type-level programming toolkit for composing advanced TypeScript types.

## **🧪 Azure Utilities**

- **@thaitype/azure-service-principal** — Utility to manage Azure Service Principals programmatically.

## **⚒️ Build & Dev Tools**

- **bun** — Fast all-in-one JavaScript runtime, bundler, and test runner.
- **tsup** — Zero-config bundler for TypeScript using esbuild.
- **vite** — Lightning-fast dev server and build tool for modern frontend projects.
- **esbuild** — Extremely fast bundler and minifier for JavaScript/TypeScript.
    - **@jgoz/esbuild-plugin-typecheck** — Adds TypeScript type-checking to esbuild.
- **tsx** — Run TypeScript files instantly using esbuild under the hood.
- **jiti** — Runtime loader for TS/ESM/CJS, ideal for config and scripts.
- **rimraf** — Cross-platform rm -rf alternative for cleaning directories.
- **nodemon** — Auto-restarts Node.js apps when file changes are detected.
- **pnpm** — Efficient, fast, and disk-saving JavaScript package manager.

## **⚙️ CLI & Automation**

- **cross-env** — Set environment variables across OSes in scripts.
- **taze** — Upgrade npm dependencies interactively with filtering.
- **changesets** — Automate changelogs and versioning in monorepos.
- **release-it** — Release automation tool (version bump, changelog, publish).
- **gleanup** — Generate Markdown bundles of source files for LLMs or docs.
- **npm-run-all** — Run multiple npm scripts in sequence or parallel.
- **zx** — Write shell scripts using JavaScript with great DX.
- **husky** — Git hook manager to run tasks before commits or pushes.

## **🧪 Lint, Test & Format**

- **eslint** — Highly configurable linter for JavaScript and TypeScript.
- **prettier** — Opinionated code formatter to keep styles consistent.
- **vitest** — Vite-native unit test framework with great DX and ESM support.
- **playwright** — End-to-end testing tool for modern web apps across browsers.

## **🧩 Monorepo Tooling**

- **nx** — Full-featured monorepo framework with smart caching and orchestration.
- **turborepo** — High-performance monorepo build system from Vercel.

## **📝 Website & Documentation**

- **vitepress** — Lightweight static site generator powered by Vite (by Vue team).
    - **@thaitype/vitepress-typed-navbar** — Typed navigation configuration for VitePress.
    - **@shikijs/vitepress-twoslash** — Add live, annotated code blocks to VitePress using Shiki + twoslash.
- **typedoc** — Generate API documentation from TypeScript source code.
    - **typedoc-vitepress-theme** — VitePress theme for beautiful TypeDoc-generated docs.
- **fumadocs** — Modern documentation framework built with Next.js.
- **resumed** — Resume generator and theme viewer for JSON Resume format.
    - **jsonresume-theme-onepage-web** — One-page web theme for JSON Resume.

## **🚀 Deploys**

- **Azure Static Web App** — Host static sites with built-in CI/CD and auth on Azure.
- **Azure Container App** — Serverless container hosting for microservices and APIs.
- **Azure Functions** — Event-driven serverless compute service by Azure.
- **Azure Kubernetes Service (AKS)** — Managed Kubernetes cluster service by Azure.
- **(More Azure Services)** — Full cloud stack support including storage, database, and networking.
- **Cloudflare Pages** — Fast, global static site hosting with edge functions.
- **Vercel** — Frontend cloud for static and dynamic apps with Git-based CI/CD.

## **🌱 Consideration to Use**

- **Numberflow** — Visual flow-based programming interface (experimental).
- **cmdk** — Headless command menu UI component for React apps.
- **Swiper** — Modern, touch-enabled slider and carousel library.
- **Silk** — Clean and performant documentation framework.
- **Animata** — Animation toolkit for smooth UI interactions.
- **Joyride** — Guide users through UI flows with tooltips and onboarding tours.
