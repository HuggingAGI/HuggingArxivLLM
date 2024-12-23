# “少即是多”：借助统一结构剪枝迈向绿色代码大型语言模型

发布时间：2024年12月20日

`LLM应用` `软件工程` `编码任务`

> Less is More: Towards Green Code Large Language Models via Unified Structural Pruning

# 摘要

> 大型语言模型（LLMs）在生成式编码任务中的广泛应用，因其高计算需求和能耗引发了担忧。与针对处理低维分类对数的分类模型所设计的以往结构剪枝方法不同，生成式代码LLMs会生成高维令牌对数序列，这使得传统剪枝目标存在天然局限。而且，现有的单组件剪枝方法应用于生成式代码LLMs时，有效性进一步受限。为此，我们提出了Flab-Pruner，这是一种创新的统一结构剪枝方法，融合了词汇、层和前馈网络（FFN）剪枝。该方法在有效减少模型参数的同时保持了性能。另外，我们为编码任务引入了定制的代码指令数据策略，以提升剪枝模型的性能恢复效率。通过对多个生成式编码任务中的三个前沿代码LLMs展开广泛评估，结果显示，Flab-Pruner在剪枝22%的参数后仍能保留原始性能的97%，且在后续训练后能达到相同甚至更优的性能。剪枝后的模型在存储、GPU使用、计算效率和环境影响等方面有显著改善，同时保持良好的稳健性。我们的研究为绿色软件工程提供了可持续的解决方案，推动了LLMs在现实世界生成式编码智能应用中的高效部署。

> The extensive application of Large Language Models (LLMs) in generative coding tasks has raised concerns due to their high computational demands and energy consumption. Unlike previous structural pruning methods designed for classification models that deal with lowdimensional classification logits, generative Code LLMs produce high-dimensional token logit sequences, making traditional pruning objectives inherently limited. Moreover, existing single component pruning approaches further constrain the effectiveness when applied to generative Code LLMs. In response, we propose Flab-Pruner, an innovative unified structural pruning method that combines vocabulary, layer, and Feed-Forward Network (FFN) pruning. This approach effectively reduces model parameters while maintaining performance. Additionally, we introduce a customized code instruction data strategy for coding tasks to enhance the performance recovery efficiency of the pruned model. Through extensive evaluations on three state-of-the-art Code LLMs across multiple generative coding tasks, the results demonstrate that Flab-Pruner retains 97% of the original performance after pruning 22% of the parameters and achieves the same or even better performance after post-training. The pruned models exhibit significant improvements in storage, GPU usage, computational efficiency, and environmental impact, while maintaining well robustness. Our research provides a sustainable solution for green software engineering and promotes the efficient deployment of LLMs in real-world generative coding intelligence applications.

[Arxiv](https://arxiv.org/abs/2412.15921)