# 从个性化与主动性视角，评估工具增强型LLM

发布时间：2025年03月02日

`LLM应用

论文摘要：在多种工具交互场景中，个性化工具的使用对于使大型语言模型（LLMs）与用户偏好保持一致至关重要。然而，现有大多数基准测试主要关注文本生成的个性化或直接工具使用，而未兼顾两者。在本研究中，我们引入了全新的基准测试ETAPP，用于评估个性化的工具调用。ETAPP包含一个沙盒环境和一个涵盖800个测试案例的综合性数据集，覆盖了多样化的用户配置文件。为提高评估准确性，我们提出了一种基于关键点的LLM评估方法。通过手动标注每个测试案例的关键点并将其提供给LLM作为参考，我们缓解了LLM作为评判系统中的偏见问题。此外，我们对优秀LLMs进行了评估，并提供了深入分析。进一步地，我们探讨了不同工具调用策略对LLMs个性化性能的影响，以及微调在我们任务中的效果。我们的偏好设置和基于关键点的评估方法的有效性也得到了验证。这些研究结果为提升个性化LLM代理提供了有价值的见解。我们的代码可在https://github.com/hypasd-art/ETAPP获取。` `个性化服务` `智能代理`

> Evaluating Personalized Tool-Augmented LLMs from the Perspectives of Personalization and Proactivity

# 摘要

> 在多种工具交互场景中，个性化工具的使用对于使大型语言模型（LLMs）与用户偏好保持一致至关重要。然而，现有大多数基准测试主要关注文本生成的个性化或直接工具使用，而未兼顾两者。在本研究中，我们引入了全新的基准测试ETAPP，用于评估个性化的工具调用。ETAPP包含一个沙盒环境和一个涵盖800个测试案例的综合性数据集，覆盖了多样化的用户配置文件。为提高评估准确性，我们提出了一种基于关键点的LLM评估方法。通过手动标注每个测试案例的关键点并将其提供给LLM作为参考，我们缓解了LLM作为评判系统中的偏见问题。此外，我们对优秀LLMs进行了评估，并提供了深入分析。进一步地，我们探讨了不同工具调用策略对LLMs个性化性能的影响，以及微调在我们任务中的效果。我们的偏好设置和基于关键点的评估方法的有效性也得到了验证。这些研究结果为提升个性化LLM代理提供了有价值的见解。我们的代码可在https://github.com/hypasd-art/ETAPP获取。

> Personalized tool utilization is essential for aligning large language models (LLMs) with user preference in interaction scenarios with various tools. However, most of the current benchmarks primarily focus on either personalization of text generation or direct tool-utilizing, without considering both. In this work, we introduce a novel benchmark ETAPP for evaluating personalized tool invocation, establishing a sandbox environment, and a comprehensive dataset of 800 testing cases covering diverse user profiles. To improve the accuracy of our evaluation, we propose a key-point-based LLM evaluation method, mitigating biases in the LLM-as-a-judge system by manually annotating key points for each test case and providing them to LLM as the reference. Additionally, we evaluate the excellent LLMs and provide an in-depth analysis. Furthermore, we investigate the impact of different tool-invoking strategies on LLMs' personalization performance and the effects of fine-tuning in our task. The effectiveness of our preference-setting and key-point-based evaluation method is also validated. Our findings offer insights into improving personalized LLM agents. Our Code is available at https://github.com/hypasd-art/ETAPP.

[Arxiv](https://arxiv.org/abs/2503.00771)