# 《动词幻影：多模态大型语言模型中动词概念幻觉的揭示与评估》

发布时间：2024年12月06日

`LLM应用` `语言模型` `多模态`

> Verb Mirage: Unveiling and Assessing Verb Concept Hallucinations in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）近来备受瞩目，在 OCR、VQA、字幕生成等诸多任务中展现出卓越能力。然而，幻觉问题始终存在。虽然已有众多方法被提出以减轻幻觉，且成效显著，但这些方法主要着眼于减轻【对象/名词相关】概念的幻觉。而对于理解人类行为至关重要的动词概念，却在很大程度上被忽略了。据我们所知，在本文中，我们是【首家】从多视角研究 MLLMs 【动词幻觉】现象的。我们的发现表明，大多数先进的 MLLMs 都存在严重的动词幻觉。为评估现有减轻对象概念幻觉的方法对动词幻觉的效果，我们对这些方法进行了评估，发现它们无法有效解决动词幻觉。为应对此问题，我们提出了一种新颖的基于丰富动词知识的调优方法来减轻动词幻觉。实验结果显示，我们的方法显著降低了与动词相关的幻觉。【我们的代码和数据将会公开】。

> Multimodal Large Language Models (MLLMs) have garnered significant attention recently and demonstrate outstanding capabilities in various tasks such as OCR, VQA, captioning, $\textit{etc}$. However, hallucination remains a persistent issue. While numerous methods have been proposed to mitigate hallucinations, achieving notable improvements, these methods primarily focus on mitigating hallucinations about $\textbf{object/noun-related}$ concepts. Verb concepts, crucial for understanding human actions, have been largely overlooked. In this paper, to the best of our knowledge, we are the $\textbf{first}$ to investigate the $\textbf{verb hallucination}$ phenomenon of MLLMs from various perspectives. Our findings reveal that most state-of-the-art MLLMs suffer from severe verb hallucination. To assess the effectiveness of existing mitigation methods for object concept hallucination on verb hallucination, we evaluated these methods and found that they do not effectively address verb hallucination. To address this issue, we propose a novel rich verb knowledge-based tuning method to mitigate verb hallucination. The experiment results demonstrate that our method significantly reduces hallucinations related to verbs. $\textit{Our code and data will be made publicly available}$.

[Arxiv](https://arxiv.org/abs/2412.04939)