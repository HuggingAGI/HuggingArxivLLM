# MAQInstruct: 基于指令的统一事件关系抽取

发布时间：2025年02月06日

`LLM应用

理由：这篇论文讨论了如何利用大型语言模型（LLM）通过指令调优来解决事件关系提取任务中的挑战。具体来说，论文提出了MAQInstruct框架，该框架通过改变任务的形式和引入二分匹配损失来优化LLM在事件关系提取中的表现。这属于LLM在实际任务中的应用，因此分类为“LLM应用”。` `事件关系提取`

> MAQInstruct: Instruction-based Unified Event Relation Extraction

# 摘要

> 提取与已知模式偏离的事件关系对传统方法（如多类分类、MASK预测或原型匹配）一直是个难题。尽管大型语言模型通过指令调优展现了强大的性能，但在事件关系提取任务中，基于指令的方法仍面临两大挑战：推理样本数量庞大，且事件关系是非顺序的。为此，我们提出了MAQInstruct框架。该框架首先将任务从“基于事件-事件指令提取关系”转变为“基于事件-关系指令选择事件”，从而减少推理样本需求。其次，通过引入二分匹配损失，降低了对生成序列的依赖。实验表明，MAQInstruct显著提升了多个LLM在事件关系提取任务中的表现。

> Extracting event relations that deviate from known schemas has proven challenging for previous methods based on multi-class classification, MASK prediction, or prototype matching. Recent advancements in large language models have shown impressive performance through instruction tuning. Nevertheless, in the task of event relation extraction, instruction-based methods face several challenges: there are a vast number of inference samples, and the relations between events are non-sequential. To tackle these challenges, we present an improved instruction-based event relation extraction framework named MAQInstruct. Firstly, we transform the task from extracting event relations using given event-event instructions to selecting events using given event-relation instructions, which reduces the number of samples required for inference. Then, by incorporating a bipartite matching loss, we reduce the dependency of the instruction-based method on the generation sequence. Our experimental results demonstrate that MAQInstruct significantly improves the performance of event relation extraction across multiple LLMs.

[Arxiv](https://arxiv.org/abs/2502.03954)