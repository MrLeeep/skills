# 智慧交通 Skills

面向中文智慧高速、智慧隧道、主动管控和 AI 智能体项目的解决方案与交付技能库。

## Skills

| Skill | 用途 |
|---|---|
| `solution-expert` | 智慧高速与智慧隧道总专家，负责整体解决方案方法和能力边界 |
| `requirement-review` | 审查需求规格说明书、功能设计、方案、原型和功能清单 |
| `agent-boundary-review` | 审查 AI 智能体、算法、规则、数据服务、平台、设备和人工职责 |
| `governance-mechanism` | 将体制机制、管理办法和联勤联动方案转成组织职责、审批权限、系统权限和业务闭环 |
| `functional-list` | 将需求拆成研发可估时、测试可验收的需求功能清单 |
| `detailed-design` | 将需求和设计材料深化为面向业主、研发、测试和交付的软件详细设计 |
| `software-function-breakdown` | 将详细设计拆成结构化软件功能工程量清单，供领导后续内部报价测算，不计算价格 |
| `meeting-to-requirements` | 将会议纪要和客户反馈转成需求变更与 Action List |
| `project-risk-review` | 从项目经理视角识别需求、数据、接口、算法、Agent、设备、第三方和工期风险 |

## 推荐工作流

### 新项目/新需求

`solution-expert` → `requirement-review` → `agent-boundary-review` → `governance-mechanism` → `functional-list` → `project-risk-review`

### 给业主编制软件详细设计

`requirement-review` → 必要时 `governance-mechanism` → `agent-boundary-review` → `functional-list` → `detailed-design`

详细设计必须达到“业主能审查、研发能理解、测试能验证”的粒度，不得只对需求原文进行扩写。

### 详细设计后形成内部报价依据

`detailed-design` → `software-function-breakdown`

输出到软件功能工程量清单为止，重点明确模块、三级功能、原子功能点、功能说明、实现类别、建设属性、范围归属、依赖和验收要点。该 Skill 不计算价格、人日、人月、税费、利润或商务折扣，后续由公司内部按自身规则测算。

### 体制机制/管理办法设计

`governance-mechanism` → `requirement-review` → `functional-list` → `project-risk-review`

重点将“谁发起、谁研判、谁会商、谁审核、谁审批、谁执行、谁反馈、谁监督”映射到系统角色、权限、流程、日志和验收要求。

### 开完需求会

`meeting-to-requirements` → `requirement-review` → 必要时 `governance-mechanism` → 更新 `functional-list` → 必要时更新 `detailed-design` 和 `software-function-breakdown` → `project-risk-review`

### 智慧隧道 AI 项目

重点关注三类智能体：

1. 预案自动生成 AI 智能体
2. 数字问数 AI 智能体
3. 运营管理综合研判 AI 智能体

任何智能体设计都必须明确输入、推理、工具、输出、边界、人工确认、失败处理和可追溯性。

## 使用原则

- 默认中文输出
- 项目材料中的术语优先于通用行业术语
- 不虚构项目事实、数据和接口字段
- 不虚构组织、岗位、审批权和授权关系
- 参考项目制度不得直接当作当前项目正式机制
- 未确认内容标记“待确认”
- 建议内容与已确认需求分开
- 系统具备控制能力不等于系统有权自动执行
- AI 推荐不等于行政或业务决策
- API 成功不等于设备执行成功
- 事实型问数结果必须来自真实数据源
- 模型研判不得伪装成确定事实
- 每项核心功能都要能落到测试和验收
- 软件功能工程量清单不得为了报价人为放大功能数量
- 功能工程量与商务价格分离

## 后续规划

计划继续增加：

- `data-dependency-analysis`：数据依赖矩阵
- `interface-analysis`：接口分析
- `device-closed-loop`：设备控制闭环
- `acceptance-design`：测试与验收设计
- `tunnel-emergency-plan`：隧道应急预案专项
- `data-qa-design`：数字问数专项
- `operation-analysis`：运营综合研判专项
