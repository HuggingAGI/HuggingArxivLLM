# # 大型语言模型是否会记住推荐数据集？以MovieLens-1M为例的初步研究

发布时间：2025年05月15日

`LLM应用` `推荐系统` `数据科学`

> Do LLMs Memorize Recommendation Datasets? A Preliminary Study on MovieLens-1M

# 摘要

> 大型语言模型（LLMs）凭借其卓越的自然语言理解和生成能力，正在推荐场景中发挥越来越重要的作用。尽管已有大量研究探索了LLMs在各种推荐任务中的应用，但目前尚无研究专门验证它们是否记住了公开推荐数据集作为其训练数据的一部分。这种现象令人担忧，因为记忆会降低研究结果的泛化能力，基于记忆数据集的基准测试无法保证对未见数据集的泛化效果。此外，记忆还可能放大偏见，例如某些流行物品可能被推荐得比其他物品更频繁。
    
    本研究旨在探讨LLMs是否记住了公开推荐数据集。具体而言，我们选取了GPT 和 Llama两个模型家族，在多个规模上进行了深入研究，重点关注了推荐系统中使用最广泛的数据集之一：MovieLens-1M。首先，我们将数据集记忆定义为通过提示LLMs能够检索到的项目属性、用户画像和用户-项目交互的程度。其次，我们分析了记忆对推荐性能的影响。最后，我们研究了记忆现象是否因模型家族和模型规模而有所不同。研究结果显示，所有模型都对MovieLens-1M数据集表现出一定程度的记忆，且推荐性能与记忆程度密切相关。我们已将所有代码开源发布在：https://github.com/sisinflab/LLM-MemoryInspector

> Large Language Models (LLMs) have become increasingly central to recommendation scenarios due to their remarkable natural language understanding and generation capabilities. Although significant research has explored the use of LLMs for various recommendation tasks, little effort has been dedicated to verifying whether they have memorized public recommendation dataset as part of their training data. This is undesirable because memorization reduces the generalizability of research findings, as benchmarking on memorized datasets does not guarantee generalization to unseen datasets. Furthermore, memorization can amplify biases, for example, some popular items may be recommended more frequently than others.
  In this work, we investigate whether LLMs have memorized public recommendation datasets. Specifically, we examine two model families (GPT and Llama) across multiple sizes, focusing on one of the most widely used dataset in recommender systems: MovieLens-1M. First, we define dataset memorization as the extent to which item attributes, user profiles, and user-item interactions can be retrieved by prompting the LLMs. Second, we analyze the impact of memorization on recommendation performance. Lastly, we examine whether memorization varies across model families and model sizes. Our results reveal that all models exhibit some degree of memorization of MovieLens-1M, and that recommendation performance is related to the extent of memorization. We have made all the code publicly available at: https://github.com/sisinflab/LLM-MemoryInspector

[Arxiv](https://arxiv.org/abs/2505.10212)