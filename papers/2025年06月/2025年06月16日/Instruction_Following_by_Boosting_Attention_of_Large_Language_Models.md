# 大型语言模型注意力增强：遵循指令的新方法

发布时间：2025年06月16日

`LLM理论` `人工智能`

> Instruction Following by Boosting Attention of Large Language Models

# 摘要

> 控制大型语言模型（LLMs）的生成仍然是确保其安全可靠部署的核心挑战。尽管提示工程和微调是常用方法，但近期研究探索了一种轻量级技术——潜在引导，通过改变LLM的内部激活来引导生成。然而，后续研究发现潜在引导的有效性有限，通常在表现上不如简单的指令提示。为了解决这一局限性，我们首先在多种行为上建立了一个基准，以便对引导技术进行标准化评估。基于此基准的见解，我们引入了指令注意力增强（InstABoost），这是一种潜在引导方法，通过在生成过程中改变模型的注意力来增强指令提示的效果。InstABoost结合了现有方法的优势，并在理论上得到了先前工作的支持，这些工作表明，可以通过操纵对指令的注意力来控制基于变换器模型的上下文规则遵循。实证结果显示，与传统的提示方法和潜在引导相比，InstABoost在控制成功方面表现更优。


> Controlling the generation of large language models (LLMs) remains a central challenge to ensure their safe and reliable deployment. While prompt engineering and finetuning are common approaches, recent work has explored latent steering, a lightweight technique that alters LLM internal activations to guide generation. However, subsequent studies revealed latent steering's effectiveness to be limited, often underperforming simple instruction prompting. To address this limitation, we first establish a benchmark across diverse behaviors for standardized evaluation of steering techniques. Building on insights from this benchmark, we introduce Instruction Attention Boosting (InstABoost), a latent steering method that boosts the strength of instruction prompting by altering the model's attention during generation. InstABoost combines the strengths of existing approaches and is theoretically supported by prior work that suggests that in-context rule following in transformer-based models can be controlled by manipulating attention on instructions. Empirically, InstABoost demonstrates superior control success compared to both traditional prompting and latent steering.

[Arxiv](https://arxiv.org/abs/2506.13734)