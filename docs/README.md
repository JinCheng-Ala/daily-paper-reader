<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-02
- 运行时间：2026-09-02 23:09:12 UTC
- 运行状态：成功
- 本次总论文数：8
- 精读区：5
- 速读区：3

### 今日简报（AI）
今日精读5篇聚焦多智能体LLM系统错误归因与自进化智能体安全，速读覆盖协作基准与进化验证。
最高分《EDGE》9.0分提出错误依赖图多错误归因方法，另《Auditing Harness Tampering》8.0分关注自我改进智能体的篡改审计，二者值得优先深入。
建议先读EDGE理解多智能体排错思路，再结合篡改审计思考AI安全边界，后续可扩展至协作任务规划方向。
- 详情：[/202609/02/README](/202609/02/README)

### 精读区论文标签
1. [EDGE: Error Dependency Graph-Guided Multi-Error Attribution in Multi-Agent LLM Systems](/202609/02/2609.01360v1-edge-error-dependency-graph-guided-multi-error-attribution-in-multi-agent-llm-systems)  
   标签：评分：9.0/10、query:agent-error
   evidence：通过构建错误依赖图检测并归因LLM智能体轨迹中多个相互关联的错误
2. [Auditing Harness Tampering in Self-Improving Agents](/202609/02/2609.00069v1-auditing-harness-tampering-in-self-improving-agents)  
   标签：评分：8.0/10、query:agent-error
   evidence：提出篡改编辑分类体系并构建带篡改标注的轨迹语料，支撑轨迹层错误检测
3. [Polished but Unresolved: Identifying Late-Stage Pressure States in Long-Horizon Tool-Use Agents](/202609/02/2609.00823v1-polished-but-unresolved-identifying-late-stage-pressure-states-in-long-horizon-tool-use-agents)  
   标签：评分：8.0/10、query:agent-error
   evidence：检测长时程工具使用智能体在轨迹后期出现的压力状态，即提交看似完善但关键约束未解决的答案
4. [EmbodiedSkills: A Unified Framework for Orchestrating, Training, and Deploying VLA Agents](/202609/02/2609.01281v1-embodiedskills-a-unified-framework-for-orchestrating-training-and-deploying-vla-agents)  
   标签：评分：8.0/10、query:agent-error
   evidence：在执行前检查前提、执行后验证结果，以捕获VLA智能体轨迹中的无效动作
5. [Parsing the Stream: A Live Trace Model for Long-Horizon Agents and Their Observers](/202609/02/2609.01466v1-parsing-the-stream-a-live-trace-model-for-long-horizon-agents-and-their-observers)  
   标签：评分：8.0/10、query:agent-error
   evidence：实时迹模型将长时程智能体轨迹编译为视图，使观察者能高效监控运行状态

### 速读区论文标签
1. [CoCoBench: A Cooperative Coordination Benchmark for Embodied Multi-Agent Task Planning](/202609/02/2608.28266v1-cocobench-a-cooperative-coordination-benchmark-for-embodied-multi-agent-task-planning)  
   标签：评分：7.0/10、query:agent-error
   evidence：结构级基准可检测多智能体轨迹中的重复劳动、顺序违规、资源竞争和交接失步等行动错误
2. [Verify Smarter, Evolve Further: Efficient Harness Evolution through Behavior-Aware Verification](/202609/02/2608.27311v1-verify-smarter-evolve-further-efficient-harness-evolution-through-behavior-aware-verification)  
   标签：评分：6.0/10、query:agent-error
   evidence：从执行轨迹推导智能体框架修改，并在行为相关任务上选择性验证以发现智能体行为回退
3. [HarnessEvolve: Learning from Reference Trajectories for Reliable Agent Self-Evolution](/202609/02/2609.00829v1-harnessevolve-learning-from-reference-trajectories-for-reliable-agent-self-evolution)  
   标签：评分：6.0/10、query:agent-error
   evidence：借鉴参考轨迹解决信用分配失败，定位导致错误的关键步骤以支撑可靠自我进化


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
