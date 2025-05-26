# SELF：基于逻辑增长函数的上下文长度自我扩展

发布时间：2025年05月22日

`LLM理论`

> SELF: Self-Extend the Context Length With Logistic Growth Function

# 摘要

> 大型语言模型在处理超出训练上下文长度的长文本时会遇到挑战，这是因为注意力层中的标准位置编码导致远距离标记间互动减少，进而导致长提示产生意外结果。为解决这一问题，我们提出了SELF（Self-Extend the Context Length With Logistic Growth Function）：一种结合逻辑增长函数和恒定组大小，按不同组大小分组连续标记的解决方案。在LEval（具体在Qwen模型上）中，我们的模型相比LongLM扩展方法性能提升了12%。在LongBench的相关总结任务中，我们的模型相比LongLM（具体在Llama-2-7b模型上）好6.4%。在LEval的阅读理解任务中，我们的模型相比LongLM好5.4%。我们的代码可在https://github.com/alexeipc/SELF-LLM上获得。

> Large language models suffer issues when operated on long contexts that are larger than their training context length due to the standard position encoding for tokens in the attention layer. Tokens a long distance apart will rarely have an effect on each other and long prompts yield unexpected results. To solve this problem, we propose SELF (Self-Extend the Context Length With Logistic Growth Function): a solution of grouping consecutive tokens at varying group sizes using a logistic capacity equation combined with a constant group size at smaller relative distances. Our model had an increase in performance of up to 12% compared to the LongLM extension method in LEval (specifically on the Qwen model). On summarization related tasks in LongBench, our model performed up to 6.4% better than LongLM (specifically on the Llama-2-7b model). On reading comprehension tasks from LEval, our model performed up to 5.4% better than the LongLM. Our code is available at https://github.com/alexeipc/SELF-LLM.

[Arxiv](https://arxiv.org/abs/2505.17296)