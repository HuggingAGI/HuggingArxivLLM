# 结构化知识增强的大型语言模型提升多跳事实核查能力

发布时间：2025年03月11日

`LLM应用` `事实核查` `知识图谱`

> Enhancing Multi-Hop Fact Verification with Structured Knowledge-Augmented Large Language Models

# 摘要

> 社交平台的快速发展加剧了虚假信息的传播，这推动了事实核查领域的研究。目前，研究者们倾向于利用语义特征将事实核查视为单跳任务来解决。然而，在现实场景中，验证一个声明往往需要多条证据，并且这些证据之间存在复杂的逻辑和关联。尽管近期研究试图通过提升模型的理解和推理能力来改善性能，但它们忽略了实体间的关键关系，而这些关系对模型的理解和预测至关重要。为了突出关系的重要性，我们引入了大型语言模型（LLMs），因为它们具备出色的理解能力。与其它方法将LLMs作为预测器不同，我们将其用作关系抽取器，因为实验表明，LLMs在理解方面表现更佳。因此，为了解决上述挑战，我们提出了一种基于LLM的结构化知识增强网络（LLM-SKAN），用于多跳事实核查。具体而言，我们采用一个由LLM驱动的知识提取器，以捕获包括实体及其复杂关联在内的细粒度信息。此外，我们设计了一个知识增强的关系图融合模块，通过与每个节点交互，全面学习更优的声明-证据表示。在四个常用数据集上的实验结果验证了我们模型的优越性和有效性。

> The rapid development of social platforms exacerbates the dissemination of misinformation, which stimulates the research in fact verification. Recent studies tend to leverage semantic features to solve this problem as a single-hop task. However, the process of verifying a claim requires several pieces of evidence with complicated inner logic and relations to verify the given claim in real-world situations. Recent studies attempt to improve both understanding and reasoning abilities to enhance the performance, but they overlook the crucial relations between entities that benefit models to understand better and facilitate the prediction. To emphasize the significance of relations, we resort to Large Language Models (LLMs) considering their excellent understanding ability. Instead of other methods using LLMs as the predictor, we take them as relation extractors, for they do better in understanding rather than reasoning according to the experimental results. Thus, to solve the challenges above, we propose a novel Structured Knowledge-Augmented LLM-based Network (LLM-SKAN) for multi-hop fact verification. Specifically, we utilize an LLM-driven Knowledge Extractor to capture fine-grained information, including entities and their complicated relations. Besides, we leverage a Knowledge-Augmented Relation Graph Fusion module to interact with each node and learn better claim-evidence representations comprehensively. The experimental results on four common-used datasets demonstrate the effectiveness and superiority of our model.

[Arxiv](https://arxiv.org/abs/2503.08495)