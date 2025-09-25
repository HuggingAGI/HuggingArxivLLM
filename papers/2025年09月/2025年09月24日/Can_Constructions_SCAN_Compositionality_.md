# 构式能否“SCAN”组合性？

发布时间：2025年09月24日

`其他` `基础理论`

> Can Constructions "SCAN" Compositionality ?

# 摘要

> 序列到序列模型即便在其他诸多任务中表现卓越，在组合性和系统性泛化方面却存在困难。我们认为，这一局限源于它们未能内化构式——即那些支持能产性重组的常规化形式-意义配对。基于这些发现，我们提出了一种无监督的伪构式挖掘方法：即从训练数据中自动提取的可变槽模板。将该方法应用于SCAN数据集后，我们在分布外拆分上带来了显著增益：ADD JUMP拆分的准确率提升至47.8%，AROUND RIGHT拆分的准确率提升至20.3%，且无需对架构进行任何修改，也无需额外监督。该模型在仅使用40%原始训练数据的情况下，也实现了具有竞争力的性能，体现出优异的数据效率。我们的发现表明，构式感知预处理有望成为替代大量架构或训练机制干预的有效方法。

> Sequence to Sequence models struggle at compositionality and systematic generalisation even while they excel at many other tasks. We attribute this limitation to their failure to internalise constructions conventionalised form meaning pairings that license productive recombination. Building on these insights, we introduce an unsupervised procedure for mining pseudo-constructions: variable-slot templates automatically extracted from training data. When applied to the SCAN dataset, our method yields large gains out-of-distribution splits: accuracy rises to 47.8 %on ADD JUMP and to 20.3% on AROUND RIGHT without any architectural changes or additional supervision. The model also attains competitive performance with? 40% of the original training data, demonstrating strong data efAciency. Our findings highlight the promise of construction-aware preprocessing as an alternative to heavy architectural or training-regime interventions.

[Arxiv](https://arxiv.org/abs/2509.20074)