# GenKnowSub：通过通用知识减法优化LLMs的模块化与可重用性

发布时间：2025年05月16日

`LLM理论`

> GenKnowSub: Improving Modularity and Reusability of LLMs through General Knowledge Subtraction

# 摘要

> 大型语言模型在零样本泛化方面常常面临挑战，为此，人们提出了多种模块化方法来应对这一难题。然而，我们推测仍存在一个关键限制：通用知识与任务特定适应之间的纠缠。为了解决这一问题，我们提出了一种模块化框架，通过构建任务特定的LoRA模块库以及通用领域的LoRA模块来分离这些组件。通过从每个任务特定模块中减去这一通用知识组件，我们获得了专注于任务相关信息的残差模块，这种方法我们称之为通用知识减法（GenKnowSub）。利用优化后的任务特定模块和Arrow路由算法【数学公式】，我们可以在不进行额外训练的情况下，动态选择和组合模块以处理新的输入。以Phi-3模型和标准Arrow作为基准，我们的研究表明，使用从包括英语、法语和德语在内的多种语言中提取的通用知识LoRAs，在广泛的基准测试中，无论是单语还是跨语言设置，都能带来一致的性能提升。在Phi-2上的进一步实验展示了GenKnowSub如何推广到较弱的大型语言模型。完整的代码和数据可在https://github.com/saharsamr/Modular-LLM获取。

> Large language models often struggle with zero-shot generalization, and several modular approaches have been proposed to address this challenge. Yet, we hypothesize that a key limitation remains: the entanglement of general knowledge and task-specific adaptations. To overcome this, we propose a modular framework that disentangles these components by constructing a library of task-specific LoRA modules alongside a general-domain LoRA. By subtracting this general knowledge component from each task-specific module, we obtain residual modules that focus more exclusively on task-relevant information, a method we call general knowledge subtraction (GenKnowSub). Leveraging the refined task-specific modules and the Arrow routing algorithm \citep{ostapenko2024towards}, we dynamically select and combine modules for new inputs without additional training. Our studies on the Phi-3 model and standard Arrow as baselines reveal that using general knowledge LoRAs derived from diverse languages, including English, French, and German, yields consistent performance gains in both monolingual and cross-lingual settings across a wide set of benchmarks. Further experiments on Phi-2 demonstrate how GenKnowSub generalizes to weaker LLMs. The complete code and data are available at https://github.com/saharsamr/Modular-LLM.

[Arxiv](https://arxiv.org/abs/2505.10939)