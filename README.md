# David Moreno

**Founding Engineer at [SideKix](https://github.com/SideKix-HQ) · Mobile-First Full-Stack Engineer · End-to-End Product Development**

I am a founding engineer at SideKix. I own the product end to end, from the first design frame and architecture decision through implementation, testing, release and iteration. I start on mobile, because that is where our members and advisors live, and I build the web and backend pieces around it: Next.js on the web and full-stack Rust where the system needs to be fast, small and correct.

## What I do at SideKix
- **Mobile first:** the native iOS app in Swift and SwiftUI, built on a reducer-based architecture with every screen matched to its Figma frame.
- **Full-stack web:** Next.js (App Router, TypeScript) for web surfaces that share the same product, design language and data as the app.
- **Full-stack Rust:** axum APIs, sqlx and Postgres, with shared types and a clean, testable architecture.
- **Product end to end:** idea, design, architecture, implementation, testing, release and iteration, shipped to TestFlight and the App Store.
- **Payments and real-time:** Stripe checkout and saved cards, credits and memberships, and live voice sessions.
- **Quality and delivery:** unit tests on every reducer, snapshot tests for every screen, and separate Debug, Staging and Release environments.

## Core competencies
| Area | Stack |
|---|---|
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
