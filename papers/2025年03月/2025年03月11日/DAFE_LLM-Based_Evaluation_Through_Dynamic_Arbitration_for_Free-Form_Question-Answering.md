# DAFE：通过动态仲裁实现的基于LLM评估，用于自由形式问答

发布时间：2025年03月11日

`LLM应用` `评估方法` `评估框架`

> DAFE: LLM-Based Evaluation Through Dynamic Arbitration for Free-Form Question-Answering

# 摘要

> 评估大型语言模型（LLMs）生成的自由形式响应依然是一个难题，因为它们具有多样性和开放性。传统方法难以应对这一挑战，而人工评估虽然可靠，但成本高昂。利用LLMs的强大力量，我们提出了动态仲裁评估框架（DAFE），采用双裁判机制，并仅在必要时引入仲裁者。DAFE通过任务特定的参考答案和动态仲裁提升了判断准确性，显著改善了Macro F1和Cohen's Kappa等指标。实验结果表明，DAFE不仅评估结果一致可靠，还实现了资源的高效利用，为评估自由形式模型输出提供了强大支持。

> Evaluating Large Language Models (LLMs) free-form generated responses remains a challenge due to their diverse and open-ended nature. Traditional supervised signal-based automatic metrics fail to capture semantic equivalence or handle the variability of open-ended responses, while human evaluation, though reliable, is resource-intensive. Leveraging LLMs as evaluators offers a promising alternative due to their strong language understanding and instruction-following capabilities. Taking advantage of these capabilities, we propose the Dynamic Arbitration Framework for Evaluation (DAFE), which employs two primary LLM-as-judges and engages a third arbitrator only in cases of disagreements. This selective arbitration prioritizes evaluation reliability while reducing unnecessary computational demands compared to conventional majority voting. DAFE utilizes task-specific reference answers with dynamic arbitration to enhance judgment accuracy, resulting in significant improvements in evaluation metrics such as Macro F1 and Cohen's Kappa. Through experiments, including a comprehensive human evaluation, we demonstrate DAFE's ability to provide consistent, scalable, and resource-efficient assessments, establishing it as a robust framework for evaluating free-form model outputs.

[Arxiv](https://arxiv.org/abs/2503.08542)