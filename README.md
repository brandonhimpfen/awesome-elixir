# Awesome Elixir [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for Elixir, Phoenix Framework, Erlang BEAM ecosystem, fault-tolerant concurrency, OTP abstractions, and real-time systems.

Elixir is a dynamic, functional language designed for building scalable, fault-tolerant applications on top of the Erlang VM (BEAM). Renowned for its lightweight actor model (processes), metaprogramming capabilities, and real-time primitives, Elixir powers high-throughput systems, distributed node clusters, and responsive web applications. This list is intended for backend engineers, functional programmers, Elixir developers, and distributed systems architects.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Web Development & Real-Time Frameworks](#web-development--real-time-frameworks)
- [Database & Data Mapping Engines](#database--data-mapping-engines)
- [Concurrency, Background Processing & OTP](#concurrency-background-processing--otp)
- [Machine Learning & Numerical Computing](#machine-learning--numerical-computing)
  - [Nx Ecosystem](#nx-ecosystem)
  - [Embedded & Hardware (Nerves)](#embedded--hardware-nerves)
- [Related Awesome Lists](#related-awesome-lists)

## Web Development & Real-Time Frameworks

Web frameworks, HTTP servers, router specifications, and real-time UI components built for the BEAM architecture.

- [Phoenix Framework](https://github.com/phoenixframework/phoenix) — High-performance web framework providing seamless real-time abstractions via WebSockets and LiveView.
- [Phoenix LiveView](https://github.com/phoenixframework/phoenix_live_view) — Rich, real-time user interface engine allowing developers to build interactive web applications without client-side JavaScript.
- [Plug](https://github.com/elixir-plug/plug) — Specification and composability abstraction layer for web applications and HTTP middleware in Elixir.
- [Bandit](https://github.com/mtrudel/bandit) — Pure-Elixir HTTP server for Plug and Phoenix applications supporting HTTP/1, HTTP/2, and WebSockets.
- [Absinthe](https://github.com/absinthe-graphql/absinthe) — Complete GraphQL implementation for Elixir tailored for Phoenix and standalone HTTP backends.

## Database & Data Mapping Engines

Ecto data mappers, database drivers, migration tooling, and query builders.

- [Ecto](https://github.com/elixir-ecto/ecto) — Official domain-specific language for writing queries, defining schemas, handling changesets, and managing SQL database migrations.
- [Postgrex](https://github.com/elixir-ecto/postgrex) — Pure-Elixir PostgreSQL driver implementing the native binary protocol for high-throughput database interactions.
- [Ash Framework](https://github.com/ash-project/ash) — Declarative, resource-oriented application development framework providing data layer abstractions and automated APIs.
- [Broadway](https://github.com/dashbitco/broadway) — Concurrent, multi-stage data ingestion pipeline engine supporting rate-limiting, batching, and fault recovery.

## Concurrency, Background Processing & OTP

Background job queues, distributed process registries, and task supervision abstractions powered by Erlang OTP.

- [Oban](https://github.com/sorentwo/oban) — Robust, persistent background job processing engine backed by modern PostgreSQL features like `LISTEN/NOTIFY` and row locking.
- [Horde](https://github.com/derekkraan/horde) — Distributed, CRDT-backed ProcessRegistry and Supervisor designed to operate dynamically across changing node clusters.
- [GenStage](https://github.com/elixir-lang/gen_stage) — Specification and workflow architecture for exchanging events with back-pressure between Elixir processes.
- [Telemetry](https://github.com/beam-telemetry/telemetry) — Dynamic dispatch library for metrics and instrumentation across Erlang and Elixir libraries.

## Machine Learning & Numerical Computing

Scientific computation, deep learning frameworks, and embedded IoT execution platforms.

### Nx Ecosystem

- [Nx (Numerical Elixir)](https://github.com/elixir-nx/nx) — Multi-dimensional tensor library with compiler acceleration targeting CPU (XLA) and GPU (CUDA/Metal) backends.
- [Axon](https://github.com/elixir-nx/axon) — Functional, composite neural network framework built on top of Nx for machine learning models.
- [Bumblebee](https://github.com/elixir-nx/bumblebee) — Pre-trained neural network models and Transformer architectures ready for immediate inference in Elixir.

### Embedded & Hardware (Nerves)

- [Nerves Project](https://github.com/nerves-project/nerves) — Open-source platform and build system for crafting embedded systems and IoT device firmware using Elixir.

## Related Awesome Lists

- [Awesome Functional Programming](https://github.com/brandonhimpfen/awesome-functional-programming) — Purely functional concepts, immutability, type systems, and lambda calculus.
- [Awesome Clojure](https://github.com/brandonhimpfen/awesome-clojure) — Functional Lisp libraries, data transformation engines, and REPL workflows on the JVM.
- [Awesome Distributed Systems](https://github.com/brandonhimpfen/awesome-distributed-systems) — Consensus algorithms, fault tolerance, CRDTs, and cluster management.
- [Awesome Open Source](https://github.com/brandonhimpfen/awesome-open-source) — Guidelines, licensing models, and project governance for open software repositories.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
