# SpiritSight 代理：一瞥即懂的高级 GUI 代理

发布时间：2025年03月05日

`Agent` `软件工程` `人机交互`

> SpiritSight Agent: Advanced GUI Agent with One Look

# 摘要

> 图形用户界面（GUI）代理在辅助人机交互和自动化用户在数字设备上的导航方面表现出色。理想的GUI代理应具备高精度、低延迟和跨平台兼容性。近期基于视觉的方法通过利用先进的视觉语言模型（VLMs）展现出潜力。尽管它们在跨平台兼容性和低延迟方面表现良好，但基于视觉的GUI代理往往因元素定位的局限性而导致精度较低。

为了解决这一问题，我们提出了$	extbf{SpiritSight}$，一种基于视觉、端到端的GUI代理，在各种GUI平台上 excels 在GUI导航任务中。首先，我们采用可扩展的方法创建了一个多层级、大规模、高质量的GUI数据集，名为$	extbf{GUI-Lasagne}$，赋予SpiritSight强大的GUI理解和定位能力。其次，我们引入了$	extbf{通用块解析（UBP）}$方法，以解决视觉输入在动态高分辨率下的模糊问题，进一步提升SpiritSight对GUI对象的定位能力。

通过这些努力，SpiritSight代理在多样化的GUI基准测试中超越了其他先进方法，展现了其在GUI导航任务中的卓越能力和兼容性。模型可在$\href{https://huggingface.co/SenseLLM/SpiritSight-Agent-8B}{this\ URL}$获取。

> Graphical User Interface (GUI) agents show amazing abilities in assisting human-computer interaction, automating human user's navigation on digital devices. An ideal GUI agent is expected to achieve high accuracy, low latency, and compatibility for different GUI platforms. Recent vision-based approaches have shown promise by leveraging advanced Vision Language Models (VLMs). While they generally meet the requirements of compatibility and low latency, these vision-based GUI agents tend to have low accuracy due to their limitations in element grounding. To address this issue, we propose $\textbf{SpiritSight}$, a vision-based, end-to-end GUI agent that excels in GUI navigation tasks across various GUI platforms. First, we create a multi-level, large-scale, high-quality GUI dataset called $\textbf{GUI-Lasagne}$ using scalable methods, empowering SpiritSight with robust GUI understanding and grounding capabilities. Second, we introduce the $\textbf{Universal Block Parsing (UBP)}$ method to resolve the ambiguity problem in dynamic high-resolution of visual inputs, further enhancing SpiritSight's ability to ground GUI objects. Through these efforts, SpiritSight agent outperforms other advanced methods on diverse GUI benchmarks, demonstrating its superior capability and compatibility in GUI navigation tasks. Models are available at $\href{https://huggingface.co/SenseLLM/SpiritSight-Agent-8B}{this\ URL}$.

[Arxiv](https://arxiv.org/abs/2503.03196)