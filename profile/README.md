# Snapshot Testing

Hello, welcome to Snapshot Testing.

This is an organization on Github that houses repositories maintained by our team. In addition, you can visit our repositories at:

- [XCSnapshotTesting](https://www.github.com/snapshot-testing/xc-snapshot-testing)
- [SnapshotTesting](https://www.github.com/snapshot-testing/swift-snapshot-testing)

## Documentation

Documentation is available at [Swift Package Index](https://swiftpackageindex.com/snapshot-testing) and in each repository through the README.md file.

## Our Objective

Our goal is to simplify and streamline UI testing across the **entire Apple ecosystem** (iOS, macOS, watchOS, and tvOS) by making it effortless to validate the visual consistency of your interfaces. Inspired by the need for reliable, maintainable, and human-readable tests, **SnapshotTesting** empowers developers to catch unintended visual regressions with minimal setup—ensuring your UI remains pixel-perfect across devices, OS versions, and design iterations.

Beyond Apple platforms, **SnapshotTesting** extends its utility to **Linux and Windows environments**, enabling snapshot validation for *non-UI scenarios* where structural precision matters. For example, it allows you to snapshot complex objects like `URLRequest` (encoded as cURL commands), network payloads, or custom data models—ensuring consistency in API contracts, backend logic, or cross-platform tooling. This flexibility makes SnapshotTesting a versatile ally whether you’re validating a SwiftUI layout or debugging a network request.

We’re continuously refining the library to align with community needs and modern testing practices. At the same time, we believe visual consistency is a cornerstone of quality assurance and **strongly advocate for Apple to integrate snapshot-based validation directly into [XCUIAutomation](https://developer.apple.com/documentation/xcuiautomation)**. This would empower developers to focus on scenarios where the goal isn’t validating *user flows* (e.g., "Does button X navigate to screen Y?"), but verifying the *visual fidelity* of interfaces—ensuring layouts, fonts, colors, and states remain consistent without brittle, script-heavy tests.

We deeply value your collaboration! Whether you’re testing a UIKit view on macOS, a cURL snapshot on Linux, or proposing enhancements for Apple’s platforms, your contributions help shape a tool that serves the **entire ecosystem**. Open an issue, share feedback, or dive into the code—let’s build more resilient UIs *and* systems, together. 🖼️✨

## Platforms

Currently, Snapshot Testing is supported on all Apple platforms, Linux and Windows.

We are interested in expanding Snapshot Testing to other platforms supported by Swift. We would love your contribution to take Snapshot Testing even further.