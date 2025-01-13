# 多智能体微调：利用多样化推理链实现自我提升

发布时间：2025年01月09日

`Agent

理由：这篇论文主要讨论了利用多智能体（multi-agent）群体来改进大型语言模型（LLMs）的方法。通过多智能体交互生成数据并进行独立更新，从而实现模型的专门化和多样化。这种方法涉及到多个智能体之间的协作和交互，属于多智能体系统（Multi-Agent Systems, MAS）的范畴，因此应归类为Agent。` `人工智能`

> Multiagent Finetuning: Self Improvement with Diverse Reasoning Chains

# 摘要

> 近年来，大型语言模型（LLMs）表现卓越，但其性能受限于训练数据。为了突破这一限制，研究者们开始探索利用LLMs生成合成数据以实现自主改进。然而，连续的自我改进可能导致收益递减。为此，我们提出了一种新的方法：将微调应用于语言模型的多智能体群体。这些模型均基于同一基础模型，通过多智能体交互生成的数据进行独立更新，从而实现专门化。通过在独立数据集上训练，我们展示了该方法如何促进模型的专门化和多样化。最终，我们的系统能够保留多样化的推理链，并在比单智能体方法更多的微调轮次中持续改进。我们通过一系列推理任务定量验证了该方法的有效性。

> Large language models (LLMs) have achieved remarkable performance in recent years but are fundamentally limited by the underlying training data. To improve models beyond the training data, recent works have explored how LLMs can be used to generate synthetic data for autonomous self-improvement. However, successive steps of self-improvement can reach a point of diminishing returns. In this work, we propose a complementary approach towards self-improvement where finetuning is applied to a multiagent society of language models. A group of language models, all starting from the same base model, are independently specialized by updating each one using data generated through multiagent interactions among the models. By training each model on independent sets of data, we illustrate how this approach enables specialization across models and diversification over the set of models. As a result, our overall system is able to preserve diverse reasoning chains and autonomously improve over many more rounds of fine-tuning than single-agent self-improvement methods. We quantitatively illustrate the efficacy of the approach across a wide suite of reasoning tasks.

[Arxiv](https://arxiv.org/abs/2501.05707)