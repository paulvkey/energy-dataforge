# 风电术语速查

以下释义用于项目交流入门，不替代标准、合同或厂商技术文件中的正式定义。建议先阅读[风电大模型项目入门](wind-primer.md)；风机结构可配合美国能源部的[互动说明](https://www.energy.gov/cmei/wind/articles/how-wind-turbine-works)理解。

| 术语 | 英文/缩写 | 项目中的简要理解 |
|---|---|---|
| 风力发电机组 | Wind Turbine Generator, WTG | 将风能转换为电能的成套设备 |
| 风电场 | Wind Farm | 多台风机及配套集电、升压、控制和运维设施 |
| 叶轮 | Rotor | 叶片和轮毂等组成的旋转部分 |
| 叶片 | Blade | 捕获风能并产生气动力的部件 |
| 轮毂 | Hub | 连接叶片与传动系统的部件 |
| 机舱 | Nacelle | 容纳传动、发电和控制等设备的结构 |
| 塔筒 | Tower | 支撑机舱和叶轮的结构 |
| 变桨系统 | Pitch System | 调整叶片桨距角的系统 |
| 偏航系统 | Yaw System | 调整机舱朝向以适应风向的系统 |
| 齿轮箱 | Gearbox | 在部分机型中调节传动转速 |
| 直驱 | Direct Drive | 叶轮直接或低级传动连接发电机的技术路线 |
| 发电机 | Generator | 将机械能转换为电能 |
| 变流器 | Converter | 调节和转换电能以满足机组和并网要求 |
| 主控 | Main Controller | 执行风机监测、逻辑和控制的核心系统 |
| SCADA | Supervisory Control and Data Acquisition | 监视控制与数据采集系统 |
| 有功功率 | Active Power | 实际完成能量转换和做功的电功率，常用 kW/MW |
| 无功功率 | Reactive Power | 用于维持电磁场和电压支撑等的功率分量 |
| 功率设定值 | Power Setpoint | 控制或调度要求机组/场站达到的目标功率 |
| 额定功率 | Rated Power | 机组设计标称输出功率 |
| 切入风速 | Cut-in Wind Speed | 机组开始发电附近的风速 |
| 额定风速 | Rated Wind Speed | 机组达到额定功率附近的风速 |
| 切出风速 | Cut-out Wind Speed | 机组停止运行附近的高风速阈值概念 |
| 功率曲线 | Power Curve | 特定条件下风速与功率关系 |
| 容量因子 | Capacity Factor | 一段时间实际发电量与理论满功率发电量之比 |
| 利用小时 | Equivalent Full-load Hours | 发电量除以装机容量得到的等效小时数 |
| 可利用率 | Availability | 设备或场站具备运行能力的程度，口径需确认 |
| 限电 | Curtailment | 因调度、电网或其他外部约束限制发电 |
| 降额 | Derating | 机组允许输出低于正常可达到水平 |
| 湍流强度 | Turbulence Intensity, TI | 风速波动程度的指标 |
| 风切变 | Wind Shear | 风速随高度变化的现象 |
| 尾流 | Wake | 上游风机对下游风速和湍流的影响 |
| 空气密度 | Air Density | 影响风能和功率的重要环境量 |
| 测风塔 | Meteorological Mast, Met Mast | 安装气象传感器进行风资源观测的塔架 |
| 激光雷达 | LiDAR | 使用激光遥感测量风场的设备 |
| 数值天气预报 | Numerical Weather Prediction, NWP | 使用数值模型预测天气 |
| 再分析数据 | Reanalysis Data | 将模型与历史观测融合形成的一致数据集 |
| 观测数据 | Observed Data | 由传感器或人工直接测得的数据 |
| 预测数据 | Forecast Data | 在某个发布时间对未来目标时间作出的估计 |
| 模拟数据 | Simulated Data | 由物理或统计模型在一定假设下生成的数据 |
| 推导数据 | Derived Data | 通过其他字段、公式或模型计算得到的数据 |
| 时间戳 | Timestamp | 一条记录对应的时间，需要说明时区和含义 |
| 采样频率 | Sampling Frequency | 传感器读取或系统记录数据的频率 |
| 聚合周期 | Aggregation Interval | 将原始数据计算为均值、最大值等统计量的窗口 |
| 质量码 | Quality Code | 表示测点有效性、通信或替代状态的代码 |
| 状态码 | Status Code | 描述机组或设备当前状态的编码 |
| 告警码 | Alarm Code | 描述满足告警条件的编码 |
| 工单 | Work Order | 运维任务、处理过程和结果的记录 |
| 预防性维护 | Preventive Maintenance | 按计划降低故障概率的维护 |
| 纠正性维护 | Corrective Maintenance | 针对故障或缺陷开展的维护 |
| 状态监测 | Condition Monitoring | 通过数据判断设备状态 |
| 故障诊断 | Fault Diagnosis | 识别故障类型、位置或原因的分析 |
| 剩余寿命 | Remaining Useful Life, RUL | 对设备继续可用时间的估计 |

## 使用注意

- 可利用率、限电和利用小时等指标可能有不同统计口径。
- 告警码和设备名称可能随厂商、机型、软件版本变化。
- 同名测点可能具有不同单位、采样和聚合方式。
- 术语表需要合作方和风电领域人员在真实场景下复核。
