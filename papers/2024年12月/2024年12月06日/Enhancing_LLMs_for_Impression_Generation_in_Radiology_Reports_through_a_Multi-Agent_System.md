# 借助多智能体系统来增强大型语言模型在放射学报告中的印象生成能力

发布时间：2024年12月06日

`Agent` `放射学`

> Enhancing LLMs for Impression Generation in Radiology Reports through a Multi-Agent System

# 摘要

> 本研究推出了“RadCouncil”，这一旨在提升放射学报告中从发现部分生成印象能力的多智能体大型语言模型（LLM）框架。RadCouncil 包含三个专门的智能体：其一为“检索”智能体，负责从向量数据库中识别并检索相似报告；其二是“放射科医生”智能体，依据给定报告的发现部分以及检索智能体所检索到的示例报告来生成印象；其三为“审查员”智能体，对生成的印象进行评估并提供反馈。RadCouncil 的性能通过定量指标（BLEU、ROUGE、BERTScore）以及由 GPT-4 评估的定性标准来衡量，以胸部 X 光作为案例进行研究。实验结果显示，RadCouncil 在包括诊断准确性、文体一致性和清晰度等多个维度上都优于单智能体方法。本研究凸显了利用多个相互作用且各有专属任务的 LLM 智能体来提升专业医疗任务表现以及开发更强大、适应性更强的医疗保健 AI 解决方案的潜力。

> This study introduces "RadCouncil," a multi-agent Large Language Model (LLM) framework designed to enhance the generation of impressions in radiology reports from the finding section. RadCouncil comprises three specialized agents: 1) a "Retrieval" Agent that identifies and retrieves similar reports from a vector database, 2) a "Radiologist" Agent that generates impressions based on the finding section of the given report plus the exemplar reports retrieved by the Retrieval Agent, and 3) a "Reviewer" Agent that evaluates the generated impressions and provides feedback. The performance of RadCouncil was evaluated using both quantitative metrics (BLEU, ROUGE, BERTScore) and qualitative criteria assessed by GPT-4, using chest X-ray as a case study. Experiment results show improvements in RadCouncil over the single-agent approach across multiple dimensions, including diagnostic accuracy, stylistic concordance, and clarity. This study highlights the potential of utilizing multiple interacting LLM agents, each with a dedicated task, to enhance performance in specialized medical tasks and the development of more robust and adaptable healthcare AI solutions.

[Arxiv](https://arxiv.org/abs/2412.06828)