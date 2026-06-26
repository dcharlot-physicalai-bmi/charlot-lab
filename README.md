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

## The through-line

The hard failures in complex systems happen at the **interfaces** between parts, and the binding cost of AI is **energy**. So everything the lab builds is provable, physically grounded, composes through clean interfaces, and accounts for itself in joules — not tokens.

## Repositories

| Repo | What it is |
|------|------------|
| [**cad-future**](https://github.com/dcharlot-physicalai-bmi/cad-future) | **CadFuture** — a lightweight, LUT‑first CAD + multi‑physics toolchain that lets embodied systems model the physics of their perceived world. |

*More lab projects land here as they open.*

## Links

- **Lab** — https://labs.physicalai-bmi.org/charlot
- **Institute for Physical AI** — https://physicalai-bmi.org
- **Bailey Military Institute** — https://baileymilitary.org

---

<div align="center">
<sub>The Charlot Lab · Institute for Physical AI · Bailey Military Institute</sub>
</div>
