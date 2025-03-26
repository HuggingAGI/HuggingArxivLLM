# PM4Bench：面向大型视觉语言模型的并行多语言多模态多任务基准测试

发布时间：2025年03月24日

`其他` `多语言` `人工智能`

> PM4Bench: A Parallel Multilingual Multi-Modal Multi-task Benchmark for Large Vision Language Model

# 摘要

> 现有的针对大型视觉语言模型（LVLMs）的多语言基准测试存在语言特定内容偏见、多模态输入格式不统一以及缺乏安全性评估等局限性。为了解决这些问题，我们提出了PM4Bench，这是首个面向LVLMs的并行多语言多模态多任务基准测试。PM4Bench采用跨10种语言的平行语料库设计，支持公平准确的跨语言比较。该基准测试包含文本和查询嵌入图像的视觉场景，要求LVLMs同时具备“看”、“读”和“思考”能力，与现实应用场景相吻合。此外，PM4Bench还加入了安全性评估，弥补现有跨语言基准测试的关键不足。通过PM4Bench，我们对11种主流LVLMs进行了评估，发现了显著的跨语言性能差异，尤其是在视觉场景下，并确定OCR能力是导致这些不平衡的关键因素。我们将在https://github.com/opendatalab/PM4Bench上发布PM4Bench。


> Existing multilingual benchmarks for Large Vision Language Models (LVLMs) suffer from limitations including language-specific content biases, disjointed multimodal input formats, and a lack of safety evaluation. To address these gaps, we propose PM4Bench, the first Parallel Multilingual Multi-Modal Multi-task Benchmark for LVLMs. PM4Bench features a parallel corpus design across 10 languages, enabling fair and accurate cross-lingual comparisons. It includes the vision setting where text and queries are embedded in images, requiring LVLMs to simultaneously "see", "read", and "think", aligning with real-world applications. Additionally, PM\textsuperscript{4}Bench incorporates safety evaluations, addressing critical oversight in existing multilingual benchmarks. Using PM4Bench, we evaluate 11 mainstream LVLMs, revealing significant cross-linguistic performance disparities, particularly in vision settings, and identifying OCR capability as a key determinant of these imbalances. We will release PM4Bench at https://github.com/opendatalab/PM4Bench .

[Arxiv](https://arxiv.org/abs/2503.18484)