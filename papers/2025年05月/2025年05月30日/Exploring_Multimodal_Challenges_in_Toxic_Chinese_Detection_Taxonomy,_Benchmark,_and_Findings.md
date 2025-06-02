# 深入探讨中文毒内容检测的多模态挑战：分类体系、基准测试与研究发现

发布时间：2025年05月30日

`LLM应用` `内容安全`

> Exploring Multimodal Challenges in Toxic Chinese Detection: Taxonomy, Benchmark, and Findings

# 摘要

> 检测有毒内容对语言模型而言既重要又具挑战性。尽管大型语言模型（LLMs）在理解中文方面表现出色，但最新研究发现，只需对有毒中文文本进行简单的字符替换，就能轻易混淆当前最先进的（SOTA）LLMs。本文着重探讨中文语言的多模态特性，这是部署LLMs进行有毒中文检测的关键难点。首先，我们提出了有毒中文内容的3种扰动策略和8种具体方法的分类体系。接着，我们基于该分类体系构建了一个数据集，并对来自中美两国的9种SOTA LLMs进行了基准测试，以评估它们在检测经过扰动的有毒中文文本方面的表现。此外，我们还研究了成本效益高的增强方案，包括in-context学习（ICL）和监督微调（SFT）。研究结果揭示了两个重要发现：（1）LLMs在检测经过扰动的多模态有毒中文内容方面的能力较弱。（2）仅使用少量扰动示例进行ICL或SFT，可能导致LLMs出现“过矫”现象，即将许多正常中文内容误判为有毒内容。

> Detecting toxic content using language models is important but challenging. While large language models (LLMs) have demonstrated strong performance in understanding Chinese, recent studies show that simple character substitutions in toxic Chinese text can easily confuse the state-of-the-art (SOTA) LLMs. In this paper, we highlight the multimodal nature of Chinese language as a key challenge for deploying LLMs in toxic Chinese detection. First, we propose a taxonomy of 3 perturbation strategies and 8 specific approaches in toxic Chinese content. Then, we curate a dataset based on this taxonomy, and benchmark 9 SOTA LLMs (from both the US and China) to assess if they can detect perturbed toxic Chinese text. Additionally, we explore cost-effective enhancement solutions like in-context learning (ICL) and supervised fine-tuning (SFT). Our results reveal two important findings. (1) LLMs are less capable of detecting perturbed multimodal Chinese toxic contents. (2) ICL or SFT with a small number of perturbed examples may cause the LLMs "overcorrect'': misidentify many normal Chinese contents as toxic.

[Arxiv](https://arxiv.org/abs/2505.24341)