# FixDrive：自动修复自动驾驶汽车的驾驶行为，每违规只需0.08美元

发布时间：2025年02月12日

`Agent` `自动驾驶` `人工智能`

> FixDrive: Automatically Repairing Autonomous Vehicle Driving Behaviour for $0.08 per Violation

# 摘要

> 自动驾驶汽车（AVs）正快速发展，Level-4 AV已投入实际运行。然而，当前的AV在适应性和性能上仍逊色于人类司机，常显保守甚至违规。现有方案如运行时强制措施虽能自动修复AV轨迹，但缺乏透明度，应属最后手段。我们提出FixDrive框架，通过分析险些事故或违规记录，生成修复策略以减少同类事件复发。这些修复采用高级领域特定语言μDrive，用于基于事件触发的驾驶行为指定。应用于先进自动驾驶系统Apollo，FixDrive可识别并可视化驾驶记录中的关键节点，并借助零样本学习的多模态大型语言模型（MLLM）生成μDrive程序。测试表明，FixDrive显著提升了AV在守法、避障及成功抵达目的地方面的表现。此外，修复AV的直接成本——15分钟离线分析和每违规0.08美元——极具实践价值。


> Autonomous Vehicles (AVs) are advancing rapidly, with Level-4 AVs already operating in real-world conditions. Current AVs, however, still lag behind human drivers in adaptability and performance, often exhibiting overly conservative behaviours and occasionally violating traffic laws. Existing solutions, such as runtime enforcement, mitigate this by automatically repairing the AV's planned trajectory at runtime, but such approaches lack transparency and should be a measure of last resort. It would be preferable for AV repairs to generalise beyond specific incidents and to be interpretable for users. In this work, we propose FixDrive, a framework that analyses driving records from near-misses or law violations to generate AV driving strategy repairs that reduce the chance of such incidents occurring again. These repairs are captured in μDrive, a high-level domain-specific language for specifying driving behaviours in response to event-based triggers. Implemented for the state-of-the-art autonomous driving system Apollo, FixDrive identifies and visualises critical moments from driving records, then uses a Multimodal Large Language Model (MLLM) with zero-shot learning to generate μDrive programs. We tested FixDrive on various benchmark scenarios, and found that the generated repairs improved the AV's performance with respect to following traffic laws, avoiding collisions, and successfully reaching destinations. Furthermore, the direct costs of repairing an AV -- 15 minutes of offline analysis and $0.08 per violation -- are reasonable in practice.

[Arxiv](https://arxiv.org/abs/2502.08260)