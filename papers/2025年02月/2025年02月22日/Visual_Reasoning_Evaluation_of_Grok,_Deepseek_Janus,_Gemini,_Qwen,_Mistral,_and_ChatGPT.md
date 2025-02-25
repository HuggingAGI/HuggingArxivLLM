# Grok、Deepseek Janus、Gemini、Qwen、Mistral 和 ChatGPT 的视觉推理能力评估

发布时间：2025年02月22日

`LLM应用` `人工智能` `多模态模型`

> Visual Reasoning Evaluation of Grok, Deepseek Janus, Gemini, Qwen, Mistral, and ChatGPT

# 摘要

> 传统上，对多模态大型语言模型（LLMs）的评估主要关注单一图像推理，忽略了上下文理解、推理稳定性和不确定性校准等关键能力。本研究通过引入一种融合多图像推理任务、基于拒绝机制的评估以及位置偏见检测的新基准，解决了这些局限性。为了量化不同答案变体重新排序后的推理一致性，我们进一步引入了熵作为新型指标。我们应用这一基准，对包括差异识别和图表解读在内的八项视觉推理任务中的Grok 3、ChatGPT-4o、ChatGPT-o1、Gemini 2.0 Flash Experimental、DeepSeek Janus模型、Qwen2.5-VL-72B-Instruct、QVQ-72B-Preview和Pixtral 12B进行了评估。结果显示，ChatGPT-o1在整体准确率（82.5%）和拒绝准确率（70.0%）上表现最佳，紧随其后的是Gemini 2.0 Flash Experimental（70.8%）。QVQ-72B-Preview在拒绝准确率上表现尤为突出（85.5%）。值得注意的是，Pixtral 12B在特定领域展现了潜力（51.7%），而Janus模型在偏见和不确定性校准方面面临挑战，表现为较低的拒绝准确率和较高的熵值。Janus模型的高熵值（Janus 7B: 0.8392，Janus 1B: 0.787）凸显了其易受位置偏见影响和推理不稳定的特点，与ChatGPT模型的低熵值和稳健推理形成鲜明对比。研究进一步表明，模型规模并非唯一决定性能的因素，这一点在参数量庞大却表现不佳的Grok 3中得到体现。通过采用多图像上下文、拒绝机制以及基于熵值的一致性指标，本研究为评估多模态LLMs树立了新标杆，为更 robust 和可靠的下一代AI系统评估提供了可能。


> Traditional evaluations of multimodal large language models (LLMs) have been limited by their focus on single-image reasoning, failing to assess crucial aspects like contextual understanding, reasoning stability, and uncertainty calibration. This study addresses these limitations by introducing a novel benchmark that integrates multi-image reasoning tasks with rejection-based evaluation and positional bias detection. To evaluate these dimensions, we further introduce entropy as a novel metric for quantifying reasoning consistency across reordered answer variants. We applied this benchmark to assess Grok 3, ChatGPT-4o, ChatGPT-o1, Gemini 2.0 Flash Experimental, DeepSeek Janus models, Qwen2.5-VL-72B-Instruct, QVQ-72B-Preview, and Pixtral 12B across eight visual reasoning tasks, including difference spotting and diagram interpretation. Our findings reveal ChatGPT-o1 leading in overall accuracy (82.5\%) and rejection accuracy (70.0\%), closely followed by Gemini 2.0 Flash Experimental (70.8\%). QVQ-72B-Preview demonstrated superior rejection accuracy (85.5\%). Notably, Pixtral 12B (51.7\%) showed promise in specific domains, while Janus models exhibited challenges in bias and uncertainty calibration, reflected in low rejection accuracies and high entropy scores. High entropy scores in Janus models (Janus 7B: 0.8392, Janus 1B: 0.787) underscore their susceptibility to positional bias and unstable reasoning, contrasting with the low entropy and robust reasoning of ChatGPT models. The study further demonstrates that model size is not the sole determinant of performance, as evidenced by Grok 3 underperformance despite its substantial parameter count. By employing multi-image contexts, rejection mechanisms, and entropy-based consistency metrics, this benchmark sets a new standard for evaluating multimodal LLMs, enabling a more robust and reliable assessment of next-generation AI systems.

[Arxiv](https://arxiv.org/abs/2502.16428)