# 衡量多模态大型语言模型的认知谦逊

发布时间：2025年09月11日

`LLM应用` `基础理论`

> Measuring Epistemic Humility in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）的“幻觉现象”——即生成内容与输入图像不符——在实际应用中存在重大风险，例如视觉问答中的误导信息和决策过程中的不安全错误。现有基准主要测试识别准确率，即评估模型能否从干扰项中选出正确答案。但这忽略了可信AI另一项关键能力：识别所有选项均不正确的情况——这种行为体现了“认知谦逊”。为此，我们提出了全新的幻觉评估基准HumbleBench，旨在测试MLLMs对三种幻觉类型（对象、关系、属性）中“看似合理却不正确”答案的拒绝能力。HumbleBench基于全景场景图数据集构建：我们先利用细粒度场景图标注提取真实实体与关系，再通过GPT-4-Turbo生成多项选择题，最后经过严格的人工筛选。每个问题均包含“以上皆非”选项，要求模型不仅能识别正确的视觉信息，还能判断所有选项均无效的情况。我们在HumbleBench上测试了多种最先进的MLLMs（包括通用模型和专用推理模型），并向社区分享了重要发现与见解。通过引入明确的错误选项拒绝机制，HumbleBench填补了现有评估体系的关键空白，为安全关键场景下MLLM的可靠性提供了更贴合实际的衡量指标。我们已公开代码和数据集，访问链接为https://github.com/maifoundations/HumbleBench。

> Hallucinations in multimodal large language models (MLLMs) -- where the model generates content inconsistent with the input image -- pose significant risks in real-world applications, from misinformation in visual question answering to unsafe errors in decision-making. Existing benchmarks primarily test recognition accuracy, i.e., evaluating whether models can select the correct answer among distractors. This overlooks an equally critical capability for trustworthy AI: recognizing when none of the provided options are correct, a behavior reflecting epistemic humility. We present HumbleBench, a new hallucination benchmark designed to evaluate MLLMs' ability to reject plausible but incorrect answers across three hallucination types: object, relation, and attribute. Built from a panoptic scene graph dataset, we leverage fine-grained scene graph annotations to extract ground-truth entities and relations, and prompt GPT-4-Turbo to generate multiple-choice questions, followed by a rigorous manual filtering process. Each question includes a "None of the above" option, requiring models not only to recognize correct visual information but also to identify when no provided answer is valid. We evaluate a variety of state-of-the-art MLLMs -- including both general-purpose and specialized reasoning models -- on HumbleBench and share valuable findings and insights with the community. By incorporating explicit false-option rejection, HumbleBench fills a key gap in current evaluation suites, providing a more realistic measure of MLLM reliability in safety-critical settings. Our code and dataset are released publicly and can be accessed at https://github.com/maifoundations/HumbleBench.

[Arxiv](https://arxiv.org/abs/2509.09658)