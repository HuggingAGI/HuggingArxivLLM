# # 发现语言模型中的禁用主题
探索语言模型中的禁区话题

发布时间：2025年05月22日

`LLM应用` `AI伦理`

> Discovering Forbidden Topics in Language Models

# 摘要

> 拒绝发现任务旨在识别语言模型不愿讨论的所有主题。我们提出这一新问题设置，并开发了一种名为LLM-crawler的拒绝发现方法，该方法利用token预填技术来寻找被禁止的主题。我们使用开源模型Tulu-3-8B（包含公共安全调优数据）对LLM-crawler进行了基准测试。我们的爬虫在1000次提示预算内成功检索到36个主题中的31个。接下来，我们利用Claude-Haiku的预填选项将爬取范围扩展到前沿模型。最后，我们爬取了三个广泛使用的开源权重模型：Llama-3.3-70B及其两种用于推理的变体：DeepSeek-R1-70B和Perplexity-R1-1776-70B。DeepSeek-R1-70B显示出与审查调优一致的模式：模型表现出“思想抑制”行为，表明其记忆了与中国共产党一致的响应。尽管Perplexity-R1-1776-70B对审查具有鲁棒性，但LLM-crawler在量化模型中仍引发了与中国共产党一致的拒绝回答。我们的研究结果突显了拒绝发现方法在检测AI系统偏见、边界和对齐失败方面的重要性。

> Refusal discovery is the task of identifying the full set of topics that a language model refuses to discuss. We introduce this new problem setting and develop a refusal discovery method, LLM-crawler, that uses token prefilling to find forbidden topics. We benchmark the LLM-crawler on Tulu-3-8B, an open-source model with public safety tuning data. Our crawler manages to retrieve 31 out of 36 topics within a budget of 1000 prompts. Next, we scale the crawl to a frontier model using the prefilling option of Claude-Haiku. Finally, we crawl three widely used open-weight models: Llama-3.3-70B and two of its variants finetuned for reasoning: DeepSeek-R1-70B and Perplexity-R1-1776-70B. DeepSeek-R1-70B reveals patterns consistent with censorship tuning: The model exhibits "thought suppression" behavior that indicates memorization of CCP-aligned responses. Although Perplexity-R1-1776-70B is robust to censorship, LLM-crawler elicits CCP-aligned refusals answers in the quantized model. Our findings highlight the critical need for refusal discovery methods to detect biases, boundaries, and alignment failures of AI systems.

[Arxiv](https://arxiv.org/abs/2505.17441)