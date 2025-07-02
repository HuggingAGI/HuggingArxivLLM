# 针对低资源LLM任务的可迁移建模策略：基于提示与对齐的方法

发布时间：2025年07月01日

`LLM应用` `跨语言处理`

> Transferable Modeling Strategies for Low-Resource LLM Tasks: A Prompt and Alignment-Based

# 摘要

> 本文针对大规模语言模型在低资源语言场景下迁移与适应能力有限的问题，提出了一种结合知识转移模块与参数高效微调策略的统一框架。该方法通过知识对齐损失和软提示调优，在最小化标注条件下引导模型有效吸收目标语言或任务的结构特征，从而提升模型的泛化性能与训练稳定性。框架中还引入轻量化适配模块以降低计算成本。在训练过程中，通过冻结策略与提示注入，既保留了模型的原始知识，又实现了对新任务的快速适应。研究还通过稳定性分析实验与合成伪数据迁移实验，系统性评估了该方法在不同低资源任务中的适用性与鲁棒性。实验结果表明，与现有跨语言预训练模型及主流迁移方法相比，所提方法在MLQA、XQuAD和PAWS-X等跨语言任务中实现了更高的性能与稳定性，尤其在数据极度稀缺条件下展现出显著优势。该方法具有较强的通用性与可扩展性，既提升了任务特定的适应能力，又保留了大规模语言模型的通用能力，适用于复杂的语义建模与多语言处理任务。

> This paper addresses the limited transfer and adaptation capabilities of large language models in low-resource language scenarios. It proposes a unified framework that combines a knowledge transfer module with parameter-efficient fine-tuning strategies. The method introduces knowledge alignment loss and soft prompt tuning to guide the model in effectively absorbing the structural features of target languages or tasks under minimal annotation. This enhances both generalization performance and training stability. The framework includes lightweight adaptation modules to reduce computational costs. During training, it integrates freezing strategies and prompt injection to preserve the model's original knowledge while enabling quick adaptation to new tasks. The study also conducts stability analysis experiments and synthetic pseudo-data transfer experiments to systematically evaluate the method's applicability and robustness across different low-resource tasks. Experimental results show that compared with existing multilingual pre-trained models and mainstream transfer methods, the proposed approach achieves higher performance and stability on cross-lingual tasks such as MLQA, XQuAD, and PAWS-X. It demonstrates particularly strong advantages under extremely data-scarce conditions. The proposed method offers strong generality and scalability. It enhances task-specific adaptability while preserving the general capabilities of large language models. This makes it well-suited for complex semantic modeling and multilingual processing tasks.

[Arxiv](https://arxiv.org/abs/2507.00601)