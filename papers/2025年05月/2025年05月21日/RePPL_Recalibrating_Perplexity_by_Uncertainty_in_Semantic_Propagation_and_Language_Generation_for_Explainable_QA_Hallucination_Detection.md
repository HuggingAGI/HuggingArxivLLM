# RePPL：通过语义传播与语言生成中的不确定性重新校准困惑度，实现可解释问答幻觉检测

发布时间：2025年05月21日

`LLM理论` `幻觉检测` `问答系统`

> RePPL: Recalibrating Perplexity by Uncertainty in Semantic Propagation and Language Generation for Explainable QA Hallucination Detection

# 摘要

> 大型语言模型 (LLMs) 虽然强大，但幻觉仍是其可信应用的拦路虎。此前研究虽通过不确定性测量提升了幻觉检测能力，却未能揭示幻觉成因，即输入中哪些部分易引发幻觉。近期关于提示攻击的研究表明，语义传播过程中存在不确定性，注意力机制跨层融合局部令牌信息为高级语义。同时，语言生成中的不确定性源于其基于概率选择高级语义进行采样。基于此，我们提出 RePPL，从这两方面重新校准不确定性度量，为每个令牌赋予可解释的不确定性得分，并以 Perplexity 风格的对数平均形式聚合为总分。实验结果表明，我们的方法在先进模型的各类问答数据集上表现优异（平均 AUC 达 0.833），并能生成令牌级不确定性得分解释幻觉现象。借助这些分数，我们初步揭示了幻觉的混乱模式，展现了其广阔的应用前景。

> Large Language Models (LLMs) have become powerful, but hallucinations remain a vital obstacle to their trustworthy use. While previous works improved the capability of hallucination detection by measuring uncertainty, they all lack the ability to explain the provenance behind why hallucinations occur, i.e., which part of the inputs tends to trigger hallucinations. Recent works on the prompt attack indicate that uncertainty exists in semantic propagation, where attention mechanisms gradually fuse local token information into high-level semantics across layers. Meanwhile, uncertainty also emerges in language generation, due to its probability-based selection of high-level semantics for sampled generations. Based on that, we propose RePPL to recalibrate uncertainty measurement by these two aspects, which dispatches explainable uncertainty scores to each token and aggregates in Perplexity-style Log-Average form as total score. Experiments show that our method achieves the best comprehensive detection performance across various QA datasets on advanced models (average AUC of 0.833), and our method is capable of producing token-level uncertainty scores as explanations for the hallucination. Leveraging these scores, we preliminarily find the chaotic pattern of hallucination and showcase its promising usage.

[Arxiv](https://arxiv.org/abs/2505.15386)