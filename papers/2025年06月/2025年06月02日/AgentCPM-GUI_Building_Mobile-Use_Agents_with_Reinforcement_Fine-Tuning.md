# AgentCPM-GUI：通过强化微调构建移动端使用的智能体

发布时间：2025年06月02日

`LLM应用` `移动应用` `GUI交互`

> AgentCPM-GUI: Building Mobile-Use Agents with Reinforcement Fine-Tuning

# 摘要

> 大型语言模型代理的最新进展为通过图形用户界面（GUI）实现任务自动化开辟了新途径，尤其在移动环境中，智能交互能够显著提升用户体验。然而，此类代理的实际应用仍面临多重挑战。现有训练数据常存在噪声且语义多样性不足，这限制了精确接地与规划的学习效果。仅依赖模仿学习的模型往往过度拟合已知界面模式，难以在新场景中泛化。此外，多数先前研究聚焦于英文界面，而忽视了非英文应用的多样性，如中文移动生态系统中的应用。为此，我们推出了AgentCPM-GUI——一个专为设备端GUI交互设计的8B参数代理。我们的训练流程包括感知增强的接地预训练、基于高质量中英文轨迹的监督微调以模仿人类行为，以及利用GRPO进行强化微调以提升推理能力。此外，我们引入了紧凑的动作空间，减少了输出长度，支持移动设备的低延迟执行。AgentCPM-GUI在五个公共基准测试和新的中文GUI基准CAGUI中表现优异，Type-Match和Exact-Match分别达到$96.9\%$和$91.3\%$。为促进研究和再现性，我们公开发布了所有代码、模型检查点和评估数据。


> The recent progress of large language model agents has opened new possibilities for automating tasks through graphical user interfaces (GUIs), especially in mobile environments where intelligent interaction can greatly enhance usability. However, practical deployment of such agents remains constrained by several key challenges. Existing training data is often noisy and lack semantic diversity, which hinders the learning of precise grounding and planning. Models trained purely by imitation tend to overfit to seen interface patterns and fail to generalize in unfamiliar scenarios. Moreover, most prior work focuses on English interfaces while overlooks the growing diversity of non-English applications such as those in the Chinese mobile ecosystem. In this work, we present AgentCPM-GUI, an 8B-parameter GUI agent built for robust and efficient on-device GUI interaction. Our training pipeline includes grounding-aware pre-training to enhance perception, supervised fine-tuning on high-quality Chinese and English trajectories to imitate human-like actions, and reinforcement fine-tuning with GRPO to improve reasoning capability. We also introduce a compact action space that reduces output length and supports low-latency execution on mobile devices. AgentCPM-GUI achieves state-of-the-art performance on five public benchmarks and a new Chinese GUI benchmark called CAGUI, reaching $96.9\%$ Type-Match and $91.3\%$ Exact-Match. To facilitate reproducibility and further research, we publicly release all code, model checkpoint, and evaluation data.

[Arxiv](https://arxiv.org/abs/2506.01391)