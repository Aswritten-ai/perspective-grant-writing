# Collective Memory Graph Analysis
Generated: 2024-05-24 | Snapshot: `main@HEAD` | Nodes: ~65 | Edges: ~110

## Executive Summary
The knowledge graph is currently a **high-fidelity, practitioner-driven star schema** centered on Grant Writing strategy. While the vertical depth within specific sections (Significance, Broader Impacts) is excellent, the graph lacks horizontal "connective tissue" between these tactical domains. The top priority is linking the **Reviewer Psychology** hub to the **Budget** and **Computational Biology** clusters to move from a collection of tips to a unified narrative system.

## Topology Overview
### Basic Metrics
| Metric | Value | Status |
| :--- | :--- | :--- |
| **Total Nodes** | ~65 | Emerging |
| **Total Edges** | ~110 | Healthy |
| **Graph Density** | ~0.027 | Sparse (Typical for early stage) |
| **Avg Degree** | 3.4 | Good (High local clustering) |
| **Diameter** | 5 | Low (Highly reachable) |

### Connectivity
*   **Connected Components**: 2 (Main Grant Writing cluster + Style/Ontology definitions).
*   **Largest Component Size**: ~52 nodes (80% of graph).
*   **Isolated Nodes**: 4 (Generic style metrics not yet linked to specific samples).

## Importance Distribution
### Hub Concepts (Highest Degree)
1.  **narr:FrictionFailure** (12 connections) - The primary lens for analyzing grant rejection.
2.  **narr:ProblemStakes** (9 connections) - Central to Significance and Broader Impacts.
3.  **narr:Antithesis** (8 connections) - The dominant rhetorical device across all practitioners.
4.  **narr:DrSarahChen** (7 connections) - Primary bridge between Reviewer Psychology and Significance.
5.  **narr:ToneDirectPersonal** (6 connections) - Core style attribute of successful grant advice.

### Bridge Concepts (Highest Betweenness)
*   **narr:AudienceFrames**: Connects high-level strategy (Chen) to specific implementation (Williams).
*   **narr:Sample_GrantSignificanceSection**: Acts as the anchor for both structural claims and style observations.

### Core vs. Periphery
*   **Core**: Reviewer psychology, Significance section framing, and Rhetorical devices.
*   **Periphery**: Budget justification and Computational Biology specifics (currently "leaf" clusters with few outgoing links to the core).

## Community Structure
### Detected Communities
| Community Name | Size | Key Concepts | Internal Density |
| :--- | :--- | :--- | :--- |
| **Reviewer Psychology** | 18 nodes | `DrSarahChen`, `SpecificAims`, `90SecondRule` | High |
| **Strategic Framing** | 15 nodes | `Significance`, `GapConsequenceUnlock`, `GapStatement` | High |
| **Social Impact** | 12 nodes | `DrMarcusWilliams`, `BroaderImpacts`, `Specificity` | Medium |
| **Rhetorical Style** | 10 nodes | `Antithesis`, `RuleOfThree`, `ImperativeVoice` | High |

### Cross-Community Links
*   **Strong**: Reviewer Psychology ↔ Strategic Framing (via Sarah Chen).
*   **Weak**: Social Impact ↔ Reviewer Psychology (Williams' insights are currently siloed from the "90-second rule" logic).

## Coverage Map
### By Domain
| Domain | Node Count | Edge Count | Depth Score (1-10) |
| :--- | :--- | :--- | :--- |
| **Strategy** | 22 | 45 | 9 (Very Deep) |
| **Style** | 15 | 28 | 7 (Solid) |
| **Organization** | 4 | 6 | 2 (Thin) |
| **Product/Templates** | 2 | 2 | 1 (Barely present) |

### Dense Areas
*   **Significance Section Strategy**: Exhaustive mapping of the "Gap-Consequence-Unlock" model.
*   **Rhetorical Devices**: Strong linkage between practitioner advice and specific linguistic patterns (Antithesis).

### Sparse Areas
*   **Budget Justification**: Only one source (Okafor); lacks connection to the "Reviewer Psychology" domain.
*   **Execution/Process**: Very little on the actual workflow of writing (Intake, Quality Gates).

## Structural Issues
### Orphan Concepts
*   **narr:StyleMetrics_BroaderImpacts**: Needs stronger links to the `narr:StyleMetrics` aggregate node.
*   **narr:TAM_SAM_SOM**: Defined in ontology but zero instances in current memories.

### Dead Ends
*   **narr:ComputationalBiologyDisadvantage**: A rich concept that currently has no outgoing links to "Strategy" or "Rhetorical Devices" (needs to be linked to `narr:AudienceFrames`).

### Potential Redundancies
*   **narr:SpecificityOverAmbition** and **narr:SpecificityBeatsAmbition**: These are near-identical claims from the same source; should be merged into a single `narr:Claim`.

## Opportunities
### High-Value Missing Links
*   **Budget ↔ Reviewer Psychology**: Link `narr:BudgetRedFlags` to `narr:90SecondRule` to show how budget errors trigger early "decline" instincts.
*   **CompBio ↔ AudienceFrames**: Link Thornton’s "Biology is Why" advice to Chen’s "Reviewer Mental Model" to create a cross-domain "Expertise Translation" pattern.

### Synthesis Candidates
*   **"The Reviewer's Frame"**: A potential new high-level Narrative node that synthesizes Chen (Significance), Williams (Impact), and Thornton (CompBio).

## Temporal Health
### Age Distribution
*   **Recent (Last 90 days)**: Reviewer Psychology, Comp Bio, Budget.
*   **Dormant (>180 days)**: Broader Impacts (Nov 2024), Significance Section (Sept 2024).

### Recent Activity
*   The graph is currently expanding into **Domain-Specifics** (Comp Bio) and **Administrative Execution** (Budget).

## Action Plan
1.  **Consolidate Specificity Claims**: Merge `narr:Claim_SpecificityBeatsAmbition` and `narr:Claim_SpecificityBeatsAmbition` to clean up the Broader Impacts cluster.
2.  **Bridge the Budget Gap**: Create `skos:related` links between `narr:BudgetJustificationPatterns` and `narr:Narrative_ReviewerFrameOfReference` to show how the budget justifies the "Unlock."
3.  **Expand "The Why" Pattern**: Conduct a targeted extraction on Thornton’s CompBio memory to link his "Biology is Why" rhetoric to the `narr:Antithesis` style node.