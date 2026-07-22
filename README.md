# Digital Twin Supply Chain Simulation

A supply chain analytics project that uses digital twin simulation to evaluate inventory dynamics, demand variability, and the bullwhip effect across a multi-tier supply chain.

The project models a 16-entity supply chain under multiple demand scenarios to analyze inventory behavior, supply chain responsiveness, and operational resilience. Based on simulation results, strategic recommendations are proposed to improve inventory policies, reduce amplification effects, and enhance overall supply chain performance.

---

## Project Overview

Modern supply chains operate in increasingly uncertain environments where demand fluctuations can propagate upstream and create significant operational inefficiencies.

This project develops a digital twin simulation of a 16-entity supply chain to evaluate how different demand patterns affect inventory levels, order fulfillment, and coordination across the network.

The simulation explores multiple business scenarios ranging from sudden demand surges to seasonal demand cycles, providing insights into inventory management and supply chain resilience. :contentReference[oaicite:2]{index=2}

---

## Business Problem

Supply chain managers must balance multiple operational objectives:

- Maintain high customer service levels
- Minimize inventory holding costs
- Prevent stockouts
- Reduce the bullwhip effect
- Improve responsiveness to demand uncertainty

This project investigates several business questions:

- How does demand variability propagate through a multi-tier supply chain?
- Which supply chain entities experience the greatest inventory fluctuations?
- How can inventory policies reduce the bullwhip effect?
- What strategies improve resilience under uncertain demand conditions?

---

## Simulation Model

The project simulates a **16-entity supply chain**, including:

- Raw Material Processor
- Component Manufacturers
- Subassembly Suppliers
- Final Assembly Plant
- Global Distribution Center
- Regional Distribution Centers (RDCs)
- Retailers
- Customer

The digital twin captures inventory flows, replenishment decisions, and interactions among all entities to evaluate system-wide performance under changing demand conditions. :contentReference[oaicite:3]{index=3}

---

## Tools & Technologies

- Digital Twin Simulation
- Supply Chain Modeling
- Time Series Analysis
- Inventory Simulation
- Scenario Analysis
- Operations Analytics
- Supply Chain Analytics

---

## Project Workflow

1. Build a digital twin of a 16-entity supply chain.
2. Configure inventory and replenishment policies.
3. Simulate multiple demand scenarios.
4. Track inventory behavior across all entities.
5. Analyze bullwhip effect propagation.
6. Evaluate supply chain responsiveness.
7. Develop operational recommendations.

---

## Simulation Scenarios

### Scenario 1 – Demand Surge

Customer demand increased by **35%** beginning in Week 15.

The simulation showed that upstream suppliers experienced significantly larger inventory swings than downstream entities, illustrating the classic bullwhip effect. Inventory peaks occurred progressively later across the supply chain due to delayed adjustments. :contentReference[oaicite:4]{index=4}

---

### Scenario 2 – Continuous Demand Growth

Customer demand increased by **10% each week** until Week 60.

Retailers and distribution centers adapted gradually, while upstream manufacturers accumulated increasingly large inventories. The raw material processor exhibited the largest inventory fluctuations, demonstrating how sustained growth amplifies variability upstream. :contentReference[oaicite:5]{index=5}

---

### Scenario 3 – Continuous Demand Decline

Demand decreased by **10% each week**.

Downstream entities reduced inventory quickly, but upstream production remained slow to adjust. This resulted in substantial excess inventory and inefficient utilization of production resources. :contentReference[oaicite:6]{index=6}

---

### Scenario 4 – Demand Uncertainty

Customer demand fluctuated through alternating periods of increases and decreases.

The simulation demonstrated that rapidly changing demand patterns created repeated inventory oscillations, particularly among upstream suppliers. These fluctuations highlighted the importance of flexible inventory policies and improved demand visibility. :contentReference[oaicite:7]{index=7}

---

### Scenario 5 – Seasonal Supply Chain

A customized simulation based on Zara's fast-fashion supply chain modeled seasonal product launches and demand cycles.

Although downstream inventory remained relatively stable, upstream manufacturers experienced repeated inventory buildups due to delayed production adjustments and forecasting limitations. The results emphasized the importance of synchronized planning and agile production systems in seasonal industries. :contentReference[oaicite:8]{index=8}

---

## Key Findings

The simulation produced several important insights:

- Demand variability becomes increasingly amplified as it moves upstream.
- The raw material processor experienced the largest inventory swings across all scenarios.
- Delayed production adjustments significantly increase excess inventory.
- Real-time demand visibility reduces unnecessary inventory accumulation.
- Flexible inventory policies improve responsiveness under uncertain demand conditions.
- Seasonal demand requires coordinated planning across all supply chain tiers.

---

## Business Recommendations

Based on the simulation results:

- Improve demand forecasting using real-time sales information.
- Share demand data across supply chain partners to reduce information distortion.
- Implement adaptive safety stock policies instead of fixed inventory targets.
- Reduce production and replenishment lead times where feasible.
- Increase coordination between suppliers, manufacturers, and distribution centers.
- Use digital twin simulations for scenario planning and operational decision support before implementing policy changes.

---

## Repository Structure

```
digital-twin-supply-chain/

│
├── Project_Report.pdf
├── Project_Presentation.pdf
└── README.md
```

---

## Repository Contents

| File | Description |
|------|-------------|
| Project_Report.pdf | Detailed analysis of simulation scenarios, inventory dynamics, and operational recommendations |
| Project_Presentation.pdf | Presentation summarizing the digital twin model, simulation results, and business insights |
| README.md | Project documentation |

---

## Team

Master of Business Analytics

UBC Sauder School of Business

- Sisly Lyu
- Candice Miao
- Xiaoxi Xu
- Michael Ruizhe Zhang
  
---

## Future Improvements

Potential future enhancements include:

- Integrating real-time demand data into the digital twin.
- Evaluating supplier disruptions and transportation delays.
- Incorporating stochastic demand forecasting models.
- Optimizing inventory policies using simulation-based optimization.
- Developing an interactive dashboard for monitoring supply chain performance.

---

## Skills Demonstrated

- Digital Twin Simulation
- Supply Chain Analytics
- Inventory Management
- Bullwhip Effect Analysis
- Time Series Analysis
- Scenario Planning
- Supply Chain Modeling
- Operations Analytics
- Business Analytics
- Supply Chain Strategy
