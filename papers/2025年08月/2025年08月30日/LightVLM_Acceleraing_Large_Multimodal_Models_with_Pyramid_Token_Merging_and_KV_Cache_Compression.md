# <翻译失败>

发布时间：2025年08月30日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。` `基础理论`

> LightVLM: Acceleraing Large Multimodal Models with Pyramid Token Merging and KV Cache Compression

# 摘要

> <翻译失败>

> In this paper, we introduce LightVLM, a simple but effective method that can be seamlessly deployed upon existing Vision-Language Models (VLMs) to greatly accelerate the inference process in a training-free manner. We divide the inference procedure of VLMs into two stages, i.e., encoding and decoding, and propose to simultaneously accelerate VLMs in both stages to largely improve model efficiency. During encoding, we propose pyramid token merging to reduce tokens of different LLM layers in a hierarchical manner by finally only keeping a few dominant tokens to achieve high efficiency. During decoding, aimed at reducing the high latency of outputting long sequences, we propose KV Cache compression to remove unnecessary caches to increase the network throughput. Experimental results show that LightVLM successfully retains 100% performance when only preserving 35% image tokens, and maintains around 98% performance when keeping only 3% image tokens. LightVLM could 2.02$\times$ the network throughput and reduce the prefilling time by 3.65$\times$. LightVLM also makes large VLMs faster again by enabling a heavy model (e.g., InternVL2.5 26B) to infer faster than significantly smaller models (e.g., InternVL2.5 8B), hopefully facilitating the real-world deployment. When generating long text sequences (e.g., 4096 tokens), LightVLM could reduce the inference time by 3.21$\times$, largely outperforming existing methods.

[Arxiv](https://arxiv.org/abs/2509.00419)