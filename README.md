### Hi, I'm Gökhan 👋

Software engineer in Istanbul, working mostly in **.NET** on backend and distributed systems. I care about the parts that break quietly: concurrency, background work, messaging, and the observability around them.

#### Open source

- **[StructuredConcurrency](https://github.com/gokhanertogan/StructuredConcurrency)** — structured concurrency for .NET. Child tasks run inside a scope that completes only when all of them have finished, and the first failure cancels the rest. [![NuGet](https://img.shields.io/nuget/v/StructuredConcurrency.svg)](https://www.nuget.org/packages/StructuredConcurrency)
- **dotnet/runtime** — performance work on `System.Xml.XPath`:
  - [#136245](https://github.com/dotnet/runtime/pull/136245) Make `following-sibling` / `preceding-sibling` axes linear instead of quadratic
  - [#136180](https://github.com/dotnet/runtime/pull/136180) Remove allocations in `translate()` and `normalize-space()`
- **[onion_template](https://github.com/gokhanertogan/onion_template)** — `dotnet new` template that generates a production-ready .NET 10 microservice with zero third-party packages (mediator, validation, result pattern, outbox and permission-based auth built in).

#### Architecture samples

| Repo | What it shows |
| --- | --- |
| [ModulerMonolith](https://github.com/gokhanertogan/ModulerMonolith) | Modular monolith with Basket, Product and Order modules; vertical slices inside onion layers |
| [SagaOrchestration](https://github.com/gokhanertogan/SagaOrchestration) | Orchestrated saga with a MassTransit state machine over RabbitMQ |
| [DistributedTransactionSagaChoreography](https://github.com/gokhanertogan/DistributedTransactionSagaChoreography) | Choreographed saga with the transactional outbox pattern |
| [TwoPhaseCommitPattern](https://github.com/gokhanertogan/TwoPhaseCommitPattern) | Two-phase commit with a coordinator across Order, Payment and Stock services |
| [DataPartitioningProject](https://github.com/gokhanertogan/DataPartitioningProject) | PostgreSQL partitioning and GIN indexes, load-tested with NBomber |

#### Stack

C# · .NET / ASP.NET Core · EF Core · PostgreSQL · SQL Server · RabbitMQ / MassTransit · SignalR · OpenTelemetry · Docker · React / TypeScript

#### Contact

[LinkedIn](https://www.linkedin.com/in/gokhanertogan/) · [NuGet](https://www.nuget.org/profiles/GokhanErtogan)
