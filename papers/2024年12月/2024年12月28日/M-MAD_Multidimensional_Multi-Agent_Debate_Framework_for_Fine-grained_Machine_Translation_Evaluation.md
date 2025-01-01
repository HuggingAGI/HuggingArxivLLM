# M-MAD：用于细粒度机器翻译评估的多维多智能体辩论框架

发布时间：2024年12月28日

`LLM应用` `机器翻译` `语言模型`

> M-MAD: Multidimensional Multi-Agent Debate Framework for Fine-grained Machine Translation Evaluation

# 摘要

> 近期，大型语言模型（LLMs）的进步催生了“LLM 作为评判者”的范式，展现出其具备类人判断的潜力。然而，在机器翻译（MT）评估领域，当下的“LLM 作为评判者”方法比不上已有的自动指标。本文中，我们提出了多维多智能体辩论（M-MAD），这是一个基于 LLM 的系统多智能体框架，用于更高级的“LLM 作为评判者”的 MT 评估。我们的发现表明，M-MAD 取得了显著进步，其原因在于：（1）将启发式 MQM 标准分解到不同的评估维度，以实现细粒度评估；（2）运用多智能体辩论来发挥 LLM 的协同推理能力；（3）将特定维度的结果综合为最终评估判断，以确保结果的稳健可靠。全面的实验显示，M-MAD 不仅超越了所有现有的“LLM 作为评判者”方法，而且能与最先进的基于参考的自动指标相抗衡，即便由像 GPT-4o mini 这样的次优模型驱动。详细的消融实验和分析凸显了我们框架设计的优越性，为“LLM 作为评判者”范式提供了全新视角。我们的代码和数据在 https://github.com/SU-JIAYUAN/M-MAD 公开可用。

> Recent advancements in large language models (LLMs) have given rise to the LLM-as-a-judge paradigm, showcasing their potential to deliver human-like judgments. However, in the field of machine translation (MT) evaluation, current LLM-as-a-judge methods fall short of learned automatic metrics. In this paper, we propose Multidimensional Multi-Agent Debate (M-MAD), a systematic LLM-based multi-agent framework for advanced LLM-as-a-judge MT evaluation. Our findings demonstrate that M-MAD achieves significant advancements by (1) decoupling heuristic MQM criteria into distinct evaluation dimensions for fine-grained assessments; (2) employing multi-agent debates to harness the collaborative reasoning capabilities of LLMs; (3) synthesizing dimension-specific results into a final evaluation judgment to ensure robust and reliable outcomes. Comprehensive experiments show that M-MAD not only outperforms all existing LLM-as-a-judge methods but also competes with state-of-the-art reference-based automatic metrics, even when powered by a suboptimal model like GPT-4o mini. Detailed ablations and analysis highlight the superiority of our framework design, offering a fresh perspective for LLM-as-a-judge paradigm. Our code and data are publicly available at https://github.com/SU-JIAYUAN/M-MAD.

[Arxiv](https://arxiv.org/abs/2412.20127)