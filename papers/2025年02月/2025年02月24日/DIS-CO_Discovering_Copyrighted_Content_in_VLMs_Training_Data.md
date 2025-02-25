# # DIS-CO：识别视觉语言模型训练数据集中的版权内容

发布时间：2025年02月24日

`LLM应用

摘要中提到的论文探讨了如何验证大型视觉语言模型（VLM）是否使用受版权保护的内容进行训练，提出了一种名为DIS-CO的方法，并通过基准数据集评估其有效性。这属于模型训练过程中的实际应用问题，因此归类为LLM应用。` `版权保护` `人工智能`

> DIS-CO: Discovering Copyrighted Content in VLMs Training Data

# 摘要

> 如何在不直接访问大型视觉语言模型 (VLM) 的训练数据的情况下验证是否使用了受版权保护的内容进行训练？受 VLM 能够识别其训练语料库中图像的启发，我们提出了 DIS-CO，这是一种推断模型开发过程中是否包含受版权保护内容的新方法。通过使用特定帧反复查询 VLM，DIS-CO 通过自由文本补全提取内容身份。为了评估其有效性，我们引入了 MovieTection，一个包含 14,000 个帧及其详细描述的基准数据集，这些帧来自模型训练截止日期前和之后发布的电影。我们的结果显示，DIS-CO 显著提高了检测性能，在有 logits 可用的模型上，平均 AUC 几乎是最佳先前方法的两倍。我们的发现还强调了一个更广泛的问题：所有测试模型似乎在某种程度上都接触过受版权保护的内容。我们的代码和数据可在 https://github.com/avduarte333/DIS-CO 获取

> How can we verify whether copyrighted content was used to train a large vision-language model (VLM) without direct access to its training data? Motivated by the hypothesis that a VLM is able to recognize images from its training corpus, we propose DIS-CO, a novel approach to infer the inclusion of copyrighted content during the model's development. By repeatedly querying a VLM with specific frames from targeted copyrighted material, DIS-CO extracts the content's identity through free-form text completions. To assess its effectiveness, we introduce MovieTection, a benchmark comprising 14,000 frames paired with detailed captions, drawn from films released both before and after a model's training cutoff. Our results show that DIS-CO significantly improves detection performance, nearly doubling the average AUC of the best prior method on models with logits available. Our findings also highlight a broader concern: all tested models appear to have been exposed to some extent to copyrighted content. Our code and data are available at https://github.com/avduarte333/DIS-CO

[Arxiv](https://arxiv.org/abs/2502.17358)