# 从炒作到洞察：重新思考大型语言模型在视觉语音识别中的整合

发布时间：2025年09月18日

`LLM应用` `媒体与娱乐`

> From Hype to Insight: Rethinking Large Language Model Integration in Visual Speech Recognition

# 摘要

> 自监督编码器的发展推动了视觉语音识别（VSR）的性能提升。近期研究将这类编码器与LLM解码器结合，虽提升了转录准确率，但这些性能增益究竟来自视觉理解还是更强的语言建模能力，仍有待厘清。为此，本研究通过多种方式系统评估LLM解码器：冻结或选择性更新视觉编码器、调整解码器规模、比较适配策略与架构，以及使用LRS2、LRS3及其组合数据集进行训练。在LRS2、LRS3和WildVSR数据集上的评估显示：调整规模与适配仅带来有限改进，而组合数据集能有效提升模型泛化能力。语义分析进一步揭示，性能提升主要源于词汇层面的处理，而非语义层面。我们在组合数据集上训练的Llama-2-13B模型，在LRS3上实现了24.7%的词错误率（WER），在WildVSR上为47.0%，成为无额外监督训练模型中的当前最优（SOTA）。研究结果表明，LLM解码器主要优化上下文推理能力而非视觉特征，这意味着要实现VSR的实质性突破，需重点提升视觉编码器性能。

> Advances in self-supervised encoders have improved Visual Speech Recognition (VSR). Recent approaches integrating these encoders with LLM decoders improves transcription accuracy; however, it remains unclear whether these gains stem from visual understanding or stronger language modeling. In this work, we systematically evaluate LLM decoders by freezing or selectively updating the visual encoder, scaling decoder size, comparing adaptation strategies and architectures, and varying training data across LRS2, LRS3, and their combination. Evaluation on LRS2, LRS3, and WildVSR shows that scaling and adaptation yield limited improvements, while combining datasets enhances generalization. Semantic analysis reveals that gains arise primarily from lexical rather than semantic processing. Our Llama-2-13B model trained on the combined set achieves 24.7\% WER on LRS3 and 47.0\% on WildVSR, establishing SOTA among models trained without additional supervision. Our findings indicate LLM decoders refine contextual reasoning rather than visual features, emphasizing the need for stronger visual encoders to drive meaningful progress.

[Arxiv](https://arxiv.org/abs/2509.14880)