# Prompt4Trust：面向多模态大语言模型的临床对齐信心校准强化学习提示增强框架

发布时间：2025年07月12日

`LLM应用

论文摘要：# 多模态大型语言模型在医疗领域的信任构建

多模态大型语言模型（MLLMs）在医疗领域的应用前景广阔，但其在安全关键环境中的实际部署面临两大挑战：(i) 对提示设计的高度敏感性，以及 (ii) 易于生成高置信度的错误回答。鉴于临床医生往往依赖模型的置信度来评估预测的可靠性，因此当模型表现出高度自信时，其准确性尤为重要。

我们提出了一种创新的解决方案——Prompt4Trust，这是首个专为MLLMs置信度校准设计的强化学习（RL）框架，专注于通过提示增强提升模型的可靠性。通过训练一个轻量级LLM生成具有上下文感知能力的辅助提示，引导下游任务的MLLM生成置信度更准确反映预测准确性的响应。

与传统的校准技术不同，Prompt4Trust特别关注对安全和可信临床决策至关重要的校准方面。除了由这种以临床为导向的校准目标驱动的改进外，我们的方法还显著提升了任务准确性，在由多种医学成像模态组成的多选题PMC-VQA基准测试中，达到了医学视觉问答（VQA）的最先进性能。

此外，我们在实验中发现，使用小型下游任务MLLM训练的框架，在更大规模的MLLM上也展示了有前景的零样本泛化能力，这表明了在不增加计算成本的情况下实现可扩展校准的潜力。

这项工作展示了自动化且符合人类认知的提示工程在提升MLLMs在安全关键环境中的可信度方面的巨大潜力。我们的代码库可在以下链接找到：https://github.com/xingbpshen/vccrl-llm。

LLM应用`

> Prompt4Trust: A Reinforcement Learning Prompt Augmentation Framework for Clinically-Aligned Confidence Calibration in Multimodal Large Language Models

# 摘要

> # 多模态大型语言模型在医疗领域的信任构建

多模态大型语言模型（MLLMs）在医疗领域的应用前景广阔，但其在安全关键环境中的实际部署面临两大挑战：(i) 对提示设计的高度敏感性，以及 (ii) 易于生成高置信度的错误回答。鉴于临床医生往往依赖模型的置信度来评估预测的可靠性，因此当模型表现出高度自信时，其准确性尤为重要。

我们提出了一种创新的解决方案——Prompt4Trust，这是首个专为MLLMs置信度校准设计的强化学习（RL）框架，专注于通过提示增强提升模型的可靠性。通过训练一个轻量级LLM生成具有上下文感知能力的辅助提示，引导下游任务的MLLM生成置信度更准确反映预测准确性的响应。

与传统的校准技术不同，Prompt4Trust特别关注对安全和可信临床决策至关重要的校准方面。除了由这种以临床为导向的校准目标驱动的改进外，我们的方法还显著提升了任务准确性，在由多种医学成像模态组成的多选题PMC-VQA基准测试中，达到了医学视觉问答（VQA）的最先进性能。

此外，我们在实验中发现，使用小型下游任务MLLM训练的框架，在更大规模的MLLM上也展示了有前景的零样本泛化能力，这表明了在不增加计算成本的情况下实现可扩展校准的潜力。

这项工作展示了自动化且符合人类认知的提示工程在提升MLLMs在安全关键环境中的可信度方面的巨大潜力。我们的代码库可在以下链接找到：https://github.com/xingbpshen/vccrl-llm。


> Multimodal large language models (MLLMs) hold considerable promise for applications in healthcare. However, their deployment in safety-critical settings is hindered by two key limitations: (i) sensitivity to prompt design, and (ii) a tendency to generate incorrect responses with high confidence. As clinicians may rely on a model's stated confidence to gauge the reliability of its predictions, it is especially important that when a model expresses high confidence, it is also highly accurate. We introduce Prompt4Trust, the first reinforcement learning (RL) framework for prompt augmentation targeting confidence calibration in MLLMs. A lightweight LLM is trained to produce context-aware auxiliary prompts that guide a downstream task MLLM to generate responses in which the expressed confidence more accurately reflects predictive accuracy. Unlike conventional calibration techniques, Prompt4Trust specifically prioritizes aspects of calibration most critical for safe and trustworthy clinical decision-making. Beyond improvements driven by this clinically motivated calibration objective, our proposed method also improves task accuracy, achieving state-of-the-art medical visual question answering (VQA) performance on the PMC-VQA benchmark, which is composed of multiple-choice questions spanning diverse medical imaging modalities. Moreover, our framework trained with a small downstream task MLLM showed promising zero-shot generalization to larger MLLMs in our experiments, suggesting the potential for scalable calibration without the associated computational costs. This work demonstrates the potential of automated yet human-aligned prompt engineering for improving the the trustworthiness of MLLMs in safety critical settings. Our codebase can be found at https://github.com/xingbpshen/vccrl-llm.

[Arxiv](https://arxiv.org/abs/2507.09279)