# 提示词分割与征服：利用分段分布式提示处理绕过大型语言模型安全过滤器

发布时间：2025年03月27日

`LLM应用` `网络安全`

> Prompt, Divide, and Conquer: Bypassing Large Language Model Safety Filters via Segmented and Distributed Prompt Processing

# 摘要

> 大型语言模型 (LLMs) 已经在多个领域实现了任务自动化和内容生成的革新，并内置了安全过滤器以防止滥用。我们提出了一种创新的越狱框架，通过结合分布式提示处理和迭代优化，成功绕过了这些安全措施，尤其在生成恶意代码方面表现突出。我们的架构由四个关键模块组成：提示分割、并行处理、响应聚合和基于 LLM 的陪审评估。在涵盖 10 个网络安全类别的 500 个恶意提示语上进行测试，该框架在生成恶意代码方面达到了 73.2% 的成功率 (SR)。值得注意的是，我们的比较分析显示，传统的单个 LLM 评委评估会高估 SR（93.8%），而我们的 LLM 陪审系统则给出了更为准确的 73.2% 的结果，人工验证也证实了单评委评估常常接受不完整的实现。此外，通过消融研究，我们展示了相较于非分布式方法，我们的分布式架构在 SR 上提升了 12%，这不仅证明了分布式提示处理的有效性，也凸显了在评估越狱尝试时采用稳健评估方法的重要性。

> Large Language Models (LLMs) have transformed task automation and content generation across various domains while incorporating safety filters to prevent misuse. We introduce a novel jailbreaking framework that employs distributed prompt processing combined with iterative refinements to bypass these safety measures, particularly in generating malicious code. Our architecture consists of four key modules: prompt segmentation, parallel processing, response aggregation, and LLM-based jury evaluation. Tested on 500 malicious prompts across 10 cybersecurity categories, the framework achieves a 73.2% Success Rate (SR) in generating malicious code. Notably, our comparative analysis reveals that traditional single-LLM judge evaluation overestimates SRs (93.8%) compared to our LLM jury system (73.2%), with manual verification confirming that single-judge assessments often accept incomplete implementations. Moreover, we demonstrate that our distributed architecture improves SRs by 12% over the non-distributed approach in an ablation study, highlighting both the effectiveness of distributed prompt processing and the importance of robust evaluation methodologies in assessing jailbreak attempts.

[Arxiv](https://arxiv.org/abs/2503.21598)