# Jasper 与 Stella：SOTA 嵌入模型的精炼

发布时间：2024年12月25日

`RAG

理由：该论文摘要主要讨论了密集检索在深度学习应用中的重要性，特别是提到了FAQ和RAG（Retrieval-Augmented Generation）作为应用场景。论文提出的解决方案（如蒸馏技术、减少向量维度的训练方法、多模态编码器升级）都是为了优化密集检索的性能，这与RAG的核心思想密切相关。因此，该论文应归类为RAG。` `信息检索`

> Jasper and Stella: distillation of SOTA embedding models

# 摘要

> 在许多深度学习应用（如FAQ和RAG）中，密集检索是一个关键组件。它通过嵌入模型将文本转化为数值向量，并利用MIPS（最大内积搜索）找到最相似的文本。为了准确评估嵌入模型，业界建立了MTEB、BEIR和AIR-Bench等基准。尽管这些基准让我们能够使用SOTA模型，但其庞大的向量维度和参数数量阻碍了它们在工业中的部署。为此，我们提出了以下解决方案：1）一种蒸馏技术，使小型学生模型也能表现出色；2）受MRL启发，基于自身或教师向量减少向量维度的训练方法；3）通过简单有效的图像-文本对齐训练，将模型升级为多模态编码器。我们利用这些技术训练了Stella和Jasper模型，并在MTEB排行榜上取得了优异成绩。模型和数据已发布在Hugging Face Hub（https://huggingface.co/infgrad/jasper_en_vision_language_v1），训练日志可在https://api.wandb.ai/links/dunnzhang0/z8jqoqpb查看。

> A crucial component of many deep learning applications (such as FAQ and RAG) is dense retrieval, in which embedding models are used to convert raw text to numerical vectors and then get the most similar text by MIPS (Maximum Inner Product Search). Some text embedding benchmarks (e.g. MTEB, BEIR, and AIR-Bench) have been established to evaluate embedding models accurately. Thanks to these benchmarks, we can use SOTA models; however, the deployment and application of these models in industry were hampered by their large vector dimensions and numerous parameters. To alleviate this problem, 1) we present a distillation technique that can enable a smaller student model to achieve good performance. 2) Inspired by MRL we present a training approach of reducing the vector dimensions based on its own vectors or its teacher vectors. 3) We do simple yet effective alignment training between images and text to make our model a multimodal encoder. We trained Stella and Jasper models using the technologies above and achieved high scores on the MTEB leaderboard. We release the model and data at Hugging Face Hub (https://huggingface.co/infgrad/jasper_en_vision_language_v1) and the training logs are at https://api.wandb.ai/links/dunnzhang0/z8jqoqpb.

[Arxiv](https://arxiv.org/abs/2412.19048)