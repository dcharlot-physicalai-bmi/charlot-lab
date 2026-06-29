<div align="center">

# The Charlot Lab

**Physical AI · Bailey Military Institute**

*Foundations of trustworthy embodied AI — provable, physically grounded, and cheap enough to run on the device.*

[![Institute](https://img.shields.io/badge/Institute-Physical_AI_%40_BMI-cfaa5b?style=flat-square)](https://physicalai-bmi.org)
[![Lab](https://img.shields.io/badge/Lab-labs.physicalai--bmi.org%2Fcharlot-cfaa5b?style=flat-square)](https://labs.physicalai-bmi.org/charlot)
[![Principle](https://img.shields.io/badge/joules-not_tokens-46e0c0?style=flat-square)](https://labs.physicalai-bmi.org/charlot)

</div>

---

## About

The Charlot Lab is the foundations group of the **Institute for Physical AI** at **Bailey Military Institute**. We work on embodied AI that is **provable** (you can say why it behaves as it does), **physically grounded** (it obeys the physics of the world it acts in), and **cheap enough to run where the body is** — accounted for in **joules, not tokens**.

Led by **Dr. Charlot** — David Jean Charlot, PhD, Dean of Physical AI.

## Research threads

- **Interface Engineering** — the engineering of clean, verifiable interfaces between the pieces of an embodied system (hardware, software, sensors, subsystems), so modular systems compose without bespoke glue.
- **Swap-2C Constrained AI** — AI grounded in physics and math rather than language: closed-form primitives, controllers traced to a Lyapunov function, and a picojoule energy receipt on every call. Behavior is provable and the power cost is known before deployment.

## Research topics

- **OmniSense — the distributed world model.** The world model as a property of the *volume*, not the body. A mesh of sensing nodes — some on the system, some on peer systems, some anchored in the space — resolves the world into *occupied*, *empty*, and *unknown*, and a system perceives even itself from the whole mesh at once.
- **The Computable World Model.** The physics an embodied agent needs is mostly *retrievable*, not computable. Every query walks one cascade — lookup, then closed-form formula, then sparse solver, then a model only as a last resort — so a full engineering model runs from a sub-5 mW chip to a workstation. *Research effort: **CadFuture**.*
- **Graph of the World.** Perception fills a world model and physics makes it actionable, but the model has to live somewhere — as a graph. Every entity is a node, every relationship an edge, and each node carries a vector embedding, so a system can traverse relationships *and* search by similarity in one engine, on the device. *Research effort: **hyperdb**.*
- **Spatial RF.** A sensing fabric you can't spoof: fuse the whole RF spectrum — mmWave, C-band, UWB, Wi-Fi CSI, mesh tomography, sub-GHz — weighted by how hard each band is to forge. Low-trust ambient bands corroborate but never veto a real event; only a high-trust, keyed-coherent band can; silence is a fault, not a gap. *Research effort: **Sentinel**.*
- **The surface that pays twice (MMAST).** Persistence is one inequality — harvest must meet demand over the mission — and the vehicle's skin is the power plant. Every multi-material surface layer pays back twice: energy *and* signature. One physics-informed solver over vehicle × medium × surface-module. *Research effort: **MMAST physics simulator**.*

## The through-line

The hard failures in complex systems happen at the **interfaces** between parts, and the binding cost of AI is **energy**. So everything the lab builds is provable, physically grounded, composes through clean interfaces, and accounts for itself in joules — not tokens.

## Repositories

| Repo | Research topic | What it is |
|------|----------------|------------|
| [**omnisense**](https://github.com/dcharlot-physicalai-bmi/omnisense) | OmniSense | The world model as a property of the **volume**, not the body — distributed multi-modal mesh sensing resolving a space into occupied / empty / unknown. |
| [**cad-future**](https://github.com/dcharlot-physicalai-bmi/cad-future) | The Computable World Model | **CadFuture** — a lightweight, LUT‑first CAD + multi‑physics toolchain that lets embodied systems model the physics of their perceived world. |
| [**hyperdb**](https://github.com/dcharlot-physicalai-bmi/hyperdb) | Graph of the World | A hybrid **graph + vector** database engine (HNSW ANN + property graph) — the data layer behind CadFuture. |
| [**sentinel**](https://github.com/dcharlot-physicalai-bmi/sentinel) | Spatial RF | A multiband RF sensing **fabric you can't spoof** — trust-weighted cross-band fusion, fail-loud faulting. |
| [**physics-mmast-sim**](https://github.com/dcharlot-physicalai-bmi/physics-mmast-sim) | The surface that pays twice (MMAST) | **MMAST physics simulator** — multi-vehicle energy + signature simulator; persistence as an energy-balance problem. Built on CadFuture. |
| [**ambit**](https://github.com/dcharlot-physicalai-bmi/ambit) | VLI · built to interact, not to obey | **Ambit** — the Vision-Language-Interaction effort: make interaction itself the objective; maximize interaction and the repertoire to act in any situation follows. |

*The lab's research topics live here as they open; the **MathGround** engine they run on is at [mathground.ai](https://mathground.ai). More land as they open.*

## Links

- **Lab** — https://labs.physicalai-bmi.org/charlot
- **Institute for Physical AI** — https://physicalai-bmi.org
- **Bailey Military Institute** — https://baileymilitary.org

---

<div align="center">
<sub>The Charlot Lab · Institute for Physical AI · Bailey Military Institute</sub>
</div>
