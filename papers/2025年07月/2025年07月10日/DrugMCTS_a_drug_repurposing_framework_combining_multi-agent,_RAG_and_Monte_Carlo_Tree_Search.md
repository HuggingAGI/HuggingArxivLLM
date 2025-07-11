# 药物重定位框架DrugMCTS：融合多智能体、RAG与蒙特卡洛树搜索的创新方案

发布时间：2025年07月10日

`LLM应用` `药物发现`

> DrugMCTS: a drug repurposing framework combining multi-agent, RAG and Monte Carlo Tree Search

# 摘要

> 大型语言模型在药物发现等科学领域展现出巨大潜力，但其推理能力仍受限于预训练知识范围。传统方法如微调或检索增强生成在计算效率或利用结构化科学数据方面存在局限。为此，我们提出DrugMCTS，一个融合RAG、多智能体协作和蒙特卡洛树搜索的新型药物重定位框架。通过五个专门智能体协同工作，DrugMCTS实现了结构化迭代推理，无需领域特定微调即可使Qwen2.5-7B-Instruct的表现超越Deepseek-R1达20%以上。在DrugBank和KIBA数据集上的实验结果表明，DrugMCTS在召回率和鲁棒性方面显著优于通用LLM和深度学习基准模型。这凸显了结构化推理、基于智能体的协作以及反馈驱动搜索机制在推进LLM药物发现应用中的关键作用。

> Recent advances in large language models have demonstrated considerable potential in scientific domains such as drug discovery. However, their effectiveness remains constrained when reasoning extends beyond the knowledge acquired during pretraining. Conventional approaches, such as fine-tuning or retrieval-augmented generation, face limitations in either imposing high computational overhead or failing to fully exploit structured scientific data. To overcome these challenges, we propose DrugMCTS, a novel framework that synergistically integrates RAG, multi-agent collaboration, and Monte Carlo Tree Search for drug repurposing. The framework employs five specialized agents tasked with retrieving and analyzing molecular and protein information, thereby enabling structured and iterative reasoning. Without requiring domain-specific fine-tuning, DrugMCTS empowers Qwen2.5-7B-Instruct to outperform Deepseek-R1 by over 20\%. Extensive experiments on the DrugBank and KIBA datasets demonstrate that DrugMCTS achieves substantially higher recall and robustness compared to both general-purpose LLMs and deep learning baselines. Our results highlight the importance of structured reasoning, agent-based collaboration, and feedback-driven search mechanisms in advancing LLM applications for drug discovery.

[Arxiv](https://arxiv.org/abs/2507.07426)