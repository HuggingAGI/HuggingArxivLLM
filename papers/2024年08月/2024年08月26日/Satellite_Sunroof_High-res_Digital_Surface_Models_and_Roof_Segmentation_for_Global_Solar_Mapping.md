# 卫星天窗：全球太阳能测绘中的高分辨率数字表面模型与屋顶分割

发布时间：2024年08月26日

`其他` `太阳能`

> Satellite Sunroof: High-res Digital Surface Models and Roof Segmentation for Global Solar Mapping

# 摘要

> 摘要：向可再生能源（尤其是太阳能）的过渡是减缓气候变化的关键。谷歌的太阳能 API 能通过航拍图像估算太阳能潜力来助力这一过渡，但其作用受地理覆盖范围的限制。本文提议借助卫星图像拓展 API 的覆盖范围，以实现全球太阳能潜力评估。我们攻克了利用深度学习模型从低分辨率和单一斜视视角构建数字表面模型（DSM）及屋顶实例分割所面临的难题。我们的模型在对齐的卫星和航拍数据集上训练，可生成 25 厘米的 DSM 和屋顶分段。建筑物上 DSM 的平均绝对误差约为 1 米，屋顶坡度误差约为 5 度，屋顶分割的交并比约为 56％，这极大地提升了太阳能 API 促进太阳能应用的潜力。

> 
Abstract:The transition to renewable energy, particularly solar, is key to mitigating climate change. Google's Solar API aids this transition by estimating solar potential from aerial imagery, but its impact is constrained by geographical coverage. This paper proposes expanding the API's reach using satellite imagery, enabling global solar potential assessment. We tackle challenges involved in building a Digital Surface Model (DSM) and roof instance segmentation from lower resolution and single oblique views using deep learning models. Our models, trained on aligned satellite and aerial datasets, produce 25cm DSMs and roof segments. With ~1m DSM MAE on buildings, ~5deg roof pitch error and ~56% IOU on roof segmentation, they significantly enhance the Solar API's potential to promote solar adoption.
    

[Arxiv](https://arxiv.org/pdf/2408.14400)