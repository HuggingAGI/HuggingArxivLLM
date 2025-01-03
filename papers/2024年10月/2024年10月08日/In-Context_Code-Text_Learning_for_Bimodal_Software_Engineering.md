# 双模态软件工程中的上下文代码-文本学习

发布时间：2024年10月08日

`LLM应用

理由：这篇论文主要讨论了如何利用预训练的CodeLLAMA模型进行代码-文本双模态的上下文学习，并提出了一个名为InCTRL的管道来统一各类软件工程任务的提示学习。论文还展示了InCTRL模型在多个软件工程任务中的性能提升，特别是在少样本学习场景下的表现。这些内容主要涉及大型语言模型（LLM）在实际应用中的使用和改进，因此将其分类为“LLM应用”。` `软件工程`

> In-Context Code-Text Learning for Bimodal Software Engineering

# 摘要

> # 摘要
随着大型语言模型的兴起，双模态软件分析一度看似触手可及。然而，软件工程中自然语言文本与代码的复杂交互带来了独特挑战，限制了预训练模型在多样化任务中的泛化能力。我们提出，代码-文本双模态的上下文学习是一条充满希望的道路。本文深入探讨了上下文代码-文本学习，重点是利用预训练的CodeLLAMA模型。
我们构建了一个涵盖23个软件工程任务的多样化数据集，并将其转化为上下文学习格式。为了高效提取信息特征，我们设计了一个可配置的提示模板。我们提出的InCTRL管道统一了各类软件工程任务的提示学习。通过对数据集的广泛评估，INCTRL模型在少样本性能上超越了包括CodeLLAMA在内的最先进模型。具体而言，INCTRL在应用于CodeLLAMA模型时，显著提升了各项任务的精度（至少约12%）和召回率（高达93.88%）。例如，在程序修复任务中，INCTRL将CodeLLAMA的BLEU分数提升了85分；在克隆检测任务中，INCTRL实现了69个百分点的提升。此外，INCTRL模型在使用检索增强生成进行个别下游任务时，展现了最先进的性能。最后，我们定性分析了INCTRL相较于CodeLLAMA的优势，并开源了所有模型以扩大其影响力。
我们的代码和数据集公开在：egin{center}
{url{https://anonymous.4open.science/r/inctrl-B65B}} \end{center}

> Bimodal software analysis initially appeared to be within reach with the advent of large language models. Unfortunately, the complex interplay of natural language text and code in software engineering, presents unique challenges that prevent pretrained models to generalize to a variety of tasks. We postulate that in-context learning for the code-text bimodality is a promising avenue. This paper thus introduces a comprehensive study of in-context code-text learning, focusing on leveraging pretrained CodeLLAMA models.
  We consider a diverse dataset encompassing 23 software engineering tasks, which we transform in an in-context learning format. To effectively extract informative features, we propose a configurable prompt template. Our proposed pipeline, InCTRL, then unifies prompt learning across various software engineering tasks. Extensive evaluation on the study datasets demonstrates the superiority of INCTRL-models in few-shot performance, surpassing state-of-the-art models including the support model, CodeLLAMA. Typically, we observe that applied to the CodeLLAMA model, INCTRL brings improvements in terms of precision (at least about 12\%) and recall (up to 93.88\%) on various tasks. For example, on the task of program repair, INCTRL improves the BLEU score of CodeLLAMA by 85 points, while for clone detection, INCTRL achieves an improvement of 69 percentage points. Moreover, INCTRL-models offer state-of-the-art performance when using retrieval-augmented generation on individual downstream tasks. Finally, we qualitatively analyze the benefits of INCTRL over CodeLLAMA and open-source all models for broader impact.
  We make our code and dataset publicly available at: \begin{center}
  {url{https://anonymous.4open.science/r/inctrl-B65B}} \end{center}

[Arxiv](https://arxiv.org/abs/2410.18107)