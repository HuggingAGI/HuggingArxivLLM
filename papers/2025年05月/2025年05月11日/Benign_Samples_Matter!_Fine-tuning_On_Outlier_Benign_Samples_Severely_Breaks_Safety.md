# 良性样本很重要！在异常良性样本上进行微调会严重破坏模型的安全性。

发布时间：2025年05月11日

`LLM理论` `人工智能安全` `模型安全`

> Benign Samples Matter! Fine-tuning On Outlier Benign Samples Severely Breaks Safety

# 摘要

> 最近的研究发现，大型语言模型（LLMs）在微调阶段存在一个令人不安的漏洞：即便是在完全无害的数据集上进行微调，也可能大幅增加模型输出的有害性。基于这一发现，我们的红队研究更进一步，开发出一种更有效的攻击方法。具体来说，我们分析并识别出那些对模型安全性下降贡献最大的良性数据集样本，然后仅在这些样本上对LLMs进行微调。我们从异常检测的角度来解决这个问题，提出了Self-Inf-N方法，用于检测和提取异常样本进行微调。我们的研究发现，仅在良性数据集中通过Self-Inf-N选择的100个异常样本上微调LLMs，就会严重损害模型的安全对齐。在七种主流LLMs上的大量实验表明，我们的攻击方法在不同架构间具有高度的迁移性，并在实际场景中仍然有效。令人震惊的是，我们的结果显示，大多数现有的缓解策略都无法防御这种攻击，这突显了开发更强大的对齐防护措施的紧迫性。代码可在https://github.com/GuanZihan/Benign-Samples-Matter获取。

> Recent studies have uncovered a troubling vulnerability in the fine-tuning stage of large language models (LLMs): even fine-tuning on entirely benign datasets can lead to a significant increase in the harmfulness of LLM outputs. Building on this finding, our red teaming study takes this threat one step further by developing a more effective attack. Specifically, we analyze and identify samples within benign datasets that contribute most to safety degradation, then fine-tune LLMs exclusively on these samples. We approach this problem from an outlier detection perspective and propose Self-Inf-N, to detect and extract outliers for fine-tuning. Our findings reveal that fine-tuning LLMs on 100 outlier samples selected by Self-Inf-N in the benign datasets severely compromises LLM safety alignment. Extensive experiments across seven mainstream LLMs demonstrate that our attack exhibits high transferability across different architectures and remains effective in practical scenarios. Alarmingly, our results indicate that most existing mitigation strategies fail to defend against this attack, underscoring the urgent need for more robust alignment safeguards. Codes are available at https://github.com/GuanZihan/Benign-Samples-Matter.

[Arxiv](https://arxiv.org/abs/2505.06843)