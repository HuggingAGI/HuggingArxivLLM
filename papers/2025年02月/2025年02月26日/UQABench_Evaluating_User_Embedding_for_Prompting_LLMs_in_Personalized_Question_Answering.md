# UQABench: 评估个性化问答中用于提示 LLMs 的用户嵌入

发布时间：2025年02月26日

`LLM应用

理由：这篇论文探讨了如何在推荐系统中应用大型语言模型（LLMs），通过用户交互数据的压缩和蒸馏，生成用户嵌入作为软提示，以提升个性化响应。研究的重点在于评估和应用LLMs在个性化推荐中的有效性，属于LLM的应用领域。` `推荐系统` `用户体验`

> UQABench: Evaluating User Embedding for Prompting LLMs in Personalized Question Answering

# 摘要

> 大型语言模型（LLMs）在自然语言处理（NLP）领域取得了显著的成功。在实际应用场景中，如推荐系统，随着用户对个性化体验的需求日益增长，将用户交互历史整合到LLMs的上下文中以提升个性化变得至关重要。然而，用户交互数据的长度和噪声问题使其直接作为文本提示使用面临挑战。一个有前景的解决方案是将交互数据压缩并蒸馏成紧凑的嵌入表示，作为软提示来辅助LLMs生成个性化的响应。尽管这种方法带来了效率上的提升，但用户嵌入是否能够充分捕捉有价值的信息并有效提示LLMs仍是一个关键问题。为此，我们提出了
ame，这是一个旨在评估用户嵌入在提示LLMs以实现个性化方面有效性的基准测试。我们建立了一个公平且标准化的评估流程，涵盖了预训练、微调和评估阶段。为了全面评估用户嵌入，我们设计了三个维度的任务：序列理解、行为预测和兴趣感知。这些评估任务涵盖了传统推荐任务对提高预测准确性的需求，以及对基于LLMs方法的更高追求，如准确理解用户兴趣和提升用户体验。我们对各种最先进的用户嵌入建模方法进行了广泛的实验。此外，我们揭示了利用用户嵌入来提示LLMs的规模法则。该基准测试现已在线提供。

> Large language models (LLMs) achieve remarkable success in natural language processing (NLP). In practical scenarios like recommendations, as users increasingly seek personalized experiences, it becomes crucial to incorporate user interaction history into the context of LLMs to enhance personalization. However, from a practical utility perspective, user interactions' extensive length and noise present challenges when used directly as text prompts. A promising solution is to compress and distill interactions into compact embeddings, serving as soft prompts to assist LLMs in generating personalized responses. Although this approach brings efficiency, a critical concern emerges: Can user embeddings adequately capture valuable information and prompt LLMs? To address this concern, we propose \name, a benchmark designed to evaluate the effectiveness of user embeddings in prompting LLMs for personalization. We establish a fair and standardized evaluation process, encompassing pre-training, fine-tuning, and evaluation stages. To thoroughly evaluate user embeddings, we design three dimensions of tasks: sequence understanding, action prediction, and interest perception. These evaluation tasks cover the industry's demands in traditional recommendation tasks, such as improving prediction accuracy, and its aspirations for LLM-based methods, such as accurately understanding user interests and enhancing the user experience. We conduct extensive experiments on various state-of-the-art methods for modeling user embeddings. Additionally, we reveal the scaling laws of leveraging user embeddings to prompt LLMs. The benchmark is available online.

[Arxiv](https://arxiv.org/abs/2502.19178)