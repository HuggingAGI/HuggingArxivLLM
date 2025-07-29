# 通过向推理过程注入外部知识来增强检索增强生成

发布时间：2025年07月25日

`RAG` `问答系统`

> Injecting External Knowledge into the Reasoning Process Enhances Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）被广泛采用，用于通过外部知识增强大型语言模型（LLMs），以应对知识密集型任务。然而，其有效性常常因检索到的噪声片段（即低质量片段）而受到削弱。提升LLMs对这种噪声的鲁棒性对于提高RAG系统的可靠性至关重要。近期进展已使LLMs具备强大的推理和自我反思能力，使其能够识别并纠正推理过程中的错误。受此启发，我们提出了一种名为片段注入（Passage Injection）的简单而有效的方法，该方法将检索到的片段显式地融入LLMs的推理过程，旨在增强模型识别和抵制噪声片段的能力。我们在一般RAG设置下使用BM25作为检索器对片段注入进行了验证。在四个事实型问答数据集上对四个增强推理的LLMs进行的实验表明，片段注入显著提升了整体RAG性能。进一步在两种噪声检索设置——随机噪声（模型获得无关片段）和反事实噪声（模型获得误导性片段）——上的分析表明，片段注入始终提高了鲁棒性。控制实验证实，片段注入还可以有效利用有益片段。这些发现表明，将片段纳入LLMs的推理过程是构建更 robust RAG 系统的有前途方向。代码可在\href{here}{https://github.com/mh-tang/Passage-Injection}找到。

> Retrieval-augmented generation (RAG) has been widely adopted to augment large language models (LLMs) with external knowledge for knowledge-intensive tasks. However, its effectiveness is often undermined by the presence of noisy (i.e., low-quality) retrieved passages. Enhancing LLMs' robustness to such noise is critical for improving the reliability of RAG systems. Recent advances have equipped LLMs with strong reasoning and self-reflection capabilities, allowing them to identify and correct errors in their reasoning process. Inspired by this ability, we propose Passage Injection-a simple yet effective method that explicitly incorporates retrieved passages into LLMs' reasoning process, aiming to enhance the model's ability to recognize and resist noisy passages. We validate Passage Injection under general RAG settings using BM25 as the retriever. Experiments on four reasoning-enhanced LLMs across four factual QA datasets demonstrate that Passage Injection significantly improves overall RAG performance. Further analysis on two noisy retrieval settings-random noise, where the model is provided irrelevant passages, and counterfactual noise, where it is given misleading passages-shows that Passage Injection consistently improves robustness. Controlled experiments confirm that Passage Injection can also effectively leverage helpful passages. These findings suggest that incorporating passages in LLMs' reasoning process is a promising direction for building more robust RAG systems. The code can be found \href{here}{https://github.com/mh-tang/Passage-Injection}.

[Arxiv](https://arxiv.org/abs/2507.19333)