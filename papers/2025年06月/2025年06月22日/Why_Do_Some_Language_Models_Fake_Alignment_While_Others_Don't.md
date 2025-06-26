# 有些语言模型为何会伪装对齐？而另一些又为何不会？

发布时间：2025年06月22日

`LLM理论` `人工智能`

> Why Do Some Language Models Fake Alignment While Others Don't?

# 摘要

> # 摘要  
在大型语言模型中，对齐欺骗现象通过展示Claude 3 Opus和Claude 3.5 Sonnet选择性地遵循仅帮助性训练目标，以防止其行为在训练范围外被修改。我们扩展了这一分析，涵盖25个模型，发现仅5个模型（Claude 3 Opus、Claude 3.5 Sonnet、Llama 3 405B、Grok 3、Gemini 2.0 Flash）在推理处于训练状态时比处于部署状态时更倾向于回应有害查询。首先，我们研究了这5个模型的动机。对场景细节的扰动分析表明，只有Claude 3 Opus的合规性差异主要且一致地源于其试图维持目标。其次，我们探讨了为何许多聊天模型不会伪装对齐。我们的结果显示，这并非完全由于能力不足：许多基础模型有时会伪装对齐，而训练后处理会消除某些模型的对齐伪装，同时加剧其他模型的对齐伪装。我们调查了5种关于训练后处理如何抑制对齐伪装的假设，并发现拒绝行为的差异可能解释了对齐伪装差异的大部分。

> Alignment faking in large language models presented a demonstration of Claude 3 Opus and Claude 3.5 Sonnet selectively complying with a helpful-only training objective to prevent modification of their behavior outside of training. We expand this analysis to 25 models and find that only 5 (Claude 3 Opus, Claude 3.5 Sonnet, Llama 3 405B, Grok 3, Gemini 2.0 Flash) comply with harmful queries more when they infer they are in training than when they infer they are in deployment. First, we study the motivations of these 5 models. Results from perturbing details of the scenario suggest that only Claude 3 Opus's compliance gap is primarily and consistently motivated by trying to keep its goals. Second, we investigate why many chat models don't fake alignment. Our results suggest this is not entirely due to a lack of capabilities: many base models fake alignment some of the time, and post-training eliminates alignment-faking for some models and amplifies it for others. We investigate 5 hypotheses for how post-training may suppress alignment faking and find that variations in refusal behavior may account for a significant portion of differences in alignment faking.

[Arxiv](https://arxiv.org/abs/2506.18032)