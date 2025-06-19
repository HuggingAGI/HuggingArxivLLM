# # 揭开数据集后验推断的合成数据方法
利用合成数据，我们成功解锁了对数据集的后验推断能力。

发布时间：2025年06月18日

`LLM应用` `数据使用` `版权保护`

> Unlocking Post-hoc Dataset Inference with Synthetic Data

# 摘要

> 大型语言模型（LLMs）的强大能力主要源于其庞大的训练数据集，这些数据集通常未经数据所有者授权抓取。数据集推理（DI）提供了一种解决方案，通过识别嫌疑数据集是否参与训练，使数据所有者能够验证数据的授权使用情况。然而，现有的DI方法需要一个与泄露数据集分布匹配的私有保留数据集，这在实践中难以获取，严重限制了DI的应用。本研究通过合成生成保留数据集来解决这一问题。我们的方法克服了两大挑战：首先，通过训练一个基于后缀补全任务的数据生成器，生成高质量且多样化的合成数据，准确反映原始数据分布；其次，通过后验校准，缩小真实数据与合成数据之间的差距。在多种文本数据集上的实验表明，使用我们的合成数据作为保留集，DI能够以高信心检测出原始训练集，同时保持低误报率。这不仅帮助版权持有者合法主张数据使用权益，也证明了我们的方法在实际诉讼中的可靠性。我们的代码可在GitHub上获取。

> The remarkable capabilities of Large Language Models (LLMs) can be mainly attributed to their massive training datasets, which are often scraped from the internet without respecting data owners' intellectual property rights. Dataset Inference (DI) offers a potential remedy by identifying whether a suspect dataset was used in training, thereby enabling data owners to verify unauthorized use. However, existing DI methods require a private set-known to be absent from training-that closely matches the compromised dataset's distribution. Such in-distribution, held-out data is rarely available in practice, severely limiting the applicability of DI. In this work, we address this challenge by synthetically generating the required held-out set. Our approach tackles two key obstacles: (1) creating high-quality, diverse synthetic data that accurately reflects the original distribution, which we achieve via a data generator trained on a carefully designed suffix-based completion task, and (2) bridging likelihood gaps between real and synthetic data, which is realized through post-hoc calibration. Extensive experiments on diverse text datasets show that using our generated data as a held-out set enables DI to detect the original training sets with high confidence, while maintaining a low false positive rate. This result empowers copyright owners to make legitimate claims on data usage and demonstrates our method's reliability for real-world litigations. Our code is available at https://github.com/sprintml/PostHocDatasetInference.

[Arxiv](https://arxiv.org/abs/2506.15271)