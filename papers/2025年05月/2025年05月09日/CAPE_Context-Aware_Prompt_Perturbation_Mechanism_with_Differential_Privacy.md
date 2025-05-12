# CAPE：上下文感知提示微调机制，带有差分隐私特性

发布时间：2025年05月09日

`LLM应用` `隐私保护` `信息处理`

> CAPE: Context-Aware Prompt Perturbation Mechanism with Differential Privacy

# 摘要

> 大型语言模型（LLMs）凭借其出色的文本理解和生成能力备受瞩目。尽管它们在ChatGPT等推理服务中广泛应用，但敏感用户数据泄露的风险也随之而来。现有解决方案主要依赖隐私增强技术，但始终面临效率、隐私与效用的权衡难题。为解决这一问题，我们提出了Cape——一种基于差分隐私的上下文感知提示微调机制，旨在实现更高效的推理并优化隐私与效用的平衡。具体而言，我们引入了更精准捕捉标记相似性的混合效用函数，并设计了分桶采样机制来应对大采样空间带来的长尾现象。通过在多个数据集上的广泛实验和消融研究，结果表明Cape在隐私-效用权衡方面显著优于现有最优方法。

> Large Language Models (LLMs) have gained significant popularity due to their remarkable capabilities in text understanding and generation. However, despite their widespread deployment in inference services such as ChatGPT, concerns about the potential leakage of sensitive user data have arisen. Existing solutions primarily rely on privacy-enhancing technologies to mitigate such risks, facing the trade-off among efficiency, privacy, and utility. To narrow this gap, we propose Cape, a context-aware prompt perturbation mechanism based on differential privacy, to enable efficient inference with an improved privacy-utility trade-off. Concretely, we introduce a hybrid utility function that better captures the token similarity. Additionally, we propose a bucketized sampling mechanism to handle large sampling space, which might lead to long-tail phenomenons. Extensive experiments across multiple datasets, along with ablation studies, demonstrate that Cape achieves a better privacy-utility trade-off compared to prior state-of-the-art works.

[Arxiv](https://arxiv.org/abs/2505.05922)