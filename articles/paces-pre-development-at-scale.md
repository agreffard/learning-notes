# Pre-Development at Scale: Modeling Risk in Early-Stage Solar Development
A data-driven framework for assessing and reducing risk in early-stage solar development.\
By Alex Oort Alonso, Kyle Baranko, Tony Wagler - [Paces](https://www.paces.com/), April 22, 2025


_Please note that these are my **personal learning notes**. Do not take them at face value, as I may have missed important details or misunderstood certain parts. Please refer to the original article for the full context._

[Full White Paper here](https://www.paces.com/white-papers/pre-development-at-scale-modeling-risk-in-early-stage-solar-development)

___


## Uncertainty In Early-Stage Development

**70%-90% of clean energy projects fail** — often after years of development and significant capital outlays — because critical risks aren’t identified early enough.

That means most development time and capital are spent on projects that never get built.

Paces set out to create a **standardized risk model** for early-stage clean energy projects that captures the key milestones and decision points across each risk category.

## Modeling Development Risk Over Time

Each milestone is assigned:
- a best and worstcase budget
- timeline
- a risk reduction score

reflecting the confidence or “information gained” in project viability by completing the milestone.

The core principle of our model is straightforward: **reduce the most risk** with the **smallest budget** as early in the development lifecycle as possible.

## Categories of Risk

1. **Site Control**:
    - **Landowner willingness**: developers must identify and engage landowners who are open to negotiating a lease or purchase at a price that aligns with the project’s economics
    - Developers are **competing with real estate investors**, industrial users, or housing developers who can often offer higher prices and move faster.
    - **Title issues** can emerge late in the process (unrecorded easements, unresolved ownership disputes, or restrictive covenants)
2. **Interconnection**
    - Interconnection in New York follows a standardized regulatory process, but it remains one of early-stage development's most consequential risk categories.
    - The **Coordinated Electric System Interconnection Review (CESIR)** is the highest-risk point in the interconnection process.
    - Compared to other community solar states, New York is more structured in its interconnection process and transparent regarding queue position and who specifically owns that position.

3. **Permitting**
    - Permitting risk is binary: a single vote can stop a project, regardless of technical merit or investment to date.
    - There is no remediation path for a denied special use permit.
4. **Environmental**
    - Environmental risk is one of the most difficult, expensive, and ultimately unpredictable aspects of early-stage development.
    - Sensitive habitats can trigger seasonal restrictions or halt permitting altogether, while wetlands, floodplains, or contamination risks may require expensive redesigns, mitigation plans, or even site abandonment.
5. **Design**
    - Design is both a cost driver and a viability gate, often revealing challenges that can't be seen from satellite imagery or landowner conversations alone.
    - Without adequate designs up-front, projects tend to shrink in size and energy/production yield once all factors are considered.


Additional factors excluded from this initial framework to maintain focus and clarity:
- off-take risk
- capital availability
- supply chain


## Using Project Archetypes to Calibrate Risk Profiles

To more accurately model development uncertainty, Paces introduces the concept of **project archetypes**: distinct risk profiles that shape how individual steps should be weighted across categories.

- **Archetype I – Environmental Constraints**
    - Sites located near known environmental hazards or sensitive areas should allocate an early budget to field studies that directly assess the specific constraint like wetlands, floodplains, or protected habitats to determine whether it poses a fatal flaw.
    - _Example de-risking strategy: Commission a full wetland delineation and report early, before committing CESIR funds._


- **Archetype II – Permitting Complexity (Sentiment)**
    - Developers should invest in local relationship-building early in the process to identify potential friction points and build goodwill.
    - _Example de-risking strategy: Meet with town officials, fire departments, and nearby residents to assess community sentiment before commissioning expensive studies._

- **Archetype III – Design Feasibility**
    - Developers must assess the cost and constructability of routing key infrastructure, like tie lines and access roads
    - _Example de-risking strategy: Advance site design early and initiate easement discussions with adjacent property owners._

- **Archetype IV – Capacity Viability**
    - In regions where substations appear to have limited remaining headroom but show large volumes of queued MW, developers must dig deeper. Queue data alone can be misleading, as many queued projects may never proceed.
    - _Example de-risking strategy: Get to a preliminary review meeting with the utility as fast as possible to assess the likelihood that queued capacity is firm before committing to costly interconnection studies or land expenses._

## Financial Model

Paces built a simplified financial model that captures both binary project failure and how escalating **development expenses (DevEx)** and **capital expenses (CapEx)** kill project viability, enabling us to compute an **expected portfolio IRR (Internal rate of return)**.

For each risk category, the model assigns:

- **A Financial Risk Scenario**: Adjusting DevEx and CapEx costs based on the best and worst case scenarios.
- **An Approval Risk Rating (1–15)**: Indicating the likelihood of the project advancing to subsequent milestones.

## Conclusion: The Pathway to Automation

- Building standardized development plans and classifying risk profiles at scale based on publicly available datasets enables developers to **assess site viability** and **forecast portfolio returns** before ever setting foot on the ground.
- With **high-quality geospatial data**, a **basic site design**, and knowledge of the **permitting and interconnection landscape**, much of the “pre-development” process can be front-loaded, identifying and reducing the majority of risk with a fraction of the time and effort typically required.

- The challenge isn’t just scale but the variability within that scale.
- Recent advances in AI offer a way to dramatically reduce this operational burden.
- Deployed effectively, intelligent agents can monitor correspondence with permitting authorities, flag when key milestones are reached, and automatically update timelines, budgets, and risk scores as new information becomes available.
- Automation adds value by enabling a **fundamentally new approach** to early-stage development:
    - **Machine-Driven**: eliminates the need for manual data entry
    - **Standardized**: creates a common language for development progress and risk evaluation
    - **Generalizable**: adapts across regions
    - **Empirical**: capturing and analyzing timelines, budgets, and success rates enables smarter decisions over time

These principles are central to Paces’ [Accelerated Development Framework](paces-accelerated-development-framework.md) .
