# Awesome iOS Development [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of the best libraries, frameworks, tools, and resources for modern iOS development with Swift and SwiftUI in 2026. Covering Swift Concurrency, SwiftData, UIKit, Xcode, testing, architecture, and the full iOS toolchain.

<div align="center">

<a href="https://extensionbooster.net">
  <img src="https://extensionbooster.net/logo.webp" alt="Extension Booster" width="150" />
</a>

<h3>💎 &nbsp;DIAMOND SPONSOR&nbsp; 💎</h3>

<p>
  <b><a href="https://extensionbooster.net">Extension Booster</a></b><br/>
  <sub>The growth platform for extension and app developers</sub>
</p>

<p>
  <sub>⭐ Real reviews &nbsp;·&nbsp; 📊 Cross-marketplace analytics (Chrome · Edge · Android · Workspace) &nbsp;·&nbsp; 🔁 Manifest V2 to V3 converter</sub>
</p>

<a href="https://extensionbooster.net"><b>🚀 Start free at extensionbooster.net →</b></a>

</div>

## Contents

- [Official Resources](#official-resources)
- [Languages](#languages)
- [UI and SwiftUI](#ui-and-swiftui)
- [Architecture](#architecture)
- [Dependency Injection](#dependency-injection)
- [Networking](#networking)
- [Concurrency and Reactive](#concurrency-and-reactive)
- [Data and Persistence](#data-and-persistence)
- [Image Loading](#image-loading)
- [Navigation and Routing](#navigation-and-routing)
- [Testing](#testing)
- [Dependency Management](#dependency-management)
- [Build and Tooling](#build-and-tooling)
- [CI/CD and Distribution](#cicd-and-distribution)
- [Analytics and Crash Reporting](#analytics-and-crash-reporting)
- [Sample Open-Source Apps](#sample-open-source-apps)
- [Cross-Platform](#cross-platform)
- [Communities, Newsletters, and Podcasts](#communities-newsletters-and-podcasts)
- [Tools and Utilities](#tools-and-utilities)
- [Contributing](#contributing)
- [License](#license)

---

## Official Resources

- [Apple Developer](https://developer.apple.com) - Central hub for Apple platform documentation, tools, and program membership.
- [Swift.org](https://www.swift.org) - Official home of the Swift open-source project, including downloads, proposals, and package resources.
- [Apple Developer Documentation](https://developer.apple.com/documentation) - Comprehensive API reference and conceptual guides for all Apple frameworks.
- [WWDC Videos](https://developer.apple.com/videos/) - Annual conference sessions covering new APIs, frameworks, and platform features.
- [Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/) - Apple's authoritative design guidance for building consistent, quality apps.
- [Xcode](https://developer.apple.com/xcode/) - Apple's official IDE for building apps across all Apple platforms.
- [Swift Forums](https://forums.swift.org) - Official discussion forum for Swift language evolution, packages, and community announcements.
- [Apple Design Resources](https://developer.apple.com/design/resources/) - Official UI kits, templates, and SF Symbols for designing Apple platform apps.
- [TestFlight](https://developer.apple.com/testflight/) - Apple's official beta testing service for distributing pre-release builds.

## Languages

- [Swift](https://github.com/swiftlang/swift) - The Swift programming language, an open-source general-purpose language for Apple platforms and beyond.
- [Swift Evolution](https://www.swift.org/swift-evolution/) - Tracks active proposals and accepted changes to the Swift language.
- [swift-evolution (GitHub)](https://github.com/swiftlang/swift-evolution) - The proposal repository for Swift language changes, used to follow and comment on upcoming features.
- [Swift Package Index](https://swiftpackageindex.com) - The community index for discovering, comparing, and evaluating Swift packages, sponsored by Apple.
- [swift-algorithms](https://github.com/apple/swift-algorithms) - Apple's open-source package of sequence and collection algorithms for Swift.
- [swift-collections](https://github.com/apple/swift-collections) - Apple's package providing high-performance data structures including OrderedDictionary, Deque, and TreeSet.
- [swift-async-algorithms](https://github.com/apple/swift-async-algorithms) - Apple's package of asynchronous sequence algorithms including debounce, throttle, merge, and combineLatest.
- [Swift Standard Library Docs](https://developer.apple.com/documentation/swift/swift-standard-library) - Reference documentation for Swift's built-in types, protocols, and global functions.

## UI and SwiftUI

- [SwiftUI](https://developer.apple.com/xcode/swiftui/) - Apple's declarative UI framework for building apps across all Apple platforms with Swift.
- [UIKit](https://developer.apple.com/documentation/uikit) - Apple's event-driven, imperative UI framework for iOS and iPadOS apps.
- [SnapKit](https://github.com/SnapKit/SnapKit) - A concise Auto Layout DSL for Swift that dramatically reduces boilerplate constraint code.
- [SwiftUIX](https://github.com/SwiftUIX/SwiftUIX) - Extends SwiftUI with missing components including TextView, ActivityIndicator, and additional layout types.
- [Pow](https://github.com/EmergeTools/Pow) - A collection of SwiftUI transition and change effects that trigger on value updates, from EmergeTools.
- [Lottie for iOS](https://github.com/airbnb/lottie-ios) - Airbnb's library for rendering After Effects vector animations natively on iOS with SwiftUI support.
- [swiftui-introspect](https://github.com/siteline/swiftui-introspect) - Introspect underlying UIKit and AppKit components from SwiftUI views without private APIs.
- [Charts](https://developer.apple.com/documentation/charts) - Apple's native Swift Charts framework for building beautiful, accessible data visualizations in SwiftUI.
- [Shimmer](https://github.com/markiv/Shimmer) - A super-light SwiftUI modifier for adding a shimmering effect to any view.
- [ConfettiSwiftUI](https://github.com/simibac/ConfettiSwiftUI) - Swift package for adding configurable confetti animations to SwiftUI views.

## Architecture

- [The Composable Architecture (TCA)](https://github.com/pointfreeco/swift-composable-architecture) - Point-Free's library for building apps in a consistent, testable, and composable way using reducers and effects.
- [MVVM with SwiftUI](https://developer.apple.com/tutorials/swiftui) - Apple's official SwiftUI tutorials demonstrating MVVM patterns with ObservableObject and the Observation framework.
- [clean-architecture-swiftui](https://github.com/nalexn/clean-architecture-swiftui) - A sample app demonstrating Clean Architecture with SwiftData, networking, DI, and unit testing in SwiftUI.
- [Point-Free Episodes](https://www.pointfree.co) - Video series by Brandon Williams and Stephen Celis covering advanced Swift, functional programming, and TCA in depth.
- [swift-dependencies](https://github.com/pointfreeco/swift-dependencies) - Point-Free's dependency management library inspired by SwiftUI's environment, enabling controlled side effects.
- [awesome-ios-architecture](https://github.com/onmyway133/awesome-ios-architecture) - A curated list of iOS architecture resources, patterns, and example projects.

## Dependency Injection

- [Factory](https://github.com/hmlongco/Factory) - A modern, compile-time safe, container-based dependency injection framework for Swift and SwiftUI.
- [swift-dependencies](https://github.com/pointfreeco/swift-dependencies) - A dependency management library for controlling and overriding dependencies in Swift apps and tests.
- [Swinject](https://github.com/Swinject/Swinject) - A lightweight, reflection-based dependency injection framework for Swift supporting iOS, macOS, and Linux.
- [Needle](https://github.com/uber/needle) - Uber's compile-time safe dependency injection framework for Swift, emphasizing hierarchical scoping.

## Networking

- [Alamofire](https://github.com/Alamofire/Alamofire) - An elegant, full-featured HTTP networking library for Swift covering request building, response serialization, and authentication.
- [Moya](https://github.com/Moya/Moya) - A network abstraction layer built on top of Alamofire that enforces typed, testable API definitions.
- [Apollo iOS](https://github.com/apollographql/apollo-ios) - A strongly-typed GraphQL client for iOS that generates Swift types from your schema and queries.
- [Get](https://github.com/kean/Get) - A lean async/await web API client built on URLSession with minimal abstractions and full URLSession access.
- [URLSession](https://developer.apple.com/documentation/foundation/urlsession) - Apple's native HTTP networking API, fully supported with async/await in Swift Concurrency.
- [Pulse](https://github.com/kean/Pulse) - A structured logging system for Apple platforms with a SwiftUI-based network inspector built in.

## Concurrency and Reactive

- [Swift Concurrency](https://developer.apple.com/documentation/swift/concurrency) - Apple's native async/await and actor model for writing safe, performant concurrent Swift code.
- [Combine](https://developer.apple.com/documentation/combine) - Apple's declarative Swift framework for processing values over time using publishers and subscribers.
- [swift-async-algorithms](https://github.com/apple/swift-async-algorithms) - Async sequence algorithms including zip, merge, debounce, throttle, and more, from Apple.
- [RxSwift](https://github.com/ReactiveX/RxSwift) - The ReactiveX extension for Swift, providing a full observable sequence library for event-driven programming.
- [AsyncAlgorithms (Docs)](https://www.swift.org/blog/swift-async-algorithms/) - The official Swift.org announcement and overview of the AsyncAlgorithms package.

## Data and Persistence

- [SwiftData](https://developer.apple.com/documentation/swiftdata) - Apple's modern persistence framework using Swift macros, replacing Core Data as the default for greenfield SwiftUI apps.
- [Core Data](https://developer.apple.com/documentation/coredata) - Apple's mature object graph and persistence framework, still recommended for complex multi-user sync scenarios.
- [GRDB.swift](https://github.com/groue/GRDB.swift) - A SQLite toolkit with SQL generation, Combine publishers, and robust concurrency, well-suited for modern Swift apps.
- [SharingGRDB](https://github.com/pointfreeco/sharing-grdb) - Point-Free's library integrating GRDB with their Sharing library for reactive, observable database access in SwiftUI.
- [Boutique](https://github.com/mergesort/Boutique) - A magical persistence library built on Bodega, giving you a persistent array with zero boilerplate via property wrappers.
- [CoreStore](https://github.com/JohnEstropia/CoreStore) - A type-safe, elegant Swift wrapper around Core Data with improved migrations and observation support.

## Image Loading

- [Kingfisher](https://github.com/onevcat/Kingfisher) - A pure-Swift, feature-rich library for asynchronous image downloading, caching, and processing.
- [Nuke](https://github.com/kean/Nuke) - A high-performance image loading framework with a small footprint, pipeline architecture, and SwiftUI support.
- [SDWebImage](https://github.com/SDWebImage/SDWebImage) - A long-established asynchronous image loading library with a broad format support and SwiftUI integration.
- [AsyncImage](https://developer.apple.com/documentation/swiftui/asyncimage) - Apple's native SwiftUI view for asynchronously loading and displaying remote images, available from iOS 15.

## Navigation and Routing

- [NavigationStack](https://developer.apple.com/documentation/swiftui/navigationstack) - Apple's native stack-based navigation API introduced in iOS 16, with programmatic deep-link support.
- [swift-navigation](https://github.com/pointfreeco/swift-navigation) - Point-Free's navigation library bringing type-safe, state-driven navigation to SwiftUI, UIKit, and beyond.
- [FlowStacks](https://github.com/johnpatrickmorgan/FlowStacks) - Hoists SwiftUI navigation and presentation state into a coordinator, supporting push, sheet, and full-screen flows.
- [TCACoordinators](https://github.com/johnpatrickmorgan/TCACoordinators) - Coordinator-pattern navigation for apps built with The Composable Architecture.
- [SwiftfulRouting](https://github.com/SwiftfulThinking/SwiftfulRouting) - Programmatic, protocol-based navigation for SwiftUI using a RouterView that wraps NavigationStack.

## Testing

- [Swift Testing](https://developer.apple.com/xcode/swift-testing/) - Apple's modern testing framework using macros for expressive, concise, and parameterized tests, built into Xcode.
- [XCTest](https://developer.apple.com/documentation/xctest) - Apple's foundational framework for unit, UI, and performance testing, integrated into Xcode.
- [Quick](https://github.com/Quick/Quick) - A BDD-style testing framework for Swift and Objective-C with readable describe/it/expect syntax.
- [Nimble](https://github.com/Quick/Nimble) - An expressive matcher framework that pairs with Quick for fluent assertions in Swift and Objective-C tests.
- [ViewInspector](https://github.com/nalexn/ViewInspector) - A framework for unit testing SwiftUI views by inspecting their structure and accessing stored state.
- [swift-snapshot-testing](https://github.com/pointfreeco/swift-snapshot-testing) - Point-Free's snapshot testing library supporting views, strings, data, and URL requests across all Apple platforms.
- [Maestro](https://github.com/mobile-dev-inc/maestro) - A declarative, YAML-based mobile UI testing framework that runs on both iOS and Android without code changes.

## Dependency Management

- [Swift Package Manager](https://www.swift.org/documentation/package-manager/) - Apple's built-in, first-party dependency manager for Swift, fully integrated into Xcode and recommended for new projects.
- [CocoaPods](https://cocoapods.org) - The long-established Ruby-based dependency manager for Apple platforms; trunk transitioning to read-only in late 2026.
- [Carthage](https://github.com/Carthage/Carthage) - A decentralized dependency manager that builds framework binaries without modifying your Xcode project.

## Build and Tooling

- [Tuist](https://github.com/tuist/tuist) - A Swift-based project generation and build caching tool that scales modular iOS projects with type-safe configuration.
- [XcodeGen](https://github.com/yonaskolb/XcodeGen) - Generates Xcode project files from a YAML specification, eliminating merge conflicts in `.xcodeproj` files.
- [Fastlane](https://github.com/fastlane/fastlane) - The leading open-source automation platform for building, testing, and releasing iOS apps.
- [SwiftLint](https://github.com/realm/SwiftLint) - A tool for enforcing Swift code style and conventions, with hundreds of configurable rules and Xcode integration.
- [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) - An opinionated code formatter for Swift source files, fully configurable and runnable as a build phase.
- [Sourcery](https://github.com/krzysztofzablocki/Sourcery) - A meta-programming tool for Swift that generates boilerplate code from annotations using Stencil or Swift templates.
- [periphery](https://github.com/peripheryapp/periphery) - Detects unused Swift declarations to help reduce code bloat and keep your codebase clean.
- [BuildBuddy / Bazel for iOS](https://github.com/buildbuddy-io/bazel-ios-tutorial) - Resources for adopting Bazel-based builds for large-scale iOS projects requiring extreme build performance.

## CI/CD and Distribution

- [Xcode Cloud](https://developer.apple.com/xcode-cloud/) - Apple's first-party cloud CI/CD service integrated into Xcode, with 25 free compute hours per month.
- [Fastlane](https://fastlane.tools) - Automates code signing, building, testing, screenshots, and App Store delivery with a Fastfile DSL.
- [Bitrise](https://bitrise.io) - A mobile-first CI/CD platform with M4 Pro Apple Silicon runners, deep Xcode integration, and a free tier.
- [GitHub Actions for iOS](https://docs.github.com/en/actions) - General-purpose CI with macOS runners for iOS builds; flexible but macOS minutes carry a 10x pricing multiplier.
- [TestFlight](https://developer.apple.com/testflight/) - Apple's official service for distributing beta builds to up to 10,000 external testers.
- [fastlane match](https://docs.fastlane.tools/actions/match/) - Synchronizes certificates and provisioning profiles across teams using an encrypted Git repository.

## Analytics and Crash Reporting

- [Sentry for iOS](https://docs.sentry.io/platforms/apple/) - Open-source error tracking with breadcrumbs, session replay, performance monitoring, and deep stack traces.
- [Firebase Crashlytics](https://firebase.google.com/products/crashlytics) - Google's lightweight, real-time crash reporter with automated alerts and Xcode symbolication.
- [TelemetryDeck](https://telemetrydeck.com) - A privacy-first analytics SDK that tracks anonymous usage signals with no PII collected, GDPR-compliant by design.
- [Firebase Analytics](https://firebase.google.com/docs/analytics) - Google's free event-based analytics SDK providing user behavior, funnel, and audience data for iOS apps.

## Sample Open-Source Apps

- [isowords](https://github.com/pointfreeco/isowords) - A word search game built in SwiftUI and The Composable Architecture, showing production-level TCA usage.
- [IceCubesApp](https://github.com/Dimillian/IceCubesApp) - A fully-featured SwiftUI Mastodon client running on iOS, macOS, iPadOS, and visionOS.
- [NetNewsWire](https://github.com/Ranchero-Software/NetNewsWire) - A free, open-source RSS/Atom reader for iOS and macOS built with Swift and native Apple frameworks.
- [wikipedia-ios](https://github.com/wikimedia/wikipedia-ios) - The official Wikipedia iOS app, a mature Swift codebase demonstrating large-scale app architecture.
- [mastodon-ios](https://github.com/mastodon/mastodon-ios) - The official Mastodon iOS app, built entirely in Swift with UIKit.
- [Firefox for iOS](https://github.com/mozilla-mobile/firefox-ios) - Mozilla's open-source Firefox browser for iOS, a large Swift codebase with extensive testing.
- [Telegram iOS](https://github.com/TelegramMessenger/Telegram-iOS) - The open-source Telegram iOS client, useful for studying high-performance UI and custom rendering techniques.

## Cross-Platform

- [Kotlin Multiplatform (KMP)](https://kotlinlang.org/docs/multiplatform.html) - JetBrains' technology for sharing business logic across iOS and Android while keeping native UI on each platform.
- [Compose Multiplatform](https://www.jetbrains.com/compose-multiplatform/) - JetBrains' Kotlin-based UI framework for sharing UI code across iOS, Android, desktop, and web.
- [React Native](https://reactnative.dev) - Meta's framework for building iOS and Android apps from a single JavaScript/TypeScript codebase.
- [Flutter](https://flutter.dev) - Google's UI toolkit for building natively compiled apps from a single Dart codebase across iOS, Android, and web.
- [Swift on Server](https://www.swift.org/server/) - Resources for using Swift in server-side contexts, enabling code sharing between iOS clients and Swift backends.

## Communities, Newsletters, and Podcasts

- [iOS Dev Weekly](https://iosdevweekly.com) - Weekly newsletter curating the best iOS development links, articles, and tools, publishing since 2011.
- [Swift by Sundell](https://www.swiftbysundell.com) - Articles, podcasts, and tips by John Sundell covering Swift, SwiftUI, and iOS app architecture.
- [SwiftLee](https://www.avanderlee.com) - Weekly blog by Antoine van der Lee covering Swift, Xcode, SwiftUI, and Apple platform best practices.
- [Hacking with Swift](https://www.hackingwithswift.com) - Paul Hudson's comprehensive learning resource with free tutorials, 100 Days of SwiftUI, and an active forum.
- [Point-Free](https://www.pointfree.co) - Video series by Brandon Williams and Stephen Celis on functional programming and advanced Swift patterns.
- [r/iOSProgramming](https://www.reddit.com/r/iOSProgramming/) - A Reddit community for iOS developers sharing projects, questions, and discussions.
- [Swift Forums](https://forums.swift.org) - The official discussion board for Swift evolution, packages, and the open-source Swift community.
- [Donny Wals](https://www.donnywals.com) - Practical articles on Swift Concurrency, SwiftData, and modern iOS development patterns.
- [Emerge Tools Blog](https://www.emergetools.com/blog) - Engineering blog covering iOS performance, binary size reduction, and SwiftUI internals.

## Tools and Utilities

- [SF Symbols](https://developer.apple.com/sf-symbols/) - Apple's library of over 7,000 icons designed to integrate with San Francisco, available in nine weights and multiple scales.
- [Proxyman](https://proxyman.io) - A native macOS app for intercepting and inspecting HTTP/HTTPS traffic from iOS simulators and physical devices.
- [Reveal](https://revealapp.com) - A runtime UI inspection tool for iOS and tvOS that provides 3D view hierarchy visualization and live editing.
- [Instruments](https://developer.apple.com/documentation/xcode/improving-your-app-s-performance) - Apple's built-in profiling tool in Xcode for analyzing CPU, memory, energy, and rendering performance.
- [RocketSim](https://www.rocketsim.app) - An Xcode Simulator extension adding recording, deeplinks, push notifications, and location simulation.
- [Swift Package Index](https://swiftpackageindex.com) - Discover, compare, and evaluate Swift packages with compatibility matrices and hosted documentation.
- [ControlRoom](https://github.com/twostraws/ControlRoom) - A macOS GUI for controlling the Xcode Simulator, including appearance, location, and push notification testing.
- [OpenSim](https://github.com/luosheng/OpenSim) - A macOS menu bar utility to browse and manage iOS Simulator apps and their data containers.

---

## Contributing

Contributions welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on adding entries, formatting, and quality standards.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Released under the [MIT License](LICENSE). Copyright (c) 2026 Quang Phan.

---

<p align="center">
  <sub>Curated for developers · From the team behind <a href="https://extensionbooster.net"><b>Extension Booster</b></a>, the growth platform for extension and app developers.</sub>
</p>
