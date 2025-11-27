# Swarm Theorem Proving Framework
### **Collective Mathematical Reasoning with Swarm Solvers, Swarm Verifiers, and Hierarchical Reinforcement Learning**

This repository contains the research code, algorithms, and LaTeX paper for a novel multi-agent theorem-proving architecture.  
The system integrates:

- **Mathematical-Only Embedding Space**  
- **Swarm of Problem Solvers (SPS)**  
- **Swarm of Verifiers (SV)**  
- **Three-Layer Hierarchical Reinforcement Learning (H-RL)**  
- **Self-verifying multi-agent critique and refinement loops**

The goal is to explore how *collective intelligence* can be used to build AI systems that reason more robustly than single-model architectures.

---

## ✨ Key Features

### 🔹 1. Mathematical-Only Embedding Space  
All agents communicate using embeddings derived strictly from **symbolic mathematical expressions**, not natural-language tokens.  
This provides structural compositionality and reduces linguistic noise.

### 🔹 2. Swarm Problem Solvers  
Multiple solver agents independently generate candidate proofs with diverse strategies:
- cautious solvers  
- fast heuristic solvers  
- minimal pattern-based solvers  
- exploration-biased solvers

### 🔹 3. Swarm Verifiers  
Each verifier agent critiques proofs with different scoring policies and defect-detection heuristics:
- strict logical verifiers  
- structural verifiers  
- lenient verifiers  
- adversarial verifiers  

### 🔹 4. Hierarchical Reinforcement Learning (H-RL)
A 3-level RL hierarchy:

| Layer | Scope | Purpose |
|-------|--------|---------|
| **1** | Individual agents | Local correctness & alignment |
| **2** | Colony level | Diversity, consensus, and stability |
| **3** | Meta-controller | Long-horizon optimization & exploration scheduling |

### 🔹 5. Emergent Collaboration
Proof candidates, critiques, disagreement signals, consensus scores, and defect maps flow through a coordination module.

