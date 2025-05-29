# # 测试时间免疫：针对（多模态）大型语言模型的通用防御框架，抵御越狱攻击

发布时间：2025年05月28日

`LLM理论` `人工智能`

> Test-Time Immunization: A Universal Defense Framework Against Jailbreaks for (Multimodal) Large Language Models

# 摘要

> 尽管（多模态）大型语言模型（LLMs）凭借其卓越能力吸引了广泛关注，但它们仍易受越狱攻击。现有防御方法虽针对特定攻击类型设计，却难以应对多样化的对抗策略。例如，基于重述的防御方法仅对文本对抗性越狱有效，而对图像攻击则无能为力。为此，我们提出了一种通用防御框架——Test-time IMmunization (TIM)，它能自适应地以自我演进的方式抵御各类越狱攻击。具体而言，TIM首先训练一个主旨标记用于高效检测，随后将其应用于推理过程中的越狱活动识别。一旦发现越狱企图，TIM会通过将检测到的越狱指令与拒绝回答配对，实施安全微调。此外，为缓解安全微调过程中参数更新对检测器性能的潜在退化，我们将微调过程与检测模块解耦。在大型语言模型和多模态大型语言模型上的大量实验均验证了TIM的有效性。

> While (multimodal) large language models (LLMs) have attracted widespread attention due to their exceptional capabilities, they remain vulnerable to jailbreak attacks. Various defense methods are proposed to defend against jailbreak attacks, however, they are often tailored to specific types of jailbreak attacks, limiting their effectiveness against diverse adversarial strategies. For instance, rephrasing-based defenses are effective against text adversarial jailbreaks but fail to counteract image-based attacks. To overcome these limitations, we propose a universal defense framework, termed Test-time IMmunization (TIM), which can adaptively defend against various jailbreak attacks in a self-evolving way. Specifically, TIM initially trains a gist token for efficient detection, which it subsequently applies to detect jailbreak activities during inference. When jailbreak attempts are identified, TIM implements safety fine-tuning using the detected jailbreak instructions paired with refusal answers. Furthermore, to mitigate potential performance degradation in the detector caused by parameter updates during safety fine-tuning, we decouple the fine-tuning process from the detection module. Extensive experiments on both LLMs and multimodal LLMs demonstrate the efficacy of TIM.

[Arxiv](https://arxiv.org/abs/2505.22271)