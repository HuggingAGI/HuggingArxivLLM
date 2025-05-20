# 挖掘模型的不一致特性，提升通过率@k表现

发布时间：2025年05月19日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型的不一致性来提升性能，通过引入一个名为“Variator”的代理，生成变体并提交候选解决方案。虽然提到了代理的概念，但核心是LLM的应用和性能提升，因此归类为LLM应用。` `网络安全`

> Leveraging LLM Inconsistency to Boost Pass@k Performance

# 摘要

> 大型语言模型 (LLMs) 在众多领域表现卓越，但对输入的微小变化却显得不够稳定。与其将其视为缺点，我们在本文中提出了一种全新的方法，利用模型的不一致性来提升 Pass@k 性能指标。具体来说，我们引入了一位“Variator”代理，它可以为给定任务生成 k 个变体，并为每个变体提交一个候选解决方案。我们的变体生成方法适用于广泛的领域，因为它与具体任务无关，并且能够处理自由格式的输入。我们通过一个基于不一致性效应的概率模型，从理论上证明了我们代理的有效性，并在 APPS 数据集上实证展示了其性能优于基线模型。此外，我们还发现，即使是在前沿推理模型中，不一致性在编码和网络安全领域依然存在，这表明我们的方法很可能在未来模型中仍然具有相关性。


> Large language models (LLMs) achieve impressive abilities in numerous domains, but exhibit inconsistent performance in response to minor input changes. Rather than view this as a drawback, in this paper we introduce a novel method for leveraging models' inconsistency to boost Pass@k performance. Specifically, we present a "Variator" agent that generates k variants of a given task and submits one candidate solution for each one. Our variant generation approach is applicable to a wide range of domains as it is task agnostic and compatible with free-form inputs. We demonstrate the efficacy of our agent theoretically using a probabilistic model of the inconsistency effect, and show empirically that it outperforms the baseline on the APPS dataset. Furthermore, we establish that inconsistency persists even in frontier reasoning models across coding and cybersecurity domains, suggesting our method is likely to remain relevant for future model generations.

[Arxiv](https://arxiv.org/abs/2505.12938)