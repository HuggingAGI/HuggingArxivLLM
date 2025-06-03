# 一概而论：跨多模型更新参数化知识

发布时间：2025年05月31日

`LLM应用` `人工智能`

> One for All: Update Parameterized Knowledge Across Multiple Models

# 摘要

> 大型语言模型（LLMs）虽然蕴含丰富知识，但难以保持更新，常导致错误和幻觉。知识编辑作为重新训练的高效替代方案，通过更新特定参数实现精准修改。然而，现有方法多针对单个模型，难以高效更新多个模型或适应新模型。为此，我们提出OnceEdit，这是一种基于集成的全新方法，采用插件模型作为编辑模块，实现多模型的稳定知识更新。基于模型集成，OnceEdit引入两大机制提升效果：首先，通过动态权重机制区分编辑相关与非编辑相关实例，合理利用集成模型知识；其次，加入集成增强机制，缓解对中心模型的过度依赖，提升编辑适用性。实验显示，OnceEdit在多种LLMs上均超越现有方法，同时保持高效编辑。分析表明，其在多模型编辑场景中表现出色，适应性强且稳定。我们的代码即将开源。

> Large language models (LLMs) encode vast world knowledge but struggle to stay up-to-date, often leading to errors and hallucinations. Knowledge editing offers an efficient alternative to retraining, enabling targeted modifications by updating specific model parameters. However, existing methods primarily focus on individual models, posing challenges in efficiently updating multiple models and adapting to new models. To address this, we propose OnceEdit, a novel ensemble-based approach that employs a plug-in model as the editing module, enabling stable knowledge updates across multiple models. Building on the model ensemble, OnceEdit introduces two key mechanisms to enhance its effectiveness. First, we introduce a dynamic weight mechanism through a \weight token for distinguishing between edit-related and non-edit-related instances, ensuring the appropriate utilization of knowledge from integrated models. Second, we incorporate an ensemble enhancement mechanism to mitigate the excessive reliance on the central model inherent in the model ensemble technique, making it more suitable for knowledge editing. Extensive experiments on diverse LLMs demonstrate that OnceEdit consistently outperforms existing methods while achieving superior editing efficiency. Further analysis confirms its adaptability and stability in multi-model editing scenarios. Our code will be available.

[Arxiv](https://arxiv.org/abs/2506.00817)