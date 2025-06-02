# # Preemptive Hallucination Reduction: An Input-Level Approach for Multimodal Language Model
抢先式幻觉减少：从输入层面入手的多模态语言模型方法

发布时间：2025年05月29日

`LLM应用` `多模态` `人工智能`

> Preemptive Hallucination Reduction: An Input-Level Approach for Multimodal Language Model

# 摘要

> 大型语言模型中的视觉幻觉问题，即模型生成的响应与视觉输入不一致，对模型的可靠性构成重大挑战，尤其在需要精确和可靠输出的场景中。当前研究主要集中在事后修正或特定模型的微调策略上，而对在输入阶段通过预处理技术解决幻觉问题的探索较少。本研究提出了一种基于集成的预处理框架，该框架能够根据问题类型自适应地选择最合适的过滤方法——噪声减少（NR）、边缘增强（EE）或原始输入（org），从而在不修改底层模型架构或训练流程的情况下有效减少幻觉现象。在专门用于测试视觉复杂输入的多模态推理基准数据集`HaloQuest`上进行评估，我们的方法通过使用SelfCheckGPT的自然语言推理（NLI）评分，实现了44.3%的幻觉率降低。这表明，仅通过智能输入调节即可显著提升大型语言模型响应的事实依据。研究结果强调了自适应预处理技术在缓解幻觉中的重要性，为构建更可靠、能够应对现实挑战的多模态系统铺平了道路。

> Visual hallucinations in Large Language Models (LLMs), where the model generates responses that are inconsistent with the visual input, pose a significant challenge to their reliability, particularly in contexts where precise and trustworthy outputs are critical. Current research largely emphasizes post-hoc correction or model-specific fine-tuning strategies, with limited exploration of preprocessing techniques to address hallucination issues at the input stage. This study presents a novel ensemble-based preprocessing framework that adaptively selects the most appropriate filtering approach -- noise reduced (NR), edge enhanced (EE), or unaltered input (org) based on the type of question posed, resulting into reduced hallucination without requiring any modifications to the underlying model architecture or training pipeline. Evaluated on the `HaloQuest' dataset -- a benchmark designed to test multimodal reasoning on visually complex inputs, our method achieves a 44.3% reduction in hallucination rates, as measured by Natural Language Inference (NLI) scores using SelfCheckGPT. This demonstrates that intelligent input conditioning alone can significantly enhance factual grounding in LLM responses. The findings highlight the importance of adaptive preprocessing techniques in mitigating hallucinations, paving the way for more reliable multimodal systems capable of addressing real-world challenges.

[Arxiv](https://arxiv.org/abs/2505.24007)