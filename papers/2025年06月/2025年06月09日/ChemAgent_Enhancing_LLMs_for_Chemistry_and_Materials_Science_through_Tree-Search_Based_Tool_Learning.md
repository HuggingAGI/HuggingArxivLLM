# ChemAgent：基于树搜索的工具学习，提升 LLMs 在化学与材料科学领域的应用能力

发布时间：2025年06月09日

`Agent` `化学信息学`

> ChemAgent: Enhancing LLMs for Chemistry and Materials Science through Tree-Search Based Tool Learning

# 摘要

> 大型语言模型（LLMs）在化学任务中展现出巨大潜力，但受限于预训练知识的滞后性和专业化学知识的整合难度。为应对这些挑战，我们开发了一种基于LLMs的智能体，通过整合137个化学工具（从基础信息检索到复杂反应预测），并构建数据整理流水线生成ChemToolBench数据集，为微调和评估提供支持。我们引入了分层进化蒙特卡洛树搜索（HE-MCTS）框架，实现工具规划与执行的独立优化。借助自动生成的数据，我们的方法支持策略模型的分步微调，并训练出超越GPT-4o性能的任务自适应PRM和ORM。实验结果表明，该方法显著提升了化学问答和发现任务的表现，为LLMs与专业工具的结合提供了强大解决方案，推动了高级化学应用的发展。所有数据和代码已开源，详情请访问https://github.com/AI4Chem/ChemistryAgent。

> Large language models (LLMs) have recently demonstrated promising capabilities in chemistry tasks while still facing challenges due to outdated pretraining knowledge and the difficulty of incorporating specialized chemical expertise. To address these issues, we propose an LLM-based agent that synergistically integrates 137 external chemical tools created ranging from basic information retrieval to complex reaction predictions, and a dataset curation pipeline to generate the dataset ChemToolBench that facilitates both effective tool selection and precise parameter filling during fine-tuning and evaluation. We introduce a Hierarchical Evolutionary Monte Carlo Tree Search (HE-MCTS) framework, enabling independent optimization of tool planning and execution. By leveraging self-generated data, our approach supports step-level fine-tuning (FT) of the policy model and training task-adaptive PRM and ORM that surpass GPT-4o. Experimental evaluations demonstrate that our approach significantly improves performance in Chemistry QA and discovery tasks, offering a robust solution to integrate specialized tools with LLMs for advanced chemical applications. All datasets and code are available at https://github.com/AI4Chem/ChemistryAgent .

[Arxiv](https://arxiv.org/abs/2506.07551)