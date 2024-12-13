# Forest-of-Thought：通过扩展测试时计算来增强 LLM 推理能力

发布时间：2024年12月12日

`LLM应用` `语言模型`

> Forest-of-Thought: Scaling Test-Time Compute for Enhancing LLM Reasoning

# 摘要

> 大型语言模型（LLMs）在各类语言任务中表现出色，然而解决复杂推理问题仍具挑战。现有的诸如思维链（CoT）和思维树（ToT）等方法虽能通过分解问题或构建提示来强化推理，但往往只进行单次推理，可能无法重审有缺陷的路径，导致准确性受损。为此，我们提出了一种新颖的推理框架——思维森林（FoT），它整合了多个推理树，借助集体决策来解决复杂逻辑问题。FoT 采用稀疏激活策略来挑选最相关的推理路径，提升了效率与准确性。另外，我们引入了动态自我校正策略，能够实时纠错并从过往错误中学习，还有共识引导的决策策略，以优化正确性和计算资源。实验结果显示，FoT 框架与这些策略相结合，极大地增强了 LLMs 的推理能力，使其能够更精准、更高效地解决复杂任务。

> Large Language Models (LLMs) have shown remarkable abilities across various language tasks, but solving complex reasoning problems remains a challenge. While existing methods like Chain-of-Thought (CoT) and Tree-of-Thought (ToT) enhance reasoning by decomposing problems or structuring prompts, they typically perform a single pass of reasoning and may fail to revisit flawed paths, compromising accuracy. To address this, we propose a novel reasoning framework called Forest-of-Thought (FoT), which integrates multiple reasoning trees to leverage collective decision-making for solving complex logical problems. FoT utilizes sparse activation strategies to select the most relevant reasoning paths, improving both efficiency and accuracy. Additionally, we introduce a dynamic self-correction strategy that enables real-time error correction and learning from past mistakes, as well as consensus-guided decision making strategies to optimize correctness and computational resources. Experimental results demonstrate that the FoT framework, combined with these strategies, significantly enhances the reasoning capabilities of LLMs, enabling them to solve complex tasks with greater precision and efficiency.

[Arxiv](https://arxiv.org/abs/2412.09078)