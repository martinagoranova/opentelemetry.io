---
title: Development
cSpell:ignore: grpcio intellij libcurl libprotobuf nlohmann openssl protoc
---
Development for this demo requires tooling in several programming languages. The minimum versions are listed below where applicable. Using the latest versions is recommended.

## Generate Protobuf Files Locally 
You can generate protobuf files locally (without Docker) to make generated code available to IDEs such as IntelliJ or VS Code.
1. Clone the [OpenTelemetry Demo GitHub repository](https://github.com/open-telemetry/opentelemetry-demo) to your local machine.
2. (Optional) Run `npm install` in the `src/frontend` directory to install the frontend dependencies required for protobuf generation.
3. Run `make generate-protobuf` to generate protobuf files for all services.

## Development Tooling Requirements

| Language / Environment | Required Tools & Minimum Versions |
| :--- | :--- |
| **.NET** | .NET 8.0+ |
| **C++** | build-essential, cmake, libcurl4-openssl-dev, libprotobuf-dev, nlohmann-json3-dev, pkg-config, protobuf-compiler |
| **Go** | Go 1.19+, protoc-gen-go, protoc-gen-go-grpc |
| **Java** | JDK 17+, Gradle 7+ |
| **JavaScript** | Node.js 16+ |
| **PHP** | PHP 8.1+, Composer 2.4+ |
| **Python** | Python 3.10, grpcio-tools 1.48+ |
| **Ruby** | Ruby 3.1+ |
| **Rust** | Rust 1.61+, protoc 3.21+, protobuf-dev |
