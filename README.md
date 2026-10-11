# ⚛️ Quantum-Enhanced Secure Cluster-Based Routing & Optimization Framework for Heterogeneous IoT Networks

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/)
[![Patent Ready](https://img.shields.io/badge/Patent_Filing-20_Claims_Drafted-green.svg)](data/patent_specification.md)
[![Quantum Framework](https://img.shields.io/badge/Quantum_Engine-QSAHE%20%7C%20QSE--FCM%20%7C%20Q--PSO-purple.svg)]()
[![Scale](https://img.shields.io/badge/Scale-1000_Nodes_%7C_500_Active-blueviolet.svg)]()
[![Graphs](https://img.shields.io/badge/Results-10_Publication_Graphs-brightgreen.svg)]()
[![Streamlit UI](https://img.shields.io/badge/Dashboard-Cyber_Quantum_UI-00f2fe.svg)]()

A complete, state-of-the-art software-simulated **Quantum-Enhanced IoT Network Clustering, Trust Verification, and Multi-Objective Routing Platform**.
Configured for **1000 Total Nodes** with **500 Sample Execution Nodes** and an automated suite of **10 Publication-Quality Graph Visualizations**.

---

## 🌟 Core Innovations & Patentable Quantum Technologies

1. **Quantum State Amplitude Hilbert Embedding (QSAHE):**
   Transforms multi-attribute classical IoT sensor vectors $\mathbf{x}_i = [p_x, p_y, E, T, d_{bs}]^T$ into normalized quantum statevectors $|\psi(\mathbf{x}_i)\rangle \in \mathcal{H}^{2^n}$ and density operators $\rho_i = |\psi_i\rangle\langle\psi_i|$.

2. **Quantum Superposition Entropic Fuzzy C-Means (QSE-FCM):**
   Replaces Euclidean distance with Quantum Overlap State Fidelity $D_Q(\psi_i, \phi_j) = 1 - |\langle\psi_i|\phi_j\rangle|^2$, Von Neumann Entropic Coherence, and simulated quantum barrier tunneling to escape classical local minima saddle points.

3. **Quantum Density-Matrix Fidelity K-Means (QDF-KMeans):**
   Clustering directly in complex projective Hilbert space with quantum Frechet centroid state updates.

4. **Parameterized Quantum Variational Classifier (PQ-VQC):**
   A 4-qubit Parameterized Quantum Circuit (PQC) utilizing Hadamard state preparation, single-qubit $R_y(\theta), R_z(\phi)$ rotations, circular CNOT entanglement rings, and Pauli-$Z$ Hamiltonian expectation measurement $\langle Z_0 \otimes Z_1 \otimes Z_2 \otimes Z_3 \rangle$ for optimal Cluster-Head election.

5. **Quantum-Behaved Delta-Well Swarm Optimization (Q-PSO):**
   Route selection governed by the Schrödinger wave equation in a 1D delta potential well:
   $$X_{i,j}(t+1) = P_{i,j}(t) \pm \alpha(t) \cdot |C_j(t) - X_{i,j}(t)| \cdot \ln\left(\frac{1}{u}\right)$$
   guaranteeing global search diversity and eliminating classical velocity stagnation.

6. **Quantum Density Matrix Trace Fidelity Trust Estimator (QDMTF-TE):**
   Quantifies node forwarding trustworthiness via 2-level operational state projections, state purity $\gamma = \text{Tr}(\rho^2)$, and trace distance $D_{tr}(\rho_{node}, |1\rangle\langle 1|)$ to neutralize subtle grayhole, blackhole, and sybil attacks.

---

## 📊 Benchmark Paradigms (5-Way Comparison)

| Paradigm | Clustering Engine | Cluster Head Election | Routing Engine | Security Trust |
| :--- | :--- | :--- | :--- | :--- |
| **1. LEACH Baseline** | Spatial Random | Energy-Weighted Random | Dijkstra Shortest Path | None |
| **2. LEACH + PSO** | Spatial Random | Energy-Weighted Random | Classical Swarm (PSO) | None |
| **3. Proposed (Classical)** | Classical K-Means | Random Forest ML | Classical Swarm (PSO) | Classical Ratio |
| **4. Quantum-Inspired** | Quantum Fidelity K-Means | Parameterized VQC | Quantum Delta-Well (Q-PSO) | Quantum Trace Fidelity |
| **5. Full Quantum Superposition** | **Quantum Superposition FCM (QSE-FCM)** | **Parameterized VQC** | **Quantum Delta-Well (Q-PSO)** | **Quantum Density Matrix** |

---

## 📈 10 Publication-Quality Graph Results Suite

When running `main.py` or exploring the Streamlit Dashboard, the project generates 10 high-resolution (300 DPI) figures saved in `results/output/`:

1. **`1_network_topology.png`**: 2D Spatial Quantum-Clustered Topology (500-1000 nodes, clusters, VQC CH stars, adversaries, Base Station).
2. **`2_pdr_comparison.png`**: Packet Delivery Ratio (PDR %) comparison across all 5 paradigms.
3. **`3_latency_delay_comparison.png`**: Average End-to-End Hop Transmission Latency (ms) comparison.
4. **`4_energy_residual_distribution.png`**: Node Residual Energy (%) and lifetime depletion profile.
5. **`5_packet_loss_throughput.png`**: Packet Loss Ratio (%) vs Delivered Throughput under adversarial attack.
6. **`6_quantum_trust_purity_scatter.png`**: Quantum State Purity $\gamma = \text{Tr}(\rho^2)$ vs Quantum Trust ($T_Q$) decision boundary.
7. **`7_security_detection_matrix.png`**: Accuracy, Precision, Recall, and F1-Score breakdown for malicious node detection.
8. **`8_qpso_convergence_curve.png`**: Multi-Objective Hamiltonian Cost Convergence Curve (Q-PSO vs Classical PSO showing barrier tunneling).
9. **`9_clustering_evaluation_metrics.png`**: 4-Way Clustering benchmark on Silhouette Score and Quantum Coherence.
10. **`10_pareto_routing_tradeoff.png`**: Multi-Objective Routing Pareto Optimal Front (Energy vs Delay vs Distance vs Threat Risk).

---

## 🚀 Quick Start & Installation

```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Run full 1000-node generation, 500-node execution benchmark, and 10 graphs
python main.py

# 3. Launch the Futuristic Cyber-Quantum Web Dashboard (Includes 10-Graph Studio)
streamlit run dashboard/app.py
```

---

## 📜 Patent Specification Document

The project automatically compiles a formal, 20-claim United States Patent / Provisional Application Specification into `data/patent_specification.md` including:
- **Field of Invention & Background Art**
- **Detailed Mathematical Derivations & Proofs**
- **20 Formal Claims (Independent & Dependent)**
- **System Architecture & Industrial Applicability**

---

## 📁 Project Architecture

```
secure-iot-routing/
├── quantum/                          # Quantum Core Mathematical Engine
│   ├── quantum_embeddings.py         # QSAHE, Density Matrices, Bloch Sphere Projection
│   ├── quantum_clustering.py         # QDF-KMeans, QSE-FCM, Classical FCM & K-Means
│   ├── quantum_vqc_ch.py             # Parameterized Quantum Variational Classifier
│   ├── quantum_pso_routing.py        # Quantum Delta-Well Swarm Optimization (Q-PSO)
│   └── quantum_trust.py              # Quantum Density Matrix Trace Fidelity Trust
├── patent/                           # Patent Generation Engine
│   └── patent_spec.py                # Formal 20-Claim Patent Specification Compiler
├── simulation/
│   ├── node_generator.py             # 1000 Virtual IoT Nodes & 500-node sampling
│   ├── clustering.py                 # Clustering Dispatcher
│   ├── network.py                    # Fast KDTree Graph & Connectivity Engine
│   └── packet_simulation.py          # Fast Multi-Hop Packet Simulation & Energy Drain
├── ml/
│   ├── generate_dataset.py           # Synthetic Training Data Generator
│   ├── train_model.py                # Random Forest Trainer
│   └── predict_cluster_head.py       # ML Cluster Head Predictor
├── security/
│   ├── attack.py                     # Blackhole & Grayhole Attack Injection
│   ├── trust.py                      # Classical Trust Baseline
│   └── detection.py                  # Anomaly Detection Metrics
├── optimization/
│   └── pso.py                        # Classical PSO Routing Baseline
├── algorithms/
│   ├── leach.py                      # LEACH Baseline
│   └── shortest_path.py              # Dijkstra & k-Shortest Paths Baseline
├── results/
│   ├── metrics.py                    # PDR, Delay, Energy, Coherence Summarizer
│   ├── graphs.py                     # 10 Publication-Quality Matplotlib Graphs & Exporter
│   └── output/                       # 10 Output Visual PNGs and Summary CSVs
├── dashboard/
│   └── app.py                        # Cyber-Quantum Web Dashboard with 10-Graph Studio
├── pipeline.py                       # Master Pipeline Orchestrator (1000 Total / 500 Executed)
├── main.py                           # CLI Benchmark, 10-Graph Generator & Patent Compiler
└── requirements.txt
```
