# HELM：通过曲率混合专家方法构建的双曲大型语言模型

发布时间：2025年05月30日

`LLM理论

摘要主要探讨了大型语言模型（LLMs）的几何结构改进，提出了基于双曲空间的HELM模型，属于模型理论层面的创新，因此归类为LLM理论。`

> HELM: Hyperbolic Large Language Models via Mixture-of-Curvature Experts

# 摘要

> 大型语言模型（LLMs）在跨领域文本建模任务中取得了巨大成功。然而，自然语言固有的语义层次结构和精妙的几何特性并未被当前LLMs完全捕捉，这主要归因于其依赖于欧几里得操作。近期研究表明，不尊重标记嵌入的几何特性会导致训练不稳定和生成性能下降。这些发现表明，转向非欧几里得几何可能使语言模型更好地与文本的内在几何特性相契合。

因此，我们提出完全基于双曲空间的操作，该空间以其广阔的、无尺度的和低失真特性而闻名。我们由此引入了HELM，一个基于双曲的大型语言模型家族，对基于Transformer的LLM进行了几何重构，旨在解决现有双曲LM在表达灵活性、必要操作集和扩展性方面的不足。我们还引入了一种曲率混合专家模型HELM-MICE，其中每个专家在独立的曲率空间中运行，以从文本中编码更精细的几何结构，以及一个密集模型HELM-D。对于HELM-MICE，我们进一步开发了双曲多头潜在注意力（HMLA），以实现高效、低KV缓存的训练和推理。对于两种模型，我们开发了旋转变换位置编码和根均方归一化的双曲等效形式。

我们在十亿参数规模上首次成功训练了完全基于双曲的大型语言模型，并在涵盖STEM问题解决、常识推理和通用知识的知名基准测试（如MMLU和ARC）上进行了评估。我们的实验结果表明，与广泛使用的LLaMA和DeepSeek中基于欧几里得架构相比，HELM架构带来了显著的性能提升——高达4%——这凸显了双曲几何在大规模语言模型预训练中带来的有效性提升和推理增强。


> Large language models (LLMs) have shown great success in text modeling tasks across domains. However, natural language exhibits inherent semantic hierarchies and nuanced geometric structure, which current LLMs do not capture completely owing to their reliance on Euclidean operations. Recent studies have also shown that not respecting the geometry of token embeddings leads to training instabilities and degradation of generative capabilities. These findings suggest that shifting to non-Euclidean geometries can better align language models with the underlying geometry of text. We thus propose to operate fully in Hyperbolic space, known for its expansive, scale-free, and low-distortion properties. We thus introduce HELM, a family of HypErbolic Large Language Models, offering a geometric rethinking of the Transformer-based LLM that addresses the representational inflexibility, missing set of necessary operations, and poor scalability of existing hyperbolic LMs. We additionally introduce a Mixture-of-Curvature Experts model, HELM-MICE, where each expert operates in a distinct curvature space to encode more fine-grained geometric structure from text, as well as a dense model, HELM-D. For HELM-MICE, we further develop hyperbolic Multi-Head Latent Attention (HMLA) for efficient, reduced-KV-cache training and inference. For both models, we develop essential hyperbolic equivalents of rotary positional encodings and RMS normalization. We are the first to train fully hyperbolic LLMs at billion-parameter scale, and evaluate them on well-known benchmarks such as MMLU and ARC, spanning STEM problem-solving, general knowledge, and commonsense reasoning. Our results show consistent gains from our HELM architectures -- up to 4% -- over popular Euclidean architectures used in LLaMA and DeepSeek, highlighting the efficacy and enhanced reasoning afforded by hyperbolic geometry in large-scale LM pretraining.

[Arxiv](https://arxiv.org/abs/2505.24722)