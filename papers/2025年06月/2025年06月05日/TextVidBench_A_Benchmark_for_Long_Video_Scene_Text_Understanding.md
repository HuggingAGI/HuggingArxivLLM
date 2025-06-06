# TextVidBench：面向长视频场景文本理解的基准测试平台

发布时间：2025年06月05日

`LLM应用`

> TextVidBench: A Benchmark for Long Video Scene Text Understanding

# 摘要

> 尽管近期在短视频文本视觉问答（ViteVQA）任务上取得了进展，但现有数据集仍存在视频时长有限和评估范围狭窄的问题，难以充分评估多模态大语言模型的能力。为了解决这些问题，我们推出了TextVidBench——首个专注于长视频文本问答（>3分钟）的基准测试。

TextVidBench在三个方面做出了重要贡献：
1) 跨领域长视频覆盖：涵盖新闻、体育、游戏等9个类别，平均视频时长2306秒，更真实地评估长视频理解能力。
2) 三阶段评估框架：“文本针在 haystack 中 -> 时间定位 -> 文本动态描述”。
3) 高质量细粒度标注：包含5,000多个问答对，并附有详细语义标签。

我们还提出了一种改进大模型的高效范式：
- 引入IT-Rope机制和时间提示工程，增强时间感知能力
- 采用非均匀位置编码，更好地处理长视频序列
- 在视频文本数据上应用轻量级微调

实验表明，TextVidBench为现有模型带来了重大挑战，而我们的方法为提升长视频场景下的文本理解能力提供了有价值的见解。

> Despite recent progress on the short-video Text-Visual Question Answering (ViteVQA) task - largely driven by benchmarks such as M4-ViteVQA - existing datasets still suffer from limited video duration and narrow evaluation scopes, making it difficult to adequately assess the growing capabilities of powerful multimodal large language models (MLLMs). To address these limitations, we introduce TextVidBench, the first benchmark specifically designed for long-video text question answering (>3 minutes). TextVidBench makes three key contributions: 1) Cross-domain long-video coverage: Spanning 9 categories (e.g., news, sports, gaming), with an average video length of 2306 seconds, enabling more realistic evaluation of long-video understanding. 2) A three-stage evaluation framework: "Text Needle-in-Haystack -> Temporal Grounding -> Text Dynamics Captioning". 3) High-quality fine-grained annotations: Containing over 5,000 question-answer pairs with detailed semantic labeling. Furthermore, we propose an efficient paradigm for improving large models through: (i) introducing the IT-Rope mechanism and temporal prompt engineering to enhance temporal perception, (ii) adopting non-uniform positional encoding to better handle long video sequences, and (iii) applying lightweight fine-tuning on video-text data. Extensive experiments on multiple public datasets as well as TextVidBench demonstrate that our new benchmark presents significant challenges to existing models, while our proposed method offers valuable insights into improving long-video scene text understanding capabilities.

[Arxiv](https://arxiv.org/abs/2506.04983)