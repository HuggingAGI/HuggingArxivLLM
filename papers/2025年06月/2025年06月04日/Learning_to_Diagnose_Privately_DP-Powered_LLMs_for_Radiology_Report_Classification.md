# 学习隐私诊断：差分隐私驱动的LLMs在放射科报告分类中的应用

发布时间：2025年06月04日

`LLM应用` `隐私保护`

> Learning to Diagnose Privately: DP-Powered LLMs for Radiology Report Classification

# 摘要

> # 摘要  
本研究提出了一种基于差分隐私（DP）微调大型语言模型（LLMs）以对放射报告文本进行多异常分类的框架。通过在微调过程中注入经过校准的噪声，该框架旨在缓解与敏感患者数据相关的隐私风险，防止数据泄露，同时保持分类性能。  
我们使用了来自公开的MIMIC-CXR胸部放射和CT-RATE计算机断层扫描数据集的50,232份放射报告，这些数据是在2011年至2019年间收集的。采用差分隐私低秩适应（DP-LoRA）在高隐私和中等隐私模式下对LLMs进行微调，用于对MIMIC-CXR数据集的14个标签和CT-RATE数据集的18个标签进行分类（隐私预算范围为{0.01, 0.1, 1.0, 10.0}）。  
模型性能通过三种模型架构（BERT-medium、BERT-small 和 ALBERT-base）的加权F1分数进行评估。统计分析比较了不同隐私级别下的模型性能，以量化隐私-效用权衡。  
通过在两个不同数据集和三种不同模型上的实验，我们观察到了清晰的隐私-效用权衡。在中等隐私保证下，DP微调模型在MIMIC-CXR数据集上实现了0.88的加权F1分数，在CT-RATE数据集上实现了0.59的加权F1分数，分别与非隐私LoRA基线的0.90和0.78相比。  
本研究结果表明，使用LoRA进行差分隐私微调能够实现有效的隐私保护多异常分类，解决了在敏感医学数据上微调LLMs的关键挑战。

> Purpose: This study proposes a framework for fine-tuning large language models (LLMs) with differential privacy (DP) to perform multi-abnormality classification on radiology report text. By injecting calibrated noise during fine-tuning, the framework seeks to mitigate the privacy risks associated with sensitive patient data and protect against data leakage while maintaining classification performance. Materials and Methods: We used 50,232 radiology reports from the publicly available MIMIC-CXR chest radiography and CT-RATE computed tomography datasets, collected between 2011 and 2019. Fine-tuning of LLMs was conducted to classify 14 labels from MIMIC-CXR dataset, and 18 labels from CT-RATE dataset using Differentially Private Low-Rank Adaptation (DP-LoRA) in high and moderate privacy regimes (across a range of privacy budgets = {0.01, 0.1, 1.0, 10.0}). Model performance was evaluated using weighted F1 score across three model architectures: BERT-medium, BERT-small, and ALBERT-base. Statistical analyses compared model performance across different privacy levels to quantify the privacy-utility trade-off. Results: We observe a clear privacy-utility trade-off through our experiments on 2 different datasets and 3 different models. Under moderate privacy guarantees the DP fine-tuned models achieved comparable weighted F1 scores of 0.88 on MIMIC-CXR and 0.59 on CT-RATE, compared to non-private LoRA baselines of 0.90 and 0.78, respectively. Conclusion: Differentially private fine-tuning using LoRA enables effective and privacy-preserving multi-abnormality classification from radiology reports, addressing a key challenge in fine-tuning LLMs on sensitive medical data.

[Arxiv](https://arxiv.org/abs/2506.04450)