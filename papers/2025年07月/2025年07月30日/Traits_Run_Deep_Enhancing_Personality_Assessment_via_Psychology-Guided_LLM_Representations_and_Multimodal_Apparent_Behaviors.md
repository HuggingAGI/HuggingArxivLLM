# 特质深藏：通过心理学引导的LLM表示和多模态外显行为提升个性评估

发布时间：2025年07月30日

`LLM应用` `心理健康`

> Traits Run Deep: Enhancing Personality Assessment via Psychology-Guided LLM Representations and Multimodal Apparent Behaviors

# 摘要

> 准确可靠的人格评估在情商、心理健康诊断和个性化教育等领域发挥重要作用。与稍纵即逝的情绪不同，人格特质具有稳定性，往往通过语言、面部表情和身体行为潜移默化地流露，且不同模态间存在异步模式。传统表层特征难以建模人格语义，跨模态理解更是难上加难。为应对这些挑战，我们提出了一种名为	extit{	extbf{Traits Run Deep}}的新型人格评估框架。该框架采用	extit{	extbf{心理学引导提示}}，提取高层次与人格相关的语义表示。同时，我们设计了	extit{	extbf{文本中心特质融合网络}}，通过丰富文本语义锚点，实现异步跨模态信号的对齐与融合。具体而言，该融合模块包括一个Chunk-Wise Projector用于降维，一个Cross-Modal Connector和Text Feature Enhancer用于有效模态融合，以及一个集成回归头以提升数据稀缺场景下的泛化能力。据我们所知，我们是首个将人格特定提示应用于引导大型语言模型（LLMs）提取人格感知语义的研究，从而提升表示质量。此外，提取并融合视听显性行为特征进一步提高了准确度。在AVI验证集上的实验结果验证了所提组件的有效性，即均方误差（MSE）降低约45%。最终在AVI Challenge 2025测试集上的评估结果证实了我们方法的优越性，在人格评估赛道中排名第一。源代码将在https://github.com/MSA-LMC/TraitsRunDeep上开放。

> Accurate and reliable personality assessment plays a vital role in many fields, such as emotional intelligence, mental health diagnostics, and personalized education. Unlike fleeting emotions, personality traits are stable, often subconsciously leaked through language, facial expressions, and body behaviors, with asynchronous patterns across modalities. It was hard to model personality semantics with traditional superficial features and seemed impossible to achieve effective cross-modal understanding. To address these challenges, we propose a novel personality assessment framework called \textit{\textbf{Traits Run Deep}}. It employs \textit{\textbf{psychology-informed prompts}} to elicit high-level personality-relevant semantic representations. Besides, it devises a \textit{\textbf{Text-Centric Trait Fusion Network}} that anchors rich text semantics to align and integrate asynchronous signals from other modalities. To be specific, such fusion module includes a Chunk-Wise Projector to decrease dimensionality, a Cross-Modal Connector and a Text Feature Enhancer for effective modality fusion and an ensemble regression head to improve generalization in data-scarce situations. To our knowledge, we are the first to apply personality-specific prompts to guide large language models (LLMs) in extracting personality-aware semantics for improved representation quality. Furthermore, extracting and fusing audio-visual apparent behavior features further improves the accuracy. Experimental results on the AVI validation set have demonstrated the effectiveness of the proposed components, i.e., approximately a 45\% reduction in mean squared error (MSE). Final evaluations on the test set of the AVI Challenge 2025 confirm our method's superiority, ranking first in the Personality Assessment track. The source code will be made available at https://github.com/MSA-LMC/TraitsRunDeep.

[Arxiv](https://arxiv.org/abs/2507.22367)