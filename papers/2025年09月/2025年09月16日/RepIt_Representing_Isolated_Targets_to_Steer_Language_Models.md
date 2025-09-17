# RepIt：孤立目标表示引导语言模型

发布时间：2025年09月16日

`LLM理论` `基础理论`

> RepIt: Representing Isolated Targets to Steer Language Models

# 摘要

> 尽管大型语言模型（LLMs）的激活引导研究日益兴起，但现有方法常产生超出预期的广泛影响。这推动了更纯净概念向量的分离，从而实现精准干预，并在更精细层面理解LLM行为。我们提出RepIt——一个简单且数据高效的框架，专门用于分离特定概念的表示。在五个前沿LLMs上，RepIt实现了精准干预：它能选择性抑制对目标概念的拒绝，同时保留其他场景的拒绝行为，所生成的模型既能回答大规模杀伤性武器（WMD）相关问题，又能在标准基准测试中保持安全评分。我们进一步发现，校正信号仅定位在100-200个神经元上，且在单个A6000上，仅需十几个示例就能提取出稳健的目标表示。这种高效性也带来了双重隐忧：仅需少量计算资源和数据就能实施操纵，进而扩展到数据稀缺、代表性不足的主题，同时避开现有基准测试。通过RepIt分离拒绝向量，本研究证明精准干预可抵消过度泛化，为更精细地控制模型行为奠定了基础。

> While activation steering in large language models (LLMs) is a growing area of research, methods can often incur broader effects than desired. This motivates isolation of purer concept vectors to enable targeted interventions and understand LLM behavior at a more granular level. We present RepIt, a simple and data-efficient framework for isolating concept-specific representations. Across five frontier LLMs, RepIt enables precise interventions: it selectively suppresses refusal on targeted concepts while preserving refusal elsewhere, producing models that answer WMD-related questions while still scoring as safe on standard benchmarks. We further show that the corrective signal localizes to just 100-200 neurons and that robust target representations can be extracted from as few as a dozen examples on a single A6000. This efficiency raises a dual concern: manipulations can be performed with modest compute and data to extend to underrepresented data-scarce topics while evading existing benchmarks. By disentangling refusal vectors with RepIt, this work demonstrates that targeted interventions can counteract overgeneralization, laying the foundation for more granular control of model behavior.

[Arxiv](https://arxiv.org/abs/2509.13281)