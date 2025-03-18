# V-Stylist：MLLM智能体协作与反思驱动的视频风格化

发布时间：2025年03月15日

`LLM应用` `视频处理` `视频编辑`

> V-Stylist: Video Stylization via Collaboration and Reflection of MLLM Agents

# 摘要

> 尽管视频风格化领域近期取得了进展，但现有方法仍难以根据用户开放式的风格描述，生成包含复杂过渡效果的视频。为解决这一难题，我们提出了一种基于多模态大型语言模型新型协作与反思范式的通用多智能体系统——V-Stylist。具体来说，我们的V-Stylist是一个系统化的流程，包含三个关键角色：（1）视频解析器将输入视频分解为若干镜头，并生成各关键镜头内容的文本提示。通过简洁的视频到镜头提示范式，它使V-Stylist能够有效处理包含复杂过渡的视频。（2）风格解析器识别用户查询中的风格，并通过稳健的树状思考搜索范式，从风格树中逐步搜索匹配的风格模型。这使V-Stylist能够精确指定用户查询中模糊的风格偏好。（3）风格艺术家利用匹配的模型，将所有视频镜头渲染为目标风格。通过创新的多轮自我反思范式，它能够根据风格要求自适应调整细节控制。通过这种模拟专业人士的创新设计，V-Stylist在实现有效自动视频风格化的主要挑战上取得了重大突破。此外，我们还构建了一个新的基准测试——文本驱动视频风格化基准（TVSBench），填补了在开放用户查询下评估复杂视频风格化的空白。大量实验证明，V-Stylist达到了当前最优水平，例如在整体平均指标上，V-Stylist分别比FRESCO和ControlVideo高出6.05%和4.51%，标志着视频风格化领域的重要进展。


> Despite the recent advancement in video stylization, most existing methods struggle to render any video with complex transitions, based on an open style description of user query. To fill this gap, we introduce a generic multi-agent system for video stylization, V-Stylist, by a novel collaboration and reflection paradigm of multi-modal large language models. Specifically, our V-Stylist is a systematical workflow with three key roles: (1) Video Parser decomposes the input video into a number of shots and generates their text prompts of key shot content. Via a concise video-to-shot prompting paradigm, it allows our V-Stylist to effectively handle videos with complex transitions. (2) Style Parser identifies the style in the user query and progressively search the matched style model from a style tree. Via a robust tree-of-thought searching paradigm, it allows our V-Stylist to precisely specify vague style preference in the open user query. (3) Style Artist leverages the matched model to render all the video shots into the required style. Via a novel multi-round self-reflection paradigm, it allows our V-Stylist to adaptively adjust detail control, according to the style requirement. With such a distinct design of mimicking human professionals, our V-Stylist achieves a major breakthrough over the primary challenges for effective and automatic video stylization. Moreover,we further construct a new benchmark Text-driven Video Stylization Benchmark (TVSBench), which fills the gap to assess stylization of complex videos on open user queries. Extensive experiments show that, V-Stylist achieves the state-of-the-art, e.g.,V-Stylist surpasses FRESCO and ControlVideo by 6.05% and 4.51% respectively in overall average metrics, marking a significant advance in video stylization.

[Arxiv](https://arxiv.org/abs/2503.12077)