# 无需大型模型的进化：基于任务原则训练语言模型

发布时间：2025年07月08日

`LLM理论` `人工智能` `机器学习`

> Evolution without Large Models: Training Language Model with Task Principles

# 摘要

> 语言模型的常用训练方法是通过大规模语言模型扩展人工数据集，从而降低训练成本。然而，这一方法仍面临高碳排放和数据泄露两大挑战。为此，我们提出了一种语言模型的自进化方法。首先，通过多级原则生成，大规模模型可基于少量数据总结任务原则。随后，小规模模型利用这些原则生成大量数据用于训练。实验表明，该方法显著优于直接使用小模型生成数据。由于仅在生成任务原则时使用大模型，碳排放大幅减少。

> A common training approach for language models involves using a large-scale language model to expand a human-provided dataset, which is subsequently used for model training.This method significantly reduces training costs by eliminating the need for extensive human data annotation. However, it still faces challenges such as high carbon emissions during data augmentation and the risk of data leakage when we use closed-source LLMs. To address these issues, we propose a self-evolution method for language models. First, we introduce the Multi-level Principle Generation, which enables a large-scale model to summarize task-completion principles based on a small amount of task data. Then, we propose the Principle-based Instance Generation, in which a smaller-scale language model uses these task principles to generate a large amount of data. This data is then used for model training. Experimental results show that our proposed method significantly improves model performance compared to directly using a smaller-scale language model to generate data. Additionally, since we only use the large-scale language model to generate the task-completion principles, the carbon emissions associated with training the model are greatly reduced.

[Arxiv](https://arxiv.org/abs/2507.05991)