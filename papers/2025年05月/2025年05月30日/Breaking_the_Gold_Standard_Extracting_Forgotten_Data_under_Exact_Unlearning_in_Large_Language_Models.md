# 打破金标准：在大型语言模型中，通过精确遗忘揭示被遗忘的数据

发布时间：2025年05月30日

`LLM应用`

> Breaking the Gold Standard: Extracting Forgotten Data under Exact Unlearning in Large Language Models

# 摘要

> 大型语言模型通常基于从互联网收集的数据集进行训练，这些数据集可能无意中包含有害或敏感的个人信息。为应对日益增长的隐私担忧，人们提出了数据删除方法，旨在从训练好的模型中移除特定数据的影响。其中，精确删除——即从零开始重新训练模型，排除目标数据——被广泛认为是黄金标准，被认为能有效抵御隐私相关攻击。然而，我们提出了一种新型数据提取攻击，即使是精确删除，也无法幸免。

我们的方法巧妙结合了删除前后的模型：通过利用删除前模型的信号引导删除后模型，我们揭示出反映被移除数据分布的模式。结合模型引导与令牌过滤策略，我们的攻击显著提高了提取成功率，在某些情况下使性能翻倍，且在MUSE、TOFU和WMDP等常见基准测试中表现优异。此外，我们在模拟的医疗诊断数据集上验证了攻击的有效性，突显了精确删除在现实世界中可能带来的隐私风险。

鉴于我们的研究发现——即删除方法可能以一种矛盾的方式增加隐私泄露的风险——我们主张在评估删除方法时，应考虑更广泛的威胁模型，不仅要关注删除后的模型，还要防范对手对先前检查点的恶意访问。

> Large language models are typically trained on datasets collected from the web, which may inadvertently contain harmful or sensitive personal information. To address growing privacy concerns, unlearning methods have been proposed to remove the influence of specific data from trained models. Of these, exact unlearning -- which retrains the model from scratch without the target data -- is widely regarded the gold standard, believed to be robust against privacy-related attacks. In this paper, we challenge this assumption by introducing a novel data extraction attack that compromises even exact unlearning. Our method leverages both the pre- and post-unlearning models: by guiding the post-unlearning model using signals from the pre-unlearning model, we uncover patterns that reflect the removed data distribution. Combining model guidance with a token filtering strategy, our attack significantly improves extraction success rates -- doubling performance in some cases -- across common benchmarks such as MUSE, TOFU, and WMDP. Furthermore, we demonstrate our attack's effectiveness on a simulated medical diagnosis dataset to highlight real-world privacy risks associated with exact unlearning. In light of our findings, which suggest that unlearning may, in a contradictory way, increase the risk of privacy leakage, we advocate for evaluation of unlearning methods to consider broader threat models that account not only for post-unlearning models but also for adversarial access to prior checkpoints.

[Arxiv](https://arxiv.org/abs/2505.24379)