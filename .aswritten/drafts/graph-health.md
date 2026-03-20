# Collective Memory Graph Analysis
Generated: 2024-05-24 | Snapshot: `worldview:all` | Nodes: 104 | Edges: 276

## Executive Summary
The graph is a highly specialized, practitioner-driven knowledge base focused on the "hidden curriculum" of NSF grant writing. It is structurally healthy with a strong "Hub-and-Spoke" topology centered on actionable grant-writing narratives. The top priority is connecting the "Open Stakes" claims to the "Settled Ground" to solidify the transition from individual practitioner advice to established institutional knowledge.

## Topology Overview
### Basic Metrics
| Metric | Value |
| :--- | :--- |
| **Total Nodes** | 104 |
| **Total Edges** | 276 |
| **Graph Density** | 0.026 (High for semantic graphs) |
| **Avg. Degree** | 5.3 connections/node |
| **Diameter** | 5 (Estimated) |

### Connectivity
*   **Connected Components**: 1 (The graph is fully connected via the `narr:` ontology).
*   **Largest Component Size**: 100% of nodes.
*   **Isolated Nodes**: 0 (All nodes are anchored to the ontology or a narrative).

## Importance Distribution
### Hub Concepts (Highest Degree)
1.  **Narrative_SpecificityOverAmbition** (12)
2.  **Narrative_VagueBudgetVaguePlan** (12)
3.  **Narrative_BiologyFramedComputation** (10)
4.  **Narrative_BudgetAsProjectPlan** (10)
5.  **Narrative_CompBioPreliminaryData** (10)
6.  **Narrative_HolisticScoringHeuristic** (10)
7.  **Narrative_InstitutionalCopyPaste** (10)
8.  **Narrative_IntegratedBroaderImpacts** (10)

### Bridge Concepts (Betweenness)
*   **Dr. James Thornton**: Bridges the "Computational Biology" domain with "General Grant Strategy."
*   **Narrative_TriageTriggers**: Connects negative "Anti-patterns" to positive "Strategic Frameworks."
*   **Claim_BudgetReadsLikeProjectPlan**: Bridges the "Organization" (Budgeting) and "Proof" (Execution) domains.

### Core vs. Periphery
*   **Core**: Grant Reviewer Psychology and Narrative Framing (Specific Aims, Significance).
*   **Periphery**: Specific tactical advice like "Supplies Lumping" or "US/UK Spelling" (Style).

## Community Structure
### Detected Communities
| Community Name | Size | Key Concepts | Internal Density |
| :--- | :--- | :--- | :--- |
| **Reviewer Psychology** | 25 nodes | `SpecificAimsPrimacy`, `HolisticScoring` | High |
| **Budgetary Strategy** | 18 nodes | `BudgetAsProjectPlan`, `TriageTriggers` | Medium |
| **Broader Impacts** | 15 nodes | `InstitutionalCopyPaste`, `Specificity` | High |
| **Comp-Bio Domain** | 12 nodes | `BiologyFramedComputation`, `Thornton` | Medium |

### Modularity Assessment
The graph shows **Low Modularity**. Domains are heavily "muddled" (interconnected), which is a strength here: it reflects how a single budget choice (Organization) impacts reviewer perception (Strategy).

## Coverage Map
### By Domain
| Domain | Node Count | Edge Count | Depth Score (1-10) |
| :--- | :--- | :--- | :--- |
| **Strategy** | 42 | 112 | 9 |
| **Organization** | 18 | 45 | 7 |
| **Proof** | 12 | 30 | 5 |
| **Style** | 15 | 22 | 4 |

### Dense Areas
*   **The "First 90 Seconds"**: Extremely rich detail on the Specific Aims page and initial reviewer gut reactions.
*   **Broader Impacts**: High density of claims regarding the failure of "Copy-Paste" institutional outreach.

### Sparse Areas
*   **Technical Documentation**: While the ontology supports it, there is little data on actual "API References" or "Schemas" for grant tracking.
*   **Style Metrics**: Many concepts exist (Readability, Jargon Density) but lack specific evidence/claims.

## Structural Issues
### Orphan Concepts
*   **narr:SpeakerProfile_ExampleLeader**: Defined in ontology but has no instances or claims attached. *Action: Populate with a specific persona or remove.*

### Dead Ends
*   **Claim_SuppliesLumpingSignal**: Has incoming support but no outgoing links to broader strategy nodes. *Action: Link to `Narrative_TriageTriggers`.*

### Potential Redundancies
*   **Narrative_SpecificityOverAmbition** vs. **Claim_SpecificityBeatsAmbition**: These are nearly identical. *Action: Merge the claim into the narrative as a supporting evidence node.*

## Opportunities
### High-Value Missing Links
*   **Link `Narrative_ReproducibilityAsBroaderImpact` to `Dr. James Thornton`**: Thornton's insights on comp-bio are the natural evidence base for reproducibility claims.
*   **Link `Style:PlainLanguage` to `Narrative_SpecificAimsPrimacy`**: Connect the tactical need for clarity to the strategic goal of winning the reviewer in 90 seconds.

### Synthesis Candidates
*   **Triage Anti-Patterns**: Multiple claims (Statistics lists, background-as-significance) could be synthesized into a single "Triage Taxonomy" node.

## Temporal Health
### Age Distribution
*   **Recent (2025)**: Budgeting and Comp-Bio insights (Thornton/Okafor).
*   **Dormant (2024)**: Reviewer Psychology (Chen).

### Recent Activity
*   The graph has grown significantly in the **Organization/Budgeting** domain in the last 30 days.

## Action Plan
1.  **Consolidate Specificity**: Merge `Claim_SpecificityBeatsAmbition` into `Narrative_SpecificityOverAmbition` to reduce redundancy.
2.  **Bridge the Gap**: Connect "Open Stakes" claims (e.g., `Claim_ThreePartStructure`) to "Settled Ground" narratives to increase graph conviction.
3.  **Flesh out Style**: Add 3-5 claims to the `Style` domain, specifically linking `JargonPolicy` to `Narrative_BiologyFramedComputation`.