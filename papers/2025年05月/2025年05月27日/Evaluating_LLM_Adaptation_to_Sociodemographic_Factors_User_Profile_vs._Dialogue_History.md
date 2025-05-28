# 探究大型语言模型如何适应社会人口统计因素：用户档案与对话历史的对比分析

发布时间：2025年05月27日

`LLM应用` `用户体验` `对话系统`

> Evaluating LLM Adaptation to Sociodemographic Factors: User Profile vs. Dialogue History

# 摘要

> 大型语言模型（LLMs）的有效互动需要根据用户的年龄、职业和教育水平等社会人口统计特征来调整回应。尽管许多实际应用利用对话历史进行情境化，但现有对LLMs行为调整的评估通常集中在单轮提示上。本文中，我们提出了一种框架，用于评估当属性通过（1）用户资料在提示中显式引入，或（2）通过多轮对话历史隐式引入时，LLMs的适应性。我们评估了模型行为在这些模式下的一致性。通过多智能体管道，我们构建了一个合成数据集，将对话历史与不同的用户资料配对，并使用价值调查模块（VSM 2013）中的问题来探测价值表达。我们的研究发现，大多数模型会根据人口统计变化调整其表达的价值观，尤其是在年龄和教育水平方面，但一致性存在差异。推理能力更强的模型表现出更大的一致性，这表明推理在稳健的社会人口统计适应中的重要性。

> Effective engagement by large language models (LLMs) requires adapting responses to users' sociodemographic characteristics, such as age, occupation, and education level. While many real-world applications leverage dialogue history for contextualization, existing evaluations of LLMs' behavioral adaptation often focus on single-turn prompts. In this paper, we propose a framework to evaluate LLM adaptation when attributes are introduced either (1) explicitly via user profiles in the prompt or (2) implicitly through multi-turn dialogue history. We assess the consistency of model behavior across these modalities. Using a multi-agent pipeline, we construct a synthetic dataset pairing dialogue histories with distinct user profiles and employ questions from the Value Survey Module (VSM 2013) (Hofstede and Hofstede, 2016) to probe value expression. Our findings indicate that most models adjust their expressed values in response to demographic changes, particularly in age and education level, but consistency varies. Models with stronger reasoning capabilities demonstrate greater alignment, indicating the importance of reasoning in robust sociodemographic adaptation.

[Arxiv](https://arxiv.org/abs/2505.21362)