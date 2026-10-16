# David Moreno

**Founding Engineer at [SideKix](https://github.com/SideKix-HQ) · Mobile-First Full-Stack Engineer · End-to-End Product Development**

I am a founding engineer at SideKix, working with the mobile team across Android and iOS. My main area is native Android in Kotlin and Jetpack Compose. We build as one team: shared architecture decisions, one design language and consistent behavior on both platforms, from the first design frame through implementation, testing, release and iteration. Mobile comes first because that is where our members and advisors live, and I build the web and backend pieces around it: Next.js on the web and full-stack Rust where the system needs to be fast, small and correct.

## Core competencies
| Area | Stack |
|---|---|
| **Mobile: Android** | Kotlin, Jetpack Compose, MVVM and clean architecture, coroutines and StateFlow, Dagger/Hilt, Room, Ktor, Material Design 3 |
| **Mobile: iOS** | Swift, SwiftUI, The Composable Architecture (TCA), Swift Concurrency, Swift Package Manager, Xcode |
| **Web and frontend** | Next.js, React, TypeScript, Tailwind CSS |
| **Rust** | Rust, axum, sqlx, Postgres |
| **Payments** | Stripe (PaymentSheet, saved cards), in-app purchases |
| **Real-time and auth** | LiveKit voice, Google Sign-In, Sign in with Apple |
| **Testing** | Swift Testing, TCA `TestStore`, snapshot testing, XCTest for UI |
| **Delivery** | xcconfig-based environments, TestFlight, Vercel preview and production deployments |
| **Design** | Figma-driven design system, accessibility and Dynamic Type |

## How I build
- **Reducer-based state:** every feature is a reducer with explicit state and actions, side effects live in dependency clients, and navigation is driven by state. Behavior is covered by tests that never touch the network.
- **One design system:** screens are built from reusable, store-free components that mirror Figma, so a style is defined once and used everywhere.
- **Environments you can trust:** the build configuration decides the backend, so a Debug build can never silently reach production.
- **Small, reviewable changes:** feature branches, pull requests into `staging`, and promotion to `release` through QA on TestFlight.

## Product areas
- **Advisor sessions:** discovery, booking, rescheduling and cancellation, with session chat for members and advisors.
- **Live voice:** a real-time voice assistant built on LiveKit.
- **Events and content:** advisor-hosted events with ticketing and check-in, plus advisor content.
- **Memberships and credits:** purchase flows, saved cards and credit balances.
- **Advisor wallet:** earnings and payout history.

## Connect
| | |
|---|---|
| **SideKix on GitHub** | [SideKix-HQ](https://github.com/SideKix-HQ) |
| **GitHub** | [DavidMorenoSidekix](https://github.com/DavidMorenoSidekix) |
