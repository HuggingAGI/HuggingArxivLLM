# 基于信息论证据的深度学习校准大型语言模型

发布时间：2025年02月10日

`LLM理论` `机器学习`

> Calibrating LLMs with Information-Theoretic Evidential Deep Learning

# 摘要

> 微调后的大型语言模型（LLMs）常因数据集规模小而表现出过度自信，导致校准效果差和不确定性估计不准确。证据深度学习（EDL）作为一种考虑不确定性的方法，能在单次前向传递中进行不确定性估计，因此成为校准微调LLMs的有前景方法。然而，尽管EDL计算高效，但其训练目标可能导致概率分布过于集中，从而引发过拟合问题。为解决此问题，我们提出通过引入信息瓶颈（IB）来正则化EDL，形成IB-EDL方法。该方法抑制了模型生成证据中的虚假信息，同时鼓励真正具有预测性的信息影响预测和不确定性估计。在多种微调LLMs和任务上的广泛实验表明，IB-EDL超越现有EDL和非EDL方法。通过提升LLMs的可信度，IB-EDL促进了其在需高水平信心校准领域的广泛应用。代码可在https://github.com/sandylaker/ib-edl获取。

> Fine-tuned large language models (LLMs) often exhibit overconfidence, particularly when trained on small datasets, resulting in poor calibration and inaccurate uncertainty estimates. Evidential Deep Learning (EDL), an uncertainty-aware approach, enables uncertainty estimation in a single forward pass, making it a promising method for calibrating fine-tuned LLMs. However, despite its computational efficiency, EDL is prone to overfitting, as its training objective can result in overly concentrated probability distributions. To mitigate this, we propose regularizing EDL by incorporating an information bottleneck (IB). Our approach IB-EDL suppresses spurious information in the evidence generated by the model and encourages truly predictive information to influence both the predictions and uncertainty estimates. Extensive experiments across various fine-tuned LLMs and tasks demonstrate that IB-EDL outperforms both existing EDL and non-EDL approaches. By improving the trustworthiness of LLMs, IB-EDL facilitates their broader adoption in domains requiring high levels of confidence calibration. Code is available at https://github.com/sandylaker/ib-edl.

[Arxiv](https://arxiv.org/abs/2502.06351)