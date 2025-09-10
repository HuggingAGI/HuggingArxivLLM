# 超越连贯性的事实性：评估医疗文本的大型语言模型水印方法

发布时间：2025年09月09日

`LLM应用` `医疗健康`

> Factuality Beyond Coherence: Evaluating LLM Watermarking Methods for Medical Texts

# 摘要

> 随着大型语言模型（LLMs）在医疗等敏感领域的应用，其流畅性却带来了安全隐患，尤其是在来源追溯与责任认定方面。水印技术通过嵌入可检测模式来缓解这些风险，但其在医疗场景中的可靠性尚未得到验证。现有评估基准多聚焦于检测质量的权衡，却忽视了水印重加权策略常利用的低熵环境下的事实风险。为此，我们提出了一套医疗专用评估工作流，可同时评估事实准确性与连贯性。借助GPT-Judger工具及进一步的人工验证，我们引入了事实性加权分数（FWS）——这一综合指标优先考量事实准确性而非连贯性，旨在为医疗领域水印技术的部署提供指导。评估结果显示，当前水印方法显著损害医疗事实性，且熵变化会降低医疗实体的表示质量。这些发现凸显了开发领域感知水印方法的必要性，以保障医疗内容的完整性。

> As large language models (LLMs) adapted to sensitive domains such as medicine, their fluency raises safety risks, particularly regarding provenance and accountability. Watermarking embeds detectable patterns to mitigate these risks, yet its reliability in medical contexts remains untested. Existing benchmarks focus on detection-quality tradeoffs, overlooking factual risks under low-entropy settings often exploited by watermarking's reweighting strategy. We propose a medical-focused evaluation workflow that jointly assesses factual accuracy and coherence. Using GPT-Judger and further human validation, we introduce the Factuality-Weighted Score (FWS), a composite metric prioritizing factual accuracy beyond coherence to guide watermarking deployment in medical domains. Our evaluation shows current watermarking methods substantially compromise medical factuality, with entropy shifts degrading medical entity representation. These findings underscore the need for domain-aware watermarking approaches that preserve the integrity of medical content.

[Arxiv](https://arxiv.org/abs/2509.07755)