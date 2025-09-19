# Fair-GPTQ：面向大型语言模型的偏差感知量化

发布时间：2025年09月18日

`LLM理论` `基础理论`

> Fair-GPTQ: Bias-Aware Quantization for Large Language Models

# 摘要

> 生成式语言模型的高内存需求催生了对量化技术的研究关注——这种技术通过将模型权重映射为低精度整数，能有效降低计算成本、内存占用和延迟。尽管GPTQ等主流方法在量化时可显著减少输入-权重乘积误差，但近期实证研究发现，它们可能加剧输出偏见，导致公平性基准性能下降，且具体哪些权重引发该问题仍不明确。本研究通过在量化目标中引入显式群体公平性约束，首次建立了量化与模型公平性的深层关联，并提出Fair-GPTQ——全球首个专为减少大型语言模型不公平性设计的量化方法。新增约束引导舍入操作学习，以减少受保护群体的有偏文本生成，尤其聚焦职业偏见刻板印象及涉及性别、种族、宗教的歧视性语言。实验显示，Fair-GPTQ对性能影响微乎其微（零样本基准保留至少90%基线准确率），相比半精度模型显著降低不公平性，同时完整保留4位量化的内存与速度优势。与现有去偏方法对比发现，在种族刻板印象基准上，其性能已与迭代零空间投影去偏方法相当。综上，研究结果验证了带群体偏见项的量化问题理论解的有效性，证实其在生成模型量化阶段减少群体偏见的实用价值，并为量化过程中通道及权重级别对公平性的贡献分析提供了新工具。

> High memory demands of generative language models have drawn attention to quantization, which reduces computational cost, memory usage, and latency by mapping model weights to lower-precision integers. Approaches such as GPTQ effectively minimize input-weight product errors during quantization; however, recent empirical studies show that they can increase biased outputs and degrade performance on fairness benchmarks, and it remains unclear which specific weights cause this issue. In this work, we draw new links between quantization and model fairness by adding explicit group-fairness constraints to the quantization objective and introduce Fair-GPTQ, the first quantization method explicitly designed to reduce unfairness in large language models. The added constraints guide the learning of the rounding operation toward less-biased text generation for protected groups. Specifically, we focus on stereotype generation involving occupational bias and discriminatory language spanning gender, race, and religion. Fair-GPTQ has minimal impact on performance, preserving at least 90% of baseline accuracy on zero-shot benchmarks, reduces unfairness relative to a half-precision model, and retains the memory and speed benefits of 4-bit quantization. We also compare the performance of Fair-GPTQ with existing debiasing methods and find that it achieves performance on par with the iterative null-space projection debiasing approach on racial-stereotype benchmarks. Overall, the results validate our theoretical solution to the quantization problem with a group-bias term, highlight its applicability for reducing group bias at quantization time in generative models, and demonstrate that our approach can further be used to analyze channel- and weight-level contributions to fairness during quantization.

[Arxiv](https://arxiv.org/abs/2509.15206)