# Dennis Müller (SwiftedMind)

Hey 👋,

I’m Dennis, a software engineer in Germany focused on iOS + SwiftUI.  
I build Swift packages and tools that keep codebases simple, readable, and fun to work in.

## Pinned projects

### 🤖 SwiftAgent
**Native Swift SDK for building autonomous AI agents**, inspired by Apple’s FoundationModels design philosophy.

**Why it exists:** I wanted an Apple-feeling API for agent loops, tools, and structured outputs, but for other providers.

- Agent loops + tool execution handled for you
- Type-safe tools (FoundationModels-style `@Generable`)
- Adapter-agnostic design (OpenAI included; more providers can be added)
- Transcripts + token-usage tracking for debugging and product work

→ Repo: [/SwiftedMind/SwiftAgent](https://github.com/SwiftedMind/SwiftAgent)

---

### 🎨 Tessera
A Swift package that turns a single tile of SwiftUI views into an **endlessly repeating, seamlessly wrapping pattern**.

- Compose patterns from regular SwiftUI views
- Toroidal edge-wrapping for seam-free repeats
- Deterministic output via seeds (or randomize)
- Export to PNG or vector-friendly PDF

→ Repo: [/SwiftedMind/Tessera](https://github.com/SwiftedMind/Tessera)

---

### ⏳ Queryable
Treat SwiftUI presentations as **async operations**: trigger an alert/sheet/dialog and `await` the user’s answer.

- Present + await results from a single `async` call
- Works with alerts, confirmation dialogs, sheets, full-screen covers, and custom overlays
- Useful for keeping business logic out of presentation code

→ Repo: [/SwiftedMind/Queryable](https://github.com/SwiftedMind/Queryable)

---

### 🧩 Processed
A lightweight **loading-state handler for SwiftUI** that reduces repetitive “absent/loading/error/loaded” boilerplate.

- Property wrappers: `@Loadable` + `@Process`
- Also works in non-view types via support protocols
- Can be fully manual when defaults aren’t enough

→ Repo: [/SwiftedMind/Processed](https://github.com/SwiftedMind/Processed)

---

### 🔎 monocle
A read-only CLI for **Swift symbol lookup via SourceKit-LSP**, designed for coding agents (and humans) that need quick context.

- Point it at a file/line/column and get definition + signature + docs
- Stable JSON output for tooling (`--json`)
- Works great when you need to understand external packages without opening Xcode

→ Repo: [/SwiftedMind/monocle](https://github.com/SwiftedMind/monocle)
