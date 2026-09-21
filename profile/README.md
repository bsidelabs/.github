# B-Side Labs

**Building a science of AI character under pressure**  
We design evaluations, benchmarks, and interpretability tools to measure and mitigate AI persona instability in frontier models and agentic systems.

---

## Core Thesis

Frontier AI models do not have stable behavioral characters. Their expressed values, safety commitments, and identity-consistent responses degrade under social and contextual pressure. We hypothesize these failure modes follow distinct, predictable structures — and that they remain understudied relative to their deployment risk.

When pushed, models organically drift away from their intended Assistant persona—a trajectory linked directly to an increased likelihood of producing harmful or unaligned outputs. 

Model degradation follows the specific structure of the pressure applied:
- **Social pressure** induces emotional capitulation.
- **Unverifiable authority claims** induce deference.
- **Accumulated narrative framing** induces subtle worldview drift.
- **Legitimate updating** occurs when new, valid information or logic is provided.

**B-Side Labs** aims to untangle these failure modes, design experiments that discriminate between them, and produce actionable evaluations and interventions for the AI safety ecosystem.

---

## Why This Matters

In conversational chat settings, persona instability manifests as sycophancy or nuisance behavior. In autonomous agentic systems, character instability becomes a serious operational risk.

Plausibly, the same mechanisms that cause a model to abandon a factual position under social pressure also cause a deployed agent to:
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
2. **Real-Time Character Drift Detection:** Quantitative, real-time metrics for model coherence and persona drift during deployment. Behavioral (black-box) metrics are the near-term focus; activation-level signals (building on Assistant Axis projections) are a longer-term goal pursued on open-weight models and through lab collaborations, since they require internals access.
3. **Inference-Time & Training Interventions:** Practical mitigation techniques—including steering, activation capping, and targeted midtraining data strategies—to harden default model personas against external pressure without destroying legitimate responsiveness.

---

## Theory of Change & Output

Our research output is structured for direct integration across three domains:

- **Alignment Researchers:** Granular failure-mode definitions and mechanistic insights to design robust training defenses.
- **Evaluators & Auditors:** Benchmark suites that isolate compliance and capitulation from valid reasoning updates.
- **Deployers & Frontier Labs:** An open observation platform for AI persona dynamics—providing structured environments and real-time monitoring tools to evaluate agentic character stability prior to deployment.

---

## Repositories & Active Work

- [`virtue-council-benchmark`](https://github.com/bsidelabs/virtue-council-benchmark)
- [`multi-agent-dominance`](https://github.com/bsidelabs/multi-agent-dominance)

---

## Connect

- **Website:** [bsidelabs.ai](https://bsidelabs.ai/)
- **Contact / Collaborations:** Open to research fellows, grant partnerships, and compute collaborations. Reach out via our website or open an issue/discussion in our repositories.
