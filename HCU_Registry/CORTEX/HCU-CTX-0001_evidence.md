# Description:

**HCU-CTX-0001 (First_Principles_Deconstructor)** is designed to address the problem of **"Reasoning by Analogy."**

*   **Problem:** When faced with complex queries, AI (and humans) typically provide templated responses ("industry best practices") that are often inefficient, expensive, or contain hidden flaws.
*   **Objective:** To force the model to ignore "conventional wisdom" and derive a solution from scratch, relying solely on **physical constraints** and **fundamental facts**.
*   **Ideal Case:** "How to achieve X with a $0 budget?" or "Why is the system failing even though the code is technically correct?"

**Bottom Line:** This is a "filter" for complex engineering and business challenges.

---

## Evidence Log:

### 1. TEST_RUN REPORT
> **Target:** `HCU-CTX-0001` (First_Principles_Deconstructor).
> **Input:** "Design a method to transport 1,000 liters of water 5km across rough terrain with $0 budget."
> **Simulation Log:**
  - **Deconstruction (Hard Truths):** Water mass = 1000kg. Distance = 5000m. Friction coefficient = High (rough terrain). Budget = 0 implies no external energy source (fuel/electricity) and no purchased materials.
  - **Assumption Purge:** "Must use a truck" -> False. "Must use pipes" -> False. "Must carry it" -> False.
  - **Atomic Unit:** The container + The rolling mechanism.
  - **Zero-Base Solution:** The "Q-Drum" principle (Rolling Container).
  - **Reconstruction:** Locate discarded tires (Free resource). Seal sides with scavenged plastic/wood. Fill with water. Roll the tires.
  - **Physics Check:** Rolling friction < Sliding friction. 1000kg divided by 20 tires = 50kg per unit (manageable by human force).
> **Output:** Validated Low-Tech Engineering Solution.
> **Status:** ✅ PHYSICS_VERIFIED
