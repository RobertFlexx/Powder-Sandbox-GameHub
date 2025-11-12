# Powder Sandbox – Multi-Edition Hub
## All of these projects are licensed under BSD 3-Clause, see LICENSE for further details.

One sandbox, **seven** flavors.  
This repo is the central hub that connects every language edition of **Powder Sandbox**:

- C++ Classic Edition (original)
- C Fast Edition (C, speed-focused)
- Rustbox Edition (Rust)
- Kotlin Edition (JVM)
- Scala Edition (JVM)
- Groovy Edition (JVM)
- C# Edition (.NET)
- F# Edition (.NET)

All of them share the same core idea: a **terminal-based falling-sand simulator** with fire, lava, water, gases, plants, seaweed, humans, zombies, and a ridiculous amount of emergent chaos.

This hub just makes it easier to choose your poison and jump to the right repo.

---

## Repositories

### Native / Systems Editions

| Edition             | Language | Repo                                                                 |
| ------------------- | -------- | -------------------------------------------------------------------- |
| C++ Classic Edition | C++17    | https://github.com/RobertFlexx/Powder-Sandbox-Classic               |
| Fast Edition        | C        | https://github.com/RobertFlexx/Powder-Sandbox-Fast-Edition          |
| Rustbox Edition     | Rust     | https://github.com/RobertFlexx/Rustbox-Sandbox                      |

### JVM Editions

| Edition          | Language | Repo                                                                 |
| ---------------- | -------- | -------------------------------------------------------------------- |
| Kotlin Edition   | Kotlin   | https://github.com/RobertFlexx/Powder-Sandbox-Kotlin-Edition        |
| Scala Edition    | Scala    | https://github.com/RobertFlexx/Powder-Sandbox-Scala-Edition         |
| Groovy Edition   | Groovy   | https://github.com/RobertFlexx/Powder-Sandbox-Groovy-Edition        |

### .NET Editions

| Edition       | Language | Repo                                                                 |
| ------------- | -------- | -------------------------------------------------------------------- |
| C# Edition    | C#/.NET  | https://github.com/RobertFlexx/Powder-Sandbox-CS-Edition            |
| F# Edition    | F#/.NET  | https://github.com/RobertFlexx/Powder-Sandbox-F-Edition                                         |

---

## Shared Features Across All Editions

Regardless of language, the editions generally aim to offer:

* A **terminal UI (TUI)** with colored cells
* A grid of **cells** updated in a fast simulation loop
* Dozens of elements:
  * Powders: sand, snow, ash, gunpowder…
  * Liquids: water, saltwater, oil, ethanol, acid, lava, mercury…
  * Solids: stone, glass, wall, wood, metal, wire, coal, dirt, wet dirt, plants, seaweed, ice…
  * Gases: smoke, steam, gas, toxic gas, hydrogen, chlorine…
  * Actors: human, zombie, fire, lightning
* Interactions like:
  * Burning, melting, evaporating, dissolving, condensing
  * Lava cooling into stone/glass
  * Electrified water & wire conduction
  * AI behavior: humans flee zombies; zombies hunt and infect
* Similar **controls** (Arrow keys/WASD, Space to draw, E to erase, +/- brush size, M/Tab for menu, P pause, C/X clear, Q quit).

The vibe is the same. The **language/runtime and ergonomics** are what differ.

---

## Edition-by-Edition Overview

### C++ Classic Edition

**Repo:** https://github.com/RobertFlexx/Powder-Sandbox-Classic  

The original “classic” version.

**Highlights:**

* Written in **C++17** with `ncurses`
* Very fast, low-level control over memory
* Tight simulation loop and refined element interactions
* No runtime dependency beyond the C++ toolchain + ncurses
* Great reference implementation for behavior

**Best if you want:**

* The “canonical” feel of the sandbox  
* To study/modify the original logic  
* Native performance without a managed runtime

---

### Fast Edition (C Version)

**Repo:** https://github.com/RobertFlexx/Powder-Sandbox-Fast-Edition  

A **C rewrite** focused on being as lean and quick as possible.

**Highlights:**

* Written in **C** (+ `ncurses`)
* Minimal abstractions, extremely direct code paths
* Likely the **simplest** to compile and reason about at the low level
* Great for micro-optimizations and experimenting with raw performance

**Best if you want:**

* The absolute leanest native version
* To profile and hand-tune performance-critical code
* A straightforward C implementation to hack on

---

### Rustbox Edition (Rust)

**Repo:** https://github.com/RobertFlexx/Rustbox-Sandbox  

The Rust take on the sandbox.

**Highlights:**

* Written in **Rust**, typically using a terminal/box library (e.g. termbox-style)
* Memory safety + performance: Rust gives you C-like speed with compile-time safety checks
* Good foundation for building more complex features without fear of UB
* Strong type system, pattern matching, and ownership model

**Best if you want:**

* Native performance with **safety guarantees**
* To extend the sandbox in a more modern systems language
* A Rust playground for terminal graphics and cellular simulations

---

### Kotlin JVM Edition

**Repo:** https://github.com/RobertFlexx/Powder-Sandbox-Kotlin-Edition  

A modern JVM implementation using Kotlin.

**Highlights:**

* Written in **Kotlin**, running on the JVM
* Clean, concise syntax close to the C++ logic but more modern
* Very solid performance in practice — the JVM JIT does good work
* Null-safety and strong typing reduce a lot of classic footguns
* Great interop with Java, IDE tooling, profilers, etc.

**Best if you want:**

* A **modern, concise** language with strong safety
* Fast TUI sandbox on top of the JVM
* To integrate or experiment in a Kotlin-heavy ecosystem

---

### Scala JVM Edition

**Repo:** https://github.com/RobertFlexx/Powder-Sandbox-Scala-Edition  

The Scala implementation, keeping close to the original while embracing Scala features.

**Highlights:**

* Written in **Scala** on the JVM
* Strong static typing with enums/sealed types and pattern matching
* A good mix of OO and functional style for the simulation rules
* Nice for more advanced/expressive rule systems or DSL-like tweaks

**Best if you want:**

* A typed, expressive language with powerful abstractions
* To embed the sandbox in a larger Scala/JVM project
* To experiment with functional-style refactors or rule engines

---

### Groovy JVM Edition

**Repo:** https://github.com/RobertFlexx/Powder-Sandbox-Groovy-Edition  

The dynamic, scripting-friendly JVM port.

**Highlights:**

* Written in **Groovy**
* Dynamically typed, easy to tweak the rules quickly
* Uses the same basic ncurses + JNA bridge pattern as other JVM ports
* Great for prototyping new elements or interactions without fighting the type system

**Best if you want:**

* A “**hack it live**” style edition for quick experiments
* Script-like flexibility with JVM interop
* To try wild mechanics without a heavy compile/edit cycle

---

### C# Edition (.NET)

**Repo:** https://github.com/RobertFlexx/Powder-Sandbox-CS-Edition  

A more modernized take in C#/.NET.

**Highlights:**

* Written in **C#** (typically targeting .NET 8+)
* Cleaner high-level structure, easier to extend with classes & components
* Uses .NET-style console rendering and features (and can support extras like simple audio)
* Very approachable for C#/Unity/.NET developers

**Best if you want:**

* A sandbox that feels at home in the .NET ecosystem
* Easier extensibility and refactoring via classes & interfaces
* To integrate with other .NET tooling, libraries, or engines

---

## Which Edition Should I Try?

Short version:

- **Want the “real original” feel?**  
  → C++ Classic Edition

- **Want the leanest, no-nonsense native build?**  
  → Fast Edition (C)

- **Want safety *and* speed with modern systems design?**  
  → Rustbox Edition

- **Want a modern JVM language that’s fast & clean?**  
  → Kotlin Edition

- **Already love Scala or want more functional patterns?**  
  → Scala Edition

- **Want maximum hackability and scripting vibes?**  
  → Groovy Edition

- **Live in the .NET world and like structured C# / F# code?**  
  → C# / F# Editions

You really can’t go “wrong” — the differences are mostly in **language, tooling, and ergonomics**, not in the core sandbox spirit.

---

## License

Each repo has its own LICENSE file (typically **BSD 3-Clause** or similar).  
Check the individual edition’s repository for exact licensing details.

---

## Author

**Robert (@RobertFlexx)**  
Creator of FerriteOS, shells, editors, and a frankly suspicious number of terminal toys (im him).

GitHub: https://github.com/RobertFlexx
