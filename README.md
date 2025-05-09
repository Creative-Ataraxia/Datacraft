# Codename: DataCraft

*A factory/automation/Education game about building real-world data engineering pipelines!*

[![status](https://img.shields.io/badge/status-pre--alpha-orange)]()
[![license](https://img.shields.io/badge/license-MIT-blue)]()
[![contributions](https://img.shields.io/badge/contributions-welcome-brightgreen)]()

---

## What's the DataCraft idea?

DataCraft turns real-world, enterprice-grade data-engineering concepts like batch vs. streaming ingestion, warehouses/lakes/lakehouses, DAG orchestration, and all a broad range of governance workflows into a hands-on, **Factorio-style** sandbox sim.
If you enjoy optimizing production lines and shaving milliseconds off jobs, or you enjoy seeing how pieces of raw materials gets molded and change on the assembly line, you've found the right game! :contentReference[oaicite:0]{index=0}:contentReference[oaicite:1]{index=1}

---

## Core Gameplay

| Step | What you do | What it teaches |
|------|-------------|-----------------|
| **1. Receive some business objectives** | “Deliver cleaned customer data in < 10 s and under \$50 compute costs.” | Framing work around real-world constraints |
| **2. Lay out a pipeline** | Drag warehouse nodes, Spark processors, dbt transforms, etc. | Data-platform building blocks |
| **3. Watch data cubes flow** | Immutable blocks change colour/shape as they transform. | Lineage + schema thinking |
| **4. Optimise** | Re-route, scale, test, and budget-trim. | Cost/perf trade-offs & observability |
| **5. Ship** | Pass validation gates, unlock harder levels & new tools. | Continuous improvement loop |

---

## Features

* **Immutable data cubes** – every block is a row; lineage you can literally follow.  
* **Warehouse / Lake / Lakehouse storage** with real trade-offs.  
* **Batch, streaming, real-time ingestion**—pay for speed like in the cloud.  
* **Visual DAG orchestrator**—zoom from pipe-level to workflow overview.  
* **Failure modes that matter**—schema drift, SLO breaches, runaway cost.  
* **Expandable toolbox**—unlock dbt, Spark, Airbyte-like extractors, ML endpoints and more as you progress.

---

## Roadmap

| Milestone | Target |
|-----------|--------|
| **`v0.1` Prototype** | Core loop, single “warehouse” map, basic batch → transform → report level |
| **`v0.2` Tooling Pass** | Streaming, dashboards, failure conditions |
| **`v0.3` Sandbox Mode** | Unlimited maps, community blueprint sharing |
| **`v1.0` Early Access** | 10+ story levels, mod support, full save system |

*(Timelines will written once prototyping starts.)*

---

## Screenshots / GIFs

> Screens and video demos will drop here once the first playable slice is ready.

---

## Getting Started (for contributors)

1. **Clone** the repo  
   ```bash
   git clone https://github.com/creative-ataraxia/DataCraft.git
   ```

2. **Open** the `/prototype` project in *Unity or Unreal* (engine TBC).
3. **Run** the `Main` scene to play the grey-boxed prototype.
4. **Hack** on a new building block, or tweak the JSON level spec, and open a pull request.

> **No game-dev experience welcome**
> Start with docs, UX mock-ups, or balancing spreadsheets—everything helps.

---

## Contributing

We follow the standard **fork → feature branch → PR** flow.
Before submitting, please read `CONTRIBUTING.md` (code style, commit format, CLA).

*Good first issues*: UI icons, tooltip text, unit-test harness, CI script.

---

## Built With (planned)

| Tech           | Role                          |
| -------------- | ----------------------------- |
| Unity / Unreal | Core engine                   |
| Yarn Spinner   | In-game tutorial scripting    |
| JSON5          | Level & tool definition files |
| GitHub Actions | CI / build pipeline           |

---

## License

Distributed under the **MIT License** – see `LICENSE` for details.

---

## Contact

Project discussions & roadmap: <[repo discussions](https://github.com/creative-ataraxia/DataCraft/discussions>

---

*Ready to help shape the future of the factory genre?*
Star ⭐ the repo, file an issue, or jump into the Discord—your feedback drives the roadmap.
