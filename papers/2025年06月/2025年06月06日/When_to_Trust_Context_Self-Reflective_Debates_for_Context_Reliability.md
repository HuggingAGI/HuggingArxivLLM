# 何时该信任上下文？——自我反思式的辩论方法评估上下文可靠性

发布时间：2025年06月06日

`LLM应用

摘要中提到，论文提出了一种轻量级框架SR-DCR，用于解决大型语言模型在处理参数化知识和上下文输入时出现的事实不一致或幻觉问题。这属于大型语言模型的实际应用改进，因此归类为LLM应用。` `上下文推理`

> When to Trust Context: Self-Reflective Debates for Context Reliability

# 摘要

> 大型语言模型在处理参数化知识与上下文输入时，常出现事实不一致或产生幻觉的问题。我们提出 Self-Reflective Debate for Contextual Reliability (SR-DCR)，一个轻量级框架，通过整合基于token的自信心评分与不对称多智能体辩论来解决此类冲突。一个被剥夺上下文的批评者向一个基于给定段落进行辩护的辩护士提出挑战；一个裁判模型评估辩论并判断上下文的可靠性。最终答案通过结合裁决与模型信心来选择。在 ClashEval 基准上的实验表明，SR-DCR 一致增强了对误导性上下文的鲁棒性，同时在可信输入上保持准确性，与经典的辩论方法和仅基于信心的基线相比，SR-DCR 在计算开销极小的情况下表现更优。代码可在 https://github.com/smiles724/Self-Reflective-Debates 获取。

> Large language models frequently encounter conflicts between their parametric knowledge and contextual input, often resulting in factual inconsistencies or hallucinations. We propose Self-Reflective Debate for Contextual Reliability (SR-DCR), a lightweight framework that integrates token-level self-confidence with an asymmetric multi-agent debate to adjudicate such conflicts. A critic, deprived of context, challenges a defender who argues from the given passage; a judge model evaluates the debate and determines the context's reliability. The final answer is selected by combining the verdict with model confidence. Experiments on the ClashEval benchmark demonstrate that SR-DCR consistently enhances robustness to misleading context while maintaining accuracy on trustworthy inputs, outperforming both classical debate and confidence-only baselines with minimal computational overhead. The code is available at https://github.com/smiles724/Self-Reflective-Debates.

[Arxiv](https://arxiv.org/abs/2506.06020)