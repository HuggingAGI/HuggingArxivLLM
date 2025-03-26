# GenHancer：不完美的生成模型竟是视觉增强的隐藏高手！

发布时间：2025年03月25日

`LLM应用` `多模态` `视觉模型`

> GenHancer: Imperfect Generative Models are Secretly Strong Vision-Centric Enhancers

# 摘要

> 生成模型与判别模型的协同作用正日益受到关注。尽管判别式对比语言-图像预训练（CLIP）在高层语义理解上表现出色，但在感知精细视觉细节方面仍显不足。为了增强表征能力，生成模型通常会将CLIP的视觉特征作为重建条件，但其背后的原理尚未得到充分探索。

通过实证研究，我们发现视觉上完美的生成结果并不总是对表征增强最有利。关键在于：如何有效提取生成模型中的精细粒度知识，同时减少无关信息的干扰。为此，我们从三个关键方面进行了深入探索：

1. **条件机制**：我们发现，即使使用少量局部token作为条件，也会大幅降低重建难度，导致训练坍塌。因此，仅使用全局视觉token作为条件是最有效的策略。
2. **去噪配置**：我们观察到端到端训练会引入冗余信息。为解决这一问题，我们提出了一种两阶段训练策略，以优先学习有用的视觉知识。此外，轻量级去噪器能够带来显著的性能提升。
3. **生成范式**：我们探索了连续和离散去噪器，均取得了令人满意的结果，验证了我们方法的灵活性。

最终，我们找到了一种有效的解决方案——GenHancer。该方法在MMVP-VLM基准测试中持续优于现有方法，例如在OpenAICLIP上提升了6.0%。增强后的CLIP还可进一步集成到多模态大语言模型中，以提升视觉中心任务的性能。所有模型和代码均已公开发布。

> The synergy between generative and discriminative models receives growing attention. While discriminative Contrastive Language-Image Pre-Training (CLIP) excels in high-level semantics, it struggles with perceiving fine-grained visual details. Generally, to enhance representations, generative models take CLIP's visual features as conditions for reconstruction. However, the underlying principle remains underexplored. In this work, we empirically found that visually perfect generations are not always optimal for representation enhancement. The essence lies in effectively extracting fine-grained knowledge from generative models while mitigating irrelevant information. To explore critical factors, we delve into three aspects: (1) Conditioning mechanisms: We found that even a small number of local tokens can drastically reduce the difficulty of reconstruction, leading to collapsed training. We thus conclude that utilizing only global visual tokens as conditions is the most effective strategy. (2) Denoising configurations: We observed that end-to-end training introduces extraneous information. To address this, we propose a two-stage training strategy to prioritize learning useful visual knowledge. Additionally, we demonstrate that lightweight denoisers can yield remarkable improvements. (3) Generation paradigms: We explore both continuous and discrete denoisers with desirable outcomes, validating the versatility of our method. Through our in-depth explorations, we have finally arrived at an effective method, namely GenHancer, which consistently outperforms prior arts on the MMVP-VLM benchmark, e.g., 6.0% on OpenAICLIP. The enhanced CLIP can be further plugged into multimodal large language models for better vision-centric performance. All the models and codes are made publicly available.

[Arxiv](https://arxiv.org/abs/2503.19480)