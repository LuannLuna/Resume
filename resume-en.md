# Luann Luna

**Senior iOS Software Engineer**

São Luís, Brazil | Open to Remote (US/EU/LATAM)
English: B2 | Portuguese: Native

+55 98 98176-4061 | [luann.marques@gmail.com](mailto:luann.marques@gmail.com) | [linkedin.com/in/luannluna](https://linkedin.com/in/luannluna) | [github.com/LuannLuna](https://github.com/LuannLuna)

---

## Professional Summary

Senior iOS Engineer (7+ yrs) who cut search latency 78% (900ms → 200ms) at LTK and led war-room triage for a launch-blocking crash impacting 1.5M+ Petz users. Deep in Swift 6 strict concurrency, SwiftUI + Observation, and feature-module SPM. Lead UIKit-to-SwiftUI migrations, design-system component authorship, and Maestro/XCTest infrastructure for revenue-critical flows.

---

## Experience

### Senior iOS Software Engineer
**Hi-Tech Talents — contracted to LikeToKnow.It (LTK)** | Oct 2025 – Apr 2026

- Consolidated 3 legacy search endpoints behind a unified async/await data layer in a Swift 6 strict-concurrency codebase, cutting search response time from 900ms to 200ms (-78%) and eliminating duplicated response-parsing paths across the iOS networking stack
- Designed and shipped 3 new SwiftUI components into the LTK design system, powering the rebuilt search experience end-to-end and positioned for adoption by other feature teams
- Expanded XCTest UI coverage on the search flow and built an end-to-end Maestro suite simulating the full user journey (login → tabbar → search → creator shop), validating cross-screen behavior that unit and UI tests alone could not catch

### Senior iOS Software Engineer
**Sebratec — contracted to Petz** | Dec 2022 – Sep 2025

- Architected the loyalty program module (MVVM + Clean Architecture) and aligned rollout with a cross-functional launch campaign; shipped as the first production SwiftUI flow at Petz carrying real business logic (prior SwiftUI use was limited to force-update screens), driving 1,000+ organic sales in the first week
- Pulled into an active war-room for a production incident where the iOS app crashed on launch for all 1.5M+ users; diagnosed the root cause as a misconfigured backend remote-config value, unblocking the backend team's fix and restoring service within ~3 hours
- Triaged and fixed 12 top-occurrence crashes using Crashlytics and Instruments, contributing to a sustained ~99% crash-free session rate across the 1.5M+ user base
- Championed and led UIKit-to-SwiftUI migration across 8 screens with a 2-developer team, halving feature delivery time from 3 months to 1.5 months and establishing SwiftUI as the team standard
- Review pull requests from other iOS engineers on the team as a senior reviewer, providing architectural and code-quality feedback on ongoing feature work

### iOS Engineer (Contract)
**Turing — contracted to StubHub** | Aug 2022 – Nov 2022

- Built a new selling module for StubHub's iOS app end-to-end, delivering the seller flow as a self-contained feature area integrated with the existing app
- Expanded unit test coverage from 22% to 58% using XCTest, catching 15+ regression bugs during development and raising confidence for faster iteration cycles
- Migrated 4 high-traffic UIKit screens to SwiftUI, reducing per-screen maintenance overhead and enabling the product team to ship UI updates faster

### iOS Engineer / Digital Solutions Architect
**Capgemini** | Jul 2021 – Jun 2022

- Re-architected the authentication flow for a 15M-customer banking app: authored an RFC documenting the existing design and the proposed change, then migrated from upfront permission loading to lazy, user-interaction-driven privilege escalation in RxSwift — cutting login time from 4.2s to 1.5s and improving the first-session experience
- Embedded with the Chat squad for a month as a cross-team iOS contributor, integrating a new intelligent-assistant SDK alongside the legacy SDK to enable seamless bot-to-human handoff within the same banking app
- Mentored a junior iOS developer on Clean Architecture and SwiftUI patterns, navigating the team toward a shared architectural standard through code reviews and pair-programming sessions that improved delivery consistency
- Participated in the iOS interview loop — conducted technical interviews and evaluated candidate submissions as part of team hiring

### Mid-Level iOS Developer
**Dextra Digital** | Oct 2019 – Jun 2021

- Built geolocation-based news discovery using CoreLocation, MapKit, and GraphQL, doubling average session time from 4.2 to 8.7 minutes
- Grew test coverage from 18% to 67% using XCTest and Quick/Nimble, preventing 25+ production bugs during 18-month period
- Co-authored 15+ components in the shared UIKit design system, adopted across 3 product teams and becoming the default elements used when building new screens
- Implemented critical security fixes in Objective-C across Dafiti Group apps (Dafiti, Kanui, Tricae), including session control and cryptographic protections required for credit card compliance
- Contributed to the iOS interview loop during team growth — ran technical interviews and evaluated candidate submissions

### Junior iOS Developer
**Verité Soluções** | Jul 2018 – Sep 2019

- Built 3 interconnected iOS applications for business management using Swift and UIKit, digitizing workflows and supporting 500+ daily operations
- Integrated Firebase Performance Monitoring to baseline load times, identified bottlenecks in critical flows, and applied targeted optimizations that resulted in 45% faster load times
- Integrated CoreLocation to surface each user's nearest store and available service-scheduling slots, paired with push notifications that drove a 40% lift in daily active usage

---

## Education

**Bachelor of Computer Science** | 2011 – 2016
Federal University of Maranhão (UFMA)

---

## Technical Skills

- **Languages & Runtime:** Swift (Swift 6, strict concurrency), Swift Concurrency (async/await), Combine
- **UI & State:** SwiftUI, UIKit, Observation (@Observable), SwiftData, Accessibility (VoiceOver, Dynamic Type)
- **Architecture & Modularization:** Clean Architecture, MVVM, MVVM-C, Coordinator Pattern, SOLID, Swift Package Manager (feature modules)
- **Quality & Performance:** XCTest, Swift Testing, Maestro (end-to-end), Instruments
- **Release & Tooling:** Fastlane, Bitrise, GitHub Actions, SwiftLint, Firebase (Crashlytics, Analytics, Remote Config)
- **APIs & Platform:** GraphQL, CoreLocation, MapKit
