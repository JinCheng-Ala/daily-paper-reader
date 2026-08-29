<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-29
- 运行时间：2026-08-29 22:15:04 UTC
- 运行状态：成功
- 本次总论文数：13
- 精读区：6
- 速读区：7

### 今日简报（AI）
今日聚焦长程智能体自我改进与多机器人韧性规划，精读两篇高分解读。最值得关注的是PILOT in the Loop的在线自提升机制，以及Trust-Aware多机器人系统的信任感知决策。后续可留意智能体对齐与无人机巡检的可靠性方向。
- 详情：[/202608/29/README](/202608/29/README)

### 精读区论文标签
1. [PILOT in the Loop: Live Self-Improvement for Long-Horizon Agents](/202608/29/2608.26530v1-pilot-in-the-loop-live-self-improvement-for-long-horizon-agents)  
   标签：评分：9.0/10、query:agent-error
   evidence：实时自我改进框架，根据轨迹评估重定向长时程代理运行
2. [Trust-Aware Sequential Decision Making and Rollout Planning for Resilient Multi-Robot Systems](/202608/29/2608.25690v1-trust-aware-sequential-decision-making-and-rollout-planning-for-resilient-multi-robot-systems)  
   标签：评分：8.0/10、query:agent-error
   evidence：信任感知监控器检测偏离规划执行的被攻击智能体
3. [Reassembling Distributed Risk: Trajectory-Conditioned Action Generation for Multi-Turn Agent Safety](/202608/29/2608.25711v1-reassembling-distributed-risk-trajectory-conditioned-action-generation-for-multi-turn-agent-safety)  
   标签：评分：8.0/10、query:agent-error
   evidence：基于轨迹条件的动作生成，检测多轮代理轨迹中的分布式安全风险
4. [Repair or Resample? Rethinking Failure Debugging in LLM Multi-Agent Systems](/202608/29/2608.25920v1-repair-or-resample-rethinking-failure-debugging-in-llm-multi-agent-systems)  
   标签：评分：8.0/10、query:agent-error
   evidence：记录MAS执行轨迹并建立干预锚点以评估和诊断故障修复
5. [How Do LLM Agents Actually Get the Flag? Trace-Level Provenance for Agentic Offensive Security Evaluation](/202608/29/2608.26237v1-how-do-llm-agents-actually-get-the-flag-trace-level-provenance-for-agentic-offensive-security-evaluation)  
   标签：评分：8.0/10、query:agent-error
   evidence：将每次运行重建为基于证据的解题画像，识别实际利用发生位置及获取flag的路径
6. [Safety Does Not Compose: Non-Decaying Loop State for Autonomous LLM Agents](/202608/29/2608.27141v1-safety-does-not-compose-non-decaying-loop-state-for-autonomous-llm-agents)  
   标签：评分：8.0/10、query:agent-error
   evidence：指出轨迹级监测器在检测跨迭代碎片化证据时失效，论证需要非衰减循环状态

### 速读区论文标签
1. [INTENT-AS-A-TOOL Makes it Easy to Track Agentic Misalignment](/202608/29/2608.27348v1-intent-as-a-tool-makes-it-easy-to-track-agentic-misalignment)  
   标签：评分：8.0/10、query:agent-error
   evidence：通过意图调用工具提供细粒度、无需评判的监测信号，用于追踪智能体不一致行为
2. [RACO: Reliability-Aware Coarse-Goal Optimization for Inspection-Oriented UAV Vision-Language Navigation](/202608/29/2608.22678v1-raco-reliability-aware-coarse-goal-optimization-for-inspection-oriented-uav-vision-language-navigation)  
   标签：评分：7.0/10、query:agent-error
   evidence：针对无人机导航轨迹中粗粒度目标漂移错误，有助于检测路径偏离
3. [Knowing When to Ask for Help: Bayesian Self-Escalation in Hierarchical LLM Agents](/202608/29/2608.24087v1-knowing-when-to-ask-for-help-bayesian-self-escalation-in-hierarchical-llm-agents)  
   标签：评分：7.0/10、query:agent-error
   evidence：利用已标注轨迹估计任务成功概率，在推理中识别可能失败并触发升级
4. [RePolicy: Reinforcement Learning for Safety-Policy Invocation in Agent Safeguards](/202608/29/2608.24275v2-repolicy-reinforcement-learning-for-safety-policy-invocation-in-agent-safeguards)  
   标签：评分：7.0/10、query:agent-error
   evidence：评估完整智能体轨迹并依据动态安全策略产出安全判断，即对行为进行错误监控
5. [LocalLSTC: A Long Short-Term Control Architecture for Locally Deployed GUI Agents](/202608/29/2608.25777v1-locallstc-a-long-short-term-control-architecture-for-locally-deployed-gui-agents)  
   标签：评分：7.0/10、query:agent-error
   evidence：识别GUI智能体轨迹中的控制失败并组织控制信息以缓解问题
6. [Agent Mesh: Reliability Primitives for Non-Idempotent Agent Delegation - Identity Adequacy and Evidence Adequacy](/202608/29/2608.26225v1-agent-mesh-reliability-primitives-for-non-idempotent-agent-delegation---identity-adequacy-and-evidence-adequacy)  
   标签：评分：7.0/10、query:agent-error
   evidence：对生产智能体软件交付平台的失败研究揭示重试/超时/错误率熔断的失效，并提出新的可靠性原语用于错误检测。
7. [SWE-Prime: Fewer Trajectories, Better Performance](/202608/29/2608.27449v1-swe-prime-fewer-trajectories-better-performance)  
   标签：评分：7.0/10、query:agent-error
   evidence：在成功轨迹中筛选低质量步骤，检测无效、冗余或风险动作，用于监督微调数据选择。


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
