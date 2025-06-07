# 东南大学 软件智能化方法 课程大作业

在书写论文的时候，每一段的逻辑结构应当按照“问题-方法-证据-意义”的结构展开，可以参考下面的四个步骤设计段落内容：
- 根据当前背景，提出具体问题
- 根据当前问题，提出解决方法
- 根据解决方法，提出实验结果
- 根据实验结果，提出理论意义

下面是剩余章节对应的PPT内容映射，以及相应的写作建议：

---

### **1. Introduction**
#### **1.1 Motivation of AI in Software Testing**
- **映射PPT内容**：
  - **幻灯片 4-5**：医疗AI肤色偏见案例（深色皮肤患者误诊率高达34%）。
  - **幻灯片 5**：自动驾驶与聊天机器人测试缺失导致的安全隐患。
- **写作建议**：
  - 引用医疗AI和自动驾驶的实际案例，强调AI测试的必要性。
  - 提出问题：传统测试方法为何无法应对AI系统的复杂性？

#### **1.2 AI as a Tool for Testing Traditional Systems**
- **映射PPT内容**：
  - **幻灯片 6-8**：深度学习模型与传统软件测试的差异（黑盒特性、概率输出、数据依赖性）。
- **写作建议**：
  - 对比传统测试方法（单元测试、边界值分析）与AI驱动测试的优劣。
  - 强调AI如何弥补传统方法的不足（如自动化数据生成、边缘场景覆盖）。

---

### **2. AI-Driven Test Data Generation**
#### **2.2 Generative AI for Synthetic Data**
- **映射PPT内容**：
  - **幻灯片 17**：生成式AI的伦理风险（训练数据过时或带偏见）。
- **写作建议**：
  - 分析生成式AI（如GANs）在测试数据生成中的潜力与局限。
  - 引用微软Tay聊天机器人案例，讨论数据偏见对测试结果的影响。

---

### **6. Challenges in AI-Assisted Testing**
#### **6.1 Over-Reliance on Training Data**
- **映射PPT内容**：
  - **幻灯片 6-8**：数据依赖性引发系统性风险（微软Tay案例）。
- **写作建议**：
  - 讨论数据偏差对AI测试的影响，并引用文献[1]第5页的实验结果。
  - 提出解决方案（如领域泛化、数据增强）。

#### **6.2 Ethical and Legal Risks in AI Testing**
- **映射PPT内容**：
  - **幻灯片 10**：AI测试的伦理挑战（自杀建议响应问题）。
- **写作建议**：
  - 引用负责任的AI原则（公平性、隐私保护），分析AI测试的法律合规性。
  - 探讨伦理审查机制（如偏见检测Oracle框架）。

---

### **7. Real-World Applications and Case Studies**
#### **7.1 AI in Medical Software Testing**
- **映射PPT内容**：
  - **幻灯片 15-16**：医疗AI公平性危机（深色皮肤样本缺失）。
- **写作建议**：
  - 详细描述医疗AI的公平性测试方法（Instance Space Adequacy）。
  - 引用PACS数据集实验，说明数据多样性对诊断准确性的提升。

#### **7.2 AI for Autonomous Driving Validation**
- **映射PPT内容**：
  - **幻灯片 17**：自动驾驶的“Oracle Problem”（动态施工区域测试）。
- **写作建议**：
  - 分析DeepXplore框架的神经元覆盖率（Neuron Coverage）。
  - 引用自动驾驶撞护栏案例，说明AI测试的必要性。

---

### **8. Future Directions and Conclusion**
#### **8.1 Emerging AI Techniques in Testing**
- **映射PPT内容**：
  - **幻灯片 138**：未来研究方向（LLM辅助测试输入生成）。
- **写作建议**：
  - 探讨大语言模型（如GPT-4）在测试用例生成中的潜力。
  - 引用文献[1]第9页，提出基于提示工程的测试自动化方案。

#### **8.2 Integration with Agile and DevOps**
- **映射PPT内容**：
  - **幻灯片 153-154**：敏捷测试与传统测试对比。
- **写作建议**：
  - 分析AI如何支持DevOps的持续集成/交付（CI/CD）流程。
  - 引用容器化技术（Docker、Kubernetes）的测试环境一致性优势。