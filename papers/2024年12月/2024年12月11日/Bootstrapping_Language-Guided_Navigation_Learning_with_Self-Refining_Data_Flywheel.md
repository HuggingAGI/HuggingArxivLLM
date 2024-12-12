# 利用自精炼数据飞轮来促进语言引导的导航学习

发布时间：2024年12月11日

`Agent` `具身人工智能` `导航学习`

> Bootstrapping Language-Guided Navigation Learning with Self-Refining Data Flywheel

# 摘要

> 在具身人工智能领域，为训练强大的语言指导智能体创造高质量数据一直是个难题。在本文中，我们推出了一种自精炼数据飞轮（SRDF），它能在无需人工参与注释的情况下，通过指令生成器和导航器这两个模型的协作，迭代精炼数据池，进而生成高质量、大规模的导航指令-轨迹对。具体而言，SRDF 先利用基础生成器创建初始数据池来训练基础导航器，接着运用训练好的导航器对数据池进行筛选。这会带来更高保真的数据，用于训练更出色的生成器，而生成器又能为训练下一轮导航器生成更高质量的数据。如此一来，这个飞轮构建起了数据自精炼流程，为大规模语言引导导航学习打造出持续优化且高效的数据集。我们的实验显示，经过几轮飞轮运转，导航器在经典的 R2R 测试集中将性能边界从 70%提升至 78%的 SPL，首次超越人类性能（76%）。同时，这一过程造就了更卓越的生成器，SPICE 从 23.5 提高到 26.2，优于以往所有的 VLN 指令生成方法。最后，我们通过增加环境和指令的多样性，展示了我们方法的可扩展性，以及预训练的导航器在各类下游导航任务中的泛化能力，在所有情形下都大幅优于最先进的方法。

> Creating high-quality data for training robust language-instructed agents is a long-lasting challenge in embodied AI. In this paper, we introduce a Self-Refining Data Flywheel (SRDF) that generates high-quality and large-scale navigational instruction-trajectory pairs by iteratively refining the data pool through the collaboration between two models, the instruction generator and the navigator, without any human-in-the-loop annotation. Specifically, SRDF starts with using a base generator to create an initial data pool for training a base navigator, followed by applying the trained navigator to filter the data pool. This leads to higher-fidelity data to train a better generator, which can, in turn, produce higher-quality data for training the next-round navigator. Such a flywheel establishes a data self-refining process, yielding a continuously improved and highly effective dataset for large-scale language-guided navigation learning. Our experiments demonstrate that after several flywheel rounds, the navigator elevates the performance boundary from 70% to 78% SPL on the classic R2R test set, surpassing human performance (76%) for the first time. Meanwhile, this process results in a superior generator, evidenced by a SPICE increase from 23.5 to 26.2, better than all previous VLN instruction generation methods. Finally, we demonstrate the scalability of our method through increasing environment and instruction diversity, and the generalization ability of our pre-trained navigator across various downstream navigation tasks, surpassing state-of-the-art methods by a large margin in all cases.

[Arxiv](https://arxiv.org/abs/2412.08467)