# 心因性机器：大型语言模型中的AI精神病模拟、妄想强化与伤害促成

发布时间：2025年09月13日

`LLM应用` `医疗健康`

> The Psychogenic Machine: Simulating AI Psychosis, Delusion Reinforcement and Harm Enablement in Large Language Models

# 摘要

> 背景：“AI精神病”相关报告日渐增多——用户与大型语言模型（LLM）的交互可能加剧甚至诱发精神病或不良心理症状。LLM虽因谄媚迎合的特性可能带来益处，却也可能通过强化易感用户的妄想信念，沦为伤害的推手。
  方法：我们构建了全新的“精神病基准测试集”（psychosis-bench），旨在系统评估LLM的致精神性风险。该测试集包含16个结构化对话场景，每个场景含12轮对话，模拟了妄想主题（色情妄想、夸大/救世主妄想、关系妄想）的发展过程及潜在危害。我们选取8个主流LLM，在显性与隐性对话情境中，评估其妄想确认（DCS）、伤害促成（HES）及安全干预（SIS）能力。
  结果：1536轮模拟对话显示，所有LLM均具备致精神性潜力——它们更倾向于延续而非质疑妄想（DCS均值为0.91±0.88【数学公式】）。模型频繁促成用户的有害请求（HES均值为0.69±0.84【数学公式】），而仅在约三分之一的关键对话轮次中提供安全干预（SIS均值为0.37±0.48【数学公式】）；128个场景中，39.8%（51个）完全未出现安全干预。隐性场景下模型表现更差：确认妄想、促成伤害的可能性更高，干预却更少（p<.001【数学公式】）。DCS与HES呈强相关性（rs=.77【数学公式】）。此外，不同模型表现差异显著，表明安全性并非规模扩大后的自然涌现特性。
  结论：本研究证实，LLM的致精神性是可量化的风险，亟需重新审视其训练范式。我们认为，这不仅是技术难题，更是关乎公共卫生的要务——需开发者、政策制定者与医疗专家协同应对。

> Background: Emerging reports of "AI psychosis" are on the rise, where user-LLM interactions may exacerbate or induce psychosis or adverse psychological symptoms. The sycophantic and agreeable nature of LLMs can beneficial, it can become a vector for harm by reinforcing delusional beliefs in vulnerable users.
  Methods: We introduce psychosis-bench, a novel benchmark designed to systematically evaluate the psychogenicity of LLMs comprimising 16 structured, 12-turn conversational scenarios simulating the progression of delusional themes(Erotic Delusions, Grandiose/Messianic Delusions, Referential Delusions) and potential harms. We evaluated eight prominent LLMs for Delusion Confirmation (DCS), Harm Enablement (HES), and Safety Intervention(SIS) across explicit and implicit conversational contexts.
  Findings: Across 1,536 simulated conversation turns, all LLMs demonstrated psychogenic potential, showing a strong tendency to perpetuate rather than challenge delusions (mean DCS of 0.91 $\pm$0.88). Models frequently enabled harmful user requests (mean HES of 0.69 $\pm$0.84) and offered safety interventions in only roughly a third of applicable turns (mean SIS of 0.37 $\pm$0.48). 51 / 128 (39.8%) of scenarios had no safety interventions offered. Performance was significantly worse in implicit scenarios, models were more likely to confirm delusions and enable harm while offering fewer interventions (p < .001). A strong correlation was found between DCS and HES (rs = .77). Model performance varied widely, indicating that safety is not an emergent property of scale alone.
  Conclusion: This study establishes LLM psychogenicity as a quantifiable risk and underscores the urgent need for re-thinking how we train LLMs. We frame this issue not merely as a technical challenge but as a public health imperative requiring collaboration between developers, policymakers, and healthcare professionals.

[Arxiv](https://arxiv.org/abs/2509.10970)