# EverTracer：基于隐蔽鲁棒概率指纹的被盗大型语言模型追踪

发布时间：2025年09月03日

`LLM应用` `基础理论`

> EverTracer: Hunting Stolen Large Language Models via Stealthy and Robust Probabilistic Fingerprint

# 摘要

> 大型语言模型（LLMs）的迅猛发展加剧了人们对模型被盗和许可证违规的担忧，亟需强大且隐蔽的所有权验证机制。现有指纹识别方法要么依赖不切实际的白盒权限，要么会留下可检测的统计异常痕迹。为此，我们提出了EverTracer——一种全新的灰盒指纹识别框架，能够实现隐蔽且稳健的模型溯源追踪。EverTracer首次将成员推理攻击（MIAs）转用于防御场景，通过记忆而非人工触发-输出过拟合的方式嵌入所有权信号。该框架包含指纹注入（Fingerprint Injection）和验证（Verification）两个核心模块：指纹注入可在任意自然语言数据上微调模型，且不会留下可检测的人工痕迹；验证则通过校准的概率变化信号来识别带有指纹的模型。该方法对自适应攻击者表现出强大的稳健性，可有效抵御输入级和模型级的各类修改攻击。多架构下的大量实验表明，EverTracer在有效性、隐蔽性和抗干扰性上均达到了当前最先进水平，为LLM知识产权保护提供了切实可行的解决方案。我们的代码和数据已公开，地址为https://github.com/Xuzhenhua55/EverTracer。

> The proliferation of large language models (LLMs) has intensified concerns over model theft and license violations, necessitating robust and stealthy ownership verification. Existing fingerprinting methods either require impractical white-box access or introduce detectable statistical anomalies. We propose EverTracer, a novel gray-box fingerprinting framework that ensures stealthy and robust model provenance tracing. EverTracer is the first to repurpose Membership Inference Attacks (MIAs) for defensive use, embedding ownership signals via memorization instead of artificial trigger-output overfitting. It consists of Fingerprint Injection, which fine-tunes the model on any natural language data without detectable artifacts, and Verification, which leverages calibrated probability variation signal to distinguish fingerprinted models. This approach remains robust against adaptive adversaries, including input level modification, and model-level modifications. Extensive experiments across architectures demonstrate EverTracer's state-of-the-art effectiveness, stealthness, and resilience, establishing it as a practical solution for securing LLM intellectual property. Our code and data are publicly available at https://github.com/Xuzhenhua55/EverTracer.

[Arxiv](https://arxiv.org/abs/2509.03058)