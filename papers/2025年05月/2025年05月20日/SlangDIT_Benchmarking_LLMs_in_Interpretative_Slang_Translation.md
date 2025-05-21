# SlangDIT：评估 LLMs 在解释性俚语翻译中的表现

发布时间：2025年05月20日

`LLM应用

理由：这篇论文专注于将大型语言模型应用于俚语翻译任务，通过构建数据集和模型来提升翻译质量，属于应用层面的创新。` `机器翻译`

> SlangDIT: Benchmarking LLMs in Interpretative Slang Translation

# 摘要

> 俚语翻译的难点在于捕捉其依赖上下文的语义延伸，因为俚语往往传达超越字面意思的含义。尽管在大型语言模型（LLMs）时代，俚语识别、解释和翻译已被作为独立任务研究，但它们之间固有的相互依存关系仍未得到充分探索。主要原因在于缺乏一个基准测试，使得其中两项任务能够成为第三项任务的先决条件，从而促进地道的翻译。本文中，我们提出了一个解释性俚语翻译任务（命名为 SlangDIT），包含三个子任务：俚语识别、跨语言俚语解释以及基于当前上下文的俚语翻译，旨在借助俚语识别和解释生成更准确的翻译。为此，我们构建了一个 SlangDIT 数据集，包含超过 25,000 余对英汉句对。每个源句至少包含一个俚语，并标注有相应的跨语言俚语解释。基于此基准测试，我们提出了一种深度思考模型，命名为 SlangOWL。该模型首先识别句子中是否包含俚语，然后判断该俚语是否具有多义性并分析其可能含义。进一步地，SlangOWL 提供针对当前上下文的俚语最佳解释。最后，根据整体思考，SlangOWL 提供一个合适的翻译。我们在 LLMs（例如 Qwen2.5 和 LLama-3.1）上进行的实验表明，我们的深度思考方法确实提升了 LLMs 的性能，其中提出的 SlangOWL 显著超越了基础模型和无思考的监督微调模型。

> The challenge of slang translation lies in capturing context-dependent semantic extensions, as slang terms often convey meanings beyond their literal interpretation. While slang detection, explanation, and translation have been studied as isolated tasks in the era of large language models (LLMs), their intrinsic interdependence remains underexplored. The main reason is lacking of a benchmark where the two tasks can be a prerequisite for the third one, which can facilitate idiomatic translation. In this paper, we introduce the interpretative slang translation task (named SlangDIT) consisting of three sub-tasks: slang detection, cross-lingual slang explanation, and slang translation within the current context, aiming to generate more accurate translation with the help of slang detection and slang explanation. To this end, we construct a SlangDIT dataset, containing over 25k English-Chinese sentence pairs. Each source sentence mentions at least one slang term and is labeled with corresponding cross-lingual slang explanation. Based on the benchmark, we propose a deep thinking model, named SlangOWL. It firstly identifies whether the sentence contains a slang, and then judges whether the slang is polysemous and analyze its possible meaning. Further, the SlangOWL provides the best explanation of the slang term targeting on the current context. Finally, according to the whole thought, the SlangOWL offers a suitable translation. Our experiments on LLMs (\emph{e.g.}, Qwen2.5 and LLama-3.1), show that our deep thinking approach indeed enhances the performance of LLMs where the proposed SLangOWL significantly surpasses the vanilla models and supervised fine-tuned models without thinking.

[Arxiv](https://arxiv.org/abs/2505.14181)