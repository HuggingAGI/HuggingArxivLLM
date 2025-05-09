# 大型语言模型在智能辅导系统中构建逻辑问题证明与提示的前景与局限

发布时间：2025年05月07日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在智能辅导系统中的应用，特别是用于生成多步骤符号逻辑证明的逐步反馈。研究评估了LLMs在这一任务中的表现，并讨论了其在教育中的潜力和局限性。因此，它属于LLM应用类别。` `智能辅导系统`

> The Promise and Limits of LLMs in Constructing Proofs and Hints for Logic Problems in Intelligent Tutoring Systems

# 摘要

> 智能辅导系统在教授形式命题逻辑证明方面表现出了有效性，但其依赖模板式解释的特性限制了个性化反馈能力。大型语言模型（LLMs）在动态反馈生成方面潜力巨大，但存在幻觉或教育不严谨解释的风险。我们评估了LLMs在构建多步骤符号逻辑证明中的逐步准确性，比较了六种提示技术在四个最先进的LLMs上的表现，测试了358个命题逻辑问题。结果显示，DeepSeek-V3在逐步证明构建中达到了84.4%的准确率，并在简单规则上表现尤为突出。我们进一步使用表现最佳的LLM为一个逻辑ITS中的1,050个独特学生问题解决状态生成解释性提示，并通过LLM评分器和人类专家对20%的样本在四个标准上进行了评估。分析发现，LLM生成的提示准确率为75%，并在一致性与清晰度方面得到了高度评价，但在解释提示为何提供及其更广泛背景方面表现欠佳。结果表明，LLMs可用于为辅导系统提供逻辑辅导提示，但需要进一步改进以确保准确性和教育适宜性。

> Intelligent tutoring systems have demonstrated effectiveness in teaching formal propositional logic proofs, but their reliance on template-based explanations limits their ability to provide personalized student feedback. While large language models (LLMs) offer promising capabilities for dynamic feedback generation, they risk producing hallucinations or pedagogically unsound explanations. We evaluated the stepwise accuracy of LLMs in constructing multi-step symbolic logic proofs, comparing six prompting techniques across four state-of-the-art LLMs on 358 propositional logic problems. Results show that DeepSeek-V3 achieved superior performance with 84.4% accuracy on stepwise proof construction and excelled particularly in simpler rules. We further used the best-performing LLM to generate explanatory hints for 1,050 unique student problem-solving states from a logic ITS and evaluated them on 4 criteria with both an LLM grader and human expert ratings on a 20% sample. Our analysis finds that LLM-generated hints were 75% accurate and rated highly by human evaluators on consistency and clarity, but did not perform as well explaining why the hint was provided or its larger context. Our results demonstrate that LLMs may be used to augment tutoring systems with logic tutoring hints, but requires additional modifications to ensure accuracy and pedagogical appropriateness.

[Arxiv](https://arxiv.org/abs/2505.04736)