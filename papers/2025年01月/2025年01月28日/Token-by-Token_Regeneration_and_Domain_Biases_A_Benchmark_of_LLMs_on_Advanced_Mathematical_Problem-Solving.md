# # 逐令牌再生与领域偏差：LLMs在高级数学问题解决上的基准测试

发布时间：2025年01月28日

`LLM应用

**理由**：这篇论文主要研究了大型语言模型（LLMs）在解决复杂数学问题时的表现，特别是通过生成可执行Python代码来进行推理。研究使用了特定的数据集和评估框架来测试不同模型的性能，并探讨了优化输出结果的方法。这些内容属于LLM在实际任务中的应用，因此分类为LLM应用。`

> Token-by-Token Regeneration and Domain Biases: A Benchmark of LLMs on Advanced Mathematical Problem-Solving

# 摘要

> 大型语言模型（LLMs）在自然语言任务中表现出色，但在复杂数学问题解决上却显得力不从心，尤其是在符号推理和输出一致性方面。本研究使用MATH数据集中的945个竞赛级问题，评估了10个参数在7到80亿之间的LLMs，重点关注它们在推理过程中生成可执行Python代码的能力，涉及超过9,450次代码执行。研究引入了一个基于mistral-large-2411的评估框架，以5分制对答案进行评分，解决了数学符号不一致的问题。研究还探讨了逐令牌重新生成输出对结果优化的影响。结果显示，顶级商业模型（gpt-4o-mini，得分83.7%）与最不有效的开源模型（open-codestral-mamba:v0.1，得分49.2%）之间存在34.5%的性能差距，尤其在数论等复杂领域更为明显。逐令牌重新生成虽然略微提高了模型llama3.1:8b的准确性（+0.8%），但也减少了36.7%的代码执行时间，突显了效率与精度之间的权衡。研究还发现，更困难的问题与所有模型的较低准确性相关。尽管使用了受控执行环境，生成的代码中不到1%是不安全的，3.17%的问题在10次尝试后仍未解决，这表明混合推理方法可能是有益的。

> Large language models (LLMs) excel in many natural language tasks, yet they struggle with complex mathemat-ical problem-solving, particularly in symbolic reasoning and maintaining consistent output. This study evalu-ates 10 LLMs with 7 to 8 billion parameters using 945 competition-level problems from the MATH dataset. The focus is on their ability to generate executable Python code as a step in their reasoning process, involving over 9,450 code executions. The research introduces an evaluation framework using mistral-large-2411 to rate answers on a 5-point scale, which helps address inconsistencies in mathematical notation. It also examines the impact of regenerating output token-by-token on refining results. The findings reveal a significant 34.5% per-formance gap between the top commercial model (gpt-4o-mini, scoring 83.7%) and the least effective open-source model (open-codestral-mamba:v0.1, scoring 49.2%). This disparity is especially noticeable in complex areas like Number Theory. While token-by-token regeneration slightly improved accuracy (+0.8%) for the model llama3.1:8b, it also reduced code execution time by 36.7%, highlighting a trade-off between efficiency and precision. The study also noted a consistent trend where harder problems correlated with lower accuracy across all models. Despite using controlled execution environments, less than 1% of the generated code was unsafe, and 3.17% of problems remained unsolved after 10 attempts, suggesting that hybrid reasoning methods may be beneficial.

[Arxiv](https://arxiv.org/abs/2501.17084)