# LongEmotion：评估大型语言模型在长上下文交互中的情绪智力

发布时间：2025年09月09日

`RAG` `媒体与娱乐`

> LongEmotion: Measuring Emotional Intelligence of Large Language Models in Long-Context Interaction

# 摘要

> 大型语言模型（LLMs）在情商（EI）与长上下文理解领域取得了显著进展。然而，现有基准测试往往忽略了长上下文场景中情商的某些方面，尤其是在现实场景中——这类场景下的交互冗长、多样且常伴有噪音。为了贴近这类现实场景，我们提出了LongEmotion基准测试，专门用于长上下文情商任务。它涵盖了多种任务，包括情感分类、情感检测、情感问答、情感对话、情感摘要及情感表达。这些任务的平均输入长度达8,777个token，其中情感表达任务还需生成长篇文本。为了在现实条件下提升性能，我们引入了检索增强生成（RAG）与协同情感建模（CoEM），并将其与标准提示方法进行对比。与传统方法不同，我们的RAG方法将对话上下文和大语言模型本身均作为检索源，无需依赖外部知识库。CoEM方法则通过将任务分解为五个阶段，整合了检索增强与有限知识注入，进一步提升了性能。实验结果表明，RAG与CoEM在大多数长上下文任务中持续提升情商相关性能，推动LLMs在情商应用领域更贴近实际场景。此外，我们在GPT系列模型上开展了对比案例研究，以展示不同模型在情商表现上的差异。代码已在GitHub开源：https://github.com/LongEmotion/LongEmotion，项目页面详见：https://longemotion.github.io/。

> Large language models (LLMs) make significant progress in Emotional Intelligence (EI) and long-context understanding. However, existing benchmarks tend to overlook certain aspects of EI in long-context scenarios, especially under realistic, practical settings where interactions are lengthy, diverse, and often noisy. To move towards such realistic settings, we present LongEmotion, a benchmark specifically designed for long-context EI tasks. It covers a diverse set of tasks, including Emotion Classification, Emotion Detection, Emotion QA, Emotion Conversation, Emotion Summary, and Emotion Expression. On average, the input length for these tasks reaches 8,777 tokens, with long-form generation required for Emotion Expression. To enhance performance under realistic constraints, we incorporate Retrieval-Augmented Generation (RAG) and Collaborative Emotional Modeling (CoEM), and compare them with standard prompt-based methods. Unlike conventional approaches, our RAG method leverages both the conversation context and the large language model itself as retrieval sources, avoiding reliance on external knowledge bases. The CoEM method further improves performance by decomposing the task into five stages, integrating both retrieval augmentation and limited knowledge injection. Experimental results show that both RAG and CoEM consistently enhance EI-related performance across most long-context tasks, advancing LLMs toward more practical and real-world EI applications. Furthermore, we conducted a comparative case study experiment on the GPT series to demonstrate the differences among various models in terms of EI. Code is available on GitHub at https://github.com/LongEmotion/LongEmotion, and the project page can be found at https://longemotion.github.io/.

[Arxiv](https://arxiv.org/abs/2509.07403)