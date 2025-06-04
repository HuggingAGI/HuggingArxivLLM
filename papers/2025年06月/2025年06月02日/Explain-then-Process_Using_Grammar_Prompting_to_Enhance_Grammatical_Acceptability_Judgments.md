# 先解释后处理：通过语法提示提升语法接受度评估

发布时间：2025年06月02日

`LLM应用

这篇论文探讨了大型语言模型在语法判断中的应用，并提出了一种新的方法“语法提示”，以提升模型的性能。该方法通过生成句法解释并将其反馈给目标模型，显著提高了语法判断的准确率，尤其在多语言环境中表现突出。因此，它属于LLM应用类别。` `语言学`

> Explain-then-Process: Using Grammar Prompting to Enhance Grammatical Acceptability Judgments

# 摘要

> 大型语言模型（LLMs）能够解释语法规则，但在判断句子可接受性时，往往无法正确应用这些规则。为此，我们提出了一种名为“语法提示”的解释后再处理范式：首先，大型LLM生成相关句法现象的简洁解释，然后将该解释作为额外上下文反馈给目标模型（无论是LLM还是小型语言模型SLM），以决定最小对中的哪个句子是语法正确。在英语BLiMP、中文SLING和俄语RuBLiMP基准测试中，这一简单的提示设计在多个句法现象上显著优于强基线模型。将LLM的元语言解释反馈给目标模型，有助于弥合知道规则与实际应用之间的差距。在SLM上，仅语法提示即可将平均LLM-SLM准确率差距缩小约20%，与链式思维结合时，差距缩小至56%（从13.0个百分点降至5.8个百分点），且成本微乎其微。这种轻量级、语言无关的提示机制，使低成本的SLM在多语言环境下也能接近前沿LLM的性能。

> Large language models (LLMs) can explain grammatical rules, yet they often fail to apply those rules when judging sentence acceptability. We present "grammar prompting", an explain-then-process paradigm: a large LLM first produces a concise explanation of the relevant syntactic phenomenon, then that explanation is fed back as additional context to the target model -- either an LLM or a smaller language model (SLM) -- before deciding which sentence of a minimal pair is grammatical. On the English BLiMP, Chinese SLING, and Russian RuBLiMP benchmarks, this simple prompt design yields substantial improvements over strong baselines across many syntactic phenomena. Feeding an LLM's metalinguistic explanation back to the target model bridges the gap between knowing a rule and using it. On SLMs, grammar prompting alone trims the average LLM-SLM accuracy gap by about 20%, and when paired with chain-of-thought, by 56% (13.0 pp -> 5.8 pp), all at negligible cost. The lightweight, language-agnostic cue lets low-cost SLMs approach frontier-LLM performance in multilingual settings.

[Arxiv](https://arxiv.org/abs/2506.02302)