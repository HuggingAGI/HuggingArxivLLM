# UML类图的行为增强：大型语言模型在方法生成中的实证研究

发布时间：2025年05月31日

`LLM应用` `软件工程` `行为建模`

> Behavioral Augmentation of UML Class Diagrams: An Empirical Study of Large Language Models for Method Generation

# 摘要

> 自动化地从自然语言用例中丰富UML类图的行为方法是一个重要挑战。本研究评估了九个大型语言模型（LLMs），利用21个结构化的废物管理用例，增强一个没有方法的UML图（包含21个类和17个关系）。总共评估了90个图（3,373个方法），使用六个指标：方法数量、签名丰富度（可见性、名称、参数、返回类型）、注释完整性（链接到用例/动作）、结构保真度、语法正确性（PlantUML编译）和命名一致性（跨模型）。所有LLMs都生成了符合UML规范的有效PlantUML图。一些模型在方法覆盖和注释准确性上表现突出，而另一些则在参数化更丰富但可追溯性较弱。这些结果表明，LLMs可以生成结构良好的方法，具有命名一致性，推动了自动化行为建模的发展。然而，注释和签名的一致性问题凸显了改进提示工程和模型选择的必要性。这些方法的快速生成支持了敏捷实践，加快了设计迭代。尽管LLMs具备这些能力，但人工监督仍至关重要，以确保准确性、恰当性和语义一致性。这将LLMs定位为软件设计中的协作伙伴。所有实验材料（.puml, .png, .csv）公开可用，以支持可重复性。

> Automating the enrichment of UML class diagrams with behavioral methods from natural language use cases is a significant challenge. This study evaluates nine large language models (LLMs) in augmenting a methodless UML diagram (21 classes, 17 relationships) using 21 structured waste-management use cases. A total of 90 diagrams (3,373 methods) were assessed across six metrics: method quantity, signature richness (visibility, names, parameters, return types), annotation completeness (linking to use cases/actions), structural fidelity, syntactic correctness (PlantUML compilation), and naming convergence (across models). All LLMs produced valid PlantUML diagrams adhering to UML conventions. Some models excelled in method coverage and annotation accuracy, while others showed richer parameterization but weaker traceability. These results demonstrate that LLMs can generate well-structured methods with consistent naming, advancing automated behavioral modeling. However, inconsistencies in annotations and signatures highlight the need for improved prompt engineering and model selection. The rapid generation of these methods supports Agile practices by enabling faster design iterations. Despite their capabilities, human oversight is essential to ensure accuracy, appropriateness, and semantic alignment. This positions LLMs as collaborative partners in software design. All experimental artifacts (\texttt{.puml}, \texttt{.png}, \texttt{.csv}) are publicly available for reproducibility.

[Arxiv](https://arxiv.org/abs/2506.00788)