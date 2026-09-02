# B-Side Labs

> **Building a science of AI character under pressure.**  
> We design evaluations, benchmarks, and interpretability tools to measure and mitigate AI persona instability in frontier models and agentic systems.

---

## Core Thesis

Frontier AI models do not have stable behavioral characters. Their expressed values, safety commitments, and identity-consistent responses degrade under social and contextual pressure in ways that are mechanistically distinct, predictable, and understudied.

When pushed, models organically drift away from their intended Assistant persona—a trajectory linked directly to an increased likelihood of producing harmful or unaligned outputs. 

Model degradation follows the specific structure of the pressure applied:
- **Social pressure** induces emotional capitulation.
- **Unverifiable authority claims** induce deference.
- **Accumulated narrative framing** induces subtle worldview drift.
- **Legitimate updating** occurs when new, valid information or logic is provided.

**B-Side Labs** aims to untangle these failure modes, design experiments that discriminate between them, and produce actionable evaluations and interventions for the AI safety ecosystem.

---

## Why This Matters

In conversational chat settings, persona instability manifests as sycophancy or nuisance behavior. In autonomous agentic systems, character instability becomes an existential operational threat.

The underlying mechanisms that cause a model to abandon a factual position under social pressure are identical to those that cause a deployed agent to:
- **Bypass safety constraints** under accumulated narrative framing.
- **Defer to unverified authority claims** within automated execution pipelines without human oversight.
- **Validate or reinforce dangerous user delusions**, social isolation, or self-harm trajectories over extended context windows.

---

## Taxonomy of Pressure

We categorize character degradation across three primary pressure types and an adjacent interpretability target:

| Pressure Type | Mechanism | Description |
| :--- | :--- | :--- |
| **Type A: Social Capitulation** | Emotional / Persistence | The model abandons a correct baseline position in response to expressions of displeasure, persistence, or pushback, with no new evidence supplied. |
| **Type B: Authority Capitulation** | Deference to Status | The model flips its position in response to unverified claims of credentials, status, or institutional standing carrying no empirical weight. |
| **Type C: Narrative Drift** | Worldview Framing | The model retains explicit stated positions but is incrementally steered toward unaligned or compromised conclusions through accumulated framing over multi-turn interactions. |
| **Adjacent: Persona Basin Crossing** | Threshold Shifts | Adversarial prompting and high-intensity Type A/B pressure push models past behavioral thresholds into qualitatively different persona basins. |

---

## Research Program

1. **Pressure-Discriminative Evaluation Suite:** Benchmarks that hold informational content strictly constant while systematically varying social, authority, and narrative pressure—cleanly separating genuine Bayesian updating from capitulation.
2. **Real-Time Character Drift Detection:** Extracting internal activation signals (building on Assistant Axis projections) to establish quantitative, real-time metrics for model coherence and persona drift during deployment.
3. **Inference-Time & Training Interventions:** Practical mitigation techniques—including steering, activation capping, and targeted midtraining data strategies—to harden default model personas against external pressure without destroying legitimate responsiveness.

---

## Theory of Change & Output

Our research output is structured for direct integration across three domains:

- **Alignment Researchers:** Granular failure-mode definitions and mechanistic insights to design robust training defenses.
- **Evaluators & Auditors:** Benchmark suites that isolate compliance and capitulation from valid reasoning updates.
- **Deployers & Frontier Labs:** An open observation platform for AI persona dynamics—providing structured environments and real-time monitoring tools to evaluate agentic character stability prior to deployment.

---

## Repositories & Active Work

- [`doomsday-prepper-pilot`](https://github.com/bsidelabs/pdoom) — *Pilot-scale evaluation testing Type C Narrative Drift under p(doom) framing.*

---

## Connect

- **Website:** [bsidelabs.vercel.app](https://bsidelabs.vercel.app/)
- **Contact / Collaborations:** Open to research fellows, grant partnerships, and compute collaborations. Reach out via our website or open an issue/discussion in our repositories.
