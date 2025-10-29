# 📦 Supply Chain Logistics Network Optimization : LP vs Genetic Algorithm

Supply chain logistics network problems have received significant attention among organizations due to their impact on cost efficiency and service performance. This notebook presents a model for a company operating multiple plants that serve geographically dispersed market zones. The goal is to allocate product demand across these plants while minimizing the total cost, which includes sourcing, manufacturing, and distribution.

---

## 🧠 Model Assumptions

1. **Single Product, Multi-Echelon System**  
   The supply chain includes multiple levels (plants → distributors → retailers) but focuses on a single product. We consider two stages for the numerical application.

2. **Deterministic Demand**  
   Demand at each market zone is known and remains constant throughout the study period.

3. **Unlimited Distributor Capacity**  
   Distributors are assumed to have no capacity constraints.

4. **Zero Transportation Lead Time**  
   Transportation time from plants to distributors and from distributors to retailers is considered negligible.

5. **Plant Capacity Constraint**  
   The total units sent to all distributors must not exceed the production capacity of the plants.

6. **Flow Conservation at Distributors**  
   All units entering a distributor must be dispatched—no inventory is held.

7. **Cost Parameters**  
   - Production cost per unit: 1.5 €
   - Distribution costs include transportation from plants to retailers and vice versa.
