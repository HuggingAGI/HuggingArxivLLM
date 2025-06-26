# # 多模态大模型真的能遗忘数据吗？隐秘的MLLM数据遗忘攻击

发布时间：2025年06月10日

`LLM理论` `隐私保护` `数据安全`

> Does Multimodal Large Language Model Truly Unlearn? Stealthy MLLM Unlearning Attack

# 摘要

> 多模态大型语言模型（MLLMs）在大规模数据训练中可能记住敏感个人信息和照片，带来严重隐私风险。为缓解这一问题，我们提出了MLLM遗忘方法，通过微调MLLMs来减少对敏感信息的“遗忘”。然而，目前尚不清楚知识是真正被遗忘，还是仅仅隐藏在模型中。因此，我们提出研究一种新的LLM遗忘攻击问题，旨在恢复已被遗忘的LLM的未学习知识。

为实现这一目标，我们提出了一种新的框架——隐秘遗忘攻击（SUA）框架，该框架学习一种通用的噪声模式。当应用于输入图像时，这种噪声可以触发模型揭示未学习的内容。尽管像素级的扰动在视觉上可能非常微妙，但它们可以在语义嵌入空间中被检测到，使得此类攻击容易受到潜在防御的攻击。为了提高隐秘性，我们引入了一种嵌入对齐损失，以最小化扰动图像和去噪图像之间的嵌入差异，从而确保攻击在语义上无法察觉。

实验结果表明，SUA能够有效从MLLMs中恢复未学习的信息。此外，所学噪声具有良好的泛化性：在样本子集上训练的单个扰动即可揭示未见图像中被遗忘的内容。这表明知识再现并非偶然失败，而是一种持续行为。

> Multimodal Large Language Models (MLLMs) trained on massive data may memorize sensitive personal information and photos, posing serious privacy risks. To mitigate this, MLLM unlearning methods are proposed, which fine-tune MLLMs to reduce the ``forget'' sensitive information. However, it remains unclear whether the knowledge has been truly forgotten or just hidden in the model. Therefore, we propose to study a novel problem of LLM unlearning attack, which aims to recover the unlearned knowledge of an unlearned LLM. To achieve the goal, we propose a novel framework Stealthy Unlearning Attack (SUA) framework that learns a universal noise pattern. When applied to input images, this noise can trigger the model to reveal unlearned content. While pixel-level perturbations may be visually subtle, they can be detected in the semantic embedding space, making such attacks vulnerable to potential defenses. To improve stealthiness, we introduce an embedding alignment loss that minimizes the difference between the perturbed and denoised image embeddings, ensuring the attack is semantically unnoticeable. Experimental results show that SUA can effectively recover unlearned information from MLLMs. Furthermore, the learned noise generalizes well: a single perturbation trained on a subset of samples can reveal forgotten content in unseen images. This indicates that knowledge reappearance is not an occasional failure, but a consistent behavior.

[Arxiv](https://arxiv.org/abs/2506.17265)