# DS$^2$-ABSA：用于少样本基于方面的情感分析的、具备标签细化的双流数据合成

发布时间：2024年12月19日

`LLM应用` `情感分析`

> DS$^2$-ABSA: Dual-Stream Data Synthesis with Label Refinement for Few-Shot Aspect-Based Sentiment Analysis

# 摘要

> 最近开发的大型语言模型（LLMs）为低资源场景下的数据稀缺问题开辟了充满希望的新道路。在少样本基于方面的情感分析（ABSA）领域，过往的努力探索了数据增强技术，促使LLMs通过修改现有样本生成新样本。然而，这些方法无法产生足够丰富多样的数据，影响了其效果。另外，一些研究借助特定指令和少量精选示例作为提示，将上下文学习应用于ABSA。虽然前景不错，但LLMs常常生成偏离任务要求的标签。为了突破这些局限，我们提出了DS$^2$-ABSA，这是一个针对少样本ABSA的双流数据合成框架。它借助LLMs从两个互补的视角合成数据：	extit{关键点驱动}和	extit{实例驱动}，能在低资源环境中有效生成多样且高质量的ABSA样本。此外，还融入了一个	extit{标签细化}模块来优化合成标签。大量实验表明，DS$^2$-ABSA明显优于以往的少样本ABSA解决方案以及其他面向LLM的数据生成方法。

> Recently developed large language models (LLMs) have presented promising new avenues to address data scarcity in low-resource scenarios. In few-shot aspect-based sentiment analysis (ABSA), previous efforts have explored data augmentation techniques, which prompt LLMs to generate new samples by modifying existing ones. However, these methods fail to produce adequately diverse data, impairing their effectiveness. Besides, some studies apply in-context learning for ABSA by using specific instructions and a few selected examples as prompts. Though promising, LLMs often yield labels that deviate from task requirements. To overcome these limitations, we propose DS$^2$-ABSA, a dual-stream data synthesis framework targeted for few-shot ABSA. It leverages LLMs to synthesize data from two complementary perspectives: \textit{key-point-driven} and \textit{instance-driven}, which effectively generate diverse and high-quality ABSA samples in low-resource settings. Furthermore, a \textit{label refinement} module is integrated to improve the synthetic labels. Extensive experiments demonstrate that DS$^2$-ABSA significantly outperforms previous few-shot ABSA solutions and other LLM-oriented data generation methods.

[Arxiv](https://arxiv.org/abs/2412.14849)