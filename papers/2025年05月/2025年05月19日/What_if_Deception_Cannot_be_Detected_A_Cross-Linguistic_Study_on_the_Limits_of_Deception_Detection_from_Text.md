# 欺骗难以察觉？跨语言研究揭示文本欺骗检测的局限性

发布时间：2025年05月19日

`LLM应用` `欺骗检测`

> What if Deception Cannot be Detected? A Cross-Linguistic Study on the Limits of Deception Detection from Text

# 摘要

> 仅凭书面文本能否检测出欺骗？欺骗性交流的线索本质上是微妙的，尤其是在仅限于文本的交流中更是如此。然而，先前的研究报告称在自动欺骗检测方面取得了相当大的成功。我们假设这些发现主要源于数据收集过程中引入的人为因素，并不适用于特定数据集之外的场景。我们通过引入一个基于信念的欺骗框架重新审视这一假设，该框架将欺骗定义为作者的主张与其真实信念之间的不一致，无论事实准确性如何，从而允许孤立地研究欺骗线索。基于此框架，我们构建了三个语料库，统称为DeFaBel，包括一个德语的欺骗与非欺骗性论点语料库及其德语和英语的多语言版本，每个语料库均在不同条件下收集，以考虑信念变化并支持跨语言分析。利用这些语料库，我们评估了常见的欺骗语言线索。在所有三种DeFaBel变体中，这些线索与欺骗标签之间的相关性微乎其微且统计上不显著，这与先前的研究形成鲜明对比，后者将此类线索视为可靠的指标。我们进一步在遵循类似数据收集协议的其他英语欺骗数据集上进行基准测试。虽然某些数据集显示出统计上显著的相关性，但效应量仍然较低，而且关键在于，具有预测性的线索在不同数据集之间并不一致。我们还评估了基于特征的模型、预训练语言模型以及指令微调的大型语言模型在欺骗检测中的表现。尽管某些模型在已建立的欺骗数据集上表现良好，但它们在DeFaBel上的表现始终接近随机水平。我们的研究发现挑战了仅凭语言线索可靠推断欺骗的假设，并呼吁重新思考在自然语言处理中欺骗的研究和建模方式。

> Can deception be detected solely from written text? Cues of deceptive communication are inherently subtle, even more so in text-only communication. Yet, prior studies have reported considerable success in automatic deception detection. We hypothesize that such findings are largely driven by artifacts introduced during data collection and do not generalize beyond specific datasets. We revisit this assumption by introducing a belief-based deception framework, which defines deception as a misalignment between an author's claims and true beliefs, irrespective of factual accuracy, allowing deception cues to be studied in isolation. Based on this framework, we construct three corpora, collectively referred to as DeFaBel, including a German-language corpus of deceptive and non-deceptive arguments and a multilingual version in German and English, each collected under varying conditions to account for belief change and enable cross-linguistic analysis. Using these corpora, we evaluate commonly reported linguistic cues of deception. Across all three DeFaBel variants, these cues show negligible, statistically insignificant correlations with deception labels, contrary to prior work that treats such cues as reliable indicators. We further benchmark against other English deception datasets following similar data collection protocols. While some show statistically significant correlations, effect sizes remain low and, critically, the set of predictive cues is inconsistent across datasets. We also evaluate deception detection using feature-based models, pretrained language models, and instruction-tuned large language models. While some models perform well on established deception datasets, they consistently perform near chance on DeFaBel. Our findings challenge the assumption that deception can be reliably inferred from linguistic cues and call for rethinking how deception is studied and modeled in NLP.

[Arxiv](https://arxiv.org/abs/2505.13147)