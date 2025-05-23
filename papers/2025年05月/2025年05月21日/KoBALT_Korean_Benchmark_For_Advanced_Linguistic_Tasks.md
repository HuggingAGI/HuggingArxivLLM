# KoBALT：韩国高级语言任务基准

发布时间：2025年05月21日

`LLM应用` `语言学` `基准测试`

> KoBALT: Korean Benchmark For Advanced Linguistic Tasks

# 摘要

> 我们推出KoBALT（韩国语高级语言任务基准），这是一个全面的、基于语言学动机的基准测试，包含涵盖五个语言学领域（句法、语义、语用学、语音学/音系学和形态学）的24种语言现象的700道多选题。KoBALT旨在提升大型语言模型（LLMs）在韩国语这一形态丰富的语言中的评估水平，通过解决传统基准测试常缺乏语言深度和类型学基础的局限性。它引入了一套由专家精选、基于语言学动机的问题，这些问题与标准韩国语语料库的n-gram重叠度极低，极大地降低了数据污染的风险，从而能够更 robustly 评估真正的语言理解能力。我们对20个当代LLMs的评估显示了显著的性能差异，最高性能模型的总体准确率为61%，但在语言学领域间表现差异较大——语义方面表现较强（66%），而在音系学（31%）和形态学（36%）方面则存在明显弱势。通过95名标注员的人类偏好评估，我们证明了KoBALT得分与人类判断之间存在强烈的相关性，验证了我们基准测试作为韩国语理解辨别性评估指标的有效性。KoBALT填补了类型学多样性语言在语言学评估方面的关键空白，并为评估韩国语模型的真正语言能力提供了一个 robust 的框架。

> We introduce KoBALT (Korean Benchmark for Advanced Linguistic Tasks), a comprehensive linguistically-motivated benchmark comprising 700 multiple-choice questions spanning 24 phenomena across five linguistic domains: syntax, semantics, pragmatics, phonetics/phonology, and morphology. KoBALT is designed to advance the evaluation of large language models (LLMs) in Korean, a morphologically rich language, by addressing the limitations of conventional benchmarks that often lack linguistic depth and typological grounding. It introduces a suite of expert-curated, linguistically motivated questions with minimal n-gram overlap with standard Korean corpora, substantially mitigating the risk of data contamination and allowing a more robust assessment of true language understanding. Our evaluation of 20 contemporary LLMs reveals significant performance disparities, with the highest-performing model achieving 61\% general accuracy but showing substantial variation across linguistic domains - from stronger performance in semantics (66\%) to considerable weaknesses in phonology (31\%) and morphology (36\%). Through human preference evaluation with 95 annotators, we demonstrate a strong correlation between KoBALT scores and human judgments, validating our benchmark's effectiveness as a discriminative measure of Korean language understanding. KoBALT addresses critical gaps in linguistic evaluation for typologically diverse languages and provides a robust framework for assessing genuine linguistic competence in Korean language models.

[Arxiv](https://arxiv.org/abs/2505.16125)