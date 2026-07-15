# FSM-eDSL

>> A research-oriented Haskell project exploring the design and implementation of a type-safe Embedded Domain-Specific Language (eDSL) for modelling, simulating, analysing, and verifying Finite State Machines (FSMs).

---

## Overview

FSM-eDSL is an ongoing research project that explores how Haskell's advanced type system can be leveraged to design expressive, safe, and extensible Embedded Domain-Specific Languages (eDSLs) for Finite State Machines (FSMs).

It investigates the use of modern functional programming techniques including algebraic data types, GADTs, DataKinds, type classes, and final tagless encoding to provide compile-time guarantees while supporting simulation, graph analysis, and formal verification.

The repository serves as the primary implementation and research workspace for the project, documenting design decisions and incremental development throughout the research process.

---

## Research Goals

The project aims to:

- Design a declarative Embedded Domain-Specific Language (eDSL) for Finite State Machines.
- Explore type-safe modelling through Haskell's advanced type system.
- Develop reusable abstractions for modelling finite state machines.
- Investigate techniques for simulation, graph analysis, and formal verification.
- Evaluate the application of functional programming to software correctness.

---

## Research Directions

The project will progressively explore the following research directions as the implementation evolves:

- Type-safe FSM modelling
- Embedded DSL design
- Interactive simulation
- Graph-based analysis using FGL
- Property-based testing with QuickCheck
- Property-based testing with Hedgehog
- SMT-based verification using SBV and Z3
- Formal verification of FSM properties

---

## Technology Stack

- Haskell
- GHC
- Stack
- Cabal
- GHCup
- Haskell Language Server (HLS)
- VS Code
- WSL2 Ubuntu
- Git & GitHub

---

## Repository Structure

```text
app/          Executable entry point
src/          Library source code
test/         Test suite
docs/         Project Documentation
diagrams/     Project diagrams
```

---

## Current Focus

The current phase focuses on strengthening the Haskell foundations required for building a type-safe eDSL, including algebraic data types, type classes, and advanced type system features.


## Building

```bash
stack build
stack test
stack ghci
```

---

## License

This project is licensed under the MIT License.

---

## Author

**Faruk Basha**

B.Tech, Computer Science and Engineering

Amrita Vishwa Vidyapeetham

Research Interests:
- Formal Verification
- Functional Programming
- Programming Languages

GitHub: https://github.com/farukbasha16
