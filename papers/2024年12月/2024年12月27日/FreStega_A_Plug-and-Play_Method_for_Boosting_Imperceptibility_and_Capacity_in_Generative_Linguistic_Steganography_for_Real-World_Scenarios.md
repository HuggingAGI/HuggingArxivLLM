# FreStega：一种能在现实场景的生成语言隐写术中提升不可感知性与容量的即插即用式方法

发布时间：2024年12月27日

`LLM应用` `信息安全` `语言隐写术`

> FreStega: A Plug-and-Play Method for Boosting Imperceptibility and Capacity in Generative Linguistic Steganography for Real-World Scenarios

# 摘要

> 语言隐写术能把秘密信息藏在看似平常的文本里，从而在监控环境中守护隐私。生成式语言隐写术借助语言模型（LMs）的概率分布，运用隐写算法生成隐写标记，因近来大型语言模型（LLM）的发展而备受关注。为增强安全性，研究人员研发了保持分布的隐写算法，以缩小隐写抽样和语言模型抽样的差距。然而，由于依赖语言模型分布，且与现实中的掩护文本存在偏差，导致在现实场景中面对隐写分析检测器时，难以做到不被察觉。另外，LLM 分布通常更具确定性，致使熵降低，进而嵌入容量也降低。在本文中，我们提出了 FreStega，这是一种用于重构生成式语言隐写术所用语言模型分布的即插即用方法。FreStega 在隐写文本自回归生成的每一步，都会动态调整来自语言模型的标记概率，充分利用序列和空间维度。在序列调整方面，依据瞬时熵动态调节温度，增强隐写文本的多样性，提升嵌入容量。在空间维度上，其分布与目标域语料库的引导相契合，紧密模仿目标域中的真实掩护文本。通过重新塑造分布，FreStega 在实际场景中提高了隐写文本的不可感知性，将隐写容量提高了 15.41%，且不影响生成文本的质量。FreStega 作为一种即插即用的补救手段，在现实场景中提升了现有保持分布的隐写术方法的不可感知性和嵌入容量。

> Linguistic steganography embeds secret information in seemingly innocent texts, safeguarding privacy in surveillance environments. Generative linguistic steganography leverages the probability distribution of language models (LMs) and applies steganographic algorithms to generate stego tokens, gaining attention with recent Large Language Model (LLM) advancements. To enhance security, researchers develop distribution-preserving stego algorithms to minimize the gap between stego sampling and LM sampling. However, the reliance on language model distributions, coupled with deviations from real-world cover texts, results in insufficient imperceptibility when facing steganalysis detectors in real-world scenarios. Moreover, LLM distributions tend to be more deterministic, resulting in reduced entropy and, consequently, lower embedding capacity. In this paper, we propose FreStega, a plug-and-play method to reconstruct the distribution of language models used for generative linguistic steganography. FreStega dynamically adjusts token probabilities from the language model at each step of stegotext auto-regressive generation, leveraging both sequential and spatial dimensions. In sequential adjustment, the temperature is dynamically adjusted based on instantaneous entropy, enhancing the diversity of stego texts and boosting embedding capacity. In the spatial dimension, the distribution is aligned with guidance from the target domain corpus, closely mimicking real cover text in the target domain. By reforming the distribution, FreStega enhances the imperceptibility of stego text in practical scenarios and improves steganographic capacity by 15.41\%, all without compromising the quality of the generated text. FreStega serves as a plug-and-play remedy to enhance the imperceptibility and embedding capacity of existing distribution-preserving steganography methods in real-world scenarios.

[Arxiv](https://arxiv.org/abs/2412.19652)