# 基于大型语言模型的多对多摘要任务实证研究

发布时间：2025年05月19日

`LLM应用` `多语言处理`

> An Empirical Study of Many-to-Many Summarization with Large Language Models

# 摘要

> Many-to-many summarization（M2MS）的目标是处理任何语言的文档，并生成对应语言的摘要。最近，大型语言模型（LLMs）展现了强大的多语言能力，这使得它们在实际应用中具备了执行M2MS的潜力。本研究对LLMs的M2MS能力进行了系统性的实证分析。具体来说，我们首先基于之前的八个领域特定数据集重新组织了M2MS数据。重新组织后的数据集包含来自五个领域和六种语言的47.8K个样本，可用于训练和评估LLMs。接着，我们在零样本和指令微调两种模式下对18种LLMs进行了基准测试。为了对比，我们还进行了传统模型（如mBART）的微调实验。实验结果表明，零样本的LLMs与微调的传统模型在性能上相当。经过指令微调后，开源LLMs的M2MS能力得到了显著提升，并在自动评估中超越了零样本的LLMs（包括GPT-4）。此外，我们还证明了这种任务特定的提升并未削弱LLMs的通用任务解决能力。然而，根据我们的人工评估，LLMs仍然面临事实准确性的问题，而指令微调可能会加剧这一问题。因此，在实际应用中构建LLM摘要器时，如何控制事实错误成为关键，这也是未来研究中值得重点关注的方面。

> Many-to-many summarization (M2MS) aims to process documents in any language and generate the corresponding summaries also in any language. Recently, large language models (LLMs) have shown strong multi-lingual abilities, giving them the potential to perform M2MS in real applications. This work presents a systematic empirical study on LLMs' M2MS ability. Specifically, we first reorganize M2MS data based on eight previous domain-specific datasets. The reorganized data contains 47.8K samples spanning five domains and six languages, which could be used to train and evaluate LLMs. Then, we benchmark 18 LLMs in a zero-shot manner and an instruction-tuning manner. Fine-tuned traditional models (e.g., mBART) are also conducted for comparisons. Our experiments reveal that, zero-shot LLMs achieve competitive results with fine-tuned traditional models. After instruct-tuning, open-source LLMs can significantly improve their M2MS ability, and outperform zero-shot LLMs (including GPT-4) in terms of automatic evaluations. In addition, we demonstrate that this task-specific improvement does not sacrifice the LLMs' general task-solving abilities. However, as revealed by our human evaluation, LLMs still face the factuality issue, and the instruction tuning might intensify the issue. Thus, how to control factual errors becomes the key when building LLM summarizers in real applications, and is worth noting in future research.

[Arxiv](https://arxiv.org/abs/2505.12983)