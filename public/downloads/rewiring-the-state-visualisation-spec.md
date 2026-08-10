# Rewiring the State: active benefits management visualisation specification

## Design purpose

The visualisation should help a reader understand **how an expected public benefit is meant to arise, how confident the public evidence is in each link, and what implementation should monitor**.

It should not present the visualisation as a scorecard of whether a current government policy is good or bad. The Cabinet Statement provides policy context; the analytical object is the expected-benefit pathway.

## Core sequence

The interface should make this chain explicit:

**Expected benefit → mechanism → enabling conditions → leading indicators → final outcomes → adaptation / learning**

A reader should be able to see where evidence attaches to only one part of that chain. For example, evidence that a preventive intervention generates long-run benefits is not automatically evidence that a particular governance reform will cause more prevention.

## Three-layer architecture

### Layer A — Expected-benefit landscape

Use stable, deterministic bands rather than a moving force-directed graph:

1. **Expected benefits** — growth, access, prevention, fairness, accountability, resilience and public value.
2. **Mechanisms** — local information, coordination, incentives, participation, integration and investment.
3. **Conditions and risks** — capability, equalisation, data, fragmentation, transition, spillovers and capture.
4. **Indicators and outcomes** — leading indicators first, then final outcomes, costs and distribution.
5. **Evidence bodies** — direct England evidence and explicitly labelled transferable evidence.

### Layer B — Selected pathway

Selecting an expected benefit opens a left-to-right pathway showing:

- the mechanism;
- necessary or plausible enabling conditions;
- leading indicators;
- final outcomes;
- body-of-evidence confidence;
- direct and indirect sources separately; and
- a short note on what would be useful to learn during implementation.

### Layer C — Evidence cards

The accessible and mobile source of truth should use cards with:

1. expected-benefit pathway;
2. evidence confidence;
3. what public evidence suggests;
4. main limitations and transferability issues;
5. what implementation should monitor; and
6. selected sources.

## Evidence language

Use labels that describe **evidence confidence**, not policy approval:

- High
- Moderate
- Low–Moderate
- Low
- Very low direct evidence

Where estimates conflict, add `mixed evidence` rather than converting the conflict into a policy verdict.

Avoid labels such as:

- policy supported / unsupported;
- right / wrong;
- success / failure before outcomes are observable; or
- recommended / rejected where the underlying evidence only establishes uncertainty or implementation conditions.

## Interaction

Filters may include:

- expected benefit;
- mechanism;
- portfolio;
- geography;
- study design;
- directness / transferability;
- evidence confidence; and
- source type.

Department should remain optional metadata rather than the primary organising structure, because machinery of government changes over time and the evidence questions are often cross-government.

## Active benefits management view

A supplementary view should allow the user to move from evidence to monitoring:

1. specify the expected benefit;
2. identify the mechanism;
3. identify conditions that must hold;
4. select leading indicators;
5. track final outcomes, cost and distribution;
6. record evidence confidence and uncertainty; and
7. define how implementation would adapt if assumptions are not borne out.

The final action language should remain neutral and operational: `scale`, `redesign`, `support`, `pause`, `remediate`, `continue monitoring`.

## Accessibility

- Every pathway must be understandable without the graph.
- Evidence confidence must never be communicated by colour alone.
- Keyboard focus and selected states must be visible.
- Mobile should default to cards rather than a dense network.
- Reduced-motion settings should remove animated transitions.
- Source links, caveats and transferability notes should remain available without hover interactions.

## Reusable design

Although the current worked example concerns devolution and place, the same architecture should support other applications without redesigning the evidence model, including:

- public investment;
- prevention;
- AI and technology adoption;
- service integration;
- place-based allocation;
- local institutional capability; and
- other public-sector reforms.

The evidence map should therefore be understood as a **Public Value Evidence Lab**, with devolution as one worked example rather than the identity of the tool itself.
