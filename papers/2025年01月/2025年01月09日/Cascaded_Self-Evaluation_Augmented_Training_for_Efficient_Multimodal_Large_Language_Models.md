# 级联自评估增强训练：打造高效多模态大语言模型

发布时间：2025年01月09日

`LLM应用

理由：这篇论文主要讨论了如何通过自我评估增强训练（SEAT）和级联自我评估增强训练（Cas-SEAT）来提升多模态大型语言模型（EMLLMs）的自我评估能力。这些方法涉及对模型的训练和推理策略进行优化，以提高其在特定任务上的性能。虽然论文中提到了思维链（CoT）推理和逐步自我评估等理论概念，但其核心内容集中在如何应用这些理论来改进EMLLMs的实际性能，因此更适合归类为LLM应用。`

> Cascaded Self-Evaluation Augmented Training for Efficient Multimodal Large Language Models

# 摘要

> 高效多模态大型语言模型（EMLLMs）近期发展迅猛。通过引入思维链（CoT）推理和逐步自我评估，其性能显著提升。然而，参数限制常使EMLLMs在推理时难以有效利用自我评估。主要挑战包括评估数据的合成、数量确定、训练与推理策略优化，以及提示选择。
    为此，我们提出了自我评估增强训练（SEAT）。SEAT利用更强大的EMLLMs进行CoT推理、数据选择和评估生成，随后用合成数据训练EMLLMs。然而，长提示处理和CoT推理质量维护仍是难题。因此，我们进一步提出级联自我评估增强训练（Cas-SEAT），将长提示拆解为更短的任务特定级联提示，降低资源有限环境下的成本。数据合成时，我们采用开源7B参数EMLLMs，并用短提示标注小数据集。
    实验证明，Cas-SEAT大幅提升了EMLLMs的自我评估能力，在MathVista、Math-V和We-Math数据集上的性能分别提升了19.68%、55.57%和46.79%。此外，Cas-SEAT数据集为未来EMLLM自我评估研究提供了宝贵资源。

> Efficient Multimodal Large Language Models (EMLLMs) have rapidly advanced recently. Incorporating Chain-of-Thought (CoT) reasoning and step-by-step self-evaluation has improved their performance. However, limited parameters often hinder EMLLMs from effectively using self-evaluation during inference. Key challenges include synthesizing evaluation data, determining its quantity, optimizing training and inference strategies, and selecting appropriate prompts.
  To address these issues, we introduce Self-Evaluation Augmented Training (SEAT). SEAT uses more powerful EMLLMs for CoT reasoning, data selection, and evaluation generation, then trains EMLLMs with the synthesized data. However, handling long prompts and maintaining CoT reasoning quality are problematic. Therefore, we propose Cascaded Self-Evaluation Augmented Training (Cas-SEAT), which breaks down lengthy prompts into shorter, task-specific cascaded prompts and reduces costs for resource-limited settings. During data synthesis, we employ open-source 7B-parameter EMLLMs and annotate a small dataset with short prompts.
  Experiments demonstrate that Cas-SEAT significantly boosts EMLLMs' self-evaluation abilities, improving performance by 19.68%, 55.57%, and 46.79% on the MathVista, Math-V, and We-Math datasets, respectively. Additionally, our Cas-SEAT Dataset serves as a valuable resource for future research in enhancing EMLLM self-evaluation.

[Arxiv](https://arxiv.org/abs/2501.05662)