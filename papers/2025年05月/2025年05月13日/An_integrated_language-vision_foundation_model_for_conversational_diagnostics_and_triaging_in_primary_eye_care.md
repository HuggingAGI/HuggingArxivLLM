# # 用于初级眼科保健的对话诊断与分诊的融合语言-视觉模型

发布时间：2025年05月13日

`LLM应用`

> An integrated language-vision foundation model for conversational diagnostics and triaging in primary eye care

# 摘要

> 现有的深度学习模型大多针对特定任务设计，且缺乏用户友好的操作界面。为此，我们提出了Meta-EyeFM——一个结合大型语言模型（LLM）与视觉基础模型（VFMs）用于眼病评估的多功能基础模型。通过引入路由机制，Meta-EyeFM能够根据文本查询进行精准的任务特定分析。我们采用低秩适应方法微调VFMs，使其能够检测眼部及全身性疾病、区分眼病严重程度并识别常见眼征。实验结果显示，Meta-EyeFM在将眼底图像准确路由到合适VFMs时达到了100%的准确率，疾病检测准确率$\ge$82.2%，严重程度区分准确率$\ge$89%，征象识别准确率$\ge$76%。与Gemini-1.5-flash和ChatGPT-4o LLMs相比，Meta-EyeFM在检测各类眼病方面准确率高出11%至43%，诊断水平可与眼科医生相媲美。这一系统不仅提升了可用性，还显著增强了诊断性能，可作为初级眼保健的决策支持工具，或用于眼底评估的在线LLM。

> Current deep learning models are mostly task specific and lack a user-friendly interface to operate. We present Meta-EyeFM, a multi-function foundation model that integrates a large language model (LLM) with vision foundation models (VFMs) for ocular disease assessment. Meta-EyeFM leverages a routing mechanism to enable accurate task-specific analysis based on text queries. Using Low Rank Adaptation, we fine-tuned our VFMs to detect ocular and systemic diseases, differentiate ocular disease severity, and identify common ocular signs. The model achieved 100% accuracy in routing fundus images to appropriate VFMs, which achieved $\ge$ 82.2% accuracy in disease detection, $\ge$ 89% in severity differentiation, $\ge$ 76% in sign identification. Meta-EyeFM was 11% to 43% more accurate than Gemini-1.5-flash and ChatGPT-4o LMMs in detecting various eye diseases and comparable to an ophthalmologist. This system offers enhanced usability and diagnostic performance, making it a valuable decision support tool for primary eye care or an online LLM for fundus evaluation.

[Arxiv](https://arxiv.org/abs/2505.08414)