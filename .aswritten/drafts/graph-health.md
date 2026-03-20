# Collective Memory Graph Analysis
Generated: 2025-03-20 | Snapshot: `main@HEAD` | Nodes: 68 | Edges: 124

## Executive Summary
The Grant Writing Collective graph is a **highly cohesive, practitioner-driven star schema** with deep expertise in reviewer psychology and structural grant framing. While the graph shows strong internal connectivity within tactical domains (Significance, Broader Impacts), it currently lacks a unified **Identity** and horizontal links between the **Budget** and **Reviewer Psychology** clusters. The top priority is codifying the organizational mission to move from a collection of expert tips to a unified strategic worldview.

## Topology Overview
### Basic Metrics
| Metric | Value | Status |
| :--- | :--- | :--- |
| **Total Nodes** | 68 | Emerging |
| **Total Edges** | 124 | Healthy |
| **Graph Density** | 0.027 | Sparse (Typical for early stage) |
| **Avg Degree** | 3.65 | Good (High local clustering) |
| **Diameter** | 5 | Low (Highly reachable) |

### Connectivity
- **Connected Components**: 2 (Main Narrative cluster + Style/Ontology definitions).
- **Largest Component Size**: 56 nodes (82% of graph).
- **Isolated Nodes**: 4 (Generic style metrics and unlinked ontology concepts like `narr:TAM_SAM_SOM`).

## Importance Distribution
### Hub Concepts (Highest Degree)
1. **narr:Narrative_ReviewerFrameOfReference** (12 connections) - The central anchor for Significance strategy.
2. **narr:Narrative_SpecificityOverAmbition** (12 connections) - Core principle for Broader Impacts.
3. **narr:Narrative_VagueBudgetVaguePlan** (12 connections) - Primary link between finance and credibility.
4. **narr:Actor_DrSarahChen** (9 connections) - Key bridge between Reviewer Psychology and Significance.
5. **narr:FrictionFailure** (8 connections) - The dominant lens for analyzing proposal rejection.

### Bridge Concepts (Highest Betweenness)
- **narr:AudienceFrames**: Connects high-level reviewer psychology (Chen) to specific implementation patterns (Williams).
- **narr:Sample_ReviewerReadingProcess**: Acts as the evidentiary anchor for both structural claims and style observations.

### Core vs. Periphery
- **Core**: Reviewer psychology, Significance section framing, and Broader Impacts.
- **Periphery**: Budget justification and Computational Biology (currently "leaf" clusters with few outgoing links to the strategic core).

## Community Structure
### Detected Communities
| Community Name | Size | Key Concepts | Internal Density |
| :--- | :--- | :--- | :--- |
| **Reviewer Psychology** | 18 nodes | `SpecificAimsPrimacy`, `90SecondRule`, `HolisticScoring` | High |
| **Strategic Framing** | 15 nodes | `GapConsequenceUnlock`, `SignificanceSectionFailure` | High |
| **Social Impact** | 12 nodes | `IntegratedBroaderImpacts`, `InstitutionalCopyPaste` | Medium |
| **Administrative Execution** | 10 nodes | `BudgetAsProjectPlan`, `EffortMilestoneAlignment` | Medium |

### Cross-Community Links
- **Strong**: Reviewer Psychology ↔ Strategic Framing (via Sarah Chen's dual expertise).
- **Weak**: Administrative Execution ↔ Reviewer Psychology (the link between budget errors and the "90-second gut reaction" is implied but not explicitly mapped).

## Coverage Map
### By Domain
| Domain | Node Count | Edge Count | Depth Score (1-10) |
| :--- | :--- | :--- | :--- |
| **Strategy** | 28 | 58 | 9 (Very Deep) |
| **Style** | 18 | 32 | 7 (Solid) |
| **Organization** | 4 | 6 | 2 (Thin) |
| **Identity** | 0 | 0 | 0 (Missing) |

### Dense Areas
- **Significance Section Strategy**: Exhaustive mapping of the "Gap-Consequence-Unlock" model.
- **Reviewer Interiority**: Strong linkage between practitioner quotes and the "90-second rule."

### Sparse Areas
- **Identity**: No mission statement or organizational "North Star" defined in the graph.
- **Computational Biology**: Mentioned in memories but lacks deep extraction into the `narr:Strategy` domain.

## Structural Issues
### Orphan Concepts
- **narr:TAM_SAM_SOM**: Defined in ontology but zero instances in current memories.
- **narr:StyleMetrics_BroaderImpacts**: Needs stronger links to the aggregate `narr:StyleMetrics` node.

### Dead Ends
- **narr:Claim_SuppliesLumpingSignal**: A rich insight that currently has no outgoing links to "Reviewer Psychology" (needs to be linked to `narr:Narrative_TriageTriggers`).

### Potential Redundancies
- **narr:Claim_SpecificityBeatsAmbition** and **narr:Narrative_SpecificityOverAmbition**: Overlapping definitions between a claim and its parent narrative.

## Opportunities
### High-Value Missing Links
- **Budget ↔ Triage Triggers**: Link `narr:Narrative_VagueBudgetVaguePlan` to `narr:Narrative_TriageTriggers` to show how budget errors trigger the "decline" instinct.
- **CompBio ↔ AudienceFrames**: Link Thornton’s "Biology is Why" advice to Chen’s "Reviewer Mental Model" to create a cross-domain "Expertise Translation" pattern.

### Synthesis Candidates
- **"The Reviewer's Frame"**: A potential new high-level Narrative node that synthesizes Chen (Significance), Williams (Impact), and Okafor (Budget).

## Temporal Health
### Age Distribution
- **Recent (Last 30 days)**: Budget Justification, Reviewer Psychology.
- **Dormant (>120 days)**: Broader Impacts (Nov 2024), Significance Section (Sept 2024).

### Recent Activity
- The graph is currently expanding into **Administrative Execution** (Okafor) and **Reviewer Interiority** (Chen).

## Action Plan
1. **Define Identity**: Save a memory explicitly defining the Grant Writing Collective's mission and unified methodology to populate the `Identity` section.
2. **Bridge the Budget Gap**: Create `skos:related` links between `narr:Narrative_VagueBudgetVaguePlan` and `narr:Narrative_TriageTriggers` to codify the budget as a primary triage signal.
3. **Consolidate Specificity**: Merge redundant specificity claims in the Broader Impacts domain to improve graph modularity.