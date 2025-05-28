# AI4Math：为大型语言模型设计的大学水平数学推理原生西班牙语基准测试

发布时间：2025年05月25日

`LLM应用` `数学推理`

> AI4Math: A Native Spanish Benchmark for University-Level Mathematical Reasoning in Large Language Models

# 摘要

> 当前数学推理基准大多局限于纯英文或基于翻译的模式，这可能导致语义偏差并掩盖特定语言的推理错误。为了解决这一问题，我们推出了AI4Math——一个包含105个原版大学数学问题的基准测试，全部以西班牙语原生创作。该数据集覆盖七个高级领域（代数、微积分、几何、概率、数论、组合学和逻辑），每个问题都附有详细的分步解答。我们评估了六种大型语言模型：GPT-4o、GPT-4o mini、o3 mini、LLaMA 3.3 70B、DeepSeek R1 685B和DeepSeek V3 685B，分别在四种配置下进行测试：零样本和思维链模式，每种模式均使用西班牙语和英语。最优模型（o3 mini、DeepSeek R1 685B、DeepSeek V3 685B）的准确率超过70%，而LLaMA 3.3 70B和GPT-4o mini的表现均低于40%。大多数模型在不同语言间的性能差距不大，其中GPT-4o在西班牙语的零样本设置下表现更优。几何、组合学和概率问题对所有模型来说仍然具有较大挑战性。这些结果凸显了本土语言基准和领域特定评估的重要性，以揭示标准指标未能捕捉的推理失效情况。

> Existing mathematical reasoning benchmarks are predominantly English only or translation-based, which can introduce semantic drift and mask languagespecific reasoning errors. To address this, we present AI4Math, a benchmark of 105 original university level math problems natively authored in Spanish. The dataset spans seven advanced domains (Algebra, Calculus, Geometry, Probability, Number Theory, Combinatorics, and Logic), and each problem is accompanied by a step by step human solution. We evaluate six large language models GPT 4o, GPT 4o mini, o3 mini, LLaMA 3.3 70B, DeepSeek R1 685B, and DeepSeek V3 685B under four configurations: zero shot and chain of thought, each in Spanish and English. The top models (o3 mini, DeepSeek R1 685B, DeepSeek V3 685B) achieve over 70% accuracy, whereas LLaMA 3.3 70B and GPT-4o mini remain below 40%. Most models show no significant performance drop between languages, with GPT 4o even performing better on Spanish problems in the zero shot setting. Geometry, Combinatorics, and Probability questions remain persistently challenging for all models. These results highlight the need for native-language benchmarks and domain-specific evaluations to reveal reasoning failures not captured by standard metrics.

[Arxiv](https://arxiv.org/abs/2505.18978)