# ELV-Halluc：长视频理解任务中语义聚合幻觉的评测基准

发布时间：2025年08月29日

`LLM应用` `媒体与娱乐`

> ELV-Halluc: Benchmarking Semantic Aggregation Hallucinations in Long Video Understanding

# 摘要

> 视频多模态大型语言模型（Video-MLLMs）在视频理解领域已取得显著进展，但其仍易产生与视频输入不一致或无关的幻觉内容。以往的视频幻觉基准主要针对短视频，将幻觉归因于强语言先验、帧缺失或视觉编码器引入的视觉-语言偏差等因素。尽管这些原因确实能解释短视频中的大部分幻觉，却仍过度简化了幻觉的成因。有时，模型会输出错误结果，但其帧级语义却是正确的。我们将此类幻觉命名为语义聚合幻觉（SAH），它源于将帧级语义聚合为事件级语义组的过程。由于长视频中多事件的语义复杂性更高，SAH的影响尤为突出，因此亟需单独且深入地探究这类幻觉的成因。为解决上述问题，我们提出了首个专注于长视频幻觉的基准ELV-Halluc，以实现对SAH的系统性研究。实验证实了SAH的存在，并发现其发生率随语义复杂性的提升而增加。此外，我们还发现模型在语义快速变化的场景下更易出现SAH。同时，我们探讨了缓解SAH的潜在策略：研究表明位置编码策略有助于减轻SAH，我们进一步采用DPO策略以增强模型对事件内及事件间语义的区分能力。为此，我们构建了包含8K对抗性数据对的数据集，在ELV-Halluc和Video-MME上均实现了性能提升，其中SAH比率大幅降低27.7%。

> Video multimodal large language models (Video-MLLMs) have achieved remarkable progress in video understanding. However, they remain vulnerable to hallucination-producing content inconsistent with or unrelated to video inputs. Previous video hallucination benchmarks primarily focus on short-videos. They attribute hallucinations to factors such as strong language priors, missing frames, or vision-language biases introduced by the visual encoder. While these causes indeed account for most hallucinations in short videos, they still oversimplify the cause of hallucinations. Sometimes, models generate incorrect outputs but with correct frame-level semantics. We refer to this type of hallucination as Semantic Aggregation Hallucination (SAH), which arises during the process of aggregating frame-level semantics into event-level semantic groups. Given that SAH becomes particularly critical in long videos due to increased semantic complexity across multiple events, it is essential to separate and thoroughly investigate the causes of this type of hallucination. To address the above issues, we introduce ELV-Halluc, the first benchmark dedicated to long-video hallucination, enabling a systematic investigation of SAH. Our experiments confirm the existence of SAH and show that it increases with semantic complexity. Additionally, we find that models are more prone to SAH on rapidly changing semantics. Moreover, we discuss potential approaches to mitigate SAH. We demonstrate that positional encoding strategy contributes to alleviating SAH, and further adopt DPO strategy to enhance the model's ability to distinguish semantics within and across events. To support this, we curate a dataset of 8K adversarial data pairs and achieve improvements on both ELV-Halluc and Video-MME, including a substantial 27.7% reduction in SAH ratio.

[Arxiv](https://arxiv.org/abs/2508.21496)