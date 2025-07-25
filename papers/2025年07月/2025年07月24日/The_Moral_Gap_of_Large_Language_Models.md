# # 大型语言模型的道德鸿沟

发布时间：2025年07月24日

`LLM应用

理由：该论文探讨了大型语言模型在道德推理任务中的应用表现，属于LLM在具体任务中的应用研究。` `社会学` `人工智能伦理`

> The Moral Gap of Large Language Models

# 摘要

> 道德基础检测是分析社会话语、开发符合伦理的人工智能系统的关键。尽管大型语言模型在多种任务中表现优异，但其在道德推理这一专门领域的表现仍有待验证。
    本研究首次通过 ROC、PR 和 DET 曲线分析，全面对比了最先进大语言模型与在 Twitter 和 Reddit 数据集上微调的变压器模型。 
    研究结果揭示了显著的性能差距：大语言模型尽管经过提示工程优化，仍存在高假阴率和系统性漏检道德内容的问题。这表明，在道德推理应用中，针对特定任务的微调方法仍优于单纯的提示方法。

> Moral foundation detection is crucial for analyzing social discourse and developing ethically-aligned AI systems. While large language models excel across diverse tasks, their performance on specialized moral reasoning remains unclear.
  This study provides the first comprehensive comparison between state-of-the-art LLMs and fine-tuned transformers across Twitter and Reddit datasets using ROC, PR, and DET curve analysis.
  Results reveal substantial performance gaps, with LLMs exhibiting high false negative rates and systematic under-detection of moral content despite prompt engineering efforts. These findings demonstrate that task-specific fine-tuning remains superior to prompting for moral reasoning applications.

[Arxiv](https://arxiv.org/abs/2507.18523)