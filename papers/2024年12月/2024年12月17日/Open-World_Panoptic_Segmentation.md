# 开放世界的全景分割

发布时间：2024年12月17日

`其他` `自动驾驶` `计算机视觉`

> Open-World Panoptic Segmentation

# 摘要

> 感知是诸如自动驾驶汽车这类自主行动视觉系统的关键基石。关键在于，这些系统要能理解周边环境，从而安全、稳健地运行。另外，部署于无约束现实世界场景中的自主系统，必须能够应对此前从未见过的新情况和新对象。在本文中，我们处理了开放世界全景分割的问题，即测试时发现新的语义类别和新的对象实例这一任务，同时在我们逐步发现的类别间强制保持一致性。我们提出了 Con2MAV，这是一种用于开放世界全景分割的方法，它拓展了我们之前为开放世界语义分割开发的 ContMAV。通过在多个数据集上开展大量实验，我们表明我们的模型在开放世界分割任务中取得了领先成果，同时在已知类别上的表现也颇具竞争力。我们会在被认可后开源我们的实现。此外，我们还提出了 PANIC（上下文全景异常），这是评估自动驾驶场景中开放世界全景分割的基准。此数据集通过安装在汽车上的多模态传感器套件记录，在语义和实例层面为异常对象提供了高质量、像素级的标注。我们的数据集包含 800 张图像，有 50 多个未知类别（即未出现在训练集中的类别）以及 4000 个对象实例，这使其成为自动驾驶场景中开放世界分割任务极具挑战性的数据集。我们在一个隐藏的测试集上为多个开放世界任务举办竞赛。我们的数据集和竞赛可在 https://www.ipb.uni-bonn.de/data/panic 获取。

> Perception is a key building block of autonomously acting vision systems such as autonomous vehicles. It is crucial that these systems are able to understand their surroundings in order to operate safely and robustly. Additionally, autonomous systems deployed in unconstrained real-world scenarios must be able of dealing with novel situations and object that have never been seen before. In this article, we tackle the problem of open-world panoptic segmentation, i.e., the task of discovering new semantic categories and new object instances at test time, while enforcing consistency among the categories that we incrementally discover. We propose Con2MAV, an approach for open-world panoptic segmentation that extends our previous work, ContMAV, which was developed for open-world semantic segmentation. Through extensive experiments across multiple datasets, we show that our model achieves state-of-the-art results on open-world segmentation tasks, while still performing competitively on the known categories. We will open-source our implementation upon acceptance. Additionally, we propose PANIC (Panoptic ANomalies In Context), a benchmark for evaluating open-world panoptic segmentation in autonomous driving scenarios. This dataset, recorded with a multi-modal sensor suite mounted on a car, provides high-quality, pixel-wise annotations of anomalous objects at both semantic and instance level. Our dataset contains 800 images, with more than 50 unknown classes, i.e., classes that do not appear in the training set, and 4000 object instances, making it an extremely challenging dataset for open-world segmentation tasks in the autonomous driving scenario. We provide competitions for multiple open-world tasks on a hidden test set. Our dataset and competitions are available at https://www.ipb.uni-bonn.de/data/panic.

[Arxiv](https://arxiv.org/abs/2412.12740)