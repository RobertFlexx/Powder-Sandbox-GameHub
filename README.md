# Powder Sandbox – Multi-Edition Game Hub

## One Physics Sandbox, Infinite Interpretations

### Intrigued and curious on how these games work? Check out the [PowderCore](https://github.com/RobertFlexx/PowderCore-Engine) engine to see how to integrate this "library/module" into your project and how the engine works as a whole.

### All projects, and this custom physics engine, are licensed under BSD 3-Clause; see [LICENSE](https://github.com/RobertFlexx/Powder-Sandbox-GameHub/blob/main/LICENSE) for details.

Welcome to the **Powder Sandbox Multi-Edition Hub**, the central place that connects all language editions of **Powder Sandbox**, the terminal-based physics simulator of falling sand, flowing liquids, electricity, and emergent behavior.

The project started as a single `ncurses`-based C++ project and has grown into an ecosystem of editions, each built in a different language with its own performance profile and design style.

Pick a language, pick a runtime, and explore.

> Interested in a helpful utility? see [Tedit](https://github.com/RobertFlexx/tedit), my minimal, helpful, text editor in C++17
---

## The Core Premise

At its core, every edition of **Powder Sandbox** has the same goal: simulate **life and destruction** inside the terminal.

Grains of sand fall. Fire spreads. Water flows. Lightning travels across metal wires and saltwater pools. Humans avoid zombies. Plants grow in moist dirt. Seaweed stretches upward under water.

From low-level **C** to high-level **Kotlin**, each version models the same small world in its own way.

---

## Objectives

* Provide a **fun, interactive terminal sandbox** that demonstrates physics and emergent behavior.
* Serve as a **cross-language reference** for building TUI-based simulators.
* Encourage experimentation with **different programming paradigms**.
* Offer a **modular engine (PowderCore)** for integration into other projects.
* Maintain a **consistent experience** across multiple editions while highlighting each language's strengths.

---

## Repository Index

### Native / Systems Editions

| Edition             | Language       | Repo                                                                                                                     |
| ------------------- | -------------- | ------------------------------------------------------------------------------------------------------------------------ |
| C++ Classic Edition | C++17          | [https://github.com/RobertFlexx/Powder-Sandbox-Classic](https://github.com/RobertFlexx/Powder-Sandbox-Classic)           |
| C Fast Edition      | C              | [https://github.com/RobertFlexx/Powder-Sandbox-Fast-Edition](https://github.com/RobertFlexx/Powder-Sandbox-Fast-Edition) |
| Rustbox Edition     | Rust           | [https://github.com/RobertFlexx/Rustbox-Sandbox](https://github.com/RobertFlexx/Rustbox-Sandbox)                         |
| Objective-C Edition | Objective-C    | https://github.com/RobertFlexx/Powder-Sandbox-Objc-Edition                                                                                                           |
| Objective-C++ Edition   | Objective-C++  | https://github.com/RobertFlexx/Powder-Sandbox-Objcpp-Edition                                                                                                           |
| OCaml Edition       | OCaml          | https://github.com/RobertFlexx/Powder-Sandbox-OCaml-Edition                                                                                                           |

### JVM Editions

| Edition        | Language | Repo                                                                                                                         |
| -------------- | -------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Kotlin Edition | Kotlin   | [https://github.com/RobertFlexx/Powder-Sandbox-Kotlin-Edition](https://github.com/RobertFlexx/Powder-Sandbox-Kotlin-Edition) |
| Scala Edition  | Scala    | [https://github.com/RobertFlexx/Powder-Sandbox-Scala-Edition](https://github.com/RobertFlexx/Powder-Sandbox-Scala-Edition)   |
| Groovy Edition | Groovy   | [https://github.com/RobertFlexx/Powder-Sandbox-Groovy-Edition](https://github.com/RobertFlexx/Powder-Sandbox-Groovy-Edition) |

### .NET Editions

| Edition    | Language | Repo                                                                                                                 |
| ---------- | -------- | -------------------------------------------------------------------------------------------------------------------- |
| C# Edition | C#/.NET  | [https://github.com/RobertFlexx/Powder-Sandbox-CS-Edition](https://github.com/RobertFlexx/Powder-Sandbox-CS-Edition) |
| F# Edition | F#/.NET  | [https://github.com/RobertFlexx/Power-Sandbox-F-Edition](https://github.com/RobertFlexx/Powder-Sandbox-F-Edition)     |

### Special Editions

| Edition       | Language | Repo          |
| ------------- | -------- | ------------- |
| HolyC Edition | HolyC    | *coming soon* |

---

## Shared Features Across All Editions

Every edition, regardless of language, shares these traits:

* **Terminal UI (TUI)** simulation with a colorful grid display
* A variety of **interacting elements**: powders, liquids, solids, gases, and entities
* Rich element reactions:

  * **Powders:** sand, snow, ash, gunpowder  
  * **Liquids:** water, saltwater, oil, acid, lava, mercury  
  * **Solids:** stone, glass, wall, metal, coal, wood, plant, seaweed  
  * **Gases:** smoke, steam, hydrogen, chlorine, toxic gas  
  * **Actors:** humans, zombies, fire, lightning  

* **Physics logic:** gravity, buoyancy, temperature, conductivity, and chain reactions
* **Simple AI system:** humans move away from fire and zombies; zombies infect humans
* **Procedural growth:** plants, seaweed, and moss react to water and dirt
* **Cross-edition controls:** similar key layout across all languages

---

## Controls

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

## Edition-by-Edition Breakdown

### C++ Classic Edition

**Repo:** [https://github.com/RobertFlexx/Powder-Sandbox-Classic](https://github.com/RobertFlexx/Powder-Sandbox-Classic)  
The original terminal version that sets the behavior standard for the other editions.

**Traits:** Fast, structured, and used as the reference implementation.

**Highlights:**

* Modern **C++17 + ncurses**
* Optimized simulation loop
* Refined lava-water, fire, and AI behaviors

---

### C Fast Edition

**Repo:** [https://github.com/RobertFlexx/Powder-Sandbox-Fast-Edition](https://github.com/RobertFlexx/Powder-Sandbox-Fast-Edition)  
A C rewrite of the C++ edition with a focus on speed and simplicity.

**Traits:** Very fast and compact, with minimal abstraction.

**Highlights:**

* Straightforward C logic
* Very fast cell updates
* Portable across systems

---

### Rustbox Edition

**Repo:** [https://github.com/RobertFlexx/Rustbox-Sandbox](https://github.com/RobertFlexx/Rustbox-Sandbox)  
A Rust edition that aims to combine performance with safety.

**Traits:** Systems-level performance with strong safety guarantees.

**Highlights:**

* Written in safe **Rust**
* Modular architecture
* Zero-cost abstractions
* Optional multi-threaded simulation

---

### Objective-C Edition

**Traits:** Combines C-based low-level efficiency with object-oriented patterns.

**Highlights:**

* Uses **Objective-C runtime**
* Enables Cocoa-style object handling in a terminal simulation
* Good for experimenting with Obj-C messaging and classes

---

### Objective-C++ Edition

**Traits:** Bridges **C++ and Objective-C** for performance and OO flexibility.

**Highlights:**

* Mixes C++ templates and Objective-C classes
* Can leverage both STL and Cocoa APIs
* Suitable for hybrid projects or Mac-based terminal simulations

---

### OCaml Edition

**Traits:** Functional-first approach with strong type inference.

**Highlights:**

* Immutable data structures for safety
* Pattern matching for element updates
* Expressive functional modeling for AI and growth

---

### Kotlin JVM Edition

**Repo:** [https://github.com/RobertFlexx/Powder-Sandbox-Kotlin-Edition](https://github.com/RobertFlexx/Powder-Sandbox-Kotlin-Edition)  
A JVM-based edition built with Kotlin.

**Traits:** Concise syntax, strong typing, and good tooling support.

**Highlights:**

* JVM + JNA for TUI rendering
* Cross-platform behavior
* Good IDE and debugging experience

---

### Scala JVM Edition

**Repo:** [https://github.com/RobertFlexx/Powder-Sandbox-Scala-Edition](https://github.com/RobertFlexx/Powder-Sandbox-Scala-Edition)  
A Scala edition that leans into functional programming while still supporting OO patterns.

**Traits:** Suited to functional experimentation and DSL-style mechanics.

**Highlights:**

* Immutable data modeling
* Strong compile-time checks
* Mix of functional and OO patterns

---

### Groovy JVM Edition

**Repo:** [https://github.com/RobertFlexx/Powder-Sandbox-Groovy-Edition](https://github.com/RobertFlexx/Powder-Sandbox-Groovy-Edition)  
A dynamic edition built in Groovy for quick iteration and scripting.

**Traits:** Easy to tweak and run without a heavy compile cycle.

**Highlights:**

* Dynamic, script-style workflow
* Good for live experiments and prototyping
* Uses the same TUI approach via JNA

---

### C# / F# Edition (.NET)

**C# Repo:** [https://github.com/RobertFlexx/Powder-Sandbox-CS-Edition](https://github.com/RobertFlexx/Powder-Sandbox-CS-Edition)  
**F# Repo:** [https://github.com/RobertFlexx/Power-Sandbox-F-Edition](https://github.com/RobertFlexx/Power-Sandbox-F-Edition)  

The .NET branch of the project, combining structured OOP and functional styles.

**Traits:** Clean, high-level code with .NET's ecosystem and tooling.

**Highlights:**

* Cross-platform using **.NET 8**
* Modular OOP in C#
* High performance scalability in C#
* Beautiful mathematical aspects in F#
* Functional logic and pattern matching in F#
* Support for extended color output and sound (where available)

---

## Choosing Your Edition

| Goal                                             | Best Edition            |
| ------------------------------------------------ | ----------------------- |
| Want the original, reference implementation      | **C++ Classic Edition** |
| Want the fastest, minimal runtime                | **C Fast Edition**      |
| Want performance and memory safety               | **Rustbox Edition**     |
| Want a modern JVM-based edition                  | **Kotlin Edition**      |
| Want functional power and strong type-safety     | **Scala Edition**       |
| Want dynamic scripting and quick iteration       | **Groovy Edition**      |
| Want structured .NET OOP design                  | **C# Edition**          |
| Want functional .NET with pattern matching       | **F# Edition**          |
| Want Objective-C/Objective-C++ experience       | **Obj-C / Obj-C++**     |
| Want functional, typed experimentation           | **OCaml Edition**       |

---

## Roadmap

Planned hub improvements:

* Unified launcher CLI for all editions  
* Shared assets repository (textures, sounds, element presets)  
* Expanded AI sandbox behavior  
* Save/load support across editions  
* Inter-edition compatibility, for example loading C++ saves in Kotlin  

---

## Philosophy

Each edition is not just a direct port. It is a slightly different interpretation of the same simulation idea.  

From plain C to type-heavy Scala, from compiled Rust to interpreted Groovy, each language highlights different tradeoffs and styles while running the same kind of world.

This project is as much about comparing languages as it is about simulating sand.

---

## License

All versions are released under the **BSD 3-Clause License**.  
Check each repository for details.

---

## Author

**Robert (@RobertFlexx)**  
Architect of FerriteOS, and builder of shells, editors, and the Powder Sandbox ecosystem.

GitHub: [https://github.com/RobertFlexx](https://github.com/RobertFlexx)

---

### Final Words

Powder Sandbox is a cross-language physics sandbox.  
Pick an edition, build it, and see how your chosen language handles the same falling world.
