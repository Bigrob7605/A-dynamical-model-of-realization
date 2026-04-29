# A Dynamical Model of Realization

From prediction error to paradigm collapse — an interactive framework for understanding how ordinary insight scales into transformative experience.

---

## What this is

Most models of insight treat it as a moment. This one treats it as a system.

The model maps the full arc from a small "huh, interesting" to ego-dissolving mystical states — not as fundamentally different categories, but as outcomes of the same recursive loop operating at different intensities, with different modulators engaged. The core argument: insight, profound realization, and peak experience are not qualitatively distinct phenomena. They are the same dynamical process, constrained differently.

Built as a single self-contained HTML file. No dependencies, no framework, no server required.

---

## The architecture

**Eight-stage recursive loop**

```
Prediction Error → Salience Reweighting → Association Expansion →
Model Destabilization → Restructuring / Optimization →
Peak Integration → Re-coherence → Embodied Integration → ↺
```

Each completed cycle raises the sensitivity floor of the next. The loop is not a sequence — it is a feedback system. Salience shapes associations; associations drive restructuring; restructuring reshapes what salience even notices.

**Four modulators**

| Modulator | Role |
|---|---|
| Emotional / physiological intensity | Gain control on the entire process |
| Self-boundary stability (Z-axis) | Determines whether the outcome crosses into peak or mystical territory |
| Compute cost / resistance | Gatekeeper — R(t) > 0.65 → signal discarded as noise |
| Constraint / reality feedback | What separates genuine insight from delusion |

**Six outcome levels**

`Discarded → Local insight → Profound insight → Paradigm collapse → Peak / mystical state`
and the failure mode: `Pathology` (high intensity + low coherence + failed constraint).

**Network topology evolution**

The model tracks how the associative network reorganizes structurally — not just grows:

- Sparse `Q≈0.48, L≈2.1` — everyday insight
- Clustered `Q≈0.35, L≈1.8` — Aha! moments
- Integrated `Q≈0.12, L≈1.3` — profound insight
- Field-like `Q≈0, C≈0.95, L=1` — mystical states

The phase transition to field-like topology (when Q drops below ~0.15 and C exceeds ~0.85 simultaneously) corresponds geometrically to the collapse of subject-object boundaries.

---

## Formalized mechanisms

Three mechanisms that usually stay hand-wavy are operationalized here:

**Compute cost / resistance**
```
R(t) = WM_saturation(t) + λ·ΔE_metabolic + β·ΔP_stability
```
Working memory saturation + metabolic efficiency penalty + prediction-disruption cost weighted by stakes. Threshold R > 0.65 → insight discarded, regardless of validity.

**Viability filter**
A new model is viable if it satisfies: Compression (ΔC > +0.15 bits/element) + Accuracy (MAE ↓ ≥ 10%) + Actionability (guides novel behavior). Conflict rule: Accuracy is the primary constraint. Compression that worsens prediction reverts to the reject path.

**Field-like topology**
Defined by three metrics simultaneously: modularity Q → 0, clustering coefficient C → 0.95, mean path length L → 1. Not just "more connections" — a structural phase transition.

---

## Interactive features

- **Click any loop stage** → detail panel shows its role, what feeds it, and what it feeds into
- **Click topology nodes** → highlights corresponding outcomes in the state space
- **Click state space regions** → highlights matching outcomes and topology
- **Click outcome cards** → shows where they land in the state space
- **Trajectory simulator** → four sliders (emotional intensity, cognitive restructuring depth, self-boundary dissolution, constraint strength) predict outcome in real time, with constraint dynamics readout
- **Animated token** → traces the recursive loop continuously, following the ring's arc

---

## Theoretical context

This model converges with and borrows from several bodies of work without being strictly derived from any of them:

- **Predictive processing / active inference** (Friston) — prediction error as the primary trigger; free-energy minimization as the viability filter logic
- **Relevance realization** (Vervaeke) — the salience reweighting mechanism and the idea that insight is fundamentally about what the system deems worth attending to
- **Integrated Information Theory** (Tononi) — the network topology metrics and the relationship between integration and conscious intensity
- **Peak experience research** (Maslow, James, Stace) — the phenomenological descriptions anchoring the upper end of the outcome spectrum, particularly the noetic quality criterion
- **Developmental stage theory** (Kegan) — the recursive loop structure and the idea that each completed cycle raises the resolution of the next

The model makes no claim to be empirically validated. It is a conceptual synthesis — useful for thinking, not for publication as-is.

---

## Usage

Single file. Open in any modern browser.

```bash
git clone https://github.com/your-username/a-dynamical-model-of-realization
open dynamical_model_v6.html
```

Or host it anywhere that serves static files — GitHub Pages, Netlify, Vercel. No build step.

---

## Background

Built through an iterative brainstorming process starting from a simpler diagram (sparse → dense network, linear process strip) and progressively stress-tested: adding feedback loops, the entropy spike before restructuring, the viability filter, embodied integration, the failure mode for pathology, and finally the formalized mechanisms and interactive cross-linking.

The design question throughout was: *what would it take for this to be defensible in a room with people who know the field?*
---

*A dynamical model of realization — recursive · constrained · embodied*
