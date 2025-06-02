# SORCE: 复杂环境中小物体检索

发布时间：2025年05月30日

`LLM应用` `计算机视觉` `图像检索`

> SORCE: Small Object Retrieval in Complex Environments

# 摘要

> 文本到图像检索（T2IR）是一项极具价值的任务，旨在将文本查询与图像进行匹配。现有方法主要关注整体图像语义或前景显著物体，可能忽略了复杂环境中不显眼的小型物体。因此，我们提出了SORCE（复杂环境中的小型物体检索），专注于使用文本查询检索复杂图像中的小型物体。我们构建了SORCE-1K基准测试，包含复杂环境图像和描述小型物体的文本查询。初步分析显示，现有方法难以捕捉小型物体并编码其语义，导致性能不佳。为此，我们提出用多个独特嵌入表示图像，并利用多模态大型语言模型（MLLMs）和区域提示（ReP）提取嵌入。实验结果表明，我们的方法在SORCE-1K上显著优于现有方法，验证了新基准的有效性，并展示了多嵌入表示和文本定制MLLM特征的潜力。

> Text-to-Image Retrieval (T2IR) is a highly valuable task that aims to match a given textual query to images in a gallery. Existing benchmarks primarily focus on textual queries describing overall image semantics or foreground salient objects, possibly overlooking inconspicuous small objects, especially in complex environments. Such small object retrieval is crucial, as in real-world applications, the targets of interest are not always prominent in the image. Thus, we introduce SORCE (Small Object Retrieval in Complex Environments), a new subfield of T2IR, focusing on retrieving small objects in complex images with textual queries. We propose a new benchmark, SORCE-1K, consisting of images with complex environments and textual queries describing less conspicuous small objects with minimal contextual cues from other salient objects. Preliminary analysis on SORCE-1K finds that existing T2IR methods struggle to capture small objects and encode all the semantics into a single embedding, leading to poor retrieval performance on SORCE-1K. Therefore, we propose to represent each image with multiple distinctive embeddings. We leverage Multimodal Large Language Models (MLLMs) to extract multiple embeddings for each image instructed by a set of Regional Prompts (ReP). Experimental results show that our multi-embedding approach through MLLM and ReP significantly outperforms existing T2IR methods on SORCE-1K. Our experiments validate the effectiveness of SORCE-1K for benchmarking SORCE performances, highlighting the potential of multi-embedding representation and text-customized MLLM features for addressing this task.

[Arxiv](https://arxiv.org/abs/2505.24441)