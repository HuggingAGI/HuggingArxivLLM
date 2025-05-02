# 针对资源匮乏方言的大型语言模型微调：以黎巴嫩方言为例

发布时间：2025年04月30日

`LLM应用`

> Fine-Tuning LLMs for Low-Resource Dialect Translation: The Case of Lebanese

# 摘要

> 本文探讨了大型语言模型（LLMs）在低资源黎巴嫩方言翻译中的表现，重点关注文化真实数据与大规模翻译数据的对比。我们基于开源的Aya23模型，分别采用基础微调、对比微调和语法提示微调三种方法进行研究。实验结果表明，使用规模较小但富含文化背景的黎巴嫩方言数据集（LW）进行微调的模型，表现优于基于大规模非母语数据训练的模型。其中，对比微调结合对比提示的方法取得了最佳效果，这表明向翻译模型引入不良示例具有显著优势。此外，为确保评估的真实性，我们提出了LebEval基准，该基准基于黎巴嫩母语内容构建，并与现有的FLoRes基准进行了对比。我们的研究结果不仅挑战了“更多数据更好”的传统观念，还凸显了文化真实性在方言翻译中的关键作用。我们的数据集和代码已开源至Github。

> This paper examines the effectiveness of Large Language Models (LLMs) in translating the low-resource Lebanese dialect, focusing on the impact of culturally authentic data versus larger translated datasets. We compare three fine-tuning approaches: Basic, contrastive, and grammar-hint tuning, using open-source Aya23 models. Experiments reveal that models fine-tuned on a smaller but culturally aware Lebanese dataset (LW) consistently outperform those trained on larger, non-native data. The best results were achieved through contrastive fine-tuning paired with contrastive prompting, which indicates the benefits of exposing translation models to bad examples. In addition, to ensure authentic evaluation, we introduce LebEval, a new benchmark derived from native Lebanese content, and compare it to the existing FLoRes benchmark. Our findings challenge the "More Data is Better" paradigm and emphasize the crucial role of cultural authenticity in dialectal translation. We made our datasets and code available on Github.

[Arxiv](https://arxiv.org/abs/2505.00114)