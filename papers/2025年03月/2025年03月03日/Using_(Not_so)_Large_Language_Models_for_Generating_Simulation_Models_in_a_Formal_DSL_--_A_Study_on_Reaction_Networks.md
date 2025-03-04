# 利用并不算大的语言模型在正式领域特定语言中生成仿真模型——一项关于反应网络的研究

发布时间：2025年03月03日

`LLM应用` `建模与仿真`

> Using (Not so) Large Language Models for Generating Simulation Models in a Formal DSL -- A Study on Reaction Networks

# 摘要

> 形式语言在建模与仿真中扮演着重要角色。它们能够将知识浓缩成便于自动执行、解释和分析的仿真模型。然而，最易被人理解的建模方式是通过自然语言，但自然语言并不容易被计算机解析。在这里，我们评估如何利用大型语言模型（LLM）将自然语言形式化为仿真模型。现有研究仅探索了使用未经过微调的大型LLM（如商用的GPT模型）。为填补这一空白，我们展示了如何对一个开放权重、70亿参数的Mistral模型进行微调，使其能够将自然语言描述转换为特定领域语言中的反应网络模型，从而提供一个可自托管、计算与内存高效的替代方案。为此，我们开发了一个合成数据生成器，作为微调与评估的基础。我们的定量评估表明，微调后的Mistral模型在84.5%的情况下能够恢复真实仿真模型。此外，我们的小型用户研究表明，该模型在一次性生成以及跨领域交互式建模方面具有实用潜力。尽管前景光明，但目前形式化的微调小模型尚无法追上大型模型的水平。我们得出结论，更高质量的训练数据是必要的，并期待未来的小型开源LLM将带来新的机遇。

> Formal languages are an integral part of modeling and simulation. They allow the distillation of knowledge into concise simulation models amenable to automatic execution, interpretation, and analysis. However, the arguably most humanly accessible means of expressing models is through natural language, which is not easily interpretable by computers. Here, we evaluate how a Large Language Model (LLM) might be used for formalizing natural language into simulation models. Existing studies only explored using very large LLMs, like the commercial GPT models, without fine-tuning model weights. To close this gap, we show how an open-weights, 7B-parameter Mistral model can be fine-tuned to translate natural language descriptions to reaction network models in a domain-specific language, offering a self-hostable, compute-, and memory efficient alternative. To this end, we develop a synthetic data generator to serve as the basis for fine-tuning and evaluation. Our quantitative evaluation shows that our fine-tuned Mistral model can recover the ground truth simulation model in up to 84.5% of cases. In addition, our small-scale user study demonstrates the model's practical potential for one-time generation as well as interactive modeling in various domains. While promising, in its current form, the fine-tuned small LLM cannot catch up with large LLMs. We conclude that higher-quality training data are required, and expect future small and open-source LLMs to offer new opportunities.

[Arxiv](https://arxiv.org/abs/2503.01675)