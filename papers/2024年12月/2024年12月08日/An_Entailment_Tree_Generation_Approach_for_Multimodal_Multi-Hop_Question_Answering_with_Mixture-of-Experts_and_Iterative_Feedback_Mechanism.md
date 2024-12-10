# 一种具备专家混合与迭代反馈机制的多模态多跳问答蕴含树生成方法

发布时间：2024年12月08日

`LLM应用` `问答系统` `多模态`

> An Entailment Tree Generation Approach for Multimodal Multi-Hop Question Answering with Mixture-of-Experts and Iterative Feedback Mechanism

# 摘要

> 随着大规模语言模型（LLMs）的兴起，将多模态信息转化为文本描述用于多模态多跳问答，当下既流行又有效。不过，我们觉得当前的多模态多跳问答方法主要面临两大挑战：其一，检索到的证据含有大量冗余信息，因不相关信息误导预测，必然致使性能大幅下降。其二，推理过程缺乏可解释的推理步骤，导致模型难以察觉处理复杂问题时的逻辑错误。为解决这些难题，我们提出了一种基于LLMs的统一方法，但鉴于LLM存在潜在错误，所以并非重度依赖它们，还创新性地把多模态多跳问答视作联合蕴含树生成与问答问题。具体来说，我们设计了一个多任务学习框架，着重促进解释性和预测任务之间的常见知识共享，同时借助专家混合避免特定任务的错误相互干扰。随后，我们设计了一个迭代反馈机制，把联合训练的结果反馈给LLM以重新生成蕴含树，旨在逐步优化潜在答案。值得一提的是，我们的方法在WebQA的官方排行榜（自2024年4月10日起）中拔得头筹，并在MultimodalQA上取得了颇具竞争力的成绩。

> With the rise of large-scale language models (LLMs), it is currently popular and effective to convert multimodal information into text descriptions for multimodal multi-hop question answering. However, we argue that the current methods of multi-modal multi-hop question answering still mainly face two challenges: 1) The retrieved evidence containing a large amount of redundant information, inevitably leads to a significant drop in performance due to irrelevant information misleading the prediction. 2) The reasoning process without interpretable reasoning steps makes the model difficult to discover the logical errors for handling complex questions. To solve these problems, we propose a unified LLMs-based approach but without heavily relying on them due to the LLM's potential errors, and innovatively treat multimodal multi-hop question answering as a joint entailment tree generation and question answering problem. Specifically, we design a multi-task learning framework with a focus on facilitating common knowledge sharing across interpretability and prediction tasks while preventing task-specific errors from interfering with each other via mixture of experts. Afterward, we design an iterative feedback mechanism to further enhance both tasks by feeding back the results of the joint training to the LLM for regenerating entailment trees, aiming to iteratively refine the potential answer. Notably, our method has won the first place in the official leaderboard of WebQA (since April 10, 2024), and achieves competitive results on MultimodalQA.

[Arxiv](https://arxiv.org/abs/2412.05821)