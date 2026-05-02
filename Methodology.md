## 🧪 Methodology & Mathematical Framework

To transform qualitative domain research into an objective ranking, each of the 100 career paths was evaluated against **10 Core Criteria**. Each criterion is scored on a scale of 0 to 10.

### 📏 The 10 Core Criteria

| Criterion | Definition |
| :--- | :--- |
| **AI Resistance** | Ability to withstand automation by LLMs and autonomous coding agents. |
| **Demand Growth** | Projected global hiring volume increase based on industry trajectories. |
| **Earning Potential** | Global salary ceilings and compensation scaling. |
| **Barrier to Entry** | Difficulty of acquiring skills (protects against market saturation). |
| **Complexity** | Depth of architectural or systemic problem-solving required. |
| **Global Opportunity** | Ability to work remotely or cross-border without restrictions. |
| **Innovation Potential**| Proximity to cutting-edge research and new tech paradigms. |
| **Longevity** | Expected lifespan of the core technologies before obsolescence. |
| **Competition Level** | Volume of graduates competing (Reverse scored). |
| **Learning ROI** | Career return relative to educational time invested. |

---

### 🧮 Calculation Formulas

To calculate the final rankings, we apply two distinct mathematical models. The **Adjusted Score** utilizes exponential weighting to prioritize roles that excel in critical areas like *AI Resistance*.

#### 1. Base Final Score
The weighted average of all criteria:
$$Score = \frac{\sum (V_i \times W_i)}{\sum W_i}$$

#### 2. Adjusted Score (Exponential Weighting)
This formula punishes roles that fail in critical high-weight areas by amplifying the impact of higher-weighted variables:
$$Score_{adj} = \frac{\sum (V_i \times W_i^{1.5})}{\sum W_i^{1.5}}$$

> **Note:** $V$ represents the value assigned (0-10) and $W$ represents the assigned weight of the specific criterion.
