# Early-Exit Deep Neural Network — A Comprehensive Survey

**Haseena Rahmath P et al.**  
*ACM Computing Surveys (2024), Vol. 57, No. 3, Article 75*  
📘 DOI: [10.1145/3698767](https://doi.org/10.1145/3698767)

---

### Overview
This repository accompanies our ACM Computing Surveys article  
**“Early-Exit Deep Neural Network — A Comprehensive Survey.”**  

The work unifies **150+ studies** on early-exit and dynamic-inference neural networks, analyzing their **architectures**, **training strategies**, **exit policies**, **application domains**, and **open challenges and future directions**.  
It provides a consolidated **taxonomy**, an **evolution timeline (2012–2024)**, and a structured discussion on how early-exit mechanisms contribute to **efficient and interpretable AI**.

---

### Main Contributions
1. **Unified Literature (150+ studies)** — Consolidates fragmented research under a coherent taxonomy of early-exit DNNs.  
2. **Benefit Analysis** — Highlights how early-exit networks mitigate latency, overfitting, overthinking, and vanishing-gradient challenges.  
3. **Architecture Review** — Describes backbone and side-branch structures that enable adaptive and intermediate inference.  
4. **Training & Exit Strategies** — Compares joint, two-stage, branch-wise, and hybrid training schemes, along with adaptive exit policies.  
5. **Evolution & Applications** — Maps the development of early-exit DNNs (2012–2024) and their use across computer vision, NLP, and signal processing.  
6. **Open Challenges & Future Directions** — Outlines unresolved problems and emerging research opportunities.

---

### Visual and Analytical Overview
The survey presents a cohesive visual and tabular narrative covering the full lifecycle of early-exit deep neural networks.  
Through conceptual illustrations, architectural schematics, training-flow diagrams, and policy frameworks, the paper constructs a layered understanding of how early-exit mechanisms evolve from conventional deep architectures into adaptive, multi-branch systems.  
Complementary tables synthesize architectural trends, training formulations, branching strategies, and exit-policy designs while emphasizing the strengths, limitations, and interconnections among approaches.  
Together, these elements offer a unified perspective on how early-exit DNNs balance computational efficiency, predictive reliability, and explainability across diverse domains.

---

### Citation
```bibtex
@article{10.1145/3698767,
  author    = {Rahmath P, Haseena and Srivastava, Vishal and Chaurasia, Kuldeep
               and Pacheco, Roberto G. and Couto, Rodrigo S.},
  title     = {Early-Exit Deep Neural Network — A Comprehensive Survey},
  year      = {2024},
  issue_date= {March 2025},
  publisher = {Association for Computing Machinery},
  address   = {New York, NY, USA},
  volume    = {57},
  number    = {3},
  issn      = {0360-0300},
  url       = {https://doi.org/10.1145/3698767},
  doi       = {10.1145/3698767},
  abstract  = {Deep neural networks (DNNs) typically have a single exit point that
               makes predictions by running the entire stack of neural layers.
               Since not all inputs require the same amount of computation to
               reach a confident prediction, recent research has focused on
               incorporating multiple “exits” into the conventional DNN architecture.
               Early-exit DNNs are multi-exit neural networks that attach side
               branches to the conventional DNN, enabling inference to stop early
               at intermediate points. This approach offers several advantages,
               including faster inference, mitigation of vanishing gradients,
               and reduction of overfitting and overthinking. It also supports
               DNN partitioning across devices and is ideal for multi-tier
               computation platforms such as edge computing. This article
               decomposes early-exit DNN architectures and reviews the advances
               in the field, exploring benefits, designs, training strategies,
               and adaptive inference mechanisms. Various design challenges,
               applications, and future directions are extensively discussed.},
  journal   = {ACM Comput. Surv.},
  month     = nov,
  articleno = {75},
  numpages  = {37},
  keywords  = {deep neural networks, early-exit neural network,
               multi-exit neural network, edge intelligence, inference acceleration}
}
