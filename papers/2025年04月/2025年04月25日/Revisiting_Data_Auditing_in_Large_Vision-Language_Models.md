# 再探大规模视觉-语言模型中的数据审计

发布时间：2025年04月25日

`其他` `视觉语言模型` `数据审计`

> Revisiting Data Auditing in Large Vision-Language Models

# 摘要

> # 摘要
随着大型语言模型（LLMs）的迅猛发展，大型视觉语言模型（VLMs）在通用代理和机器人控制等任务中展现出巨大潜力。然而，VLMs通常基于网络抓取的海量图像进行训练，引发了版权和隐私方面的担忧，使得数据审计变得日益紧迫。成员推断（MI）作为一种关键的审计技术应运而生，并在开源VLMs如LLaVA中取得了令人鼓舞的成果（AUC > 80%）。在本研究中，我们重新审视了这些进展，并揭示了一个关键问题：当前MI基准测试因成员与非成员图像之间的分布偏移而引入了捷径提示，导致MI性能被夸大。我们进一步分析了这种偏移的本质，并提出了一种基于最优传输的度量方法，以量化分布差异。为了在现实场景中评估MI，我们构建了新的基准测试，其中成员与非成员图像遵循独立同分布。现有MI方法在这些无偏条件下表现欠佳，仅略优于随机猜测。此外，我们通过探查VLM嵌入空间中的贝叶斯最优性，探索了MI的理论上限，发现不可约误差率仍然较高。尽管前景不容乐观，我们分析了为何VLMs的MI尤为具有挑战性，并识别出三种可行的审计场景——微调、访问真实文本以及基于集合的推断——为数据审计提供了可行路径。本研究系统地揭示了MI在VLMs中的局限性与机遇，为未来可信数据审计的努力提供了指导。

> With the surge of large language models (LLMs), Large Vision-Language Models (VLMs)--which integrate vision encoders with LLMs for accurate visual grounding--have shown great potential in tasks like generalist agents and robotic control. However, VLMs are typically trained on massive web-scraped images, raising concerns over copyright infringement and privacy violations, and making data auditing increasingly urgent. Membership inference (MI), which determines whether a sample was used in training, has emerged as a key auditing technique, with promising results on open-source VLMs like LLaVA (AUC > 80%). In this work, we revisit these advances and uncover a critical issue: current MI benchmarks suffer from distribution shifts between member and non-member images, introducing shortcut cues that inflate MI performance. We further analyze the nature of these shifts and propose a principled metric based on optimal transport to quantify the distribution discrepancy. To evaluate MI in realistic settings, we construct new benchmarks with i.i.d. member and non-member images. Existing MI methods fail under these unbiased conditions, performing only marginally better than chance. Further, we explore the theoretical upper bound of MI by probing the Bayes Optimality within the VLM's embedding space and find the irreducible error rate remains high. Despite this pessimistic outlook, we analyze why MI for VLMs is particularly challenging and identify three practical scenarios--fine-tuning, access to ground-truth texts, and set-based inference--where auditing becomes feasible. Our study presents a systematic view of the limits and opportunities of MI for VLMs, providing guidance for future efforts in trustworthy data auditing.

[Arxiv](https://arxiv.org/abs/2504.18349)