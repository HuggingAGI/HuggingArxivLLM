# 稀疏注意力向量：生成式多模态模型的特征可作为判别性的视觉语言分类器

发布时间：2024年11月28日

`LLM应用` `计算机视觉` `多模态模型`

> Sparse Attention Vectors: Generative Multimodal Model Features Are Discriminative Vision-Language Classifiers

# 摘要

> 像 LLaVA 和 Qwen-VL 这样的生成式大型多模态模型（LMMs）在众多视觉语言（VL）任务中表现出众，像图像描述、视觉问答等。尽管表现出色，但 LMMs 并不直接适用于基础的判别式视觉语言任务，比如图像分类和多项选择 VQA 这类需要离散标签预测的任务。在将 LMMs 用于判别任务时，关键难题在于从生成模型中提取有用特征。为解决此问题，我们提出一种在模型潜在空间中找寻特征的办法，从而更有效地将 LMMs 用于判别任务。为此，我们推出了稀疏注意力向量（SAVs）——一种无需微调的方法，它把 LMMs 中稀疏的注意力头激活（少于 1%的头）当作 VL 任务的强大特征。仅凭借少量示例，SAVs 在一系列判别任务中与各种少量示例和微调基线相比，展现出了顶尖的性能。我们的实验还显示，SAVs 的性能能够随着更多示例而提升，并能推广到相似任务，这确立了 SAVs 是既有效又强大的多模态特征表示。

> Generative Large Multimodal Models (LMMs) like LLaVA and Qwen-VL excel at a wide variety of vision-language (VL) tasks such as image captioning or visual question answering. Despite strong performance, LMMs are not directly suited for foundational discriminative vision-language tasks (i.e., tasks requiring discrete label predictions) such as image classification and multiple-choice VQA. One key challenge in utilizing LMMs for discriminative tasks is the extraction of useful features from generative models. To overcome this issue, we propose an approach for finding features in the model's latent space to more effectively leverage LMMs for discriminative tasks. Toward this end, we present Sparse Attention Vectors (SAVs) -- a finetuning-free method that leverages sparse attention head activations (fewer than 1\% of the heads) in LMMs as strong features for VL tasks. With only few-shot examples, SAVs demonstrate state-of-the-art performance compared to a variety of few-shot and finetuned baselines on a collection of discriminative tasks. Our experiments also imply that SAVs can scale in performance with additional examples and generalize to similar tasks, establishing SAVs as both effective and robust multimodal feature representations.

[Arxiv](https://arxiv.org/abs/2412.00142)