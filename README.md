# Discord.js-v15-Documentation

<p align="center">
  <img src="https://discord.js.org/static/logo.svg" alt="discord.js Logo" width="600" />
</p>

<p align="center">
  <img src="https://img.shields.io/npm/v/discord.js/dev?color=blue&label=Dev%20Version&logo=npm" />
  <a href="https://discord.gg/djs"><img src="https://img.shields.io/discord/222078108977594368?color=5865F2&logo=discord&logoColor=white" alt="Discord server" /></a>
  <a href="https://www.npmjs.com/package/discord.js"><img src="https://img.shields.io/npm/v/discord.js.svg?maxAge=3600" alt="npm version" /></a>
  <a href="https://www.npmjs.com/package/discord.js"><img src="https://img.shields.io/npm/dt/discord.js.svg?maxAge=3600" alt="npm downloads" /></a>
  <a href="https://github.com/discordjs/discord.js/actions"><img src="https://github.com/discordjs/discord.js/actions/workflows/test.yml/badge.svg" alt="Tests status" /></a>
  <a href="https://github.com/discordjs/discord.js/commits/main/packages/discord.js"><img alt="Last commit." src="https://img.shields.io/github/last-commit/discordjs/discord.js?logo=github&logoColor=ffffff&path=packages%2Fdiscord.js" /></a>
  <a href="https://codecov.io/gh/discordjs/discord.js"><img src="https://codecov.io/gh/discordjs/discord.js/branch/main/graph/badge.svg?precision=2" alt="Code coverage" /></a>
</p>

<p align="center">
  <a href="https://vercel.com/?utm_source=discordjs&utm_campaign=oss"><img src="https://raw.githubusercontent.com/discordjs/discord.js/main/.github/powered-by-vercel.svg" alt="Vercel" /></a>
  <a href="https://www.cloudflare.com"><img src="https://raw.githubusercontent.com/discordjs/discord.js/main/.github/powered-by-workers.png" alt="Cloudflare Workers" height="44" /></a>
</p>

<h1 align="center">🚀 discord.js v15 — Developer Preview</h1>

<p align="center">
  The next evolution of the most powerful Node.js library for building Discord bots
</p>

---

## 📌 Summary

`discord.js v15` represents a significant upgrade aimed at modernizing the developer experience and aligning with the latest Discord API advancements. This version introduces improved native support, better caching strategies, enhanced developer tooling, and future-ready design patterns.

---

## 📦 Installation

```bash
npm install discord.js@dev
```

> ⚠️ Requires **Node.js v20.0.0 or later**
>
> Use [nvm](https://github.com/nvm-sh/nvm) or [nvm-windows](https://github.com/coreybutler/nvm-windows) for seamless version management.

---

## ✨ Highlights & Features

### ✅ Native Web API Support

* First-class integration with `fetch`, `AbortController`, `ReadableStream`
* Internal replacement of old polyfills
* Powered by [`undici`](https://github.com/nodejs/undici)

### 💬 Modern Interaction Capabilities

* Native APIs for modals, context menus, and UI components
* Enhanced collectors & interaction responses
* Future command routing system in the works

### ⚙️ Efficient Caching System

* Fully customizable cache layers
* Toggle caching per resource (guilds, users, members, roles...)
* Expected REST-only mode for minimal memory use

### 🧠 Improved Developer Experience

* Fully retyped for advanced TypeScript support
* Smarter IntelliSense with `Client` and `Interaction`
* Annotated JSDoc and better inline documentation

### 🌐 Gateway & Protocol Upgrades

* Complete support for Discord Gateway v11
* Graceful reconnections & lifecycle tracking

---

## 📊 Version Comparison (v14 vs v15)

| Feature                | v14.x      | v15 (dev)     |
| ---------------------- | ---------- | ------------- |
| Node.js Support        | 16.x+      | 20.x+         |
| Native `fetch`         | ❌          | ✅             |
| Modals Support         | ⚠️ Partial | ✅ Full Native |
| Typings & IntelliSense | Moderate   | 🔥 Excellent  |
| REST-only Mode         | ❌          | ✅ (Expected)  |
| Built-in Router        | ❌          | 🧪 Planned    |

---

## 🛠️ Recommended Tooling

* **Node.js:** v20.x or higher
* **TypeScript:** v5.x
* **Linters:** ESLint, Prettier
* **Project Structure:** Modular (commands, events, handlers)

---

## 🔮 Roadmap & Speculation

| Area                    | Future Status  | Description                                            |
| ----------------------- | -------------- | ------------------------------------------------------ |
| ESM-only Support        | Likely         | CJS to be deprecated in favor of modern module systems |
| Built-in Command Router | In development | Simplified interaction-based routing system            |
| CLI Tools               | In discussion  | Scaffolding and command generation support             |
| Tree-shaking Support    | Possible       | Smaller production builds with dead-code elimination   |

---

## 📚 Learning & References

* [GitHub Repository](https://github.com/discordjs/discord.js)
* [NPM Page](https://www.npmjs.com/package/discord.js)
* [Official Documentation (dev)](https://discord.js.org/#/docs/discord.js/dev/general/welcome)
* [Changelog](https://github.com/discordjs/discord.js/releases)
* [Discord API Docs](https://discord.com/developers/docs/intro)

---

## 🤝 Community & Contributions

* 🐞 [Submit Issues](https://github.com/discordjs/discord.js/issues)
* 🧠 [Join the Discord API Server](https://discord.gg/discord-api)
* 🐦 [Follow @discordjs](https://twitter.com/discordjs) for updates

---

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRphxd9RsT9Sf1FNaSzzPSKKH_woY1G09AF_qVKsOsguYAS62gD6ljLPyk&s=10" width="400" alt="discord.js preview" />
</p>

<p align="center"><i>Built with ❤️ by the open-source community — shaping the future of Discord bot development.</i></p>
