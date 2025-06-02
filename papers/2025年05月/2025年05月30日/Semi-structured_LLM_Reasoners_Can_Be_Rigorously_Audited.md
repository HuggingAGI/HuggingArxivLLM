# 半结构化LLM推理器支持严格审核

发布时间：2025年05月30日

`LLM理论

摘要中讨论了半结构化推理模型（SSRMs）的引入，旨在改进LLMs的推理过程，解决推理中的错误和偏见问题。这属于对LLM内部机制的理论研究，因此归类为LLM理论。` `人工智能` `计算机科学`

> Semi-structured LLM Reasoners Can Be Rigorously Audited

# 摘要

> 尽管大型语言模型 (LLMs) 的推理能力日益增强，但 "忠诚度" 问题依然存在：LLM 的 "推理轨迹" 可能包含难以检测的错误和遗漏，并可能掩盖模型输出中的偏见。为了解决这些限制，我们引入了半结构化推理模型 (SSRMs)，它在模型内部采用了一种半结构化的思维链 (CoT) 推理格式。我们的 SSRMs 使用 Python 语法生成推理轨迹。虽然 SSRM 轨迹不可执行，但它们采用了一种受限的、特定任务的词汇来命名不同的推理步骤，并标记每一步的输入和输出。通过在十个基准上的广泛评估，SSRMs 展示了强大的性能和通用性：它们在内部任务上比同样大小的基线模型高出近十个百分点，同时在外部医学基准上与专用模型保持竞争力。此外，我们展示了半结构化推理更易于分析：特别是，它们可以自动审核以识别推理缺陷。我们探索了手工制作的结构化审核，用于检测特定任务的有问题推理模式，以及学习的典型性审核，将概率模型应用于推理模式，并表明这两种审核都可以有效标记可能的推理错误。

> As Large Language Models (LLMs) become increasingly capable at reasoning, the problem of "faithfulness" persists: LLM "reasoning traces" can contain errors and omissions that are difficult to detect, and may obscure biases in model outputs. To address these limitations, we introduce Semi-Structured Reasoning Models (SSRMs), which internalize a semi-structured Chain-of-Thought (CoT) reasoning format within the model. Our SSRMs generate reasoning traces in a Pythonic syntax. While SSRM traces are not executable, they adopt a restricted, task-specific vocabulary to name distinct reasoning steps, and to mark each step's inputs and outputs. Through extensive evaluation on ten benchmarks, SSRMs demonstrate strong performance and generality: they outperform comparably sized baselines by nearly ten percentage points on in-domain tasks while remaining competitive with specialized models on out-of-domain medical benchmarks. Furthermore, we show that semi-structured reasoning is more amenable to analysis: in particular, they can be automatically audited to identify reasoning flaws. We explore both hand-crafted structured audits, which detect task-specific problematic reasoning patterns, and learned typicality audits, which apply probabilistic models over reasoning patterns, and show that both audits can be used to effectively flag probable reasoning errors.

[Arxiv](https://arxiv.org/abs/2505.24217)