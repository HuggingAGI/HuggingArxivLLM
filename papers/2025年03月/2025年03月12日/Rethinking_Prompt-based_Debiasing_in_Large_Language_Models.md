# 重新审视大型语言模型中的基于提示的去偏见方法

发布时间：2025年03月12日

`LLM理论` `伦理学`

> Rethinking Prompt-based Debiasing in Large Language Models

# 摘要

> 研究大型语言模型 (LLMs) 中的偏见对于开发可信的 AI 至关重要。虽然基于提示的方法很常见，但其有效性依赖于模型固有理解偏见的假设。我们的研究系统地分析了这一假设，使用 BBQ 和 StereoSet 基准测试在开源模型以及商业 GPT 模型上进行了验证。实验结果表明，基于提示的方法效果有限且表面化；例如，Llama2-7B-Chat 模型在 BBQ 数据集上虽然在识别偏见问题上表现优异，但仍然将超过 90% 的无偏内容误分类为有偏。此外，偏见基准测试中的特定评估和问题设置常常导致 LLMs 选择“回避性回答”，忽视问题的核心以及响应与上下文的相关性。而且，以往方法看似成功的原因可能源于有缺陷的评估指标。我们的研究表明，基于提示的方法可能存在着“虚假的繁荣”，并强调需要重新思考偏见评估指标，以确保 AI 真正值得信赖。

> Investigating bias in large language models (LLMs) is crucial for developing trustworthy AI. While prompt-based through prompt engineering is common, its effectiveness relies on the assumption that models inherently understand biases. Our study systematically analyzed this assumption using the BBQ and StereoSet benchmarks on both open-source models as well as commercial GPT model. Experimental results indicate that prompt-based is often superficial; for instance, the Llama2-7B-Chat model misclassified over 90% of unbiased content as biased, despite achieving high accuracy in identifying bias issues on the BBQ dataset. Additionally, specific evaluation and question settings in bias benchmarks often lead LLMs to choose "evasive answers", disregarding the core of the question and the relevance of the response to the context. Moreover, the apparent success of previous methods may stem from flawed evaluation metrics. Our research highlights a potential "false prosperity" in prompt-base efforts and emphasizes the need to rethink bias metrics to ensure truly trustworthy AI.

[Arxiv](https://arxiv.org/abs/2503.09219)