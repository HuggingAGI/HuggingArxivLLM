# RoCA：鲁棒跨域端到端自动驾驶技术

发布时间：2025年06月11日

`LLM应用` `自动驾驶` `自动驾驶系统`

> RoCA: Robust Cross-Domain End-to-End Autonomous Driving

# 摘要

> 端到端（E2E）自动驾驶作为新兴范式，正展现出巨大潜力。然而，跨域部署的实际挑战（如不同城市间的适配）却鲜有研究关注。尽管已有研究尝试将大型语言模型（LLMs）融入其中以利用其开放世界知识，但LLMs无法保证跨域驾驶性能，且在领域适应过程中可能产生高昂的再训练成本。本文提出了一种名为RoCA的新颖框架，专注于实现鲁棒的跨域端到端自动驾驶。RoCA通过联合概率分布对E2E流水线中编码自车及周围车辆信息的tokens进行建模。采用高斯过程（GP）实例化后，RoCA能够学习一组具有对应轨迹的基础tokens，这些tokens能够覆盖多样化的驾驶场景。由此，面对任意驾驶场景，RoCA均能进行概率性未来轨迹推断。通过将RoCA与基础E2E模型结合进行源域训练，我们显著提升了基础模型的泛化能力，且无需额外的推理计算。此外，RoCA在新目标域上的鲁棒适应能力表现尤为突出，显著超越了直接微调的效果。我们对RoCA进行了全面的跨域场景评估，结果表明其在域泛化和适应性能方面均表现优异。

> End-to-end (E2E) autonomous driving has recently emerged as a new paradigm, offering significant potential. However, few studies have looked into the practical challenge of deployment across domains (e.g., cities). Although several works have incorporated Large Language Models (LLMs) to leverage their open-world knowledge, LLMs do not guarantee cross-domain driving performance and may incur prohibitive retraining costs during domain adaptation. In this paper, we propose RoCA, a novel framework for robust cross-domain E2E autonomous driving. RoCA formulates the joint probabilistic distribution over the tokens that encode ego and surrounding vehicle information in the E2E pipeline. Instantiating with a Gaussian process (GP), RoCA learns a set of basis tokens with corresponding trajectories, which span diverse driving scenarios. Then, given any driving scene, it is able to probabilistically infer the future trajectory. By using RoCA together with a base E2E model in source-domain training, we improve the generalizability of the base model, without requiring extra inference computation. In addition, RoCA enables robust adaptation on new target domains, significantly outperforming direct finetuning. We extensively evaluate RoCA on various cross-domain scenarios and show that it achieves strong domain generalization and adaptation performance.

[Arxiv](https://arxiv.org/abs/2506.10145)