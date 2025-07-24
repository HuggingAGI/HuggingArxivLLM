# 驾驭 RLHF 实现 LLM 的健壮不可回答性识别与可靠响应生成。

发布时间：2025年07月22日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）在对话式信息检索系统中处理不可回答问题的能力，提出了SALU方法，通过多任务学习和强化学习来提升模型的自我意识和判断能力。研究重点在于改进LLM的生成机制，属于LLM的理论层面。` `对话式信息检索` `问答系统`

> Harnessing RLHF for Robust Unanswerability Recognition and Trustworthy Response Generation in LLMs

# 摘要

> 对话式信息检索（CIR）系统虽然提供了直观的信息获取方式，但如何可靠地处理无法回答的问题，以避免生成误导性或虚构内容，是其面临的核心挑战。传统方法依赖外部分类器，这可能与LLM生成过程产生不一致。本文提出了一种名为Self-Aware LLM for Unanswerability（SALU）的新方法，将不可回答性检测深度集成到LLM的生成过程中。SALU采用多任务学习框架，既进行标准问答（QA），又生成不可回答查询的显式弃用。其创新点在于引入了一个基于置信度评分的带有用户反馈的强化学习（RLHF）阶段，该阶段通过惩罚虚构回答和奖励适当弃用来培养模型对知识边界的自我意识。在我们的C-IR_Answerability数据集上进行的大量实验表明，SALU在正确回答或弃用问题的整体准确性方面优于现有方法。人工评估进一步证实了SALU的可靠性，其在事实准确性、适当弃用以及显著减少虚构内容方面表现优异，证明了它能够稳健地“知道何时说‘我不知道’”。

> Conversational Information Retrieval (CIR) systems, while offering intuitive access to information, face a significant challenge: reliably handling unanswerable questions to prevent the generation of misleading or hallucinated content. Traditional approaches often rely on external classifiers, which can introduce inconsistencies with the core generative Large Language Models (LLMs). This paper introduces Self-Aware LLM for Unanswerability (SALU), a novel approach that deeply integrates unanswerability detection directly within the LLM's generative process. SALU is trained using a multi-task learning framework for both standard Question Answering (QA) and explicit abstention generation for unanswerable queries. Crucially, it incorporates a confidence-score-guided reinforcement learning with human feedback (RLHF) phase, which explicitly penalizes hallucinated responses and rewards appropriate abstentions, fostering intrinsic self-awareness of knowledge boundaries. Through extensive experiments on our custom-built C-IR_Answerability dataset, SALU consistently outperforms strong baselines, including hybrid LLM-classifier systems, in overall accuracy for correctly answering or abstaining from questions. Human evaluation further confirms SALU's superior reliability, achieving high scores in factuality, appropriate abstention, and, most importantly, a dramatic reduction in hallucination, demonstrating its ability to robustly "know when to say 'I don't know'."

[Arxiv](https://arxiv.org/abs/2507.16951)