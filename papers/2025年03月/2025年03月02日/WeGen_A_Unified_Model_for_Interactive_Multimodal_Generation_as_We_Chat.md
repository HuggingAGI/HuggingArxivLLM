# WeGen：统一交互式多模态生成模型，像我们聊天一样自然

发布时间：2025年03月02日

`LLM应用

摘要中提到WeGen是一个多模态生成模型，旨在作为设计副驾驶，帮助用户生成和细化设计输出。它结合了生成与理解，并在迭代过程中促进两者交互，以满足用户需求。这属于大型语言模型的应用，特别是在设计辅助领域的应用。` `视觉设计`

> WeGen: A Unified Model for Interactive Multimodal Generation as We Chat

# 摘要

> 现有的多模态生成模型难以成为合格的设计副驾驶，因为它们常常在指令不够详细时难以生成富有想象力的输出，或者缺乏与提供的参考保持一致的能力。在此工作中，我们引入了WeGen，一个统一多模态生成与理解，并在迭代生成过程中促进两者交互的模型。它可以为不够详细的指令生成多样化且富有创造力的结果。并且可以根据用户对话中的指令逐步细化先前的生成结果或整合参考中的特定内容。在此过程中，它能够保留用户已满意部分的一致性。为此，我们整理了一个大规模数据集，从互联网视频中提取，包含丰富的物体动态以及通过先进基础模型自动标注的动态描述。这两部分信息交织成一个单一序列，使WeGen能够学习一致性感知生成，即在生成指定动态的同时，保持未指定内容与指令的一致性。此外，我们引入了提示自我重写机制以增强生成多样性。大量实验表明WeGen中统一多模态理解和生成的有效性，并在各种视觉生成基准上实现了最先进的性能。这些结果还展示了WeGen作为用户友好型设计副驾驶的潜力。代码和模型将在https://github.com/hzphzp/WeGen上提供。

> Existing multimodal generative models fall short as qualified design copilots, as they often struggle to generate imaginative outputs once instructions are less detailed or lack the ability to maintain consistency with the provided references. In this work, we introduce WeGen, a model that unifies multimodal generation and understanding, and promotes their interplay in iterative generation. It can generate diverse results with high creativity for less detailed instructions. And it can progressively refine prior generation results or integrating specific contents from references following the instructions in its chat with users. During this process, it is capable of preserving consistency in the parts that the user is already satisfied with. To this end, we curate a large-scale dataset, extracted from Internet videos, containing rich object dynamics and auto-labeled dynamics descriptions by advanced foundation models to date. These two information are interleaved into a single sequence to enable WeGen to learn consistency-aware generation where the specified dynamics are generated while the consistency of unspecified content is preserved aligned with instructions. Besides, we introduce a prompt self-rewriting mechanism to enhance generation diversity. Extensive experiments demonstrate the effectiveness of unifying multimodal understanding and generation in WeGen and show it achieves state-of-the-art performance across various visual generation benchmarks. These also demonstrate the potential of WeGen as a user-friendly design copilot as desired. The code and models will be available at https://github.com/hzphzp/WeGen.

[Arxiv](https://arxiv.org/abs/2503.01115)