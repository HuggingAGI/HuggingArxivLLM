# # 不止于表面：深挖大语言模型的意识形态深度

发布时间：2025年08月29日

`LLM理论` `基础理论`

> Beyond the Surface: Probing the Ideological Depth of Large Language Models

# 摘要

> 大型语言模型（LLMs）已表现出显著的意识形态倾向，但其立场的稳定性与深度却仍不为人所了解。表层回应常可通过简单的提示词设计被操控，这不禁让人怀疑它们是否真正反映了连贯的内在意识形态。本文提出并研究LLMs中的“意识形态深度”概念，将其定义为模型内部政治表征的稳健性与复杂性。我们采用双重研究方法：其一，通过指令提示与激活引导，测量两款知名开源LLM的“可引导性”。研究发现，部分模型可轻松在自由派与保守派观点间切换，而另一些模型则表现出抵触或拒绝率升高的现象，这说明它们的意识形态结构更为根深蒂固。其二，借助稀疏自编码器（SAEs）探究这些模型的内部机制。初步分析表明，可引导性较低的模型具备更独特、更抽象的意识形态特征。评估发现，一款模型的政治特征数量比另一相似规模模型多7.3倍。这一发现使得我们能在意识形态“深”模型中定向消融某一核心政治特征，进而使其在相关话题的推理上产生一致且符合逻辑的转变；而对“浅”模型进行相同干预时，结果却是拒绝输出增多。综上，我们的研究表明：意识形态深度是LLMs的可量化属性，而可引导性则为洞察其潜在政治架构提供了重要窗口。

> Large Language Models (LLMs) have demonstrated pronounced ideological leanings, yet the stability and depth of these positions remain poorly understood. Surface-level responses can often be manipulated through simple prompt engineering, calling into question whether they reflect a coherent underlying ideology. This paper investigates the concept of "ideological depth" in LLMs, defined as the robustness and complexity of their internal political representations. We employ a dual approach: first, we measure the "steerability" of two well-known open-source LLMs using instruction prompting and activation steering. We find that while some models can easily switch between liberal and conservative viewpoints, others exhibit resistance or an increased rate of refusal, suggesting a more entrenched ideological structure. Second, we probe the internal mechanisms of these models using Sparse Autoencoders (SAEs). Preliminary analysis reveals that models with lower steerability possess more distinct and abstract ideological features. Our evaluations reveal that one model can contain 7.3x more political features than another model of similar size. This allows targeted ablation of a core political feature in an ideologically "deep" model, leading to consistent, logical shifts in its reasoning across related topics, whereas the same intervention in a "shallow" model results in an increase in refusal outputs. Our findings suggest that ideological depth is a quantifiable property of LLMs and that steerability serves as a valuable window into their latent political architecture.

[Arxiv](https://arxiv.org/abs/2508.21448)