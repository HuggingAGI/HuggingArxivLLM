# CyberV：视频理解测试时的扩展控制论

发布时间：2025年06月09日

`LLM应用` `视频处理` `人工智能`

> CyberV: Cybernetics for Test-time Scaling in Video Understanding

# 摘要

> 当前多模态大型语言模型（MLLMs）在处理长视频或复杂视频时面临挑战，主要由于其前馈处理特性导致的测试时计算需求高、鲁棒性不足和准确性有限。参数较少的模型可能受这些限制更为严重。为了解决这些问题，我们提出了一种受控制论启发的新框架，将视频MLLMs重新设计为具备自监控、自修正和动态资源分配能力的自适应系统。

我们的方法CyberV引入了一个包含MLLM推理系统、传感器和控制器的控制回路。传感器实时监控MLLM的前向过程，收集注意力漂移等中间解释信息。控制器则根据这些信息，决定何时触发自修正机制，并生成反馈指导下一轮推理。这一测试时自适应缩放框架无需重新训练或添加组件，即可显著增强冻结的MLLMs性能。

实验结果表明，CyberV在VideoMMMU基准测试中将Qwen2.5-VL-7B的性能提升了8.3%，将InternVL3-8B提升了5.5%，超越了竞争力强劲的专有模型GPT-4o。应用于Qwen2.5-VL-72B时，性能提升更是达到10.0%，甚至可与人类专家相媲美。此外，CyberV在VideoMME和WorldSense等通用基准测试上也表现出色，充分证明了其在提升MLLMs对动态视频理解的鲁棒性和准确性方面的有效性与泛化能力。

项目代码已开源，地址为https://github.com/marinero4972/CyberV。


> Current Multimodal Large Language Models (MLLMs) may struggle with understanding long or complex videos due to computational demands at test time, lack of robustness, and limited accuracy, primarily stemming from their feed-forward processing nature. These limitations could be more severe for models with fewer parameters. To address these limitations, we propose a novel framework inspired by cybernetic principles, redesigning video MLLMs as adaptive systems capable of self-monitoring, self-correction, and dynamic resource allocation during inference. Our approach, CyberV, introduces a cybernetic loop consisting of an MLLM Inference System, a Sensor, and a Controller. Specifically, the sensor monitors forward processes of the MLLM and collects intermediate interpretations, such as attention drift, then the controller determines when and how to trigger self-correction and generate feedback to guide the next round. This test-time adaptive scaling framework enhances frozen MLLMs without requiring retraining or additional components. Experiments demonstrate significant improvements: CyberV boosts Qwen2.5-VL-7B by 8.3% and InternVL3-8B by 5.5% on VideoMMMU, surpassing the competitive proprietary model GPT-4o. When applied to Qwen2.5-VL-72B, it yields a 10.0% improvement, achieving performance even comparable to human experts. Furthermore, our method demonstrates consistent gains on general-purpose benchmarks, such as VideoMME and WorldSense, highlighting its effectiveness and generalization capabilities in making MLLMs more robust and accurate for dynamic video understanding. The code is released at https://github.com/marinero4972/CyberV.

[Arxiv](https://arxiv.org/abs/2506.07971)