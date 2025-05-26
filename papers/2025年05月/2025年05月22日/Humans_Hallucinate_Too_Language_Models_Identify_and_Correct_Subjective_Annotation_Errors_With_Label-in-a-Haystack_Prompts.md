# # 人类也会犯错：语言模型通过针在 haystack 中的提示识别并纠正主观标注错误

发布时间：2025年05月22日

`LLM应用` `机器学习`

> Humans Hallucinate Too: Language Models Identify and Correct Subjective Annotation Errors With Label-in-a-Haystack Prompts

# 摘要

> 在自然语言处理中，建模复杂主观任务（如情感和道德识别）极具挑战性，主要源于人类标注的显著差异。这种差异通常反映了合理的语义解释差异，而非单纯噪声。因此，我们需要方法来区分合法的主观性和错误。我们通过在这些情境下探索使用大型语言模型（LLMs）进行标签验证来应对这一挑战。

首先，我们提出了一种基于上下文学习的二元过滤基线，用于评估文档-标签对的合理性。随后，我们引入了“标签在稻草堆中”的设置：将查询及其标签包含在展示给LLMs的示例中，并提供任务特定指令（如情感识别），而非简单复制标签。我们展示了标签未能复制到LLM输出中与任务相关且具有信息量。

在此基础上，我们提出了用于主观标签校正的标签在稻草堆中修正（LiaHR）框架：当模型输出与参考黄金标签不一致时，我们将生成的标签分配给示例，而不是丢弃它。这种方法可集成到标注流水线中，以提高信噪比。全面的分析、人工评估和生态效度研究验证了LiaHR在标签校正方面的实用性。代码可在https://github.com/gchochla/LiaHR获取。

> Modeling complex subjective tasks in Natural Language Processing, such as recognizing emotion and morality, is considerably challenging due to significant variation in human annotations. This variation often reflects reasonable differences in semantic interpretations rather than mere noise, necessitating methods to distinguish between legitimate subjectivity and error. We address this challenge by exploring label verification in these contexts using Large Language Models (LLMs). First, we propose a simple In-Context Learning binary filtering baseline that estimates the reasonableness of a document-label pair. We then introduce the Label-in-a-Haystack setting: the query and its label(s) are included in the demonstrations shown to LLMs, which are prompted to predict the label(s) again, while receiving task-specific instructions (e.g., emotion recognition) rather than label copying. We show how the failure to copy the label(s) to the output of the LLM are task-relevant and informative. Building on this, we propose the Label-in-a-Haystack Rectification (LiaHR) framework for subjective label correction: when the model outputs diverge from the reference gold labels, we assign the generated labels to the example instead of discarding it. This approach can be integrated into annotation pipelines to enhance signal-to-noise ratios. Comprehensive analyses, human evaluations, and ecological validity studies verify the utility of LiaHR for label correction. Code is available at https://github.com/gchochla/LiaHR.

[Arxiv](https://arxiv.org/abs/2505.17222)