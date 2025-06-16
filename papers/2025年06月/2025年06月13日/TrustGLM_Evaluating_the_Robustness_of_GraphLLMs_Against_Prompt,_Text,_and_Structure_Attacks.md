# TrustGLM: 图语言模型（GraphLLMs）在面对提示、文本和结构攻击时的鲁棒性评估

发布时间：2025年06月13日

`LLM应用` `图学习` `对抗攻击`

> TrustGLM: Evaluating the Robustness of GraphLLMs Against Prompt, Text, and Structure Attacks

# 摘要

> 受大型语言模型（LLMs）成功的启发，研究领域正经历一场从传统图学习方法向基于LLMs的图框架（正式称为GraphLLMs）的重大转向。GraphLLMs通过整合三个关键组件，充分挖掘了LLMs的推理能力：输入节点的文本属性、节点邻域的结构信息，以及指导决策的任务特定提示。尽管前景光明，但GraphLLMs在面对对抗性扰动时的鲁棒性仍未得到充分探索——这在高风险场景中部署这些模型时是一个关键问题。为填补这一空白，我们提出了TrustGLM，一项全面研究，旨在评估GraphLLMs在文本、图结构和提示操控三个维度上抵御对抗攻击的脆弱性。我们从每个视角实施了最先进的攻击算法，以严格评估模型的韧性。通过在来自不同领域的六个基准数据集上进行广泛实验，我们的发现揭示，GraphLLMs极易受到仅替换节点文本属性中少数语义相似词的文本攻击。我们还发现，标准的图结构攻击方法能显著降低模型性能，而随机打乱提示模板中的候选标签集则会导致性能大幅下降。除了表征这些漏洞外，我们还研究了针对每种攻击向量的数据增强训练和对抗训练防御技术，这些方法展现了增强GraphLLMs鲁棒性的巨大潜力。我们希望开源的TrustGLM库能促进快速、公平的评估，并激发该领域进一步的创新研究。

> Inspired by the success of large language models (LLMs), there is a significant research shift from traditional graph learning methods to LLM-based graph frameworks, formally known as GraphLLMs. GraphLLMs leverage the reasoning power of LLMs by integrating three key components: the textual attributes of input nodes, the structural information of node neighborhoods, and task-specific prompts that guide decision-making. Despite their promise, the robustness of GraphLLMs against adversarial perturbations remains largely unexplored-a critical concern for deploying these models in high-stakes scenarios. To bridge the gap, we introduce TrustGLM, a comprehensive study evaluating the vulnerability of GraphLLMs to adversarial attacks across three dimensions: text, graph structure, and prompt manipulations. We implement state-of-the-art attack algorithms from each perspective to rigorously assess model resilience. Through extensive experiments on six benchmark datasets from diverse domains, our findings reveal that GraphLLMs are highly susceptible to text attacks that merely replace a few semantically similar words in a node's textual attribute. We also find that standard graph structure attack methods can significantly degrade model performance, while random shuffling of the candidate label set in prompt templates leads to substantial performance drops. Beyond characterizing these vulnerabilities, we investigate defense techniques tailored to each attack vector through data-augmented training and adversarial training, which show promising potential to enhance the robustness of GraphLLMs. We hope that our open-sourced library will facilitate rapid, equitable evaluation and inspire further innovative research in this field.

[Arxiv](https://arxiv.org/abs/2506.11844)