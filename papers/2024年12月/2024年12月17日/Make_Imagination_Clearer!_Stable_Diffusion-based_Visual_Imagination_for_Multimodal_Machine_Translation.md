# 让想象更明晰！基于稳定扩散的多模态机器翻译的视觉想象

发布时间：2024年12月17日

`LLM应用` `机器翻译` `多模态`

> Make Imagination Clearer! Stable Diffusion-based Visual Imagination for Multimodal Machine Translation

# 摘要

> 视觉信息已被用于增强机器翻译（MT），但其效果很大程度上取决于大量带有手动图像标注的双语平行句对是否可得。在本文中，我们把基于稳定扩散的想象网络引入多模态大型语言模型（MLLM），为每个源语句清晰生成图像，进而推动多模型MT的发展。特别地，我们借助强化学习建立启发式的人类反馈，确保生成的图像与源语句一致，无需图像标注的监督，突破了MT中运用视觉信息的瓶颈。此外，该方法使得富有想象力的视觉信息能够融入大规模的纯文本MT以及多模态MT。实验结果显示，我们的模型显著优于现有的多模态MT和纯文本MT，在Multi30K多模态MT基准测试中，平均提升超过14个BLEU点。

> Visual information has been introduced for enhancing machine translation (MT), and its effectiveness heavily relies on the availability of large amounts of bilingual parallel sentence pairs with manual image annotations. In this paper, we introduce a stable diffusion-based imagination network into a multimodal large language model (MLLM) to explicitly generate an image for each source sentence, thereby advancing the multimodel MT. Particularly, we build heuristic human feedback with reinforcement learning to ensure the consistency of the generated image with the source sentence without the supervision of image annotation, which breaks the bottleneck of using visual information in MT. Furthermore, the proposed method enables imaginative visual information to be integrated into large-scale text-only MT in addition to multimodal MT. Experimental results show that our model significantly outperforms existing multimodal MT and text-only MT, especially achieving an average improvement of more than 14 BLEU points on Multi30K multimodal MT benchmarks.

[Arxiv](https://arxiv.org/abs/2412.12627)