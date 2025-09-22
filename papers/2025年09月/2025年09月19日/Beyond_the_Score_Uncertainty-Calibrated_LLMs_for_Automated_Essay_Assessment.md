# # 不止于分数：不确定性校准大型语言模型助力自动化作文评估

发布时间：2025年09月19日

`LLM应用` `教育科技`

> Beyond the Score: Uncertainty-Calibrated LLMs for Automated Essay Assessment

# 摘要

> 自动作文评分（AES）系统虽在部分公开基准测试中评分表现已接近人类水平，但实际应用落地——尤其是在高风险考试中——仍受限制。主要瓶颈在于：多数模型仅输出单一分数，缺乏置信度或解释作为辅助。为此，我们引入conformal预测这一无需假设数据分布的包装方法，为任意分类器赋予集合值输出能力及正式的覆盖保证。我们在三个多样化语料库（ASAP、TOEFL11、剑桥FCE）上对两款开源大型语言模型（Llama-3 8B和Qwen-2.5 3B）进行微调，并在90%风险水平下完成校准。可靠性评估采用UAcc指标（一种不确定性感知准确率），该指标会奖励既准确又简洁的模型。据我们所知，这是首次将conformal预测与UAcc结合应用于作文评分的研究。结果显示，校准后的模型在持续满足覆盖目标的同时，还能保持预测集合的紧凑性，表明开源中型LLM已能支持教师参与的AES系统；我们将扩展研究和更广泛的用户调研列为未来工作方向。

> Automated Essay Scoring (AES) systems now reach near human agreement on some public benchmarks, yet real-world adoption, especially in high-stakes examinations, remains limited. A principal obstacle is that most models output a single score without any accompanying measure of confidence or explanation. We address this gap with conformal prediction, a distribution-free wrapper that equips any classifier with set-valued outputs and formal coverage guarantees. Two open-source large language models (Llama-3 8B and Qwen-2.5 3B) are fine-tuned on three diverse corpora (ASAP, TOEFL11, Cambridge-FCE) and calibrated at a 90 percent risk level. Reliability is assessed with UAcc, an uncertainty-aware accuracy that rewards models for being both correct and concise. To our knowledge, this is the first work to combine conformal prediction and UAcc for essay scoring. The calibrated models consistently meet the coverage target while keeping prediction sets compact, indicating that open-source, mid-sized LLMs can already support teacher-in-the-loop AES; we discuss scaling and broader user studies as future work.

[Arxiv](https://arxiv.org/abs/2509.15926)