# # Primus：网络安全领域首个先驱性开源数据集系列，专为 LLM 训练打造

发布时间：2025年02月16日

`LLM应用` `网络安全` `数据集`

> Primus: A Pioneering Collection of Open-Source Datasets for Cybersecurity LLM Training

# 摘要

> 大型语言模型（LLMs）在金融、法律和医学等领域取得了显著进展，但在网络安全领域，开源数据集的匮乏问题尤为突出，尤其是高质量的网络安全预训练语料库。尽管研究表明LLMs的知识主要在预训练阶段获取，这一问题仍未得到充分解决。为此，我们推出了一套全面的数据集，涵盖预训练、指令微调以及带有网络安全特定自我反思数据的推理蒸馏等主要训练阶段。通过广泛的消融研究，我们证明了这些数据集在公共网络安全基准上的有效性。具体而言，持续预训练使综合得分提升了15.88%，推理蒸馏则在安全认证（CISSP）方面带来了10%的提升。我们计划将所有数据集和经过训练的网络安全LLMs在ODC-BY和MIT许可证下公开发布，以推动社区进一步研究。如需获取所有数据集和模型权重，请访问https://huggingface.co/collections/trendmicro-ailab/primus-67b1fd27052b802b4af9d243。

> Large Language Models (LLMs) have shown remarkable advancements in specialized fields such as finance, law, and medicine. However, in cybersecurity, we have noticed a lack of open-source datasets, with a particular lack of high-quality cybersecurity pretraining corpora, even though much research indicates that LLMs acquire their knowledge during pretraining. To address this, we present a comprehensive suite of datasets covering all major training stages, including pretraining, instruction fine-tuning, and reasoning distillation with cybersecurity-specific self-reflection data. Extensive ablation studies demonstrate their effectiveness on public cybersecurity benchmarks. In particular, continual pre-training on our dataset yields a 15.88% improvement in the aggregate score, while reasoning distillation leads to a 10% gain in security certification (CISSP). We will release all datasets and trained cybersecurity LLMs under the ODC-BY and MIT licenses to encourage further research in the community. For access to all datasets and model weights, please refer to https://huggingface.co/collections/trendmicro-ailab/primus-67b1fd27052b802b4af9d243.

[Arxiv](https://arxiv.org/abs/2502.11191)