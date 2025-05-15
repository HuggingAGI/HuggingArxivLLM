# 打造大模型助力高性能微处理器 VHDL 设计

发布时间：2025年05月14日

`LLM应用` `硬件设计` `高性能处理器设计`

> Customizing a Large Language Model for VHDL Design of High-Performance Microprocessors

# 摘要

> 近年来，大型语言模型（LLMs）在硬件设计领域迅速发展，尤其是在提升芯片设计工具生产力方面。关于LLMs在芯片设计的RTL规范中的应用，Verilog和VHDL是两大主流语言。尽管Verilog因其高流行度受到更多关注，但VHDL在行业中的持续受欢迎程度却未得到应有的重视。此外，关于高性能处理器设计组织的独特需求以及在这些环境中部署AI解决方案的技术，讨论也相对较少。本文将带领大家了解我们开发一个专门用于解释VHDL代码的大型语言模型（LLM）的历程，这一任务对一个拥有数十年高性能处理器设计经验的组织尤为重要。我们详细介绍了如何为特定需求开发测试集，并在对基础LLM进行扩展预训练（EPT）时用于模型评估。结果显示，专家对EPT模型生成的代码解释评估从基础模型的43%显著提升至69%。我们还展示了如何开发一个LLM作为裁判来评估模型，其效果与专家评估者相当。这使我们能够推导和评估众多新模型，包括一个预期专家评估者评分达71%的EPT模型的指令微调版本。实验数据表明，通过引入更新的基础模型，评分有望进一步提升至85%以上。最后，我们探讨了如何利用生成式AI领域的最新进展，进一步提升硬件设计LLMs的质量。

> The use of Large Language Models (LLMs) in hardware design has taken off in recent years, principally through its incorporation in tools that increase chip designer productivity. There has been considerable discussion about the use of LLMs in RTL specifications of chip designs, for which the two most popular languages are Verilog and VHDL. LLMs and their use in Verilog design has received significant attention due to the higher popularity of the language, but little attention so far has been given to VHDL despite its continued popularity in the industry. There has also been little discussion about the unique needs of organizations that engage in high-performance processor design, and techniques to deploy AI solutions in these settings. In this paper, we describe our journey in developing a Large Language Model (LLM) specifically for the purpose of explaining VHDL code, a task that has particular importance in an organization with decades of experience and assets in high-performance processor design. We show how we developed test sets specific to our needs and used them for evaluating models as we performed extended pretraining (EPT) of a base LLM. Expert evaluation of the code explanations produced by the EPT model increased to 69% compared to a base model rating of 43%. We further show how we developed an LLM-as-a-judge to gauge models similar to expert evaluators. This led us to deriving and evaluating a host of new models, including an instruction-tuned version of the EPT model with an expected expert evaluator rating of 71%. Our experiments also indicate that with the potential use of newer base models, this rating can be pushed to 85% and beyond. We conclude with a discussion on further improving the quality of hardware design LLMs using exciting new developments in the Generative AI world.

[Arxiv](https://arxiv.org/abs/2505.09610)