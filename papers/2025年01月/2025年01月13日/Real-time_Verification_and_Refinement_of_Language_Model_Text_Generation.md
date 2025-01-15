# 语言模型文本生成的实时验证与优化

发布时间：2025年01月13日

`LLM应用

理由：这篇论文主要讨论的是如何通过Streaming-VR方法在大型语言模型（LLMs）生成文本的过程中实时验证和改进其输出，以提高事实准确性。这属于对LLMs在实际应用中的改进和优化，因此归类为“LLM应用”。` `人工智能`

> Real-time Verification and Refinement of Language Model Text Generation

# 摘要

> 大型语言模型（LLMs）在多种自然语言任务中表现卓越，但有时会生成事实错误的答案。尽管已有许多研究致力于识别并改进这些错误，但由于这些方法仅在LLMs生成完整响应后才进行验证，因此部署效率较低。此外，我们发现，一旦LLMs在早期生成错误标记，后续标记也更容易出错。为此，我们提出了Streaming-VR（流式验证与改进），一种旨在提升LLM输出验证与改进效率的新方法。Streaming-VR能够在生成标记时实时验证和纠正，确保每个标记子集在生成过程中即被另一个LLM实时检查和改进。通过对多个数据集的全面评估，我们证明该方法不仅提升了LLMs的事实准确性，还比现有改进方法更为高效。

> Large language models (LLMs) have shown remarkable performance across a wide range of natural language tasks. However, a critical challenge remains in that they sometimes generate factually incorrect answers. To address this, while many previous work has focused on identifying errors in their generation and further refining them, they are slow in deployment since they are designed to verify the response from LLMs only after their entire generation (from the first to last tokens) is done. Further, we observe that once LLMs generate incorrect tokens early on, there is a higher likelihood that subsequent tokens will also be factually incorrect. To this end, in this work, we propose Streaming-VR (Streaming Verification and Refinement), a novel approach designed to enhance the efficiency of verification and refinement of LLM outputs. Specifically, the proposed Streaming-VR enables on-the-fly verification and correction of tokens as they are being generated, similar to a streaming process, ensuring that each subset of tokens is checked and refined in real-time by another LLM as the LLM constructs its response. Through comprehensive evaluations on multiple datasets, we demonstrate that our approach not only enhances the factual accuracy of LLMs, but also offers a more efficient solution compared to prior refinement methods.

[Arxiv](https://arxiv.org/abs/2501.07824)