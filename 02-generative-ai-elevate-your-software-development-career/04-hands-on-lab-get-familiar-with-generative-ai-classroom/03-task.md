# Software Development Methodologies

This document summarizes the primary software development methodologies and their key differences.

---

## 1. Waterfall
**Description:** Linear, sequential approach. Each phase (requirements, design, implementation, testing, deployment, maintenance) must be completed before moving to the next.

**Key Features:**
- Fixed scope and timeline
- Documentation-heavy
- Changes are difficult once the project is underway

**Best For:** Projects with well-defined requirements and low expected changes.  
**Drawbacks:** Inflexible; late discovery of issues can be costly.

---

## 2. Agile
**Description:** Iterative and incremental approach emphasizing flexibility, collaboration, and customer feedback.

**Key Features:**
- Short development cycles called **sprints** (1–4 weeks)
- Frequent stakeholder involvement
- Adaptive to changing requirements

**Best For:** Projects where requirements are expected to evolve.  
**Drawbacks:** Can lack formal documentation; requires disciplined team collaboration.

**Popular frameworks under Agile:**
- **Scrum:** Focuses on sprints, roles (Scrum Master, Product Owner), and ceremonies (standups, sprint review).
- **Kanban:** Visual workflow management using boards; emphasizes continuous delivery.
- **Extreme Programming (XP):** Emphasizes pair programming, test-driven development (TDD), and continuous integration.

---

## 3. DevOps
**Description:** Collaboration between development and operations teams for continuous integration, delivery, and deployment.

**Key Features:**
- Automation of build, testing, and deployment
- Continuous monitoring and feedback
- Focus on reliability and scalability

**Best For:** Projects requiring frequent releases and high operational stability.  
**Drawbacks:** Requires cultural change; can be complex to implement initially.

---

## 4. Spiral
**Description:** Combines iterative development with systematic risk analysis.

**Key Features:**
- Emphasis on risk management
- Iterative refinement of the product
- Each iteration produces a prototype or partial solution

**Best For:** Large, high-risk projects or projects with uncertain requirements.  
**Drawbacks:** Can be expensive and complex to manage.

---

## 5. Rapid Application Development (RAD)
**Description:** Focuses on fast prototyping and iterative delivery with minimal upfront planning.

**Key Features:**
- Quick iterations and frequent user feedback
- Emphasis on reusable components and tools
- Short development cycles

**Best For:** Projects with tight deadlines or rapidly changing requirements.  
**Drawbacks:** Less structured; can compromise scalability or maintainability.

---

## 6. Lean
**Description:** Derived from Lean manufacturing, emphasizes maximizing value and minimizing waste.

**Key Features:**
- Focus on efficiency and eliminating unnecessary processes
- Continuous improvement
- Customer-centric development

**Best For:** Teams aiming to improve productivity and reduce overhead.  
**Drawbacks:** Requires experienced teams to identify waste correctly.

---

## Key Differences Summary

| Methodology | Approach    | Flexibility | Iterations | Focus                                 |
|-------------|-------------|------------ |------------|---------------------------------------|
| Waterfall   | Linear      | Low         | No         | Documentation, planning               |
| Agile       | Iterative   | High        | Yes        | Customer feedback, adaptability       |
| DevOps      | Continuous  | High        | Yes        | Deployment, automation, collaboration |
| Spiral      | Risk-driven | Medium      | Yes        | Risk management, prototyping          |
| RAD         | Prototyping | High        | Yes        | Speed, rapid delivery                 |
| Lean        | Value-driven| Medium      | Yes        | Efficiency, reducing waste            |
