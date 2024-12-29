# 用于对话情感识别的有效上下文建模框架

发布时间：2024年12月20日

`其他` `情绪识别`

> Effective Context Modeling Framework for Emotion Recognition in Conversations

# 摘要

> 在对话中的情绪识别（ERC）能够帮助我们更深入地理解说话者每次发言所传达的情绪。近来，图神经网络（GNNs）在捕捉数据关系上展现出优势，尤其是在上下文信息建模和多模态融合方面。但现有方法常常难以充分捕捉多种模态与对话上下文间的复杂交互，限制了其表现力。为克服这些局限，我们提出了ConxGNN，这是一个基于GNN的创新框架，旨在捕捉对话中的上下文信息。ConxGNN有两个关键的并行模块：一个多尺度异构图，能捕获发言对情绪变化的多样影响；一个超图，用于对模态和发言间的多元关系建模。这些模块的输出整合进一个融合层，其中应用了跨模态注意力机制以生成富含上下文的表示。另外，ConxGNN通过在损失函数中引入重新加权方案，解决了识别少数或语义相似情绪类别的难题。在IEMOCAP和MELD基准数据集上的实验结果表明，我们的方法行之有效，相比以往的基线达到了最先进的性能。

> Emotion Recognition in Conversations (ERC) facilitates a deeper understanding of the emotions conveyed by speakers in each utterance within a conversation. Recently, Graph Neural Networks (GNNs) have demonstrated their strengths in capturing data relationships, particularly in contextual information modeling and multimodal fusion. However, existing methods often struggle to fully capture the complex interactions between multiple modalities and conversational context, limiting their expressiveness. To overcome these limitations, we propose ConxGNN, a novel GNN-based framework designed to capture contextual information in conversations. ConxGNN features two key parallel modules: a multi-scale heterogeneous graph that captures the diverse effects of utterances on emotional changes, and a hypergraph that models the multivariate relationships among modalities and utterances. The outputs from these modules are integrated into a fusion layer, where a cross-modal attention mechanism is applied to produce a contextually enriched representation. Additionally, ConxGNN tackles the challenge of recognizing minority or semantically similar emotion classes by incorporating a re-weighting scheme into the loss functions. Experimental results on the IEMOCAP and MELD benchmark datasets demonstrate the effectiveness of our method, achieving state-of-the-art performance compared to previous baselines.

[Arxiv](https://arxiv.org/abs/2412.16444)