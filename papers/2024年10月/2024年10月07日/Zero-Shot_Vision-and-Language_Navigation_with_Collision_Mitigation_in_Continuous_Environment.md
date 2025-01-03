# 连续环境下的零-shot 视觉与语言导航及碰撞缓解

发布时间：2024年10月07日

`Agent

理由：这篇论文描述了一个由多个模块组成的系统，用于视觉与语言导航，并特别关注碰撞缓解。该系统利用大型基础模型（如ChatGPT和CLIP）来预测移动方向和距离，并通过模块化的方式实现导航任务。这种系统可以被视为一个智能代理（Agent），因为它能够根据环境信息和指令自主决策并执行导航任务。因此，将其分类为Agent是合适的。` `机器人导航` `计算机视觉`

> Zero-Shot Vision-and-Language Navigation with Collision Mitigation in Continuous Environment

# 摘要

> 我们提出了零-shot视觉与语言导航与碰撞缓解（VLN-CM），它考虑了这些因素。VLN-CM由四个模块组成，每一步预测下一个移动的方向和距离。我们为每个模块利用大型基础模型。选择方向时，我们使用注意力点预测器（ASP）、视图选择器（VS）和进度监视器（PM）。ASP使用大型语言模型（如ChatGPT）将导航指令分割成注意力点，这些点是移动目标位置的对象或场景（如一扇黄色的门）。VS从每30度间隔的全景图像中选择包含注意力点的图像，使用CLIP相似度。然后选择所选图像的角度作为移动方向。PM使用基于规则的方法决定在多个注意力点中接下来关注哪一个。如果当前注意力点与视觉观察的相似度连续下降，PM确定代理已通过当前点并移动到下一个点。选择移动距离时，我们使用开放地图预测器（OMP）。OMP利用全景深度信息预测占用掩码，基于占用掩码在预测方向上选择无碰撞距离。我们使用VLN-CE的验证数据评估了方法，结果显示优于多种基线方法，且OMP在缓解代理碰撞方面效果显著。

> We propose the zero-shot Vision-and-Language Navigation with Collision Mitigation (VLN-CM), which takes these considerations. VLN-CM is composed of four modules and predicts the direction and distance of the next movement at each step. We utilize large foundation models for each modules. To select the direction, we use the Attention Spot Predictor (ASP), View Selector (VS), and Progress Monitor (PM). The ASP employs a Large Language Model (e.g. ChatGPT) to split navigation instructions into attention spots, which are objects or scenes at the location to move to (e.g. a yellow door). The VS selects from panorama images provided at 30-degree intervals the one that includes the attention spot, using CLIP similarity. We then choose the angle of the selected image as the direction to move in. The PM uses a rule-based approach to decide which attention spot to focus on next, among multiple spots derived from the instructions. If the similarity between the current attention spot and the visual observations decreases consecutively at each step, the PM determines that the agent has passed the current spot and moves on to the next one. For selecting the distance to move, we employed the Open Map Predictor (OMP). The OMP uses panorama depth information to predict an occupancy mask. We then selected a collision-free distance in the predicted direction based on the occupancy mask. We evaluated our method using the validation data of VLN-CE. Our approach showed better performance than several baseline methods, and the OPM was effective in mitigating collisions for the agent.

[Arxiv](https://arxiv.org/abs/2410.17267)