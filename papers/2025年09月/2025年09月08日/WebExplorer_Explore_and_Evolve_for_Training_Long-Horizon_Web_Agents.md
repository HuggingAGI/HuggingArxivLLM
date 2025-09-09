# WebExplorer：探索与演进——长程网络智能体的训练

发布时间：2025年09月08日

`Agent` `基础理论`

> WebExplorer: Explore and Evolve for Training Long-Horizon Web Agents

# 摘要

> 大型语言模型（LLMs）的应用范式正日益转向智能体，而网页浏览能力是从各类在线资源获取信息的核心。但现有开源网页智能体在复杂任务中要么信息检索能力有限，要么实现方式不够透明。本研究指出，核心瓶颈在于缺乏具有挑战性的信息检索数据。为突破这一限制，我们提出WebExplorer——一种结合模型探索与迭代式长-短查询演变的系统性数据生成方案。该方案能生成需多步推理和复杂网页导航的挑战性查询-答案对。基于这一高质量数据集，我们先通过监督微调、再经强化学习，成功研发出先进网页智能体WebExplorer-8B。该模型支持128K上下文长度与最多100次工具调用，可胜任长程问题求解。在多项信息检索基准测试中，WebExplorer-8B在同规模模型中性能领先：作为80亿参数模型，其经强化学习训练后平均可高效搜索16轮，在BrowseComp-en/zh上准确率超越WebSailor-72B，并在WebWalkerQA与FRAMES任务中，于参数规模上限1000亿的模型中表现最优。除信息检索任务外，该模型在HLE基准测试中也展现出优异的泛化能力，即便其训练数据仅为知识密集型问答数据。这些结果验证了我们的方法为构建长程网页智能体提供了切实可行的路径。

> The paradigm of Large Language Models (LLMs) has increasingly shifted toward agentic applications, where web browsing capabilities are fundamental for retrieving information from diverse online sources. However, existing open-source web agents either demonstrate limited information-seeking abilities on complex tasks or lack transparent implementations. In this work, we identify that the key challenge lies in the scarcity of challenging data for information seeking. To address this limitation, we introduce WebExplorer: a systematic data generation approach using model-based exploration and iterative, long-to-short query evolution. This method creates challenging query-answer pairs that require multi-step reasoning and complex web navigation. By leveraging our curated high-quality dataset, we successfully develop advanced web agent WebExplorer-8B through supervised fine-tuning followed by reinforcement learning. Our model supports 128K context length and up to 100 tool calling turns, enabling long-horizon problem solving. Across diverse information-seeking benchmarks, WebExplorer-8B achieves the state-of-the-art performance at its scale. Notably, as an 8B-sized model, WebExplorer-8B is able to effectively search over an average of 16 turns after RL training, achieving higher accuracy than WebSailor-72B on BrowseComp-en/zh and attaining the best performance among models up to 100B parameters on WebWalkerQA and FRAMES. Beyond these information-seeking tasks, our model also achieves strong generalization on the HLE benchmark even though it is only trained on knowledge-intensive QA data. These results highlight our approach as a practical path toward long-horizon web agents.

[Arxiv](https://arxiv.org/abs/2509.06501)