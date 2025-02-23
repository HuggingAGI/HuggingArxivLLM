# # SegAug：CTC对齐的分段增强方法，提升基于RNN-Transducer的语音识别鲁棒性

发布时间：2025年02月20日

`其他

这篇论文主要探讨了RNN-Transducer（RNN-T）在语音识别中的应用，并提出了一种新的数据增强方法SegAug来改善模型的性能，特别是减少删除错误。虽然与自然语言处理相关，但它并未涉及大型语言模型（LLM）的应用或理论，而是专注于语音识别技术的改进。因此，它被归类为其他。` `语音识别`

> SegAug: CTC-Aligned Segmented Augmentation For Robust RNN-Transducer Based Speech Recognition

# 摘要

> RNN-Transducer（RNN-T）作为语音识别领域的主流架构，将声学建模与语言建模巧妙融合于端到端框架之中。然而，其预测器在训练过程中对连续单词依赖关系的过度倚重，导致了较高的删除错误率，尤其在处理不常见或领域外短语时表现明显。现有的正则化和数据增强方法虽能改善部分问题，却常以牺牲其他性能为代价。为此，我们提出了一种基于对齐的增强技术 SegAug，它通过生成语义级别较低但上下文丰富的音频-文本配对，引导模型更专注于声学特征的同时，也使内部语言模型学习到更多样化的文本模式，从而有效降低删除错误并显著提升整体性能。在 LibriSpeech 和 Tedlium-v3 数据集上的实验表明，SegAug 相较现有方法，在小规模场景下相对WER降低了12.5%，在大规模场景下降低了6.9%。其中，大部分性能提升源于删除错误的显著减少，分别达到了45.4%和18.5%的相对降幅。这一结果充分证明了 SegAug 在提升 RNN-T 稳健性方面的卓越效果，为在复杂多变的场景中实现更优的语音识别性能提供了极具潜力的解决方案。

> RNN-Transducer (RNN-T) is a widely adopted architecture in speech recognition, integrating acoustic and language modeling in an end-to-end framework. However, the RNN-T predictor tends to over-rely on consecutive word dependencies in training data, leading to high deletion error rates, particularly with less common or out-of-domain phrases. Existing solutions, such as regularization and data augmentation, often compromise other aspects of performance. We propose SegAug, an alignment-based augmentation technique that generates contextually varied audio-text pairs with low sentence-level semantics. This method encourages the model to focus more on acoustic features while diversifying the learned textual patterns of its internal language model, thereby reducing deletion errors and enhancing overall performance. Evaluations on the LibriSpeech and Tedlium-v3 datasets demonstrate a relative WER reduction of up to 12.5% on small-scale and 6.9% on large-scale settings. Notably, most of the improvement stems from reduced deletion errors, with relative reductions of 45.4% and 18.5%, respectively. These results highlight SegAug's effectiveness in improving RNN-T's robustness, offering a promising solution for enhancing speech recognition performance across diverse and challenging scenarios.

[Arxiv](https://arxiv.org/abs/2502.14685)