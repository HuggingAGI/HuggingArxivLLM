# LLM-Pack：物流应用中直观的生鲜处理方案

发布时间：2025年03月11日

`LLM应用` `机器人`

> LLM-Pack: Intuitive Grocery Handling for Logistics Applications

# 摘要

> 机器人和自动化在物流领域发挥着越来越重要的作用，但目前仍主要局限于传统的仓库环境中。在 grocery 零售方面，虽然 cashier-less 超市等创新已经出现，但顾客仍然需要手动挑选和打包 groceries。尽管机器人领域对 bin picking 问题投入了大量关注，但打包 objects 和 groceries 的任务却鲜有触及。然而，以正确的顺序打包 grocery 物品对于防止产品损坏至关重要，例如，重物不应放置在易碎物品之上。然而，确定正确的打包顺序的具体标准却十分困难，尤其是考虑到商店中物品的多样性。在本文中，我们介绍了 LLM-Pack，这是一种全新的 grocery 打包方法。LLM-Pack 结合了语言和视觉基础模型，用于识别 groceries 并生成一个打包序列，模拟人类的打包策略。LLM-Pack 无需专门训练即可处理新的 grocery 物品，其模块化设计使得底层基础模型的升级变得轻松。我们对我们的方法进行了全面评估，以展示其性能。我们将在本文发表时公开 LLM-Pack 的源代码。

> Robotics and automation are increasingly influential in logistics but remain largely confined to traditional warehouses. In grocery retail, advancements such as cashier-less supermarkets exist, yet customers still manually pick and pack groceries. While there has been a substantial focus in robotics on the bin picking problem, the task of packing objects and groceries has remained largely untouched. However, packing grocery items in the right order is crucial for preventing product damage, e.g., heavy objects should not be placed on top of fragile ones. However, the exact criteria for the right packing order are hard to define, in particular given the huge variety of objects typically found in stores. In this paper, we introduce LLM-Pack, a novel approach for grocery packing. LLM-Pack leverages language and vision foundation models for identifying groceries and generating a packing sequence that mimics human packing strategy. LLM-Pack does not require dedicated training to handle new grocery items and its modularity allows easy upgrades of the underlying foundation models. We extensively evaluate our approach to demonstrate its performance. We will make the source code of LLMPack publicly available upon the publication of this manuscript.

[Arxiv](https://arxiv.org/abs/2503.08445)