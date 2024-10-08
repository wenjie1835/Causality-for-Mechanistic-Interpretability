# Causality-for-Mechanistic-Interpretability
This repository features research papers focused on achieving mechanistic interpretability through causality. By leveraging causal reasoning, these studies aim to unravel how specific components in AI models contribute to decision-making processes, enhancing transparency and reliability in AI systems.
Contend

# Table of Contents: Causal Interpretability with Different Intervention Methods

-  [1.Patch-Based Methods](#patch-based-methods)
   - [1.1. Activation Patching](##Activation-Patching)
   - [1.2. Subgraph/Circuit Patching](##Subgrapg/Circiut-Patching)
   - [1.3. Feature Patching](##Feature-Patching)
   - [1.4. Hybrid Patching](##Global-Activation-Patching)
- [2. Ablation-Based Methods](#ablation-based-methods)
   - [2.1. Neuron Ablation](##Neuron-Ablation)
   - [2.2. Path Ablation](##Path-Ablation)
   - [2.3. Layer Ablation](##Layer-Ablation)
## Patch-Based Methods
Patching methods aim to analyze whether a component has the same impact in two scenarios by replacing the activation values, paths, or feature representations of a certain component in the model.
### Activation Patching
1. (arXiv 2024) **Towards Best Practices of Activation Patching in Language Models: Metrics and Methods.** _Bereska_. [[pdf](https://arxiv.org/abs/2309.16042)]
### Subgrapg/Circiut Patching
1. (ICLR 2024) **Is This the Subspace You Are Looking for? An Interpretability Illusion for Subspace Activation Patching.** _Makelov_. [[pdf](https://openreview.net/forum?id=Ebt7JgMHv1)]
2. (NIPS 2023) **Towards Automated Circuit Discovery for Mechanistic Interpretability.** _Conmy_. [[pdf](https://proceedings.neurips.cc/paper_files/paper/2023/file/34e1dbe95d34d7ebaf99b9bcaeb5b2be-Paper-Conference.pdf)]
### Feature Patching

### Hybrid Patching
1. (WWW 2024) **Interpretation-Empowered Neural Cleanse for Backdoor Attacks.** _Ning_. [[pdf](https://dl.acm.org/doi/abs/10.1145/3589335.3651525?casa_token=s2LGhymJRWoAAAAA:zijX22TzvSdlCr2xEuIpcVtPJP8DSI-XsFrtVxAI0y_MRJznM31GF4FVFENRyE03Knc8fkXDAo5Yog)]
## Ablation-Based Methods
Ablation methods evaluate the contribution of a component to the model's output by deleting or disabling that component.
### Neuron Ablation

### Path Ablation

### Layer Ablation

