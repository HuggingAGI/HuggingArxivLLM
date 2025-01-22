# BiMarker: 利用双极水印技术提升大型语言模型的文本水印检测能力

发布时间：2025年01月21日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）生成文本的水印技术，特别是提出了双极水印（BiMarker）来提升水印文本的可检测性。这属于LLM在实际应用中的技术改进，因此归类为LLM应用。` `信息安全`

> BiMarker: Enhancing Text Watermark Detection for Large Language Models with Bipolar Watermarks

# 摘要

> 大型语言模型（LLMs）的快速普及引发了对其滥用的担忧，以及区分AI生成文本与人类撰写内容的挑战。现有水印技术（如\kgw）在低水印强度、严格误报要求和低熵场景下仍存在局限。我们的分析表明，当前检测方法依赖于对非水印文本的粗略估计，这限制了水印的可检测性。为此，我们提出了双极水印（BiMarker），通过将生成文本分为正负两极，利用绿色标记计数的差异进行检测。这种差异机制显著提升了水印文本的可检测性。理论分析和实验结果验证了BiMarker的有效性及其与现有优化技术的兼容性，为LLM生成内容的水印技术开辟了新的优化方向。

> The rapid proliferation of Large Language Models (LLMs) has raised concerns about misuse and the challenges of distinguishing AI-generated text from human-written content. Existing watermarking techniques, such as \kgw, still face limitations under low watermark strength, stringent false-positive requirements, and low-entropy scenarios. Our analysis reveals that current detection methods rely on coarse estimates of non-watermarked text, which constrains watermark detectability. We propose the Bipolar Watermark (BiMarker), a novel approach that divides generated text into positive and negative poles, leveraging the difference in green token counts for detection. This differential mechanism significantly enhances the detectability of watermarked text. Theoretical analysis and experimental results demonstrate BiMarker's effectiveness and compatibility with existing optimization techniques, offering a new optimization dimension for watermarking in LLM-generated content.

[Arxiv](https://arxiv.org/abs/2501.12174)