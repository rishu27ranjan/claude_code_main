# Claw Code (Python Rewrite)

<p align="center">
  <strong>A clean-room Python reimplementation of an agent harness system</strong>
</p>

---

## Overview

**Claw Code** is a ground-up Python rewrite of an agent orchestration system inspired by recently surfaced design patterns in modern AI coding assistants.

This project focuses on:

* Harness architecture
* Tool orchestration
* Task execution workflows
* Runtime structure and observability

It is **not a copy** of any proprietary codebase. Instead, it is a **clean-room implementation** built to explore and extend these ideas in an open, maintainable way.

---

## Project Status

* ✅ Python-first architecture established
* ✅ Core modules and structure implemented
* ✅ Test suite in place
* ⚠️ Not yet feature-complete vs. original inspiration
* 🚧 Active development ongoing

A **Rust implementation** is currently in progress (`dev/rust`) to provide:

* Improved performance
* Memory safety
* More robust runtime execution

---

## Why This Exists

This project began as an effort to understand how modern AI agent systems:

* Coordinate tools
* Manage execution loops
* Structure task pipelines
* Maintain context across operations

After evaluating legal and ethical considerations, the repository was redesigned to focus entirely on an **original Python implementation**, rather than any exposed source material.

---

## Repository Structure

```
.
├── src/                    # Core Python implementation
│   ├── main.py            # CLI entrypoint
│   ├── models.py          # Core data structures
│   ├── task.py            # Task abstraction
│   ├── tools.py           # Tool definitions
│   ├── commands.py        # Command registry
│   ├── query_engine.py    # Introspection + summaries
│   └── port_manifest.py   # Workspace state tracking
│
├── tests/                 # Unit tests
├── assets/                # Images and documentation assets
└── README.md
```

---

## Key Concepts

### 1. Harness Architecture

A structured runtime that coordinates:

* Commands
* Tools
* Tasks
* Execution flow

### 2. Tooling Layer

Encapsulates external capabilities into reusable units.

### 3. Command System

Defines how users or agents interact with the system.

### 4. Task Execution

Represents units of work with clear lifecycle handling.

### 5. Introspection

Built-in visibility into system structure via query tools.

---

## Getting Started

### Install & Run

```bash
# Run summary of current system
python3 -m src.main summary

# View workspace manifest
python3 -m src.main manifest

# List subsystems
python3 -m src.main subsystems --limit 16
```

### Testing

```bash
python3 -m unittest discover -s tests -v
```

### Optional: Parity Audit

```bash
python3 -m src.main parity-audit
```

---

## Current Capabilities

* System structure inspection
* Command and tool registry tracking
* Workspace manifest generation
* Basic execution scaffolding

---

## Limitations

* Not a full runtime-equivalent system yet
* Partial implementation of execution logic
* Lacks production-grade orchestration features

---

## Development Direction

Planned improvements include:

* Full execution loop implementation
* Advanced tool chaining
* Stateful agent workflows
* Better observability and logging
* Rust-based runtime backend

---

## Philosophy

This project is built around a few core principles:

* **Transparency over hype**
* **Architecture over imitation**
* **Exploration over replication**

The goal is to create a **clear, extensible reference implementation** for agent harness systems.

---

## Community

If you're interested in:

* LLM systems
* Agent workflows
* Tool orchestration
* AI infrastructure

You’re welcome to contribute, experiment, and build on top of this project.

---

## Disclaimer

* This project is an independent implementation
* It is **not affiliated with or endorsed by any AI company**
* No proprietary source code is included

---

