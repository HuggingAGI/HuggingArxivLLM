# 一种基于伦理的大型语言模型（LLM）内部威胁合成与检测方法

发布时间：2025年09月08日

`LLM应用` `基础理论`

> An Ethically Grounded LLM-Based Approach to Insider Threat Synthesis and Detection

# 摘要

> 内部威胁因其技术与行为特征识别的复杂性，正成为组织面临的一大难题。学术界已从技术、心理和教育等多维度对内部威胁展开深入研究，但该领域研究普遍依赖静态且访问受限的数据集，这制约了自适应检测模型的研发。为此，本研究提出一种新颖的伦理驱动方法，利用大型语言模型（LLM）Claude Sonnet 3.7动态合成系统日志消息，部分消息中隐含内部威胁场景的指标。这些消息呈现高度不平衡的特点（内部威胁仅占1%），从而真实模拟了现实世界的数据分布。研究团队分别采用Claude Sonnet 3.7与GPT-4o对系统日志进行内部威胁分析，并通过精确率、召回率、MCC及ROC AUC等统计指标评估两者性能。结果显示，Sonnet 3.7在几乎所有指标上均显著优于GPT-4o，尤其在降低误报率和提升检测精度方面表现突出。这一成果充分证明，LLMs在合成数据集生成与内部威胁检测领域极具应用前景。

> Insider threats are a growing organizational problem due to the complexity of identifying their technical and behavioral elements. A large research body is dedicated to the study of insider threats from technological, psychological, and educational perspectives. However, research in this domain has been generally dependent on datasets that are static and limited access which restricts the development of adaptive detection models. This study introduces a novel, ethically grounded approach that uses the large language model (LLM) Claude Sonnet 3.7 to dynamically synthesize syslog messages, some of which contain indicators of insider threat scenarios. The messages reflect real-world data distributions by being highly imbalanced (1% insider threats). The syslogs were analyzed for insider threats by both Claude Sonnet 3.7 and GPT-4o, with their performance evaluated through statistical metrics including precision, recall, MCC, and ROC AUC. Sonnet 3.7 consistently outperformed GPT-4o across nearly all metrics, particularly in reducing false alarms and improving detection accuracy. The results show strong promise for the use of LLMs in synthetic dataset generation and insider threat detection.

[Arxiv](https://arxiv.org/abs/2509.06920)