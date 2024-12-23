# 用于复杂缝纫图案生成的多模态潜在扩散模型

发布时间：2024年12月18日

`其他`

> Multimodal Latent Diffusion Model for Complex Sewing Pattern Generation

# 摘要

> 在服装设计中生成缝纫图案，因其对计算机图形友好且编辑灵活的特性，正受到越来越多的关注。以往的缝纫图案生成方法虽能产出精美的服装，却难以设计出具有精细控制的复杂服装。为应对这些问题，我们提出了 SewingLDM，这是一个由文本提示、身体形状和服装草图控制生成缝纫图案的多模态生成模型。起初，我们把缝纫图案的原始向量拓展为更全面的表述，以涵盖更繁杂的细节，接着将其压缩至一个紧凑的潜在空间。为学习潜在空间中的缝纫图案分布，我们设计了两步训练策略，把多模态条件（即身体形状、文本提示和服装草图）注入扩散模型，保证生成的服装合身且细节可控。全面的定性和定量实验显示了我们所提方法的有效性，在复杂服装设计和各种身体适应性方面大幅超越了以往的方法。我们的项目页面：https://shengqiliu1.github.io/SewingLDM。

> Generating sewing patterns in garment design is receiving increasing attention due to its CG-friendly and flexible-editing nature. Previous sewing pattern generation methods have been able to produce exquisite clothing, but struggle to design complex garments with detailed control. To address these issues, we propose SewingLDM, a multi-modal generative model that generates sewing patterns controlled by text prompts, body shapes, and garment sketches. Initially, we extend the original vector of sewing patterns into a more comprehensive representation to cover more intricate details and then compress them into a compact latent space. To learn the sewing pattern distribution in the latent space, we design a two-step training strategy to inject the multi-modal conditions, \ie, body shapes, text prompts, and garment sketches, into a diffusion model, ensuring the generated garments are body-suited and detail-controlled. Comprehensive qualitative and quantitative experiments show the effectiveness of our proposed method, significantly surpassing previous approaches in terms of complex garment design and various body adaptability. Our project page: https://shengqiliu1.github.io/SewingLDM.

[Arxiv](https://arxiv.org/abs/2412.14453)