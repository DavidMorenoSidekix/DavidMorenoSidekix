# David Moreno

**Founding Engineer at [SideKix](https://github.com/SideKix-HQ) · Mobile-First Full-Stack Engineer · End-to-End Product Development · Applied AI**

I am a founding engineer at SideKix, part of the development team across Android, Flutter and iOS. My depth is in Rust, Kotlin with Jetpack Compose, Kotlin Multiplatform and Dart (Flutter). I'm backed by clean architecture, strong testing and audit habits, a deep training in context engineering and a solid agentic AI professional development background using Claude Code.

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
I build with Claude Code, and the setup is designed so the AI follows the same rules a senior engineer on the team would, on every platform.

- **Layered project rules:** each repository has a committed `CLAUDE.md` with the shared architecture, design system and testing rules for the team. A personal, untracked `CLAUDE.local.md` adds stricter day-to-day rules and wins on conflicts, so every session starts with the rules already loaded.
- **Architecture as written rules:** unidirectional state, clear layers from UI to data, side effects isolated behind clients, and no business logic in views. The rules say what to do and what never to do, so a change that breaks the pattern is caught before it is written.
- **Specialized agents and skills:** agents and skills handle repeatable work such as visual verification, rendering each changed screen and comparing it with the design, so UI work is checked against Figma and not by eye.
- **Tests as the gate:** every behavior change ships with tests that never touch the network, and screens are covered by visual tests. A change is not done until the tests pass and the diff has been reviewed against the rules.
- **Audit and document, don't drive-by fix:** problems found during a task are written down in an audit document and ticketed. They are not refactored unasked, which keeps every pull request small and reviewable.
- **Guardrails around the repo:** a fixed git identity per project, feature branches only, pull requests into `staging`, promotion to `release` through QA, and no secrets or environment values in source.
- **Ask before changing the foundation:** new dependencies, new patterns and new folders need a decision from the team first.

## Studies and certifications
### Currently studying
| Program | Institution | Period |
|---|---|---|
| Specialization in Enterprise Artificial Intelligence | Costa Rica Institute of Technology (TEC) | Sep 2026 to Feb 2027 |
| Master of Science in Information Technology (MSIT) | University of the People | In progress |

### Education
- Baccalaureate in Business Informatics, University of Costa Rica (UCR), 2018

### Certifications and continuous learning
| Year | Course |
|---|---|
| **2026** | Building Industry-Level Multiplatform Apps With Kotlin Multiplatform (PL Coding GmbH) |
| | Ultimate Compose Multiplatform: Android/iOS + Testing (Udemy) |
| **2025** | Technical Agents of Change: Agentic Coding and Context Engineering (Chipp) |
| **2020** | Complete Kotlin Development Masterclass |
| | Mastering Kotlin: Null Safety |
| | Flutter and Firebase |
| **2019** | Firebase and Firestore Masterclass |
| | Android Jetpack Masterclass (Kotlin) |
| | Flutter and Dart (59 hrs) |
| | Xamarin Forms 4.0 with ASP.NET Core API |
| **2016** | Microsoft Xamarin Basic Diploma |

## Connect
| | |
|---|---|
| **SideKix on GitHub** | [SideKix-HQ](https://github.com/SideKix-HQ) |
| **GitHub** | [DavidMorenoSidekix](https://github.com/DavidMorenoSidekix) |
| **LinkedIn** | [david-moreno-533bb5155](https://www.linkedin.com/in/david-moreno-533bb5155/) |
| **Founder** | [Artificialss.ai](https://artificialss.ai/) |
