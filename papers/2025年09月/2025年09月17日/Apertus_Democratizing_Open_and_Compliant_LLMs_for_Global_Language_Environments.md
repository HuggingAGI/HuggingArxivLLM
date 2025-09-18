# Apertus：推动开放合规大型语言模型在全球语言环境中的普及

发布时间：2025年09月17日

`LLM应用` `基础理论`

> Apertus: Democratizing Open and Compliant LLMs for Global Language Environments

# 摘要

> 我们推出了Apertus——一套完全开放的大型语言模型（LLMs），旨在解决当前开放模型生态中的两大系统性问题：数据合规性与多语言表示。与许多先前模型不同——这些模型发布权重时缺乏可复现的数据管道，也未顾及内容所有者的权利——Apertus仅基于公开可用数据进行预训练，不仅追溯遵守robots.txt排除规则，还过滤非许可、有害及个人身份信息内容。为降低记忆风险，我们在预训练中采用Goldfish目标，在保留下游任务性能的同时，有效抑制数据的逐字记忆。Apertus模型还扩大了多语言覆盖范围，在1800多种语言的15万亿token上训练，约40%的预训练数据为非英语内容。该模型以80亿和700亿参数规模发布，在多语言基准测试中，其性能在完全开放模型中接近最先进水平，可与开源权重同类模型相媲美，甚至超越。除模型权重外，我们还以宽松许可协议发布了开发周期中的所有科研成果，包括数据准备脚本、检查点、评估套件及训练代码，以便实现透明审计与扩展。

> We present Apertus, a fully open suite of large language models (LLMs) designed to address two systemic shortcomings in today's open model ecosystem: data compliance and multilingual representation. Unlike many prior models that release weights without reproducible data pipelines or regard for content-owner rights, Apertus models are pretrained exclusively on openly available data, retroactively respecting robots.txt exclusions and filtering for non-permissive, toxic, and personally identifiable content. To mitigate risks of memorization, we adopt the Goldfish objective during pretraining, strongly suppressing verbatim recall of data while retaining downstream task performance. The Apertus models also expand multilingual coverage, training on 15T tokens from over 1800 languages, with ~40% of pretraining data allocated to non-English content. Released at 8B and 70B scales, Apertus approaches state-of-the-art results among fully open models on multilingual benchmarks, rivalling or surpassing open-weight counterparts. Beyond model weights, we release all scientific artifacts from our development cycle with a permissive license, including data preparation scripts, checkpoints, evaluation suites, and training code, enabling transparent audit and extension.

[Arxiv](https://arxiv.org/abs/2509.14233)