# # 评估开源大语言模型在自动事实核查中的评测

发布时间：2025年03月07日

`LLM应用` `事实核查` `信息真实性`

> Evaluating open-source Large Language Models for automated fact-checking

# 摘要

> 随着在线虚假信息的泛滥，自动事实核查的需求日益迫切。大型语言模型（LLMs）作为一种潜在工具，可以帮助完成这一任务，但其有效性仍有待验证。本研究评估了多种开源LLMs的事实核查能力，重点关注它们在不同上下文信息水平下评估声明的能力。我们进行了三个关键实验：（1）评估LLMs是否能够识别声明与事实核查文章之间的语义关系，（2）评估模型在给定相关事实核查文章时验证声明的准确性，（3）测试LLMs在利用Google和维基百科等外部知识来源进行事实核查的能力。我们的结果显示，LLMs在识别声明与文章之间的联系以及验证已核查的事实方面表现良好，但在确认事实新闻方面表现不佳，其效果甚至不及传统微调模型如RoBERTa。此外，引入外部知识并未显著提升LLMs的性能，这表明需要采用更定制化的解决方案。我们的研究结果凸显了LLMs在自动事实核查方面的潜力和局限性，强调在它们能够可靠取代人工事实核查员之前，仍需进一步改进。

> The increasing prevalence of online misinformation has heightened the demand for automated fact-checking solutions. Large Language Models (LLMs) have emerged as potential tools for assisting in this task, but their effectiveness remains uncertain. This study evaluates the fact-checking capabilities of various open-source LLMs, focusing on their ability to assess claims with different levels of contextual information. We conduct three key experiments: (1) evaluating whether LLMs can identify the semantic relationship between a claim and a fact-checking article, (2) assessing models' accuracy in verifying claims when given a related fact-checking article, and (3) testing LLMs' fact-checking abilities when leveraging data from external knowledge sources such as Google and Wikipedia. Our results indicate that LLMs perform well in identifying claim-article connections and verifying fact-checked stories but struggle with confirming factual news, where they are outperformed by traditional fine-tuned models such as RoBERTa. Additionally, the introduction of external knowledge does not significantly enhance LLMs' performance, calling for more tailored approaches. Our findings highlight both the potential and limitations of LLMs in automated fact-checking, emphasizing the need for further refinements before they can reliably replace human fact-checkers.

[Arxiv](https://arxiv.org/abs/2503.05565)