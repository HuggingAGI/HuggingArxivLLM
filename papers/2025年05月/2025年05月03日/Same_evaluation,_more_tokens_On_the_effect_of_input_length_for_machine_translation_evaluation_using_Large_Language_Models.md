# 相同的评估，更多的标记：探讨大语言模型在机器翻译评估中输入长度的影响

发布时间：2025年05月03日

`LLM应用

理由：这篇论文探讨了大型语言模型在机器翻译质量评估中的应用，特别是针对长文档的评估挑战。论文提出并测试了多种策略以优化LLMs的评估能力，属于LLM的实际应用研究。` `机器翻译`

> Same evaluation, more tokens: On the effect of input length for machine translation evaluation using Large Language Models

# 摘要

> 机器翻译质量评估一直是技术难题，尤其是面对长文档时更具挑战性。近期研究发现，大型语言模型（LLMs）能够通过MQM错误标注提供可靠且可解释的句子级翻译评估。随着现代LLMs支持更大的上下文窗口，一个自然的问题随之而来：我们是否可以将整篇译文输入LLM进行质量评估？理想状态下，评估结果应不受文本长度影响，保持一致的错误标注。然而，我们的研究发现，文本长度显著影响评估结果：文本越长，错误标注越少，系统排名准确性越低。为解决这一问题，我们测试了多种策略，包括粒度对齐提示、焦点句子提示（FSP）和微调方法，以优化LLMs的评估能力。其中，焦点句子提示和微调方法有效缓解了长度偏差问题，使LLMs在长文本翻译评估中表现更加可靠。

> Accurately evaluating machine-translated text remains a long-standing challenge, particularly for long documents. Recent work has shown that large language models (LLMs) can serve as reliable and interpretable sentence-level translation evaluators via MQM error span annotations. With modern LLMs supporting larger context windows, a natural question arises: can we feed entire document translations into an LLM for quality assessment? Ideally, evaluation should be invariant to text length, producing consistent error spans regardless of input granularity. However, our analysis shows that text length significantly impacts evaluation: longer texts lead to fewer error spans and reduced system ranking accuracy. To address this limitation, we evaluate several strategies, including granularity-aligned prompting, Focus Sentence Prompting (FSP), and a fine-tuning approach to better align LLMs with the evaluation task. The latter two methods largely mitigate this length bias, making LLMs more reliable for long-form translation evaluation.

[Arxiv](https://arxiv.org/abs/2505.01761)