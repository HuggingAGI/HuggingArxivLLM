# 强化微调自然缓解持续后训练中的遗忘问题

发布时间：2025年07月07日

`LLM应用` `多模态`

> Reinforcement Fine-Tuning Naturally Mitigates Forgetting in Continual Post-Training

# 摘要

> 持续后训练（CPT）是一种广泛应用于多模态大型语言模型的重要技术，能够使其适应快速变化的下游任务需求。尽管现有研究主要集中在数据重放、模型扩展等方法上，但持续后训练中学习范式的核心作用仍未得到充分探索。本文对持续后训练的两种核心范式——监督微调（SFT）和强化微调（RFT）进行了深入比较分析，研究它们在持续后训练过程中对知识保留的不同影响。我们的实验基于包含七种多样化多模态任务的基准数据集，并使用Qwen2.5-VL-7B-Instruct作为持续后训练的基础模型。研究发现：（1）在持续学习下游任务时，SFT会导致之前学习的任务出现灾难性遗忘，而RFT能够固有地保留先前知识，并达到与多任务训练相当的性能水平。（2）RFT成功保护并甚至增强了模型在标准基准测试（如MMMU和MMLU-Pro）中的通用知识。相反，SFT则严重削弱了模型的通用能力。进一步分析表明，显式机制（如KL惩罚和链式推理）并非主要影响因素。相反，我们发现强化微调中固有的隐式正则化是缓解遗忘的关键因素。最后，我们提出了一种基于展开的实例筛选算法，以提升RFT的稳定性和效率。本研究全面展示了RFT作为持续后训练稳健范式的优越性。

> Continual post-training (CPT) is a popular and effective technique for adapting foundation models like multimodal large language models to specific and ever-evolving downstream tasks. While existing research has primarily concentrated on methods like data replay, model expansion, or parameter regularization, the fundamental role of the learning paradigm within CPT remains largely unexplored. This paper presents a comparative analysis of two core post-training paradigms: supervised fine-tuning (SFT) and reinforcement fine-tuning (RFT), investigating their respective impacts on knowledge retention during CPT. Our experiments are conducted on a benchmark comprising seven diverse multimodal tasks, utilizing Qwen2.5-VL-7B-Instruct as the base model for continual post-training. The investigation yields two significant findings: (1) When continuously learning on downstream tasks, SFT leads to catastrophic forgetting of previously learned tasks. In contrast, RFT inherently preserves prior knowledge and achieve performance comparable to multi-task training. (2) RFT successfully protects and even enhances the model's general knowledge on standard benchmarks (e.g., MMMU and MMLU-Pro). Conversely, SFT degrades general model capabilities severely. Further analysis shows that explicit mechanisms, such as KL penalty and chain-of-thought reasoning, are not the primary factors. Instead, we find that the implicit regularization inherent to RFT is a key factor in mitigating forgetting. Finally, we propose a rollout-based instance filtering algorithm to improve the stability and efficiency of RFT. Our comprehensive study demonstrates the superiority of RFT as a robust paradigm for continual post-training.

[Arxiv](https://arxiv.org/abs/2507.05386)