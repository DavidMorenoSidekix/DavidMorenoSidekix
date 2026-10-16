# David Moreno

**Founding Engineer at [SideKix](https://github.com/SideKix-HQ) · Mobile-First Full-Stack Engineer · End-to-End Product Development**

I am a founding engineer at SideKix, working with the mobile team across Android and iOS. My main area is native Android in Kotlin and Jetpack Compose, alongside Kotlin Multiplatform and Flutter. We build as one team: shared architecture decisions, one design language and consistent behavior on both platforms.

## Core competencies
| Area | Stack |
|---|---|
| **Mobile: Android** | Kotlin, Jetpack Compose, MVVM and clean architecture, coroutines and StateFlow, Dagger/Hilt, Room, Ktor, Material Design 3 |
| **Mobile: cross-platform** | Kotlin Multiplatform, Flutter, Dart |
| **Mobile: iOS** | Swift, SwiftUI, The Composable Architecture (TCA), Swift Concurrency, Swift Package Manager, Xcode |
| **Web and frontend** | Next.js, React, TypeScript, Tailwind CSS |
| **Rust** | Rust, axum, sqlx, Postgres |
| **Payments** | Stripe (PaymentSheet, saved cards), in-app purchases |
| **Real-time and auth** | LiveKit voice, Google Sign-In, Sign in with Apple |
| **Testing** | Swift Testing, TCA `TestStore`, snapshot testing, XCTest for UI |
| **Delivery** | xcconfig-based environments, TestFlight, Vercel preview and production deployments |
| **Design** | Figma-driven design system, accessibility and Dynamic Type |

## How I build
I build with Claude Code, and the setup is designed so the AI follows the same rules a senior engineer on the team would.

- **Layered project rules:** a committed `CLAUDE.md` holds the shared architecture, design system and testing rules for the whole team. A personal, untracked `CLAUDE.local.md` adds stricter day-to-day rules and wins on conflicts, so every session starts with the rules already loaded.
- **Architecture as written rules:** reducer-based state with explicit actions, side effects only in dependency clients, one-way layering from view to system, and no business logic in views. The rules say what to do and what never to do, so a change that breaks the pattern is caught before it is written.
- **Specialized agents and skills:** a visual-verification agent and a snapshot skill render each changed screen and compare it with the design, so UI work is checked against Figma and not by eye.
- **Tests as the gate:** every behavior change ships with a reducer test that never touches the network, plus snapshot tests for screens. A change is not done until the tests and the diff review against the rules both pass.
- **Audit and document, don't drive-by fix:** problems found during a task are written down in an audit document and ticketed. They are not refactored unasked, which keeps every pull request small and reviewable.
- **Guardrails around the repo:** a fixed git identity per project, feature branches only, pull requests into `staging`, promotion to `release` through QA, and no secrets or environment values in source.
- **Ask before changing the foundation:** new dependencies, new patterns and new folders need a decision from the team first.

## Connect
| | |
|---|---|
| **SideKix on GitHub** | [SideKix-HQ](https://github.com/SideKix-HQ) |
| **GitHub** | [DavidMorenoSidekix](https://github.com/DavidMorenoSidekix) |
