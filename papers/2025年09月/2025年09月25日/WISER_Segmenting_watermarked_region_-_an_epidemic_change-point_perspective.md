# WISER：水印区域分割——疫情变化点视角

发布时间：2025年09月25日

`LLM应用` `媒体与娱乐`

> WISER: Segmenting watermarked region - an epidemic change-point perspective

# 摘要

> 随着大型语言模型的普及，内容真实性问题日益凸显，催生了众多水印方案的研发。这些方案可通过特定密钥检测机器生成文本，而无密钥的读者则无法察觉。相应的检测机制通常采用统计假设检验来判断水印是否存在，这一方向已引发广泛研究。然而，对于混合来源文本中具体哪些段落带有水印这一更细粒度的问题，相关研究却较为匮乏：现有方法要么缺乏可扩展性，要么无法为改写和后期编辑提供稳健的理论保证。在本研究中，我们从流行病变化点的视角出发，为这类水印分割问题提供了全新思路。通过剖析两者的异同，我们提出了WISER——一种新颖且计算高效的水印分割算法。理论上，我们通过推导有限样本误差界验证了算法的有效性，并证明其能在单篇文本中一致检测多个水印段落。实验结果进一步表明，在嵌入多种水印方案的各类基准数据集上，WISER在计算速度与准确性上均显著优于现有先进方法。理论与实证研究共同证实，WISER在多数场景下可有效实现水印定位，同时也揭示了经典统计问题的洞见如何为现代实际问题提供理论可靠且计算高效的解决方案。

> With the increasing popularity of large language models, concerns over content authenticity have led to the development of myriad watermarking schemes. These schemes can be used to detect a machine-generated text via an appropriate key, while being imperceptible to readers with no such keys. The corresponding detection mechanisms usually take the form of statistical hypothesis testing for the existence of watermarks, spurring extensive research in this direction. However, the finer-grained problem of identifying which segments of a mixed-source text are actually watermarked, is much less explored; the existing approaches either lack scalability or theoretical guarantees robust to paraphrase and post-editing. In this work, we introduce a unique perspective to such watermark segmentation problems through the lens of epidemic change-points. By highlighting the similarities as well as differences of these two problems, we motivate and propose WISER: a novel, computationally efficient, watermark segmentation algorithm. We theoretically validate our algorithm by deriving finite sample error-bounds, and establishing its consistency in detecting multiple watermarked segments in a single text. Complementing these theoretical results, our extensive numerical experiments show that WISER outperforms state-of-the-art baseline methods, both in terms of computational speed as well as accuracy, on various benchmark datasets embedded with diverse watermarking schemes. Our theoretical and empirical findings establish WISER as an effective tool for watermark localization in most settings. It also shows how insights from a classical statistical problem can lead to a theoretically valid and computationally efficient solution of a modern and pertinent problem.

[Arxiv](https://arxiv.org/abs/2509.21160)