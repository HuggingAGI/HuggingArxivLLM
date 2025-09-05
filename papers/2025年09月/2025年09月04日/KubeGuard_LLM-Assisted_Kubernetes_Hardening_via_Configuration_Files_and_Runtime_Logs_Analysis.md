# KubeGuard：LLM辅助的Kubernetes加固——基于配置文件与运行时日志分析

发布时间：2025年09月04日

`LLM应用` `工业与制造`

> KubeGuard: LLM-Assisted Kubernetes Hardening via Configuration Files and Runtime Logs Analysis

# 摘要

> Kubernetes（K8s）作为云原生应用编排工具的广泛应用，带来了诸多安全挑战，如资源配置错误和权限过度宽松。若不解决这些问题，可能导致未授权访问、权限提升及集群内横向移动等风险。现有多数K8s安全解决方案侧重于检测配置错误，通常采用静态分析或异常检测方法。相比之下，本文提出了KubeGuard——一个新颖的运行时日志驱动推荐框架，旨在通过解决权限过度宽松的配置来缓解风险。KubeGuard通过两项互补任务强化K8s环境：资源创建与资源优化。它利用大型语言模型（LLMs），通过模块化提示链工作流，分析反映系统实际行为的配置清单和运行时日志。这种方法使KubeGuard能够为新资源生成最小权限配置，并优化现有配置清单以缩小攻击面。KubeGuard输出的配置清单以建议形式呈现，供用户（如开发人员和运维人员）审查并采用，从而提升集群安全性。我们的评估表明，KubeGuard能有效生成和优化K8s的角色、网络策略及部署配置清单，且同时支持专有和开源的LLMs。其高精确率、召回率和F1分数证实了KubeGuard的实用性——它能将运行时可观测性转化为可操作的最小权限配置指导。

> The widespread adoption of Kubernetes (K8s) for orchestrating cloud-native applications has introduced significant security challenges, such as misconfigured resources and overly permissive configurations. Failing to address these issues can result in unauthorized access, privilege escalation, and lateral movement within clusters. Most existing K8s security solutions focus on detecting misconfigurations, typically through static analysis or anomaly detection. In contrast, this paper presents KubeGuard, a novel runtime log-driven recommender framework aimed at mitigating risks by addressing overly permissive configurations. KubeGuard is designed to harden K8s environments through two complementary tasks: Resource Creation and Resource Refinement. It leverages large language models (LLMs) to analyze manifests and runtime logs reflecting actual system behavior, using modular prompt-chaining workflows. This approach enables KubeGuard to create least-privilege configurations for new resources and refine existing manifests to reduce the attack surface. KubeGuard's output manifests are presented as recommendations that users (e.g., developers and operators) can review and adopt to enhance cluster security. Our evaluation demonstrates that KubeGuard effectively generates and refines K8s manifests for Roles, NetworkPolicies, and Deployments, leveraging both proprietary and open-source LLMs. The high precision, recall, and F1-scores affirm KubeGuard's practicality as a framework that translates runtime observability into actionable, least-privilege configuration guidance.

[Arxiv](https://arxiv.org/abs/2509.04191)