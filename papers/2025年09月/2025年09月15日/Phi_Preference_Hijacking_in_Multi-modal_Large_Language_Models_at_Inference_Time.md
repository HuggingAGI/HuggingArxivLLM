# # Phi：多模态大型语言模型推理时的偏好劫持

发布时间：2025年09月15日

`LLM应用` `基础理论`

> Phi: Preference Hijacking in Multi-modal Large Language Models at Inference Time

# 摘要

> 近年来，多模态大型语言模型（MLLMs）已在多个领域备受瞩目。但随着其广泛应用，也带来了严峻的安全隐患。本文揭示了MLLMs的一项新安全风险：其输出偏好可被精心优化的图像任意操控。这类攻击往往会生成与上下文相关却带有偏见的响应，这些响应既非明显有害也不违背伦理，因此难以察觉。具体而言，我们提出了一种名为“偏好劫持（Phi）”的新方法，通过偏好劫持图像来操控MLLM的响应偏好。该方法在推理阶段即可生效，且无需对模型进行任何修改。此外，我们还引入了一种通用劫持扰动——这是一种可迁移组件，可嵌入到不同图像中，将MLLM的响应劫持到攻击者指定的任意偏好。多任务实验结果验证了我们方法的有效性。Phi的代码已开源，地址为https://github.com/Yifan-Lan/Phi。

> Recently, Multimodal Large Language Models (MLLMs) have gained significant attention across various domains. However, their widespread adoption has also raised serious safety concerns. In this paper, we uncover a new safety risk of MLLMs: the output preference of MLLMs can be arbitrarily manipulated by carefully optimized images. Such attacks often generate contextually relevant yet biased responses that are neither overtly harmful nor unethical, making them difficult to detect. Specifically, we introduce a novel method, Preference Hijacking (Phi), for manipulating the MLLM response preferences using a preference hijacked image. Our method works at inference time and requires no model modifications. Additionally, we introduce a universal hijacking perturbation -- a transferable component that can be embedded into different images to hijack MLLM responses toward any attacker-specified preferences. Experimental results across various tasks demonstrate the effectiveness of our approach. The code for Phi is accessible at https://github.com/Yifan-Lan/Phi.

[Arxiv](https://arxiv.org/abs/2509.12521)