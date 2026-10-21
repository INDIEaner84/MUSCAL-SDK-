# MUSCAL SDK
## Evidence-Based Security Infrastructure for Extensible AI Systems

### 1. What Is the MUSCAL SDK?

The **MUSCAL SDK (Software Development Kit)** is the developer interface for building plugins and integrations for the MUSCAL runtime.

It is designed to connect externally developed components to the MUSCAL infrastructure through defined interfaces, while keeping the proprietary core separate from the extension layer.

Rather than requiring developers to modify the underlying system directly, the SDK provides an interface through which supported extensions can be developed and integrated.

MUSCAL aims to combine extensibility, architectural control, and an evidence-oriented approach to security and system governance.

### 2. What Makes It Different?

**Controlled Core, Open Extension Layer**

The central MUSCAL implementation remains proprietary, while the plugin SDK is licensed under the MIT License. This separation allows developers to work with the supported extension interface without requiring access to the proprietary core.

**Evidence-Oriented Security**

MUSCAL's architectural direction emphasizes the distinction between security claims and verifiable evidence. Where implemented, this can include traceable events, reproducible tests, and documented system behavior. The actual security guarantees depend on the capabilities implemented and independently verified.

**Modular Extensibility**

The SDK provides a foundation for connecting supported plugins and integrations without requiring direct modifications to the core. This can help separate individual extensions from the underlying runtime architecture.

**Potential for an Extensible Ecosystem**

An accessible SDK can enable third-party developers to build integrations and contribute additional functionality. Stable interfaces, clear documentation, compatibility guarantees, and effective security controls are essential to realizing that potential.

### 3. How Do You Use the MUSCAL SDK?

The general development workflow consists of five steps:

**Step 1 — Set Up Your Environment**

Obtain the SDK, review its documentation and license, and configure the development environment required by the project.

**Step 2 — Explore the Interfaces**

Identify the supported plugin interfaces, available APIs, data
