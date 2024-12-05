# Mimir：提升视频扩散模型，实现精准的文本理解

发布时间：2024年12月04日

`LLM应用`

> Mimir: Improving Video Diffusion Models for Precise Text Understanding

# 摘要

> 文本因其叙事特性，在视频生成中成为关键的控制信号。为把文本描述转化为视频片段，当下的视频扩散模型虽借鉴了文本编码器的特征，却在文本理解上能力有限。大型语言模型（LLMs）近来的成功彰显了仅解码器转换器的强大，其为文本到视频（T2V）生成带来了三大显著优势，即凭借出色的可扩展性达成精确的文本理解、依靠下一个标记预测实现超越输入文本的想象，以及通过指令调整灵活地优先考虑用户兴趣。不过，两种不同文本建模范式产生的特征分布差异，阻碍了 LLMs 在已有的 T2V 模型中的直接运用。本研究借助 Mimir 应对这一挑战，Mimir 是一个端到端的训练框架，配有精心设计的标记融合器，用于协调文本编码器和 LLMs 的输出。如此设计让 T2V 模型既能充分利用已学到的视频先验知识，又能发挥 LLMs 的文本相关能力。大量的定量和定性结果表明，Mimir 在生成文本理解出色的高质量视频方面成效显著，尤其是在处理短标题和应对移动变化时。项目页面: https://lucaria-academy.github.io/Mimir/

> Text serves as the key control signal in video generation due to its narrative nature. To render text descriptions into video clips, current video diffusion models borrow features from text encoders yet struggle with limited text comprehension. The recent success of large language models (LLMs) showcases the power of decoder-only transformers, which offers three clear benefits for text-to-video (T2V) generation, namely, precise text understanding resulting from the superior scalability, imagination beyond the input text enabled by next token prediction, and flexibility to prioritize user interests through instruction tuning. Nevertheless, the feature distribution gap emerging from the two different text modeling paradigms hinders the direct use of LLMs in established T2V models. This work addresses this challenge with Mimir, an end-to-end training framework featuring a carefully tailored token fuser to harmonize the outputs from text encoders and LLMs. Such a design allows the T2V model to fully leverage learned video priors while capitalizing on the text-related capability of LLMs. Extensive quantitative and qualitative results demonstrate the effectiveness of Mimir in generating high-quality videos with excellent text comprehension, especially when processing short captions and managing shifting motions. Project page: https://lucaria-academy.github.io/Mimir/

[Arxiv](https://arxiv.org/abs/2412.03085)