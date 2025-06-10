# # SWE-Dev：打造软件工程代理，实现训练与推理的高效扩展

发布时间：2025年06月09日

`Agent` `软件工程`

> SWE-Dev: Building Software Engineering Agents with Training and Inference Scaling

# 摘要

> 大型语言模型（LLMs）在从对话式问题解决到涉及工具使用的实际任务方面取得了迅速进展，例如软件工程（SWE）。近期由LLM驱动的工具包，如OpenAI Codex和Cursor，提供了软件开发过程的端到端自动化。然而，构建有效的SWE代理仍面临挑战，主要是由于高质量训练数据和有效测试用例的匮乏。为了解决这一问题，我们提出了SWE-Dev，一个基于开源LLMs构建的SWE代理。首先，我们开发了一个强大的管道来合成测试用例以进行补丁评估。其次，我们扩展了代理轨迹来构建训练数据，用于构建SWE-Dev。在SWE-bench-Verified基准上的实验表明，SWE-Dev模型在所有开源SWE代理中表现出色。具体来说，SWE-Dev 7B和32B参数模型的成功率分别达到了23.4%和36.6%，超越了现有的开源模型。所有代码、模型和数据集均可在https://github.com/THUDM/SWE-Dev公开获取。

> Large language models (LLMs) have advanced rapidly from conversational problem solving to addressing real-world tasks involving tool use, such as software engineering (SWE). Recent LLM-powered toolkits, such as OpenAI Codex and Cursor, have offered end-to-end automation of the software development process. However, building effective SWE agents remains challenging due to the lack of high-quality training data and effective test cases. To address this issue, we present SWE-Dev, an SWE agent built upon open-source LLMs. First, we develop a robust pipeline to synthesize test cases for patch evaluation. Second, we scale up agent trajectories to construct the training data for building SWE-Dev. Experiments on the SWE-bench-Verified benchmark show that the SWE-Dev models can achieve top performance among all open SWE agents. Specifically, the success rates of the SWE-Dev 7B and 32B parameter models reach 23.4% and 36.6%, respectively, outperforming state-of-the-art open-source models. All code, models, and datasets are publicly available at https://github.com/THUDM/SWE-Dev.

[Arxiv](https://arxiv.org/abs/2506.07636)