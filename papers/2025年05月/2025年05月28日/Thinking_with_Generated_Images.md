# # 生成图像中的思考艺术

发布时间：2025年05月28日

`LLM应用` `视觉推理` `人工智能`

> Thinking with Generated Images

# 摘要

> 我们提出了一种全新的范式——“基于生成图像的思考”（Thinking with Generated Images），它从根本上改变了大型多模态模型（LMMs）处理视觉推理的方式。通过自动生成中间视觉思考步骤，使模型能够在文本与视觉模态之间进行原生的跨模态推理。目前，基于LMMs的视觉推理要么受限于处理用户提供的固定图像，要么仅通过基于文本的思考链（CoT）进行推理。而“基于生成图像的思考”开启了一种全新的认知维度，使模型能够主动构建中间视觉思考，自我批判视觉假设，并将其作为推理过程中的关键环节进行优化。我们通过两种互补机制展示了这一方法的有效性：(1) 带有中间视觉子目标的视觉生成，其中模型将复杂的视觉任务分解为可管理的组件，并逐步生成和整合这些组件；(2) 带有自我批判的视觉生成，模型首先生成初始视觉假设，通过文本推理分析其不足，并基于自我批判生成优化的输出。在视觉生成基准测试中，我们的方法相较于基线方法取得了显著提升，模型在处理复杂多物体场景时的性能相对提升了高达50%（从38%提升至57%）。无论是生物化学家探索新型蛋白质结构，建筑师迭代空间设计，法医分析师重构犯罪现场，还是篮球运动员构思战术布局，我们的方法使AI模型能够进行人类创造力、分析能力和战略思维所具有的那种视觉想象和迭代优化。我们开源了我们的工具包，地址为https://github.com/GAIR-NLP/thinking-with-generated-images。

> We present Thinking with Generated Images, a novel paradigm that fundamentally transforms how large multimodal models (LMMs) engage with visual reasoning by enabling them to natively think across text and vision modalities through spontaneous generation of intermediate visual thinking steps. Current visual reasoning with LMMs is constrained to either processing fixed user-provided images or reasoning solely through text-based chain-of-thought (CoT). Thinking with Generated Images unlocks a new dimension of cognitive capability where models can actively construct intermediate visual thoughts, critique their own visual hypotheses, and refine them as integral components of their reasoning process. We demonstrate the effectiveness of our approach through two complementary mechanisms: (1) vision generation with intermediate visual subgoals, where models decompose complex visual tasks into manageable components that are generated and integrated progressively, and (2) vision generation with self-critique, where models generate an initial visual hypothesis, analyze its shortcomings through textual reasoning, and produce refined outputs based on their own critiques. Our experiments on vision generation benchmarks show substantial improvements over baseline approaches, with our models achieving up to 50% (from 38% to 57%) relative improvement in handling complex multi-object scenarios. From biochemists exploring novel protein structures, and architects iterating on spatial designs, to forensic analysts reconstructing crime scenes, and basketball players envisioning strategic plays, our approach enables AI models to engage in the kind of visual imagination and iterative refinement that characterizes human creative, analytical, and strategic thinking. We release our open-source suite at https://github.com/GAIR-NLP/thinking-with-generated-images.

[Arxiv](https://arxiv.org/abs/2505.22525)