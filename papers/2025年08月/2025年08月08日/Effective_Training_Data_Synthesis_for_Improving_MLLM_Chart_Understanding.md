# 提升多语言大规模语言模型图表理解的有效训练数据合成方法

发布时间：2025年08月08日

`LLM应用` `数据科学`

> Effective Training Data Synthesis for Improving MLLM Chart Understanding

# 摘要

> 有效解读科学图表的能力，即图表理解能力，是构建高效科学智能体的核心要素。然而，现有的多模态大型语言模型（MLLMs），尤其是开源版本，在具有挑战性的基准测试中通常只能达到30%-50%的成功率。先前通过合成图表对MLLMs进行微调的研究往往受限于合成图表与真实图表的相似度不足，这可能影响模型在复杂真实图表上的训练效果和性能。本研究展示了图表生成模块化和视觉细节多样化能够提升图表理解能力。具体而言，我们设计了一个五步数据合成流水线：分离单图生成的数据和函数创建，基于前期子图生成后期子图以支持多子图图表，视觉上多样化生成的图表，过滤低质量数据，并最终通过GPT-4o生成问答对（QA）。这种方法使我们能够高效生成微调数据集，并引入了有效图表数据集（ECD），其中包含10,000多张图表图像和300,000多对问答，涵盖25个主题，并拥有250多种视觉复杂度高的图表类型组合。我们证明，ECD能够持续提升多种MLLMs在真实世界和合成测试集上的性能。代码、数据和模型可在以下链接获取：https://github.com/yuweiyang-anu/ECD.

> Being able to effectively read scientific plots, or chart understanding, is a central part toward building effective agents for science. However, existing multimodal large language models (MLLMs), especially open-source ones, are still falling behind with a typical success rate of 30%-50% on challenging benchmarks. Previous studies on fine-tuning MLLMs with synthetic charts are often restricted by their inadequate similarity to the real charts, which could compromise model training and performance on complex real-world charts. In this study, we show that modularizing chart generation and diversifying visual details improves chart understanding capabilities. In particular, we design a five-step data synthesis pipeline, where we separate data and function creation for single plot generation, condition the generation of later subplots on earlier ones for multi-subplot figures, visually diversify the generated figures, filter out low quality data, and finally generate the question-answer (QA) pairs with GPT-4o. This approach allows us to streamline the generation of fine-tuning datasets and introduce the effective chart dataset (ECD), which contains 10k+ chart images and 300k+ QA pairs, covering 25 topics and featuring 250+ chart type combinations with high visual complexity. We show that ECD consistently improves the performance of various MLLMs on a range of real-world and synthetic test sets. Code, data and models are available at: https://github.com/yuweiyang-anu/ECD.

[Arxiv](https://arxiv.org/abs/2508.06492)