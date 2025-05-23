# # 通过安全导向的探测优化降低LLM微调风险

发布时间：2025年05月22日

`LLM理论` `人工智能安全` `风险管理`

> Mitigating Fine-tuning Risks in LLMs via Safety-Aware Probing Optimization

# 摘要

> 大型语言模型（LLMs）在多领域取得了显著进展，但也引发了生成有害内容的安全担忧。尽管预训练阶段采用了安全对齐技术，但微调仍可能无意中削弱安全性。本文探讨了非有害数据微调导致安全下降的根本原因，并提出了安全感知探测（SAP）框架。SAP通过在梯度传播中引入安全探测器，识别潜在风险，降低了安全性能下降的风险，同时提升了任务性能并保持了模型安全性。实验结果表明，SAP显著降低了有害内容生成率，测试损失与标准微调相当。我们的代码已开源。

> The significant progress of large language models (LLMs) has led to remarkable achievements across numerous applications. However, their ability to generate harmful content has sparked substantial safety concerns. Despite the implementation of safety alignment techniques during the pre-training phase, recent research indicates that fine-tuning LLMs on adversarial or even benign data can inadvertently compromise their safety. In this paper, we re-examine the fundamental issue of why fine-tuning on non-harmful data still results in safety degradation. We introduce a safety-aware probing (SAP) optimization framework designed to mitigate the safety risks of fine-tuning LLMs. Specifically, SAP incorporates a safety-aware probe into the gradient propagation process, mitigating the model's risk of safety degradation by identifying potential pitfalls in gradient directions, thereby enhancing task-specific performance while successfully preserving model safety. Our extensive experimental results demonstrate that SAP effectively reduces harmfulness below the original fine-tuned model and achieves comparable test loss to standard fine-tuning methods. Our code is available at https://github.com/ChengcanWu/SAP.

[Arxiv](https://arxiv.org/abs/2505.16737)