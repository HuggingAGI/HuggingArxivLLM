# 结合LLM辅助判断的网络对话欺诈与概念漂移联合检测

发布时间：2025年05月07日

`LLM应用` `网络安全`

> Joint Detection of Fraud and Concept Drift inOnline Conversations with LLM-Assisted Judgment

# 摘要

> 在数字通信平台上检测虚假互动仍然是一个极具挑战性且尚未完全解决的问题。这些互动可能看似普通的垃圾信息，也可能逐步升级为复杂的诈骗行为，使得早期识别恶意意图变得困难。传统的检测方法通常依赖于静态异常检测技术，难以适应对话中的动态变化。一个主要问题是将良性的主题转换误判为欺诈行为（即概念漂移），这会导致误报或漏报威胁。我们提出了一种两阶段检测框架，首先通过定制的集成分类模型识别可疑对话。为了提高检测的可靠性，我们引入了基于单类漂移检测器（OCDD）的概念漂移分析步骤，专门用于分析标记对话中的对话转变。当检测到漂移时，大型语言模型（LLM）会评估这种转变是欺诈操控还是合法的主题变更。如果未检测到漂移，则推断行为属于垃圾信息。我们通过社交工程聊天场景的数据集验证了框架的有效性，并展示了其在提高实时欺诈检测准确性和可解释性方面的优势。为了比较不同方法的优劣，我们将模块化框架与一种双LLM基线进行了对比，后者使用不同的语言模型分别执行检测和判断任务。

> Detecting fake interactions in digital communication platforms remains a challenging and insufficiently addressed problem. These interactions may appear as harmless spam or escalate into sophisticated scam attempts, making it difficult to flag malicious intent early. Traditional detection methods often rely on static anomaly detection techniques that fail to adapt to dynamic conversational shifts. One key limitation is the misinterpretation of benign topic transitions referred to as concept drift as fraudulent behavior, leading to either false alarms or missed threats. We propose a two stage detection framework that first identifies suspicious conversations using a tailored ensemble classification model. To improve the reliability of detection, we incorporate a concept drift analysis step using a One Class Drift Detector (OCDD) to isolate conversational shifts within flagged dialogues. When drift is detected, a large language model (LLM) assesses whether the shift indicates fraudulent manipulation or a legitimate topic change. In cases where no drift is found, the behavior is inferred to be spam like. We validate our framework using a dataset of social engineering chat scenarios and demonstrate its practical advantages in improving both accuracy and interpretability for real time fraud detection. To contextualize the trade offs, we compare our modular approach against a Dual LLM baseline that performs detection and judgment using different language models.

[Arxiv](https://arxiv.org/abs/2505.07852)