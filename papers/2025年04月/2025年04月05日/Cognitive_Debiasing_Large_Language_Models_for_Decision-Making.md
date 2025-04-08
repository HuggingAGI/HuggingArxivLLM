# # 认知去偏大型语言模型在决策中的应用
认知去偏大型语言模型在决策任务中表现优异，但目前我们对其在决策过程中动态机制的理解以及影响其表现的关键因素仍不充分。本研究旨在探讨这些模型在决策任务中的具体表现机制。

发布时间：2025年04月05日

`LLM应用` `决策支持`

> Cognitive Debiasing Large Language Models for Decision-Making

# 摘要

> 大型语言模型（LLMs）在金融、医疗和法律领域的决策支持应用中展现出巨大潜力，尤其是在作为个人对话助手时表现突出。尽管提示工程策略显著提升了LLMs的决策能力，但其内在的认知偏见仍是一个亟待解决的难题。认知偏见是决策过程中系统性偏离规范或理性思维的模式，可能导致输出结果不准确。现有的偏见缓解策略往往假设输入提示仅包含一种特定的偏见类型，这在现实场景中并不适用，因为实际情况可能涉及多种偏见。

针对这一挑战，我们提出了一种名为“自我去偏”（self-debiasing）的新方法，通过迭代优化提示来提升LLMs的可靠性。该方法包括三个关键步骤——偏见识别、偏见分析和认知去偏——逐步消除提示中的潜在偏见。实验结果表明，在无偏见、单偏见和多偏见的多种场景下，无论是闭源还是开源的LLMs，我们的自我去偏方法在准确率上均优于现有的提示工程技术和偏见缓解方法。

> Large language models (LLMs) have shown potential in supporting decision-making applications, particularly as personal conversational assistants in the financial, healthcare, and legal domains. While prompt engineering strategies have enhanced the capabilities of LLMs in decision-making, cognitive biases inherent to LLMs present significant challenges. Cognitive biases are systematic patterns of deviation from norms or rationality in decision-making that can lead to the production of inaccurate outputs. Existing cognitive bias mitigation strategies assume that input prompts contain (exactly) one type of cognitive bias and therefore fail to perform well in realistic settings where there maybe any number of biases.
  To fill this gap, we propose a cognitive debiasing approach, called self-debiasing, that enhances the reliability of LLMs by iteratively refining prompts. Our method follows three sequential steps -- bias determination, bias analysis, and cognitive debiasing -- to iteratively mitigate potential cognitive biases in prompts. Experimental results on finance, healthcare, and legal decision-making tasks, using both closed-source and open-source LLMs, demonstrate that the proposed self-debiasing method outperforms both advanced prompt engineering methods and existing cognitive debiasing techniques in average accuracy under no-bias, single-bias, and multi-bias settings.

[Arxiv](https://arxiv.org/abs/2504.04141)