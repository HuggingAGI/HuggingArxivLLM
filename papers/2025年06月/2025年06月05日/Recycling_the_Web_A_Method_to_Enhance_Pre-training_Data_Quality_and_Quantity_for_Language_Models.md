# 网络重生：提升语言模型预训练数据质与量的创新方法

发布时间：2025年06月05日

`LLM应用` `机器学习`

> Recycling the Web: A Method to Enhance Pre-training Data Quality and Quantity for Language Models

# 摘要

> 扩展规律表明，大型语言模型的性能随着模型规模和数据规模的增加而提升。然而，预训练中依赖的大规模网络爬取数据增长速度与计算资源供应并不同步，且高质量文本的可用性更是有限：数据过滤管道通常会移除高达99%的初始网络抓取内容。为应对预训练中的“数据瓶颈”，我们提出了REWIRE（通过引导重写来循环利用网络内容），一种将低质量文档转化为可用训练数据的方法。实验表明，在DCLM基准的10亿、30亿和70亿规模上，与仅使用过滤后的网络数据相比，使用高质量原始文本与重写文本的混合在22个任务中分别提升了1.0、1.3和2.5个百分点。进一步分析显示，约82%的混合文本来自对低质量文档的转化。REWIRE在生成合成数据方面优于相关方法，包括维基百科式的改写、问答合成和知识提取。这些结果表明，循环利用网络文本有可能成为一种简单有效的扩展预训练数据的方法。


> Scaling laws predict that the performance of large language models improves with increasing model size and data size. In practice, pre-training has been relying on massive web crawls, using almost all data sources publicly available on the internet so far. However, this pool of natural data does not grow at the same rate as the compute supply. Furthermore, the availability of high-quality texts is even more limited: data filtering pipelines often remove up to 99% of the initial web scrapes to achieve state-of-the-art. To address the "data wall" of pre-training scaling, our work explores ways to transform and recycle data discarded in existing filtering processes. We propose REWIRE, REcycling the Web with guIded REwrite, a method to enrich low-quality documents so that they could become useful for training. This in turn allows us to increase the representation of synthetic data in the final pre-training set. Experiments at 1B, 3B and 7B scales of the DCLM benchmark show that mixing high-quality raw texts and our rewritten texts lead to 1.0, 1.3 and 2.5 percentage points improvement respectively across 22 diverse tasks, compared to training on only filtered web data. Training on the raw-synthetic data mix is also more effective than having access to 2x web data. Through further analysis, we demonstrate that about 82% of the mixed in texts come from transforming lower-quality documents that would otherwise be discarded. REWIRE also outperforms related approaches of generating synthetic data, including Wikipedia-style paraphrasing, question-answer synthesizing and knowledge extraction. These results suggest that recycling web texts holds the potential for being a simple and effective approach for scaling pre-training data.

[Arxiv](https://arxiv.org/abs/2506.04689)