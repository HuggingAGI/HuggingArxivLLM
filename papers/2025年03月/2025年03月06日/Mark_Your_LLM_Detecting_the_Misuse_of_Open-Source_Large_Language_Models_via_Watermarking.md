# 为你的LLM打上水印：利用水印技术识别开源大模型的不当使用

发布时间：2025年03月06日

`LLM应用` `软件开发` `版权保护`

> Mark Your LLM: Detecting the Misuse of Open-Source Large Language Models via Watermarking

# 摘要

> 随着开源大型语言模型（如Llama3）能力的不断提升，开发水印技术以防范其滥用变得尤为重要。现有水印技术要么在推理过程中添加水印，这并不适用于开源模型，要么主要针对分类模型，而非当前的生成模型。将这些技术应用于开源模型以检测滥用仍是一个待解难题。本研究针对开源LLMs界定了两类滥用情形：知识产权（IP）侵权与LLM使用违规。我们进一步探究了推理时水印蒸馏与后门水印在这两种情境中的适用性。为评估不同微调场景对水印的影响及其对模型性能的作用，我们提出了全面的评估方案。实验结果表明，后门水印在检测IP侵权方面表现优异，而推理时水印蒸馏虽适用于两种场景，但面对进一步微调时鲁棒性较低，且对模型性能的影响更为显著。未来，探索更先进的水印技术以检测开源LLMs的滥用行为，将是值得深耕的重要方向。

> As open-source large language models (LLMs) like Llama3 become more capable, it is crucial to develop watermarking techniques to detect their potential misuse. Existing watermarking methods either add watermarks during LLM inference, which is unsuitable for open-source LLMs, or primarily target classification LLMs rather than recent generative LLMs. Adapting these watermarks to open-source LLMs for misuse detection remains an open challenge. This work defines two misuse scenarios for open-source LLMs: intellectual property (IP) violation and LLM Usage Violation. Then, we explore the application of inference-time watermark distillation and backdoor watermarking in these contexts. We propose comprehensive evaluation methods to assess the impact of various real-world further fine-tuning scenarios on watermarks and the effect of these watermarks on LLM performance. Our experiments reveal that backdoor watermarking could effectively detect IP Violation, while inference-time watermark distillation is applicable in both scenarios but less robust to further fine-tuning and has a more significant impact on LLM performance compared to backdoor watermarking. Exploring more advanced watermarking methods for open-source LLMs to detect their misuse should be an important future direction.

[Arxiv](https://arxiv.org/abs/2503.04636)