# 📊 Strategic Product Initiative Prioritization Tool

An interactive, client-side web application designed to help Product Managers prioritize feature backlogs, align initiatives with high-level business objectives, and simulate resource constraints in real-time.

### 🔗 Live Link: [View Interactive App Here](https://dhavalk21.github.io/Product-Prioritization-Tool/)


## 🚀 Key Features

* __Objective-Aligned Planning:__ Every initiative is mapped to a primary business driver (e.g., Revenue Expansion, User Acquisition, Personalization, Operational Efficiency).

* __Customizable Scenario Simulator:__ Adjust active multipliers for Audience Volume (Reach), Risk Management (Confidence), and Engineering Cost (Effort) to simulate immediate changes in company strategy or technical bandwidth.

* __Interactive Resource Allocation:__ Automatically visualizes how technical resources (measured in Person-Months) are distributed across different company objectives.

* __Dynamic Prioritization:__ Instantly calculates both the Base RICE Score and the Simulated RICE Score, dynamically re-sorting the backlog pipeline.

* __Easy Collaboration:__ Features a one-click Markdown Export to copy your prioritized table directly into a Product Requirement Document (PRD), Notion workspace, or Slack channel.

## 🛠️ Built-in Strategic Metrics (The RICE Formula)

This engine calculates priorities using the standard RICE framework:

$$\text{RICE Score} = \frac{\text{Reach} \times \text{Impact} \times \text{Confidence}}{\text{Effort}}$$

Parameter Guidelines:

* __Reach:__ Estimated number of target users impacted per quarter.

* __Impact:__ Estimated contribution to the goal:

  * 3 = Critical/Massive Bet

  * 2 = High Value

  * 1 = Medium Value

  * 0.5 = Low/Minor Improvement

* __Confidence:__ Risk mitigation level based on available data:

  * 1.0 (100%) = Solid Data / High Confidence

  * 0.8 (80%) = Market Research / Medium Confidence

  * 0.5 (50%) = High Speculation / Low Confidence

* __Effort:__ Estimated development time measured in Person-Months (PM).

## 📋 Business Objectives Supported

To keep roadmap planning balanced and strategic, initiatives are classified under eight core business metrics:

* 🟢 __Revenue Expansion:__ Up-selling, cross-selling, and closing new customer contracts.

* 🔵 __Customer Retention:__ Improving system stability, reducing churn, and keeping existing users happy.

* 🔴 __User Acquisition:__ Growing top-of-funnel signups, trials, and organic traffic.

* 🟣 __Personalization:__ Tailoring custom dashboards, recommendations, and feed algorithms.

* 💗 __User Engagement:__ Deepening active usage, session duration, and feature adoption.

* 🔵 __Market Penetration:__ Launching into new geographic regions or business segments.

* 🟡 __Operational Efficiency:__ Addressing technical debt, optimizing queries, and building internal tools.

* ⚪ __Security & Compliance:__ Passing audits, managing user data privacy, and strengthening trust.
