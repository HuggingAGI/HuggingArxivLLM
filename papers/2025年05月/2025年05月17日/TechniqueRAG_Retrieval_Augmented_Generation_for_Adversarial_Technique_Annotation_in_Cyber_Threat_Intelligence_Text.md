# TechniqueRAG：网络威胁情报文本中对抗性技术标注的检索增强生成方法

发布时间：2025年05月17日

`RAG` `网络安全`

> TechniqueRAG: Retrieval Augmented Generation for Adversarial Technique Annotation in Cyber Threat Intelligence Text

# 摘要

> 精准识别安全文本中的对抗技术，是构建高效网络安全防御体系的关键所在。然而，当前技术手段面临着两难抉择：或是采用领域适用性有限的通用模型，或是依赖于大型标注数据集和复杂任务优化（如定制化难样本挖掘与降噪）的高资源消耗方案，这些资源在专业领域往往难以获取。
    为此，我们推出了一种名为TechniqueRAG的特定领域增强生成式检索框架（RAG），通过整合现成检索器、指令微调的LLM以及少量的文本-技术配对，成功突破了这一瓶颈。我们的创新方案仅需在有限的领域示例上微调生成模块，从而规避了高资源消耗的检索训练需求。传统RAG虽通过检索与生成的结合缓解了幻觉问题，但其对通用检索器的依赖常导致噪声干扰，影响领域精准度。针对这一痛点，我们借助零样本LLM重排序技术，显著提升了检索质量与领域适用性，实现检索结果与对抗技术的精准匹配。
    多项安全基准测试表明，TechniqueRAG在无需额外任务优化或标注数据的情况下，已达到业界顶尖水准，而深入的分析则进一步揭示了其内在优势。

> Accurately identifying adversarial techniques in security texts is critical for effective cyber defense. However, existing methods face a fundamental trade-off: they either rely on generic models with limited domain precision or require resource-intensive pipelines that depend on large labeled datasets and task-specific optimizations, such as custom hard-negative mining and denoising, resources rarely available in specialized domains.
  We propose TechniqueRAG, a domain-specific retrieval-augmented generation (RAG) framework that bridges this gap by integrating off-the-shelf retrievers, instruction-tuned LLMs, and minimal text-technique pairs. Our approach addresses data scarcity by fine-tuning only the generation component on limited in-domain examples, circumventing the need for resource-intensive retrieval training. While conventional RAG mitigates hallucination by coupling retrieval and generation, its reliance on generic retrievers often introduces noisy candidates, limiting domain-specific precision. To address this, we enhance retrieval quality and domain specificity through zero-shot LLM re-ranking, which explicitly aligns retrieved candidates with adversarial techniques.
  Experiments on multiple security benchmarks demonstrate that TechniqueRAG achieves state-of-the-art performance without extensive task-specific optimizations or labeled data, while comprehensive analysis provides further insights.

[Arxiv](https://arxiv.org/abs/2505.11988)