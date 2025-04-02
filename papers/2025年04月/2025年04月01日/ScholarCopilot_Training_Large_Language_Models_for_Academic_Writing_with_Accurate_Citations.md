# # 标题  
ScholarCopilot：专为学术写作打造，确保引用准确无误的大型语言模型训练方法

发布时间：2025年04月01日

`RAG` `学术写作` `学术出版`

> ScholarCopilot: Training Large Language Models for Academic Writing with Accurate Citations

# 摘要

> 学术写作不仅需要连贯的文本生成，还需要对相关文献进行精准引用。尽管检索增强生成（RAG）系统在通用文本生成的事实准确性方面取得了显著进展，但它们在支持专业学术写作方面的能力仍有待提升。为此，我们推出了ScholarCopilot——一个统一框架，旨在增强大型语言模型，使其能够生成兼具准确性和上下文相关引用的专业学术文章。

ScholarCopilot通过生成检索令牌[RET]动态判断何时检索学术参考文献，并利用其表示从数据库中查找相关引用。这些检索到的参考文献会被输入到模型中，从而增强生成过程。我们在一个框架内同时优化生成和引用任务，以提高整体效率。

在50万篇arXiv论文的训练基础上，我们的模型在评估数据集中实现了40.1%的top-1检索准确率，显著超越了E5-Mistral-7B-Instruct（15.0%）和BM25（9.8%）等基线。在包含1,000个学术写作样本的数据集上，ScholarCopilot在生成质量（从相关性、连贯性、学术严谨性、完整性和创新性五个维度衡量）上获得了16.2/25的评分，超越了参数量为其10倍的Qwen-2.5-72B-Instruct（15.8/25）。

通过人类研究，我们进一步证实了ScholarCopilot在引用召回率、写作效率和整体用户体验方面的卓越表现，充分验证了我们方法的有效性。

> Academic writing requires both coherent text generation and precise citation of relevant literature. Although recent Retrieval-Augmented Generation (RAG) systems have significantly improved factual accuracy in general-purpose text generation, their capacity to adequately support professional academic writing remains limited. In this work, we introduce ScholarCopilot, a unified framework designed to enhance existing large language models for generating professional academic articles with accurate and contextually relevant citations. ScholarCopilot dynamically determines when to retrieve scholarly references by generating a retrieval token [RET], and then utilizes its representation to look up relevant citations from a database. The retrieved references are fed into the model to augment the generation process. We jointly optimize both the generation and citation tasks within a single framework to increase efficiency. Trained on 500K papers from arXiv, our model achieves a top-1 retrieval accuracy of 40.1% on our evaluation dataset, outperforming baselines such as E5-Mistral-7B-Instruct (15.0%) and BM25 (9.8%). On a dataset of 1,000 academic writing samples, ScholarCopilot scores 16.2/25 in generation quality (measured across relevance, coherence, academic rigor, completeness, and innovation), surpassing models with 10x more parameters such as Qwen-2.5-72B-Instruct (15.8/25). Human studies also confirm ScholarCopilot's superior performance in citation recall, writing efficiency, and overall user experience, confirming the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2504.00824)