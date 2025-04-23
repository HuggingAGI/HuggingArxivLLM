# 最坏情况下大型语言模型的版权侵权认证缓解方法

发布时间：2025年04月22日

`LLM应用` `版权保护` `内容生成`

> Certified Mitigation of Worst-Case LLM Copyright Infringement

# 摘要

> 大型语言模型（LLMs）在预训练过程中接触版权材料，引发了对其部署后可能无意中侵权的担忧。这一问题催生了旨在防止模型生成与版权内容实质性相似文本的“版权撤回”方法。尽管现有方法在应对一般风险时有一定效果，但我们发现它们忽视了最坏情况下的版权风险，具体表现为存在来自版权来源的长篇逐字引用。我们提出了一种名为BloomScrub的简单而高效的推理时版权撤回方法。该方法通过反复交替引用检测和重写技术，将潜在侵权内容转化为安全形式。借助高效的布隆过滤器，我们的方法即使在大规模真实语料库中也能实现可扩展的版权筛查。当引用过长无法移除时，系统可以选择不回应，从而提供经过认证的风险降低。实验结果表明，BloomScrub不仅降低了侵权风险，还保留了模型的实用性，并通过自适应的回应策略支持不同严格程度的版权执行标准。我们的研究表明，轻量级的推理时方法在版权预防方面可能出人意料地有效。

> The exposure of large language models (LLMs) to copyrighted material during pre-training raises concerns about unintentional copyright infringement post deployment. This has driven the development of "copyright takedown" methods, post-training approaches aimed at preventing models from generating content substantially similar to copyrighted ones. While current mitigation approaches are somewhat effective for average-case risks, we demonstrate that they overlook worst-case copyright risks exhibits by the existence of long, verbatim quotes from copyrighted sources. We propose BloomScrub, a remarkably simple yet highly effective inference-time approach that provides certified copyright takedown. Our method repeatedly interleaves quote detection with rewriting techniques to transform potentially infringing segments. By leveraging efficient data sketches (Bloom filters), our approach enables scalable copyright screening even for large-scale real-world corpora. When quotes beyond a length threshold cannot be removed, the system can abstain from responding, offering certified risk reduction. Experimental results show that BloomScrub reduces infringement risk, preserves utility, and accommodates different levels of enforcement stringency with adaptive abstention. Our results suggest that lightweight, inference-time methods can be surprisingly effective for copyright prevention.

[Arxiv](https://arxiv.org/abs/2504.16046)