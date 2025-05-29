# 我们了解 LLM 的知识边界吗？一项关于知识探查一致性的研究

发布时间：2025年05月27日

`LLM理论` `人工智能`

> Do We Know What LLMs Don't Know? A Study of Consistency in Knowledge Probing

# 摘要

> 大型语言模型 (LLMs) 的可靠性因幻觉现象而严重受损，准确识别模型的知识缺口至关重要。现有知识缺口探测方法从基于校准到基于提示各不相同，本文提出了一种基于输入变体和定量指标的新评估流程。通过这一流程，我们发现了知识缺口探测中的两大不一致性： (1) 方法内不一致性：提示中的微小语义扰动即可导致同一方法下检测到的知识缺口出现显著差异，例如仅重新排序答案选项就可能将一致性降至约 40%。 (2) 方法间不一致性：不同探测方法对模型是否已知答案的判断存在矛盾。即使模型、数据集和提示完全一致，方法间的一致性仍低至 7%。这些发现对现有探测方法提出挑战，凸显了开发更稳健的扰动鲁棒探测框架的紧迫性。

> The reliability of large language models (LLMs) is greatly compromised by their tendency to hallucinate, underscoring the need for precise identification of knowledge gaps within LLMs. Various methods for probing such gaps exist, ranging from calibration-based to prompting-based methods. To evaluate these probing methods, in this paper, we propose a new process based on using input variations and quantitative metrics. Through this, we expose two dimensions of inconsistency in knowledge gap probing. (1) Intra-method inconsistency: Minimal non-semantic perturbations in prompts lead to considerable variance in detected knowledge gaps within the same probing method; e.g., the simple variation of shuffling answer options can decrease agreement to around 40%. (2) Cross-method inconsistency: Probing methods contradict each other on whether a model knows the answer. Methods are highly inconsistent -- with decision consistency across methods being as low as 7% -- even though the model, dataset, and prompt are all the same. These findings challenge existing probing methods and highlight the urgent need for perturbation-robust probing frameworks.

[Arxiv](https://arxiv.org/abs/2505.21701)