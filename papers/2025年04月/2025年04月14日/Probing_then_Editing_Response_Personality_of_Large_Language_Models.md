# 探究并编辑大型语言模型的响应人格

发布时间：2025年04月14日

`LLM理论` `人工智能`

> Probing then Editing Response Personality of Large Language Models

# 摘要

> 大型语言模型（LLMs）在生成具有连贯个性特征的响应方面表现优异，但关于个性特征如何在模型参数中编码仍是一个未解之谜。本研究提出了一种分层探查框架，系统性地揭示了LLMs在响应生成中对个性的分层编码机制。通过在11个开源LLMs上进行的PersonalityEdit基准实验，我们发现个性特征主要编码于模型的中高层，且指令微调模型在个性分离上表现更佳。进一步地，我们通过探查超平面的边界解释，提出了一种分层扰动方法，实现对LLMs推理过程中个性表达的编辑。实验表明，即使提示明确指定个性，我们的方法仍能有效改变模型的响应个性。个性特征间的转换难度差异显著，这一现象与探查实验中的表示距离相吻合。最后，我们的MMLU基准评估和时间分析表明，该个性编辑方法在保持较低训练成本和合理推理延迟的同时，对模型一般能力的影响微乎其微。代码已开源，地址为https://github.com/universe-sky/probing-then-editing-personality。

> Large Language Models (LLMs) have demonstrated promising capabilities to generate responses that exhibit consistent personality traits. Despite the major attempts to analyze personality expression through output-based evaluations, little is known about how such traits are internally encoded within LLM parameters. In this paper, we introduce a layer-wise probing framework to systematically investigate the layer-wise capability of LLMs in encoding personality for responding. We conduct probing experiments on 11 open-source LLMs over the PersonalityEdit benchmark and find that LLMs predominantly encode personality for responding in their middle and upper layers, with instruction-tuned models demonstrating a slightly clearer separation of personality traits. Furthermore, by interpreting the trained probing hyperplane as a layer-wise boundary for each personality category, we propose a layer-wise perturbation method to edit the personality expressed by LLMs during inference. Our results show that even when the prompt explicitly specifies a particular personality, our method can still successfully alter the response personality of LLMs. Interestingly, the difficulty of converting between certain personality traits varies substantially, which aligns with the representational distances in our probing experiments. Finally, we conduct a comprehensive MMLU benchmark evaluation and time overhead analysis, demonstrating that our proposed personality editing method incurs only minimal degradation in general capabilities while maintaining low training costs and acceptable inference latency. Our code is publicly available at https://github.com/universe-sky/probing-then-editing-personality.

[Arxiv](https://arxiv.org/abs/2504.10227)