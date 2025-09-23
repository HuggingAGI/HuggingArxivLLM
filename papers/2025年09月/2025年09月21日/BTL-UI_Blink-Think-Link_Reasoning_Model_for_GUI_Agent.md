# BTL-UI：瞬视-思考-连接推理模型（面向GUI智能体）

发布时间：2025年09月21日

`Agent` `基础理论`

> BTL-UI: Blink-Think-Link Reasoning Model for GUI Agent

# 摘要

> 在AI驱动的人机图形用户界面（GUI）交互自动化领域，尽管多模态大型语言模型和强化微调技术发展迅猛，成果斐然，但一个核心难题始终存在：它们的交互逻辑与人类自然的GUI交互模式相去甚远。为填补这一空白，我们提出了“Blink-Think-Link”（BTL）——一个受大脑启发的人机GUI交互框架，它模拟了用户与图形界面交互时的人类认知过程。该系统将交互拆解为三个符合生物认知规律的阶段：（1）Blink（扫视）——快速定位并聚焦相关屏幕区域，类比人类眼球的扫视运动；（2）Think（思考）——进行高层次推理与决策，映射认知规划过程；（3）Link（连接）——生成精确运动控制所需的可执行命令，模拟人类的动作选择机制。此外，我们为BTL框架引入了两项关键技术创新：（1）Blink数据生成——专为扫视数据优化的自动化标注流水线；（2）BTL奖励机制——首个基于规则、同时结合过程与结果驱动强化学习的奖励机制。基于该框架，我们开发了名为BTL-UI的GUI智能体模型。在综合基准测试中，该模型在静态GUI理解和动态交互任务上均展现出持续领先的性能，为BTL框架在开发先进GUI智能体方面的有效性提供了确凿的实证支持。

> In the field of AI-driven human-GUI interaction automation, while rapid advances in multimodal large language models and reinforcement fine-tuning techniques have yielded remarkable progress, a fundamental challenge persists: their interaction logic significantly deviates from natural human-GUI communication patterns. To fill this gap, we propose "Blink-Think-Link" (BTL), a brain-inspired framework for human-GUI interaction that mimics the human cognitive process between users and graphical interfaces. The system decomposes interactions into three biologically plausible phases: (1) Blink - rapid detection and attention to relevant screen areas, analogous to saccadic eye movements; (2) Think - higher-level reasoning and decision-making, mirroring cognitive planning; and (3) Link - generation of executable commands for precise motor control, emulating human action selection mechanisms. Additionally, we introduce two key technical innovations for the BTL framework: (1) Blink Data Generation - an automated annotation pipeline specifically optimized for blink data, and (2) BTL Reward -- the first rule-based reward mechanism that enables reinforcement learning driven by both process and outcome. Building upon this framework, we develop a GUI agent model named BTL-UI, which demonstrates consistent state-of-the-art performance across both static GUI understanding and dynamic interaction tasks in comprehensive benchmarks. These results provide conclusive empirical validation of the framework's efficacy in developing advanced GUI Agents.

[Arxiv](https://arxiv.org/abs/2509.15566)