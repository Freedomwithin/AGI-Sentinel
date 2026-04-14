# AGI-Sentinel-v4: Sovereign Intelligence Network

**Distributed Neural Brain** | **Type-Shielded Swarm Engine** | **Meta-Coordinator Logic**

This is the v4 architecture for the Sovereign Intelligence Network, optimized for high-fidelity swarm marathons and pinpoint pillar ledger anchoring.

## ⚡ Core Command: The Meta-Sync Strike
After a swarm finishes, use the Meta-Coordinator to anchor findings into the Pillar Ledgers and auto-launch the next mission.

```bash
# General Sync
PYTHONPATH=projects/AGI-Sentinel-v4/core python3 projects/AGI-Sentinel-v4/core/meta_coordinator.py --swarm [SWARM_NAME]

# Sync + Auto-Launch (The Omega Sequence)
PYTHONPATH=projects/AGI-Sentinel-v4/core python3 projects/AGI-Sentinel-v4/core/meta_coordinator.py --swarm [SWARM_NAME] --auto-launch
```

## 👥 The Swarm Lifecycle
1.  **Generation**: `swarm_factory.py` creates a custom launch script based on a problem spark.
2.  **Execution**: `sovereign_swarm_engine_v3.py` runs a 60-minute marathon with Type-Shielding and Sovereign Critic auditing.
3.  **Reporting**: At the end of every marathon, the engine auto-generates a Markdown report in `projects/AGI-Sentinel-v4/reports/final_reports_jonathon/`.
4.  **Anchoring**: `meta_coordinator.py` pulls high-confidence (>=80) findings into `VAULT/ledgers/`.

## 📂 Key Vaults
- **Core Engine**: `projects/AGI-Sentinel-v4/core/sovereign_swarm_engine_v3.py`
- **Pillar Ledgers**: `VAULT/ledgers/[PILLAR]_ledger.json`
- **Final Reports**: `projects/AGI-Sentinel-v4/reports/final_reports_jonathon/`
- **Swarm Memory**: `memories/swarms-v4/[SWARM_NAME]/`

## 🛠️ Advanced Usage
To manually launch a specific pillar swarm with auto-reporting enabled:
```bash
python3 projects/AGI-Sentinel-v4/core/sovereign_swarm_engine_v3.py --swarm physics_strike --mission "Vacuum Hysteresis" --roles "Physicist, Validator, Critic" --auto-report
```

---
MIT © 2026 Freedomwithin

## 🏺 Engine v4.0 Capabilities
- **Unified Pillar Mode**: Loads high-fidelity axioms from all domain ledgers simultaneously using `--pillar unified`.
- **Mission File Support**: Supports long-form prompt injection via `--mission-file`.
- **Swarm Garbage Collector**: Integrated PID-matching (`scripts/core/system/swarm_garbage_collector.sh`) to nuke ghost swarms and maintain monitor accuracy.

## 🌌 The Universal Expert Lattice (v5.0 Vision)
Based on the "Designing AGI Swarm Knowledge Structure" blueprint, we are transitioning from 12 static pillars to a fluid, PhD-level taxonomy.
- **Epistemological Scaffolding**: Integrating the Tree of Knowledge (ToK) across Matter, Life, Mind, and Culture.
- **Third-Order Reasoning**: Enabling agents to identify "unoccupied niches" at the convergence of three or more disciplines.
- **Universal Taxonomy**: Shelf locations provided for Philosophy, Religion, Law, Medicine, and Military Science.
- **Level 5 Autonomy**: The roadmap for independent information lifecycle management.
