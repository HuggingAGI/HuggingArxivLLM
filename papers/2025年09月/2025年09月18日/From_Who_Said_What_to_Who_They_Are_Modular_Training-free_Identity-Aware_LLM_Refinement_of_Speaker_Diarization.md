# 从“谁说了什么”到“他们是谁”：模块化、无需训练的身份感知大语言模型优化说话人分轨

发布时间：2025年09月18日

`LLM应用` `医疗健康`

> From Who Said What to Who They Are: Modular Training-free Identity-Aware LLM Refinement of Speaker Diarization

# 摘要

> 说话人分割（SD）在实际场景中常因动态环境和未知说话人数量而面临挑战。SD很少单独使用，通常与自动语音识别（ASR）结合，但基于特定领域数据联合训练的非模块化方法灵活性有限。此外，许多应用场景需要真实的说话人身份，而非SD输出的伪标签。为此，我们提出一种无需训练的模块化流程，整合现成的SD、ASR和大型语言模型（LLM），以实现“谁在说、说了什么、是谁说的”的完整识别。该方法通过对协调后的SD和ASR输出采用结构化LLM提示，利用对话上下文中的语义连贯性优化低置信度说话人标签，并在纠正说话人分割错误的同时赋予角色身份。在真实世界的患者-临床医生数据集上，该方法相比基线协调后的SD和ASR，相对误差降低了29.7%。它无需额外训练即可提升分割性能，并为实际应用中的SD、ASR及说话人身份检测提供完整解决方案。

> Speaker diarization (SD) struggles in real-world scenarios due to dynamic environments and unknown speaker counts. SD is rarely used alone and is often paired with automatic speech recognition (ASR), but non-modular methods that jointly train on domain-specific data have limited flexibility. Moreover, many applications require true speaker identities rather than SD's pseudo labels. We propose a training-free modular pipeline combining off-the-shelf SD, ASR, and a large language model (LLM) to determine who spoke, what was said, and who they are. Using structured LLM prompting on reconciled SD and ASR outputs, our method leverages semantic continuity in conversational context to refine low-confidence speaker labels and assigns role identities while correcting split speakers. On a real-world patient-clinician dataset, our approach achieves a 29.7% relative error reduction over baseline reconciled SD and ASR. It enhances diarization performance without additional training and delivers a complete pipeline for SD, ASR, and speaker identity detection in practical applications.

[Arxiv](https://arxiv.org/abs/2509.15082)