# Foxvoid Studio

<div align="center">

**Building the next generation of Game Development-as-a-Service (GaaS).** We bridge the gap between high-performance Rust programming and instant WebAssembly deployment.

[Website](https://foxvoid.com) • [Fantasy Craft](https://github.com/foxvoid-studio/fantasy_craft) • [Discord](https://discord.gg/placeholder) • [Twitter](https://twitter.com/placeholder)

</div>

---

## 🚀 Our Mission

**Foxvoid Studio** is a technology company dedicated to democratizing game development in **Rust**. We believe that building performant, type-safe games shouldn't come with the burden of complex deployment pipelines.

We are building an ecosystem where a developer can go from `cargo new` to a monetized, multiplayer-ready web game in minutes.

---

## 🛠️ The Ecosystem

### 🎮 Fantasy Craft (The Engine)
Fantasy Craft is our flagship game engine and SDK, designed for speed and simplicity. It allows developers to create 2D and 2.5D games using a robust ECS architecture without the bloat.

* **Core:** Built on **Rust** for safety and performance.
* **Rendering:** Powered by **Macroquad** for lightweight, cross-platform graphics.
* **Architecture:** Data-Oriented Design using **Hecs** (Entity Component System).
* **Physics:** Integrated **Parry2d** for precise collision detection.
* **WASM-First:** Optimized to run flawlessly in browsers via WebAssembly.

### ☁️ Foxvoid Platform (The Infrastructure)
We don't just provide an engine; we provide the entire stage. Foxvoid is a comprehensive **PaaS (Platform as a Service)** that handles the heavy lifting for game developers.

* **Instant Deployment:** A cloud build pipeline (powered by **Celery** & **Docker**) that compiles Rust code to optimized WASM in seconds.
* **Universal Storage:** A **Django** backend with **PostgreSQL (JSONB)** allowing games to save states, player stats, and global world data via a simple SDK.
* **Native Launcher:** A centralized hub to play games natively, bridging the gap between Web and Desktop.
* **Fair Economy:** Integrated **Stripe Connect** marketplace, allowing developers to monetize their creations directly.

---

## 🧩 Tech Stack

We believe in using the right tool for the job. Our stack blends the performance of systems programming with the robustness of modern web frameworks.

| Component | Technology | Why we use it |
| :--- | :--- | :--- |
| **Game Logic** | 🦀 **Rust** | Memory safety, zero-cost abstractions, and WASM support. |
| **Backend** | 🐍 **Django (Python)** | Rapid development, security, and powerful ORM. |
| **API** | 🔌 **Django Rest Framework** | Seamless communication between the Game Client and the Cloud. |
| **Database** | 🐘 **PostgreSQL** | Storing relational data and structured JSON game states (NoSQL-like). |
| **Task Queue** | 🐇 **Celery + Redis** | Handling asynchronous build tasks and asset processing. |
| **Frontend** | ⚛️ **WASM + HTML5** | Running console-quality games in the browser. |

---

## 🔮 Roadmap

We are currently in active development. Here is what we are building:

- [x] **Core Engine:** Macroquad + Hecs integration.
- [x] **Web Platform:** Django-based auth and project management.
- [ ] **Cloud Build System:** Automated `cargo build` to WASM pipeline.
- [ ] **Data SDK:** `foxvoid::storage` API for cloud saves and leaderboards.
- [ ] **Asset Pipeline:** Auto-conversion of assets (WebP/Ogg) for faster loading.
- [ ] **Marketplace:** Beta launch of the Developer Asset Store and Game Monetization.

---

## 🤝 Join the Revolution

We are looking for passionate Rustaceans, Pythonistas, and Game Designers to help us build the future of indie game dev.

* Interested in the **Engine**? Check out the [Fantasy Craft Repo](https://github.com/foxvoid-studio).
* Interested in the **Platform**? [Contact us](mailto:contact@foxvoid.com).

<div align="center">
  <sub>© 2025 Foxvoid Studio. All rights reserved.</sub>
</div>
