# 为山羊养殖户打造基于检索增强生成的AI知识助手

发布时间：2025年09月11日

`RAG` `农业科技`

> Towards an AI-based knowledge assistant for goat farmers based on Retrieval-Augmented Generation

# 摘要

> 大型语言模型（LLMs）在众多行业中已逐渐成为备受认可的知识传播利器。然而，其在畜牧业中的应用却受限，原因包括知识来源的获取难度、多样性及复杂性等多重因素。为此，本研究开发了一款智能知识辅助系统，专门用于支持养殖山羊的健康管理。该系统借助检索增强生成（RAG）技术，创新性地提出表格文本化与决策树文本化两种结构化知识处理方法，旨在提升大型语言模型（LLMs）对异构数据格式的理解能力。基于这些方法，团队构建了特定领域的山羊养殖知识库，从而增强LLM的跨场景泛化能力。该知识库涵盖五大核心领域：疾病防治、营养管理、饲养管理、羊奶管理及基础养殖知识。此外，系统还集成了在线搜索模块，可实时检索最新信息。为验证系统性能，研究开展了六项消融实验，以检验各组件的作用。实验结果显示，异构知识融合方法表现最优，在验证集和测试集上的平均准确率分别达到87.90%和84.22%；在基于文本、表格、决策树的问答任务中，准确率均超85%，证实了模块化设计下结构化知识融合的有效性。错误分析发现，遗漏是主要错误类型，这为进一步提升检索覆盖率和上下文整合能力指明了方向。综上，本研究结果证实了该系统在山羊养殖实际应用中的稳健性与可靠性。

> Large language models (LLMs) are increasingly being recognised as valuable knowledge communication tools in many industries. However, their application in livestock farming remains limited, being constrained by several factors not least the availability, diversity and complexity of knowledge sources. This study introduces an intelligent knowledge assistant system designed to support health management in farmed goats. Leveraging the Retrieval-Augmented Generation (RAG), two structured knowledge processing methods, table textualization and decision-tree textualization, were proposed to enhance large language models' (LLMs) understanding of heterogeneous data formats. Based on these methods, a domain-specific goat farming knowledge base was established to improve LLM's capacity for cross-scenario generalization. The knowledge base spans five key domains: Disease Prevention and Treatment, Nutrition Management, Rearing Management, Goat Milk Management, and Basic Farming Knowledge. Additionally, an online search module is integrated to enable real-time retrieval of up-to-date information. To evaluate system performance, six ablation experiments were conducted to examine the contribution of each component. The results demonstrated that heterogeneous knowledge fusion method achieved the best results, with mean accuracies of 87.90% on the validation set and 84.22% on the test set. Across the text-based, table-based, decision-tree based Q&A tasks, accuracy consistently exceeded 85%, validating the effectiveness of structured knowledge fusion within a modular design. Error analysis identified omission as the predominant error category, highlighting opportunities to further improve retrieval coverage and context integration. In conclusion, the results highlight the robustness and reliability of the proposed system for practical applications in goat farming.

[Arxiv](https://arxiv.org/abs/2509.09848)