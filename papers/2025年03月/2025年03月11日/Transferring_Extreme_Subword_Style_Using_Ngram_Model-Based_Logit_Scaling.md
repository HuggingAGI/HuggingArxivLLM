# # 基于Ngram模型的Logit Scaling实现极端子词风格迁移

发布时间：2025年03月11日

`LLM应用` `文本生成`

> Transferring Extreme Subword Style Using Ngram Model-Based Logit Scaling

# 摘要

> 我们提出了一种基于ngram模型的logit缩放技术，能够在推理过程中有效迁移极端子词风格变化到大型语言模型中。通过追踪生成文本相对于评估模型的ngram插值版本和原始版本的困惑度来展示其有效性。在最小化前者度量的同时，让后者接近目标作者或角色生成文本的困惑度，使我们能够在保持流畅性的同时选择足够的适应程度。

> We present an ngram model-based logit scaling technique that effectively transfers extreme subword stylistic variation to large language models at inference time. We demonstrate its efficacy by tracking the perplexity of generated text with respect to the ngram interpolated and original versions of an evaluation model. Minimizing the former measure while the latter approaches the perplexity of a text produced by a target author or character lets us select a sufficient degree of adaptation while retaining fluency.

[Arxiv](https://arxiv.org/abs/2503.08550)