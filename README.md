# Powder Sandbox – Multi-Edition Game Hub

## One Physics Sandbox, Infinite Interpretations

### Licensed under BSD 3-Clause — see [LICENSE](https://github.com/RobertFlexx/Powder-Sandbox-GameHub/blob/main/LICENSE) for details.

Welcome to the **Powder Sandbox Multi-Edition Hub**, the central nexus that connects all language editions of **Powder Sandbox** — the ever-evolving, terminal-based physics simulator of falling sand, flowing liquids, crackling electricity, and chaotic emergent beauty.

Born from a single `ncurses`-based C++ project, this simulation has grown into an entire ecosystem of editions — each built in a different language, each with its own flavor, performance quirks, and design philosophy.

Choose your style, your language, your runtime — and dive into the chaos.

---

## 🌋 The Core Premise

At its heart, every edition of **Powder Sandbox** shares the same dream: simulate **life and destruction** inside the terminal.

Grains of sand fall. Fire spreads. Water flows. Lightning crackles across metal wires and saltwater pools. Humans flee zombies. Plants grow in moist dirt. Seaweed stretches toward the light.

Every version — from bare-metal **C** to high-level **Kotlin** — captures this interplay of physics and entropy in its own unique way.

---

## 🧭 Repository Index

### 🧱 Native / Systems Editions

| Edition             | Language | Repo                                                                                                                     |
| ------------------- | -------- | ------------------------------------------------------------------------------------------------------------------------ |
| C++ Classic Edition | C++17    | [https://github.com/RobertFlexx/Powder-Sandbox-Classic](https://github.com/RobertFlexx/Powder-Sandbox-Classic)           |
| C Fast Edition      | C        | [https://github.com/RobertFlexx/Powder-Sandbox-Fast-Edition](https://github.com/RobertFlexx/Powder-Sandbox-Fast-Edition) |
| Rustbox Edition     | Rust     | [https://github.com/RobertFlexx/Rustbox-Sandbox](https://github.com/RobertFlexx/Rustbox-Sandbox)                         |

### ☕ JVM Editions

| Edition        | Language | Repo                                                                                                                         |
| -------------- | -------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Kotlin Edition | Kotlin   | [https://github.com/RobertFlexx/Powder-Sandbox-Kotlin-Edition](https://github.com/RobertFlexx/Powder-Sandbox-Kotlin-Edition) |
| Scala Edition  | Scala    | [https://github.com/RobertFlexx/Powder-Sandbox-Scala-Edition](https://github.com/RobertFlexx/Powder-Sandbox-Scala-Edition)   |
| Groovy Edition | Groovy   | [https://github.com/RobertFlexx/Powder-Sandbox-Groovy-Edition](https://github.com/RobertFlexx/Powder-Sandbox-Groovy-Edition) |

### 🧩 .NET Editions

| Edition    | Language | Repo                                                                                                                 |
| ---------- | -------- | -------------------------------------------------------------------------------------------------------------------- |
| C# Edition | C#/.NET  | [https://github.com/RobertFlexx/Powder-Sandbox-CS-Edition](https://github.com/RobertFlexx/Powder-Sandbox-CS-Edition) |
| F# Edition | F#/.NET  | [https://github.com/RobertFlexx/Power-Sandbox-F-Edition](https://github.com/RobertFlexx/Power-Sandbox-F-Edition)     |

---

## 🔥 Shared Features Across All Editions

Every edition — no matter the language — brings these defining traits:

* **Terminal UI (TUI)** simulation with colorful grid rendering
* A universe of **interacting elements** — powders, liquids, solids, gases, and entities
* Rich element reactions:

  * **Powders:** sand, snow, ash, gunpowder
  * **Liquids:** water, saltwater, oil, acid, lava, mercury
  * **Solids:** stone, glass, wall, metal, coal, wood, plant, seaweed
  * **Gases:** smoke, steam, hydrogen, chlorine, toxic gas
  * **Actors:** humans, zombies, fire, lightning
* **Physics logic:** gravity, buoyancy, temperature, conductivity, and chain reactions
* **AI system:** humans evade fire and zombies; zombies infect the living
* **Procedural growth:** plants, seaweed, and moss react to water and dirt
* **Cross-edition controls:** consistent key layout across all languages

---

## 🧮 Controls

| Key               | Action                 |
| ----------------- | ---------------------- |
| Arrow keys / WASD | Move cursor            |
| Space             | Place current element  |
| E                 | Erase with empty space |
| + / -             | Adjust brush size      |
| M / Tab           | Open element menu      |
| P                 | Pause simulation       |
| C / X             | Clear screen           |
| Q                 | Quit simulation        |

---

## 🧠 Edition-by-Edition Breakdown

### ⚙️ **C++ Classic Edition**

**Repo:** [https://github.com/RobertFlexx/Powder-Sandbox-Classic](https://github.com/RobertFlexx/Powder-Sandbox-Classic)
The original terminal masterpiece — a love letter to retro physics sims.

**Traits:** Fast, polished, cleanly structured. Acts as the behavioral reference for all future editions.

**Highlights:**

* Modern **C++17 + ncurses**
* Optimized simulation loop
* Refined lava-water, fire, and AI behaviors
* True to the original chaotic sandbox roots

---

### ⚡ **C Fast Edition**

**Repo:** [https://github.com/RobertFlexx/Powder-Sandbox-Fast-Edition](https://github.com/RobertFlexx/Powder-Sandbox-Fast-Edition)
A raw C rewrite of the C++ edition, stripped to the bare metal.

**Traits:** The fastest, most compact version — trades modularity for speed.

**Highlights:**

* Minimal abstraction, pure C logic
* Extremely fast cell updates
* Clean and portable across systems

---

### 🦀 **Rustbox Edition**

**Repo:** [https://github.com/RobertFlexx/Rustbox-Sandbox](https://github.com/RobertFlexx/Rustbox-Sandbox)
A reimagined Rust build that balances safety and performance.

**Traits:** Systems-level power without memory risk.

**Highlights:**

* Written in safe **Rust**
* Fully modular architecture
* Compile-time safety with zero-cost abstractions
* Optional multi-threaded simulation

---

### ☕ **Kotlin JVM Edition**

**Repo:** [https://github.com/RobertFlexx/Powder-Sandbox-Kotlin-Edition](https://github.com/RobertFlexx/Powder-Sandbox-Kotlin-Edition)
A modern, sleek, and performant JVM edition.

**Traits:** Minimal syntax, expressive logic, cross-platform stability.

**Highlights:**

* JVM + JNA for TUI rendering
* Concise and type-safe
* Excellent IDE and debugging support

---

### 🧠 **Scala JVM Edition**

**Repo:** [https://github.com/RobertFlexx/Powder-Sandbox-Scala-Edition](https://github.com/RobertFlexx/Powder-Sandbox-Scala-Edition)
A typed, expressive, and functional approach to the sandbox.

**Traits:** Perfect for functional experimentation and DSL-style mechanics.

**Highlights:**

* Immutable data model
* Strong compile-time checks
* Functional + OO blend for flexible rules

---

### 🌀 **Groovy JVM Edition**

**Repo:** [https://github.com/RobertFlexx/Powder-Sandbox-Groovy-Edition](https://github.com/RobertFlexx/Powder-Sandbox-Groovy-Edition)
A dynamic, scripting-ready edition for rapid experimentation.

**Traits:** Instant feedback and no compile overhead.

**Highlights:**

* Fully dynamic, edit-and-run style
* Ideal for live scripting and feature testing
* Same TUI experience via JNA bridge

---

### 🎮 **C# / F# Edition (.NET)**

**C# Repo:** [https://github.com/RobertFlexx/Powder-Sandbox-CS-Edition](https://github.com/RobertFlexx/Powder-Sandbox-CS-Edition)
**F# Repo:** [https://github.com/RobertFlexx/Power-Sandbox-F-Edition](https://github.com/RobertFlexx/Power-Sandbox-F-Edition)
The modern .NET branch — feature-rich, organized, and extensible.

**Traits:** Clean, high-level code with .NET polish.

**Highlights:**

* Cross-platform under **.NET 8**
* Modular OOP (C#) and functional logic (F#)
* Supports sound effects and extended color output

---

## 🧩 Choosing Your Edition

| Goal                                             | Best Edition            |
| ------------------------------------------------ | ----------------------- |
| Want the original, reference implementation      | **C++ Classic Edition** |
| Want the fastest, minimal runtime                | **C Fast Edition**      |
| Want performance *and* memory safety             | **Rustbox Edition**     |
| Want a modern JVM-based feel                     | **Kotlin Edition**      |
| Want functional power and type-safety            | **Scala Edition**       |
| Want dynamic scripting flexibility               | **Groovy Edition**      |
| Want structured .NET OOP design                  | **C# Edition**          |
| Want functional .NET logic with pattern matching | **F# Edition**          |

---

## 🧱 Roadmap

Future hub goals:

* 🌈 Unified launcher CLI for all editions
* 🧩 Shared assets repository (textures, sounds, element presets)
* 🧠 AI sandbox expansion (neural sand logic?)
* 💾 Save/load support across editions
* 🔌 Inter-edition compatibility: load C++ saves in Kotlin, etc.

---

## 🪐 Philosophy

Each edition is more than a port — it’s a reinterpretation.
From bare C to type-rich Scala, from compiled Rust to interpreted Groovy — every version captures a different side of the same universe.

This is not just about code. It’s about seeing how **different languages simulate the same chaos**.

---

## 📜 License

All versions are released under the **BSD 3-Clause License**.
Check each repository for details.

---

## 👤 Author

**Robert (@RobertFlexx)**
Architect of FerriteOS, builder of shells, editors, and the entire Powder Sandbox ecosystem.

GitHub: [https://github.com/RobertFlexx](https://github.com/RobertFlexx)

---

### ⚙️ Final Words

Powder Sandbox isn’t just a physics simulator — it’s a **cross-language experiment**.
A sandbox of code, chaos, and creativity.

Choose your edition. Compile your world. Watch it fall apart beautifully.
