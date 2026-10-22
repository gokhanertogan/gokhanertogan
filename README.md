### Hi, I'm Gökhan 👋

Software Development Team Lead in Istanbul with 10+ years of experience in **.NET**. I build and lead work on microservices and event-driven systems, and I care about the parts that break quietly: concurrency, background work, messaging, and the observability around them.

#### Experience

- **Software Development Team Lead · Boyner** (2024 – present): leading the Campaign and Basket microservices after the move from a monolith; Kafka and RabbitMQ messaging, DDD
- **Senior Software Developer · Boyner** (2022 – 2024): e-commerce monolith covering products, basket, payments and campaigns
- **Software Design Senior Engineer · Netaş** (2021 – 2022): unified single-card system for FIFA World Cup 2022 in Qatar (stadium access, transportation, facilities)
- **Backend Developer · Arge Bilişim** (2019 – 2021) and **Leonardo Travel** (2017 – 2018): ERP/MRP modules; B2B and B2C hotel reservation platforms

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

C# · .NET / ASP.NET Core · EF Core · Dapper · SQL Server · PostgreSQL · MongoDB · Redis · Kafka · RabbitMQ / MassTransit · SignalR · OpenTelemetry · Docker · Kubernetes · Azure · React / TypeScript

#### Education

- M.Sc. in Artificial Intelligence · Ahmet Yesevi University (in progress)
- M.Sc. in Software Engineering · Ahmet Yesevi University
- B.Sc. in Business Administration · Anadolu University (in progress)
- B.Sc. in Management Information Systems · Anadolu University
- B.Ed. in Computer Education and Instructional Technology · İbrahim Çeçen University

#### Contact

[LinkedIn](https://www.linkedin.com/in/gokhanertogan/) · [NuGet](https://www.nuget.org/profiles/GokhanErtogan)
