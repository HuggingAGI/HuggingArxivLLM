# 用LLMs优化提示，消除AI图像生成中的偏见

发布时间：2025年04月15日

`LLM应用` `图像生成` `人工智能伦理`

> Using LLMs as prompt modifier to avoid biases in AI image generators

# 摘要

> 本研究旨在探索大型语言模型 (LLMs) 如何通过优化用户提示来降低文本到图像生成系统中的偏见。我们将偏见定义为模型在面对中性提示时，与人口统计学特征不一致的不公平偏离。通过在 Stable Diffusion XL、3.5 和 Flux 上进行的实验，我们发现经过 LLM 优化的提示能够显著提升图像多样性并有效减少偏见，而无需对图像生成器本身进行修改。尽管在处理复杂提示时偶尔会出现与原始意图相悖的结果，但总体而言，这种方法为欠指定的请求提供了更加丰富多样的解释，而非简单的表面变化。该方法尤其适用于较为基础的图像生成器，尽管在某些特定情境下（如残疾人群体的表征）仍存在局限性。所有提示和生成的图像均可在 https://iisys-hof.github.io/llm-prompt-img-gen/ 获取。

> This study examines how Large Language Models (LLMs) can reduce biases in text-to-image generation systems by modifying user prompts. We define bias as a model's unfair deviation from population statistics given neutral prompts. Our experiments with Stable Diffusion XL, 3.5 and Flux demonstrate that LLM-modified prompts significantly increase image diversity and reduce bias without the need to change the image generators themselves. While occasionally producing results that diverge from original user intent for elaborate prompts, this approach generally provides more varied interpretations of underspecified requests rather than superficial variations. The method works particularly well for less advanced image generators, though limitations persist for certain contexts like disability representation. All prompts and generated images are available at https://iisys-hof.github.io/llm-prompt-img-gen/

[Arxiv](https://arxiv.org/abs/2504.11104)