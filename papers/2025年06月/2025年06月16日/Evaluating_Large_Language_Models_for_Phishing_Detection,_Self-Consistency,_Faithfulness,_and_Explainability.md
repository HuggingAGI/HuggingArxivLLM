# 评估大型语言模型在钓鱼检测、自我一致性和忠实性以及可解释性方面的表现

发布时间：2025年06月16日

`LLM应用` `网络安全` `信息安全`

> Evaluating Large Language Models for Phishing Detection, Self-Consistency, Faithfulness, and Explainability

# 摘要

> 网络钓鱼攻击持续威胁网络安全，攻击者不断进化以规避检测。尽管AI和ML技术进步显著，但准确分类并解释钓鱼邮件仍具挑战。得益于NLP的突破，大型语言模型（LLMs）在特定领域钓鱼分类任务中展现出潜力。然而，提升模型可靠性不仅需要准确预测，还需要一致且可信的解释。关键问题是：LLMs能否既准确分类钓鱼邮件，又能生成可靠解释？我们微调了BERT、Llama和Wizard等Transformer模型，结合二元序列分类、对比学习（CL）和直接偏好优化（DPO），提升领域相关性。通过基于SHAPley值的一致性度量（CC SHAP），我们评估了模型在分类和解释性方面的表现。CC SHAP衡量预测解释标记对齐度，测试模型的忠实度和一致性，揭示其推理逻辑。研究表明，Llama模型在预测解释对齐方面表现更佳，CC SHAP分数更高，但决策准确性不足。Wizard模型则在预测准确性上更优，但CC SHAP分数较低。

> Phishing attacks remain one of the most prevalent and persistent cybersecurity threat with attackers continuously evolving and intensifying tactics to evade the general detection system. Despite significant advances in artificial intelligence and machine learning, faithfully reproducing the interpretable reasoning with classification and explainability that underpin phishing judgments remains challenging. Due to recent advancement in Natural Language Processing, Large Language Models (LLMs) show a promising direction and potential for improving domain specific phishing classification tasks. However, enhancing the reliability and robustness of classification models requires not only accurate predictions from LLMs but also consistent and trustworthy explanations aligning with those predictions. Therefore, a key question remains: can LLMs not only classify phishing emails accurately but also generate explanations that are reliably aligned with their predictions and internally self-consistent? To answer these questions, we have fine-tuned transformer based models, including BERT, Llama models, and Wizard, to improve domain relevance and make them more tailored to phishing specific distinctions, using Binary Sequence Classification, Contrastive Learning (CL) and Direct Preference Optimization (DPO). To that end, we examined their performance in phishing classification and explainability by applying the ConsistenCy measure based on SHAPley values (CC SHAP), which measures prediction explanation token alignment to test the model's internal faithfulness and consistency and uncover the rationale behind its predictions and reasoning. Overall, our findings show that Llama models exhibit stronger prediction explanation token alignment with higher CC SHAP scores despite lacking reliable decision making accuracy, whereas Wizard achieves better prediction accuracy but lower CC SHAP scores.

[Arxiv](https://arxiv.org/abs/2506.13746)