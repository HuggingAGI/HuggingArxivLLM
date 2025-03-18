# # 编辑迁移：通过视觉上下文关系学习图像编辑
编辑迁移：通过视觉上下文关系学习图像编辑

发布时间：2025年03月17日

`其他` `图像处理` `生成模型`

> Edit Transfer: Learning Image Editing via Vision In-Context Relations

# 摘要

> 我们提出了一种名为编辑迁移（Edit Transfer）的新方法，该方法通过学习单一的源-目标示例的转换，将其应用于新的查询图像。虽然基于文本的方法在语义操作方面表现出色，但它们难以处理精确的几何细节。而基于参考的编辑通常专注于风格或外观，难以处理非刚性变换。编辑迁移通过从源-目标对中显式学习编辑变换，克服了纯文本和以外观为中心参考方法的局限性。受大型语言模型中上下文学习的启发，我们提出了一种基于视觉关系的上下文学习范式，基于DiT的文本到图像模型。我们将编辑示例和查询图像排列成一个统一的四面板复合图，然后应用轻量级的LoRA微调，以从极小的示例中捕捉复杂的空间变换。尽管仅使用了42个训练样本，编辑迁移在多样化的非刚性场景中显著优于最先进的TIE和RIE方法，展示了少量样本视觉关系学习的有效性。

> We introduce a new setting, Edit Transfer, where a model learns a transformation from just a single source-target example and applies it to a new query image. While text-based methods excel at semantic manipulations through textual prompts, they often struggle with precise geometric details (e.g., poses and viewpoint changes). Reference-based editing, on the other hand, typically focuses on style or appearance and fails at non-rigid transformations. By explicitly learning the editing transformation from a source-target pair, Edit Transfer mitigates the limitations of both text-only and appearance-centric references. Drawing inspiration from in-context learning in large language models, we propose a visual relation in-context learning paradigm, building upon a DiT-based text-to-image model. We arrange the edited example and the query image into a unified four-panel composite, then apply lightweight LoRA fine-tuning to capture complex spatial transformations from minimal examples. Despite using only 42 training samples, Edit Transfer substantially outperforms state-of-the-art TIE and RIE methods on diverse non-rigid scenarios, demonstrating the effectiveness of few-shot visual relation learning.

[Arxiv](https://arxiv.org/abs/2503.13327)