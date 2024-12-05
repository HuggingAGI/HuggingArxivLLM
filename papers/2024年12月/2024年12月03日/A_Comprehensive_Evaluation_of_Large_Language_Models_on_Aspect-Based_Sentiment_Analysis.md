# 关于大型语言模型在基于方面的情感分析的全面评估

发布时间：2024年12月03日

`LLM应用` `情感分析`

> A Comprehensive Evaluation of Large Language Models on Aspect-Based Sentiment Analysis

# 摘要

> 近来，大型语言模型（LLMs）在自然语言处理领域备受关注，以强大的推理和生成能力变革了众多下游任务。比如，上下文学习（ICL）带来了无需微调的新模式，让开箱即用的LLMs能通过类比学习执行下游任务，无需任何微调操作。另外，在有大量训练数据的依赖微调范式中，作为高性价比的方法，参数高效微调（PEFT）让LLMs能取得和完全微调相当的出色表现。
然而，LLMs运用的这些出色技术在ABSA领域还未充分施展。以往的研究在ABSA中探索LLMs时，只是在ICL中随机选用输入 - 输出对作为示例，致使评估不全面、不深入。在本文中，我们对ABSA领域的LLMs展开了全面评估，涵盖13个数据集、8个ABSA子任务和6个LLMs。具体来说，我们设计了统一的任务公式，来统一“多个范式中多个ABSA子任务的多个LLMs”。对于依赖微调的范式，我们利用基于指令的多任务学习对LLMs进行有效微调。对于无需微调的范式，我们提出了3种示例选择策略来激发LLMs的少样本能力。我们大量的实验表明，在依赖微调的范式中，与微调的小型语言模型（SLMs）相比，LLMs达到了新的顶尖水平。更重要的是，在SLMs无效的无需微调范式中，具备ICL的LLMs依然展现出令人瞩目的潜力，甚至在某些ABSA子任务上能与微调的SLMs一较高下。

> Recently, Large Language Models (LLMs) have garnered increasing attention in the field of natural language processing, revolutionizing numerous downstream tasks with powerful reasoning and generation abilities. For example, In-Context Learning (ICL) introduces a fine-tuning-free paradigm, allowing out-of-the-box LLMs to execute downstream tasks by analogy learning without any fine-tuning. Besides, in a fine-tuning-dependent paradigm where substantial training data exists, Parameter-Efficient Fine-Tuning (PEFT), as the cost-effective methods, enable LLMs to achieve excellent performance comparable to full fine-tuning.
  However, these fascinating techniques employed by LLMs have not been fully exploited in the ABSA field. Previous works probe LLMs in ABSA by merely using randomly selected input-output pairs as demonstrations in ICL, resulting in an incomplete and superficial evaluation. In this paper, we shed light on a comprehensive evaluation of LLMs in the ABSA field, involving 13 datasets, 8 ABSA subtasks, and 6 LLMs. Specifically, we design a unified task formulation to unify ``multiple LLMs for multiple ABSA subtasks in multiple paradigms.'' For the fine-tuning-dependent paradigm, we efficiently fine-tune LLMs using instruction-based multi-task learning. For the fine-tuning-free paradigm, we propose 3 demonstration selection strategies to stimulate the few-shot abilities of LLMs. Our extensive experiments demonstrate that LLMs achieve a new state-of-the-art performance compared to fine-tuned Small Language Models (SLMs) in the fine-tuning-dependent paradigm. More importantly, in the fine-tuning-free paradigm where SLMs are ineffective, LLMs with ICL still showcase impressive potential and even compete with fine-tuned SLMs on some ABSA subtasks.

[Arxiv](https://arxiv.org/abs/2412.02279)