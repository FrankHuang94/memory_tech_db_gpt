# 04 HBF（高带宽闪存）新兴技术

HBF 试图在昂贵、低延迟的 HBM 与容量大但较慢的 SSD 之间，建立靠近加速器的 NAND 层。它的潜在价值是把推理模型的较冷权重或数据以更低成本、更高带宽供给，但成立条件包括介质/控制器、软件调度、主机接口和跨厂商标准的一致性。它应被看作分层协同，而非 HBM 或 CXL 的直接替代。

| 原文 | 快速阅读要点 |
|---|---|
| [HBF 概览](../04-hbf-emerging-tech/01-hbf-overview.md) | 架构概念、推理 TCO、生态立场、软件要求和采用风险。 |
| [HBF 标准化](../04-hbf-emerging-tech/02-hbf-standardization.md) | OCP、SanDisk、SK hynix、BiCS/CBA、咨询委员会、样品与量产路径。 |
| [HBF vs. HBM vs. CXL](../04-hbf-emerging-tech/03-hbf-vs-hbm-vs-cxl.md) | 带宽、延迟、容量、成本、工作负载匹配和采购决策矩阵。 |

需追踪的不是概念演示，而是可互操作规范、真实平台支持、NAND 供给与控制器软件能否让延迟被有效隐藏。
