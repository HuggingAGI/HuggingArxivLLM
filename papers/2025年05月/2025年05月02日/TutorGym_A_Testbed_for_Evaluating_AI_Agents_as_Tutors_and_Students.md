# TutorGym：AI导师与学生能力评测平台

发布时间：2025年05月02日

`LLM应用` `教育科技`

> TutorGym: A Testbed for Evaluating AI Agents as Tutors and Students

# 摘要

> 大型语言模型（LLM）在MATH和GSM8K等学术基准测试中的性能提升，为其作为独立辅导工具和人类学习模拟器的应用提供了更广阔的可能性。然而，这些新应用的评估不仅限于最终解决方案的生成能力，为此我们推出了TutorGym，一个专为现有智能辅导系统（ITS）设计的标准测试接口。TutorGym支持在经过课堂验证的ITS环境中（如认知辅导系统CTAT、学徒辅导系统和OATutors）直接评估AI代理的表现。与传统问题解答基准不同，TutorGym将AI代理置于真实ITS的交互界面中，模拟导师或学习者的角色。作为导师，AI代理需要提供包括生成示例、提示和分步反馈在内的辅导支持，其效果可与现有ITS的自适应分步支持直接对比。作为学习者，AI代理直接从ITS的指导下学习，其学习轨迹和错误模式可与真实学生数据进行比较。TutorGym为在多种学习环境中训练和评估不同类型的AI代理（包括LLMs、学习计算模型和强化学习代理）提供了一个统一框架。目前，TutorGym涵盖223个不同辅导领域。初步评估显示，当前LLMs在辅导任务中表现尚不理想——在错误动作识别方面仅略高于随机水平，下一步动作的正确率也只有约52-70%——但当它们通过上下文学习作为学生进行训练时，能够生成接近人类的学习曲线。

> Recent improvements in large language model (LLM) performance on academic benchmarks, such as MATH and GSM8K, have emboldened their use as standalone tutors and as simulations of human learning. However, these new applications require more than evaluations of final solution generation. We introduce TutorGym to evaluate these applications more directly. TutorGym is a standard interface for testing artificial intelligence (AI) agents within existing intelligent tutoring systems (ITS) that have been tested and refined in classroom studies, including Cognitive Tutors (CTAT), Apprentice Tutors, and OATutors. TutorGym is more than a simple problem-solution benchmark, it situates AI agents within the interactive interfaces of existing ITSs. At each step of problem-solving, AI agents are asked what they would do as a tutor or as a learner. As tutors, AI agents are prompted to provide tutoring support -- such as generating examples, hints, and step-level correctness feedback -- which can be evaluated directly against the adaptive step-by-step support provided by existing ITSs. As students, agents directly learn from ITS instruction, and their mistakes and learning trajectories can be compared to student data. TutorGym establishes a common framework for training and evaluating diverse AI agents, including LLMs, computational models of learning, and reinforcement learning agents, within a growing suite of learning environments. Currently, TutorGym includes 223 different tutor domains. In an initial evaluation, we find that current LLMs are poor at tutoring -- none did better than chance at labeling incorrect actions, and next-step actions were correct only ~52-70% of the time -- but they could produce remarkably human-like learning curves when trained as students with in-context learning.

[Arxiv](https://arxiv.org/abs/2505.01563)