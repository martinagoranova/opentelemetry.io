---
title: OpenTelemetry Demo Docs
linkTitle: Demo
cascade:
  repo: https://github.com/open-telemetry/opentelemetry-demo
weight: 180
---

The OpenTelemetry Demo is a microservice-based distributed system designed to demonstrate OpenTelemetry in a near real-world environment. 

This project serves three main purposes:
* **Demonstration:** Provides a realistic example of instrumentation and observability in action.
* **Integration:** Builds a base for vendors and tool authors to test their OpenTelemetry integrations.
* **Testing:** Creates a living environment for contributors to validate new versions of the API, SDK, and components.

To explore the demo or customize it for your needs, follow the technical workflow below:

### 1. Getting Started & Installation
Before running the application, review the environment prerequisites and installation steps.
* **[Requirements](requirements/)** – System, application, and telemetry specifications.
* **[Docker Deployment](docker-deployment/)** – Steps for quick local setup.
* **[Kubernetes Deployment](kubernetes-deployment/)** – Steps for cloud and cluster deployments.

### 2. Architecture & Design
Understand how the services interact and how telemetry data flows through the system.
* **[Architecture](architecture/)** – Global overview of the microservices ecosystem.
* **[Collector Data Flow](collector-data-flow/)** – Visual representation of data routing.
* **[Services](services/)** – Detailed breakdown of each individual microservice.

### 3. Features & Use Cases
See OpenTelemetry features in action and learn how to trigger specific scenarios.
* **[Telemetry Features](telemetry-features/)** – Overview of implemented traces, metrics, and logs.
* **[Feature Flags](feature-flags/)** – Instructions for simulating system errors and memory leaks.

### 4. Advanced & Development
Resources for modifying the source code and contributing to the project.
* **[Development](development/)** – How to set up a local development environment.
* **[Tests](tests/)** – Running automated tests against the deployment.

