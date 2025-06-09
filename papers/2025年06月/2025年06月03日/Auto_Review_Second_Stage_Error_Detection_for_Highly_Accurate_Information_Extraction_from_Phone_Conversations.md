# 第二阶段错误检测：从电话对话中实现高精度信息提取的自动审查方法

发布时间：2025年06月03日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLM）来解决医疗领域自动化福利验证电话中的信息提取问题。通过引入后处理管道，结合多种ASR替代方案和伪标签方法，显著提升了电话记录的质量，从而提高了自动化审核系统的效率。研究重点在于LLM的实际应用，因此归类为LLM应用。`

> Auto Review: Second Stage Error Detection for Highly Accurate Information Extraction from Phone Conversations

# 摘要

> 自动化福利验证电话能够节省医疗领域大量时间，同时让患者更快获得治疗。这些电话中的信息准确性至关重要，因为它直接影响患者的医疗体验。由于电话记录中的噪声问题，我们采用了一个两阶段系统，其中包括一个针对潜在噪声字段的电话后审查阶段，由人工审核员手动验证提取的数据——这是一项劳动密集型任务。为了自动化这一阶段，我们引入了Auto Review，它在保持高准确性标准的同时大幅减少了人工 effort。然而，由于该系统高度依赖电话记录，并且受到自动语音识别（ASR）问题的性能瓶颈影响，这一问题在电话中使用领域特定术语时进一步加剧。在本研究中，我们提出了一种后处理管道，用于准确提取信息。通过使用多种ASR替代方案以及无需手动校正记录的伪标签方法，我们提高了准确性。使用通用大型语言模型和基于特征的模型管道进行的实验表明，校正后的电话记录质量有了显著提升，从而提高了Auto Review的效率。

> Automating benefit verification phone calls saves time in healthcare and helps patients receive treatment faster. It is critical to obtain highly accurate information in these phone calls, as it can affect a patient's healthcare journey. Given the noise in phone call transcripts, we have a two-stage system that involves a post-call review phase for potentially noisy fields, where human reviewers manually verify the extracted data$\unicode{x2013}$a labor-intensive task. To automate this stage, we introduce Auto Review, which significantly reduces manual effort while maintaining a high bar for accuracy. This system, being highly reliant on call transcripts, suffers a performance bottleneck due to automatic speech recognition (ASR) issues. This problem is further exacerbated by the use of domain-specific jargon in the calls. In this work, we propose a second-stage postprocessing pipeline for accurate information extraction. We improve accuracy by using multiple ASR alternatives and a pseudo-labeling approach that does not require manually corrected transcripts. Experiments with general-purpose large language models and feature-based model pipelines demonstrate substantial improvements in the quality of corrected call transcripts, thereby enhancing the efficiency of Auto Review.

[Arxiv](https://arxiv.org/abs/2506.05400)