# BodyMetric：评估文本转图像生成中人体的逼真程度

发布时间：2024年12月05日

`LLM应用` `图像生成` `人体图像`

> BodyMetric: Evaluating the Realism of HumanBodies in Text-to-Image Generation

# 摘要

> 从文本精确生成人体图像对于当下先进的文本到图像模型而言，依旧是个棘手难题。常见的身体相关瑕疵有多余或缺失的肢体、不切实际的姿势、身体部位模糊等等。当下，此类瑕疵的评估高度依赖耗时的人工判断，这限制了大规模对模型进行基准测试的能力。为此，我们提出了 BodyMetric，这是一种可学习的指标，能够预测图像中的人体真实感。BodyMetric 基于真实感标签以及多模态信号进行训练，其中包括从输入图像推断出的 3D 人体表示和文本描述。为推动这一方法，我们设计了一个标注流程来收集有关人体真实感的专家评级，从而为该任务创建了一个新的数据集，即 BodyRealism。消融研究支持了我们对 BodyMetric 的架构选择，以及利用 3D 人体先验捕捉 2D 图像中身体相关瑕疵的重要性。与评估图像中一般用户偏好的同期指标相比，BodyMetric 专门反映了身体相关的瑕疵。我们通过此前大规模无法实现的应用彰显了 BodyMetric 的实用性。特别是，我们使用 BodyMetric 对文本到图像模型生成逼真人体的能力进行基准测试。我们还展示了 BodyMetric 依据预测的真实感分数对生成图像进行排名的有效性。

> Accurately generating images of human bodies from text remains a challenging problem for state of the art text-to-image models. Commonly observed body-related artifacts include extra or missing limbs, unrealistic poses, blurred body parts, etc. Currently, evaluation of such artifacts relies heavily on time-consuming human judgments, limiting the ability to benchmark models at scale. We address this by proposing BodyMetric, a learnable metric that predicts body realism in images. BodyMetric is trained on realism labels and multi-modal signals including 3D body representations inferred from the input image, and textual descriptions. In order to facilitate this approach, we design an annotation pipeline to collect expert ratings on human body realism leading to a new dataset for this task, namely, BodyRealism. Ablation studies support our architectural choices for BodyMetric and the importance of leveraging a 3D human body prior in capturing body-related artifacts in 2D images. In comparison to concurrent metrics which evaluate general user preference in images, BodyMetric specifically reflects body-related artifacts. We demonstrate the utility of BodyMetric through applications that were previously infeasible at scale. In particular, we use BodyMetric to benchmark the generation ability of text-to-image models to produce realistic human bodies. We also demonstrate the effectiveness of BodyMetric in ranking generated images based on the predicted realism scores.

[Arxiv](https://arxiv.org/abs/2412.04086)