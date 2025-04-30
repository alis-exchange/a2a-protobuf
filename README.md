# Protobufs for Agent2Agent (A2A) Protocol

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) <!-- Choose your license and update badge -->
[![Community Project](https://img.shields.io/badge/Project-Community_Driven-brightgreen?style=flat-square)]() <!-- Optional: Badge indicating community effort -->


## Overview

This repository provides Protobuf (`.proto`) definitions derived from the official [Agent2Agent (A2A)](https://github.com/google/A2A/tree/main) protocol. The official A2A protocol specifications are defined using JSON Schema. This project aims to offer an alternative representation using Protobufs for potential benefits in performance, type safety, and cross-language code generation.

This is not an official A2A Protocol project. Definitions are not guaranteed to be accurate, complete or up-to-date and may change based on feedback and updates to the official protocol.

For official definitions and documentation, please refer to the following:

* Website: https://google.github.io/A2A

* GitHub repository: https://github.com/google/A2A

* Blog: https://developers.googleblog.com/en/a2a-a-new-era-of-agent-interoperability/

## Purpose

The primary goals of this project are:

1.  **Provide A2A Protobuf Definitions:** Offer Protobuf definitions that correspond to the official A2A Protocol specification.
2.  **Facilitate Integration:** Enable developers who prefer or require Protobufs to interact with / build systems using the A2A protocol.
3.  **Collaboration:** Create a space for discussion, feedback, and improvement of the use of Protobufs for developing A2A-compliant systems.

## Why Protobuf for A2A?

Using Protobufs offers several potential advantages:

*   **Efficiency:** Protobuf serialization is often more compact and performant than JSON.
*   **Type Safety:** Protobuf definitions provide strong typing, which can be checked at compile time in many languages.
*   **Code Generation:** Protobuf compilers can automatically generate data access classes in various programming languages (Java, Python, C++, Go, C#, etc.).

## Project Structure

```
a2a-protobuf/
├── a2a/
│   └── v1/         
│       └── service.proto   # A2A Protocol Protobuf definitions
├── LICENSE                 # Project license
└── README.md               # This file
```

## Contributing

Contributions and suggestions are welcome! For bugs, suggestions, discussions or improvements, please open an issue detailing the topic or submit a pull request.

## Potentially useful resources

* [gRPC](https://grpc.io)
* [Google AIPs](https://google.aip.dev/1)

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
