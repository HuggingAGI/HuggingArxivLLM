# 利用生成预训练变压器（GPT）生成数据中心数据包跟踪

发布时间：2025年01月21日

`LLM应用

理由：该论文摘要描述了使用生成预训练变换器（GPT）架构来生成数据中心流量痕迹，这是一种将大型语言模型（LLM）应用于特定领域（数据中心流量生成）的实际应用。因此，它属于“LLM应用”类别。` `数据中心` `流量优化`

> Harnessing Generative Pre-Trained Transformer for Datacenter Packet Trace Generation

# 摘要

> 如今，依赖数据中心的应用程序快速增长，亟需技术进步以满足日益增长的流量和计算需求。数据中心的流量痕迹对未来的发展和优化至关重要，但这些痕迹很少公开。研究人员通常使用简化的数学模型，这些模型无法重现复杂的流量模式，从而错失实际流量中的优化机会。在本研究中，我们推出了DTG-GPT，一种基于生成预训练变换器（GPT）架构的数据包级数据中心流量生成器。我们在少量来自不同领域的流量痕迹上训练模型，并提供了一种简单的方法来评估生成痕迹与原始痕迹的保真度。结果表明，DTG-GPT能够合成新的痕迹，模仿真实流量中的时空模式，并且可以为不同规模的网络生成痕迹，同时保持高保真度。我们的发现表明，未来类似的DTG-GPT模型将帮助数据中心运营商通过训练好的GPT模型向研究社区发布流量信息。

> Today, the rapid growth of applications reliant on datacenters calls for new advancements to meet the increasing traffic and computational demands. Traffic traces from datacenters are essential for further development and optimization of future datacenters. However, traces are rarely released to the public. Researchers often use simplified mathematical models that lack the depth needed to recreate intricate traffic patterns and, thus, miss optimization opportunities found in realistic traffic. In this preliminary work, we introduce DTG-GPT, a packet-level Datacenter Traffic Generator (DTG), based on the generative pre-trained transformer (GPT) architecture used by many state-of-the-art large language models. We train our model on a small set of available traffic traces from different domains and offer a simple methodology to evaluate the fidelity of the generated traces to their original counterparts. We show that DTG-GPT can synthesize novel traces that mimic the spatiotemporal patterns found in real traffic traces. We further demonstrate that DTG-GPT can generate traces for networks of different scales while maintaining fidelity. Our findings indicate the potential that, in the future, similar models to DTG-GPT will allow datacenter operators to release traffic information to the research community via trained GPT models.

[Arxiv](https://arxiv.org/abs/2501.12033)