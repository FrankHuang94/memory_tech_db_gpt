# 03 HBM 深入

HBM 通过超宽、较低频率的接口，以较好的每瓦带宽把多颗 DRAM 堆叠在逻辑芯片旁。其价值不只是 DRAM 颗粒：基底裸片、TSV、微凸块、堆叠良率、中介层、热设计、已知良品裸片（KGD）和客户平台认证形成整条约束链。AI 加速器客户的规格与认证节奏会反过来决定供需。

| 原文 | 快速阅读要点 |
|---|---|
| [HBM 基础](../03-hbm-deep-dive/01-hbm-fundamentals.md) | 堆栈结构、通道/银行、基底裸片、TSV、良率、可靠性和中介层瓶颈。 |
| [HBM 代际](../03-hbm-deep-dive/02-hbm-generations.md) | HBM1 至 HBM5 的规格与商业阶段；路线图需区分已标准化内容和厂商预告。 |
| [厂商路线图](../03-hbm-deep-dive/03-hbm-vendor-roadmaps.md) | SK hynix、三星、美光的晶圆、封装和 HBM4 扩产约束。 |
| [关键专利与 IP](../03-hbm-deep-dive/04-hbm-key-tech-patents-ip.md) | TSV、基底裸片、热、封装、混合键合，以及专利之外的工艺诀窍。 |
| [客户生态](../03-hbm-deep-dive/05-hbm-customer-ecosystem.md) | NVIDIA、AMD、Google TPU、自定义平台、供应商认证与内存经济性。 |

判断 HBM 周期时，应同时核对裸片产能、封装产能、基板/中介层、测试时间和客户认证；任一环节都可能比 DRAM 晶圆先成为交付上限。
