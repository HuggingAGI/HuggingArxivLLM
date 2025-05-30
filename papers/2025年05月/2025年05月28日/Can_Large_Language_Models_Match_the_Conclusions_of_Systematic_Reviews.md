# 大型语言模型能否与系统综述的结论相匹配？

发布时间：2025年05月28日

`LLM应用` `临床研究`

> Can Large Language Models Match the Conclusions of Systematic Reviews?

# 摘要

> 系统综述（SR）是基于证据的临床决策、研究和政策制定的基石。专家们通过总结和分析个体研究中的证据，为专门主题提供见解。随着科学论文的指数级增长，人们越来越感兴趣利用大型语言模型（LLMs）来自动化生成系统综述。然而，LLMs在批判性评估证据和跨多份文件推理以提供与领域专家相同水平建议的能力仍然研究不足。因此，我们提出问题：当大型语言模型能够访问到相同的文献时，它们是否能够与临床专家撰写的系统综述结论相匹配？

为了探索这一问题，我们提出了MedEvidence，一个将100份系统综述的研究发现与其所依据的文献配对的基准测试。我们对24种LLMs在MedEvidence上的表现进行了评估，包括推理型、非推理型、医学专业型以及不同规模（从70亿到7000亿参数）的模型。通过系统性评估，我们发现：推理能力并不必然提升表现，更大模型也并非始终带来更大增益，而基于知识的微调在MedEvidence上反而降低了准确度。相反，大多数模型表现出相似的行为：性能随着token长度增加而下降，它们的回答显得过于自信，并且与人类专家相反，所有模型对低质量研究发现缺乏应有的科学怀疑态度。

这些结果表明，尽管这些系统已经部署并被临床医生使用，但大型语言模型要可靠地匹配专家级系统综述的观察结果，仍需进一步研究。我们向更广泛的科研界公开了代码库和基准测试，以便进一步研究基于LLMs的系统综述系统。

> Systematic reviews (SR), in which experts summarize and analyze evidence across individual studies to provide insights on a specialized topic, are a cornerstone for evidence-based clinical decision-making, research, and policy. Given the exponential growth of scientific articles, there is growing interest in using large language models (LLMs) to automate SR generation. However, the ability of LLMs to critically assess evidence and reason across multiple documents to provide recommendations at the same proficiency as domain experts remains poorly characterized. We therefore ask: Can LLMs match the conclusions of systematic reviews written by clinical experts when given access to the same studies? To explore this question, we present MedEvidence, a benchmark pairing findings from 100 SRs with the studies they are based on. We benchmark 24 LLMs on MedEvidence, including reasoning, non-reasoning, medical specialist, and models across varying sizes (from 7B-700B). Through our systematic evaluation, we find that reasoning does not necessarily improve performance, larger models do not consistently yield greater gains, and knowledge-based fine-tuning degrades accuracy on MedEvidence. Instead, most models exhibit similar behavior: performance tends to degrade as token length increases, their responses show overconfidence, and, contrary to human experts, all models show a lack of scientific skepticism toward low-quality findings. These results suggest that more work is still required before LLMs can reliably match the observations from expert-conducted SRs, even though these systems are already deployed and being used by clinicians. We release our codebase and benchmark to the broader research community to further investigate LLM-based SR systems.

[Arxiv](https://arxiv.org/abs/2505.22787)