# 大型语言模型能否可靠地在词汇多样化的情境中进行逻辑推理的翻译？

发布时间：2025年06月04日

`LLM应用` `人工智能` `逻辑推理`

> Are LLMs Reliable Translators of Logical Reasoning Across Lexically Diversified Contexts?

# 摘要

> 神经符号方法结合大型语言模型（LLMs）与求解器，在需要长推理链的逻辑推理问题上表现出色。在此范式下，LLMs充当翻译器，将自然语言推理问题转化为正式逻辑公式，随后由可靠的符号求解器返回正确解。尽管取得成功，但LLMs作为翻译器难以处理词汇多样化这一常见语言现象，表明其在现实场景中不可靠。现有逻辑推理基准缺乏词汇多样性，未能挑战LLMs的翻译能力，掩盖了这一问题。为此，我们提出了SCALe基准，通过**逻辑不变的词汇多样化**方法填补这一空白。通过使用LLMs将原始数据集转换为词汇多样化但逻辑等价的版本，我们在新数据集上评估LLMs将多样表达映射到统一逻辑符号的能力。实验表明，当前LLMs在此能力上存在缺陷。基于此，我们提出MenTaL方法，引导LLMs首先构建统一多样化表达的表格，然后再进行翻译。通过上下文学习和监督微调（SFT）应用MenTaL，显著提升了LLMs翻译器在词汇多样化文本上的性能。代码已开放：https://github.com/wufeiwuwoshihua/LexicalDiver。


> Neuro-symbolic approaches combining large language models (LLMs) with solvers excels in logical reasoning problems need long reasoning chains. In this paradigm, LLMs serve as translators, converting natural language reasoning problems into formal logic formulas. Then reliable symbolic solvers return correct solutions. Despite their success, we find that LLMs, as translators, struggle to handle lexical diversification, a common linguistic phenomenon, indicating that LLMs as logic translators are unreliable in real-world scenarios. Moreover, existing logical reasoning benchmarks lack lexical diversity, failing to challenge LLMs' ability to translate such text and thus obscuring this issue. In this work, we propose SCALe, a benchmark designed to address this significant gap through **logic-invariant lexical diversification**. By using LLMs to transform original benchmark datasets into lexically diversified but logically equivalent versions, we evaluate LLMs' ability to consistently map diverse expressions to uniform logical symbols on these new datasets. Experiments using SCALe further confirm that current LLMs exhibit deficiencies in this capability. Building directly on the deficiencies identified through our benchmark, we propose a new method, MenTaL, to address this limitation. This method guides LLMs to first construct a table unifying diverse expressions before performing translation. Applying MenTaL through in-context learning and supervised fine-tuning (SFT) significantly improves the performance of LLM translators on lexically diversified text. Our code is now available at https://github.com/wufeiwuwoshihua/LexicalDiver.

[Arxiv](https://arxiv.org/abs/2506.04575)