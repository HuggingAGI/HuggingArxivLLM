# 您的模型能理解基因吗？ 这是针对生物和文本模型的基因属性基准

发布时间：2024年12月05日

`LLM应用`

> Does your model understand genes? A benchmark of gene properties for biological and text models

# 摘要

> 近年来，深度学习方法，尤其是基础模型在生物研究中的应用迅猛增长。这些模型有的基于文本，有的基于底层生物数据，特别是各类组学数据进行训练。然而，由于训练数据和下游任务存在差异，持续对比这些模型的性能颇具挑战。为应对此问题，我们研发了一种与架构无关的基准测试方法，该方法并非直接评估模型，而是借助每个模型的实体表示向量，为每个基准测试任务训练简单的预测模型。如此一来，确保了所有类型的模型均以相同的输入和输出类型接受评估。在此，我们聚焦于从专业策划的生物信息学数据库中采集的基因属性。这些基因属性分为五大类：基因组属性、调节功能、定位、生物过程和蛋白质属性。总体而言，我们基于这些数据库设定了数百个任务，涵盖二分类、多标签和多类别分类任务。我们运用这些基准任务来评估基于表达的模型、大型语言模型、蛋白质语言模型、基于 DNA 的模型以及传统基线。我们的发现表明，在基因组属性和调节功能任务中，基于文本的模型和蛋白质语言模型通常胜过基于表达的模型，而基于表达的模型在定位任务中表现更佳。这些成果应当有助于制定更具针对性的人工智能策略，以促进生物理解和治疗发现。为保证研究结果的可重复性和透明度，我们已在 github.com/BiomedSciAI/gene-benchmark 公开了源代码和基准数据，以供进一步研究和拓展。

> The application of deep learning methods, particularly foundation models, in biological research has surged in recent years. These models can be text-based or trained on underlying biological data, especially omics data of various types. However, comparing the performance of these models consistently has proven to be a challenge due to differences in training data and downstream tasks. To tackle this problem, we developed an architecture-agnostic benchmarking approach that, instead of evaluating the models directly, leverages entity representation vectors from each model and trains simple predictive models for each benchmarking task. This ensures that all types of models are evaluated using the same input and output types. Here we focus on gene properties collected from professionally curated bioinformatics databases. These gene properties are categorized into five major groups: genomic properties, regulatory functions, localization, biological processes, and protein properties. Overall, we define hundreds of tasks based on these databases, which include binary, multi-label, and multi-class classification tasks. We apply these benchmark tasks to evaluate expression-based models, large language models, protein language models, DNA-based models, and traditional baselines. Our findings suggest that text-based models and protein language models generally outperform expression-based models in genomic properties and regulatory functions tasks, whereas expression-based models demonstrate superior performance in localization tasks. These results should aid in the development of more informed artificial intelligence strategies for biological understanding and therapeutic discovery. To ensure the reproducibility and transparency of our findings, we have made the source code and benchmark data publicly accessible for further investigation and expansion at github.com/BiomedSciAI/gene-benchmark.

[Arxiv](https://arxiv.org/abs/2412.04075)