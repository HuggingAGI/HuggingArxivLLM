# 在狭窄领域中的越狱防御：现有方法的局限及一种新的转录分类器途径

发布时间：2024年12月02日

`LLM应用` `语言模型` `安全防御`

> Jailbreak Defense in a Narrow Domain: Limitations of Existing Methods and a New Transcript-Classifier Approach

# 摘要

> 防御大型语言模型不被越狱，避免其出现一系列广义上的禁止行为，这是个悬而未决的难题。在本文里，我们探讨了仅禁止一组狭义行为时越狱防御的难度。以防止 LLM 协助用户制造炸弹为例展开研究。我们发现，像安全培训、对抗训练以及输入/输出分类器等常见的防御手段都无法彻底解决此问题。为了寻求更优解，我们研发了一种转录分类器防御，其效果优于所测试的基准防御。然而，我们的分类器防御在某些情形下仍会失效，这凸显了即便在狭窄领域，越狱防御也困难重重。

> Defending large language models against jailbreaks so that they never engage in a broadly-defined set of forbidden behaviors is an open problem. In this paper, we investigate the difficulty of jailbreak-defense when we only want to forbid a narrowly-defined set of behaviors. As a case study, we focus on preventing an LLM from helping a user make a bomb. We find that popular defenses such as safety training, adversarial training, and input/output classifiers are unable to fully solve this problem. In pursuit of a better solution, we develop a transcript-classifier defense which outperforms the baseline defenses we test. However, our classifier defense still fails in some circumstances, which highlights the difficulty of jailbreak-defense even in a narrow domain.

[Arxiv](https://arxiv.org/abs/2412.02159)