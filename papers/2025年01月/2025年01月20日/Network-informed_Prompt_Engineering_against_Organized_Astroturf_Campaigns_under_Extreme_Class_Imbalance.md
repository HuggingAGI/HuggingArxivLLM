# 网络信息提示工程：应对极端类别不平衡下的有组织虚假宣传

发布时间：2025年01月20日

`RAG

理由：这篇论文提出了一种基于大型语言模型（LLMs）的框架，并引入了“平衡检索增强生成（Balanced RAG）”组件，用于检测社交媒体上的协调虚假信息活动。RAG（Retrieval-Augmented Generation）是一种结合检索和生成的技术，通常用于增强语言模型的能力。论文中的方法通过提示工程和Balanced RAG来提升LLMs的性能，因此应归类为RAG。` `社交媒体` `虚假信息检测`

> Network-informed Prompt Engineering against Organized Astroturf Campaigns under Extreme Class Imbalance

# 摘要

> # 摘要
检测有组织的政治活动对于打击社交媒体上的虚假信息至关重要。现有方法主要依赖网络科学、图机器学习和自然语言处理技术，通过分析用户互动（如转发）和帖子文本相似性来识别这些活动。尽管这些方法在识别虚假宣传活动方面表现不俗，但它们面临类别不平衡等挑战。为解决这一问题，近期研究多采用数据增强或增加正样本数量，但这些方法在实际应用中往往不够理想。本文提出了一种基于大型语言模型（LLMs）的全新框架，引入平衡检索增强生成（Balanced RAG）组件，用于识别虚假宣传活动。我们的方法将帖子文本信息和用户互动作为输入，通过提示工程和Balanced RAG方法，有效检测X（Twitter）上的协调虚假信息活动。该框架无需训练或微调语言模型，而是通过提示工程和Balanced RAG的优势，帮助LLMs克服类别不平衡问题，精准识别协调政治活动。实验结果显示，结合提示工程和Balanced RAG方法，我们的框架在精确率、召回率和F1分数上比传统图方法提升了2到3倍。

> Detecting organized political campaigns is of paramount importance in fighting against disinformation on social media. Existing approaches for the identification of such organized actions employ techniques mostly from network science, graph machine learning and natural language processing. Their ultimate goal is to analyze the relationships and interactions (e.g. re-posting) among users and the textual similarities of their posts. Despite their effectiveness in recognizing astroturf campaigns, these methods face significant challenges, notably the class imbalance in available training datasets. To mitigate this issue, recent methods usually resort to data augmentation or increasing the number of positive samples, which may not always be feasible or sufficient in real-world settings. Following a different path, in this paper, we propose a novel framework for identifying astroturf campaigns based solely on large language models (LLMs), introducing a Balanced Retrieval-Augmented Generation (Balanced RAG) component. Our approach first gives both textual information concerning the posts (in our case tweets) and the user interactions of the social network as input to a language model. Then, through prompt engineering and the proposed Balanced RAG method, it effectively detects coordinated disinformation campaigns on X (Twitter). The proposed framework does not require any training or fine-tuning of the language model. Instead, by strategically harnessing the strengths of prompt engineering and Balanced RAG, it facilitates LLMs to overcome the effects of class imbalance and effectively identify coordinated political campaigns. The experimental results demonstrate that by incorporating the proposed prompt engineering and Balanced RAG methods, our framework outperforms the traditional graph-based baselines, achieving 2x-3x improvements in terms of precision, recall and F1 scores.

[Arxiv](https://arxiv.org/abs/2501.11849)