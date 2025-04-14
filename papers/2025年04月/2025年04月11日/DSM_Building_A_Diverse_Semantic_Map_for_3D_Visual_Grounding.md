# DSM：构建多样化语义地图在三维视觉定位中的应用

发布时间：2025年04月11日

`LLM应用

理由：这篇论文探讨了多模态大语言模型（VLMs）在机器人场景理解任务中的应用，特别是在3D视觉定位任务中的应用。论文提出了一种多样化语义地图构建方法，利用VLMs捕捉场景中的语义信息，并通过几何滑动窗口策略创建多样化语义地图。该方法在实验中表现出优于现有方法的结果，并在实际机器人任务中得到验证。因此，这篇论文属于LLM应用类别，因为它展示了VLMs在具体任务中的应用和效果。` `机器人`

> DSM: Building A Diverse Semantic Map for 3D Visual Grounding

# 摘要

> 近年来，多模态大语言模型（VLMs）在机器人领域的研究和应用日益广泛，特别是在机器人场景理解任务中。现有用于3D视觉定位任务的VLMs方法主要依赖几何和视觉信息获取场景信息，却忽视了对场景中多样化语义信息的提取以及对物体外观、物理特性和可承受性等丰富隐式语义属性的理解。结合几何和语言的3D场景图是环境感知的理想表示方法，也是语言模型在3D视觉定位任务中的有效载体。针对这些不足，我们提出了一种专门针对执行3D视觉定位任务的机器人代理的多样化语义地图构建方法。该方法利用VLMs捕捉场景中物体的潜在语义属性和关系，并通过几何滑动窗口地图构建策略创建多样化语义地图（DSM）。基于DSM，我们增强了对定位信息的理解，并提出了一种名为DSM-Grounding的新方法。实验结果表明，我们的方法在语义分割和3D视觉定位等任务中优于现有方法，特别是在整体指标上优于最先进的方法。此外，我们已在机器人上部署了该方法，验证了其在导航和抓取任务中的有效性。

> In recent years, with the growing research and application of multimodal large language models (VLMs) in robotics, there has been an increasing trend of utilizing VLMs for robotic scene understanding tasks. Existing approaches that use VLMs for 3D Visual Grounding tasks often focus on obtaining scene information through geometric and visual information, overlooking the extraction of diverse semantic information from the scene and the understanding of rich implicit semantic attributes, such as appearance, physics, and affordance. The 3D scene graph, which combines geometry and language, is an ideal representation method for environmental perception and is an effective carrier for language models in 3D Visual Grounding tasks. To address these issues, we propose a diverse semantic map construction method specifically designed for robotic agents performing 3D Visual Grounding tasks. This method leverages VLMs to capture the latent semantic attributes and relations of objects within the scene and creates a Diverse Semantic Map (DSM) through a geometry sliding-window map construction strategy. We enhance the understanding of grounding information based on DSM and introduce a novel approach named DSM-Grounding. Experimental results show that our method outperforms current approaches in tasks like semantic segmentation and 3D Visual Grounding, particularly excelling in overall metrics compared to the state-of-the-art. In addition, we have deployed this method on robots to validate its effectiveness in navigation and grasping tasks.

[Arxiv](https://arxiv.org/abs/2504.08307)