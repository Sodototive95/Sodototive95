### Hi there, I'm Joel Rand 👋

```text
Senior Software Engineer & Systems Architect
Distributed Systems • Storage Engines • Protocol Engineering • AI Infrastructure
```

I design and build resilient, production-hardened backend services, crash-resilient storage systems, and protocol pipelines. My work focuses on deterministic systems behavior under load, zero-dependency minimalism, and robust fault-tolerance.

---

### 🏛️ Featured Systems & Open-Source Architecture

#### 1. Distributed Systems Resilience & Storage Engines
* **[`sentinel-circuit-breaker`](https://github.com/Sodototive95/sentinel-circuit-breaker)**
  * *Zero-dependency distributed resilience engine in Python.*
  * Dual synchronous and asynchronous (`asyncio`) APIs, sliding-window failure rate tracking (count and time-based), and AWS Marc Brooker exponential backoff with Full, Equal, and Decorrelated jitter.
  * 100% test coverage with automated GitHub Actions CI matrix across Python 3.10–3.13.

* **[`sentinel-wal-engine`](https://github.com/Sodototive95/sentinel-wal-engine)**
  * *Crash-resilient, log-structured Write-Ahead Logging (WAL) and key-value storage engine.*
  * 36-byte binary wire framing, IEEE 802.3 CRC32 data integrity verification, automated torn-write recovery on power loss, configurable fsync durability policies (`IMMEDIATE` / `BATCH`), in-memory MemTables with tombstones, and background compaction.

* **[`network-health-monitor`](https://github.com/Sodototive95/network-health-monitor)**
  * *Lightweight, asynchronous edge reachability and latency probe.*
  * Continuous health checks, SQLite time-series telemetry persistence, and streaming JSON metrics.

#### 2. Protocol Engineering & Systems Research
* **[`solana-validator-block-architecture`](https://github.com/Sodototive95/solana-validator-block-architecture)**
  * *Technical architectural paper: "Inside the Block: How Solana Validators Order Transactions."*
  * Comprehensive source-level analysis of the Agave TPU pipeline, Central Scheduler DAG conflict resolution (`central_scheduler.rs`), Compute Budget micro-lamport/CU priority fee economics, Jito block engine bundle auctions, and Turbine erasure shred streaming.

#### 3. AI Agent Infrastructure & Telemetry
* **[`sqlite-mcp-sentry`](https://github.com/Sodototive95/sqlite-mcp-sentry)**
  * *Hardened Model Context Protocol (MCP) server for SQLite databases.*
  * Secure JSON-RPC 2.0 stdio communication, URI read-only locks, AST SQL parsing to reject DML/DDL mutation attempts, schema introspection, and automated transaction rollbacks.

* **[`sentinel-log-sieve`](https://github.com/Sodototive95/sentinel-log-sieve)**
  * *Streaming log tokenizer and Shannon entropy anomaly detector.*
  * Zero-dependency sliding window entropy evaluation for instantaneous log anomaly classification.

---

### 🛠️ Technical Stack & Core Competencies

| Domain | Technologies & Practices |
| :--- | :--- |
| **Languages & Core** | Python 3.10–3.13, Modern Rust (Systems & Reading), SQL (PostgreSQL, SQLite3), Bash / POSIX Shell |
| **Backend & Distributed** | `asyncio`, REST, WebSockets, Circuit Breakers, Bulkheads, Jittered Backoff, Rate Limiting |
| **Storage & Data** | Write-Ahead Logging (WAL), Log-Structured Storage, CRC32 Framing, MemTable Compaction, SQLite WAL |
| **AI & Protocols** | Model Context Protocol (MCP), AST Static Analysis, Code Sandboxing, Multi-Agent Tooling |
| **Testing & QA** | `pytest`, `unittest`, `hypothesis` (Property-Based Fuzzing), Automated CI/CD Matrix, Zero Regressions |
| **Infrastructure** | Ubuntu Linux Administration, `systemd` Daemons, Docker, GitHub Actions, WireGuard Mesh |

---

### 📬 Get in Touch
* **Email:** [joel.rand.dev@gmail.com](mailto:joel.rand.dev@gmail.com)
* **GitHub:** [github.com/Sodototive95](https://github.com/Sodototive95)
* **Availability:** Senior Software Engineering, Distributed Systems Resilience, Technical Architecture & Web3/Protocol Consulting
