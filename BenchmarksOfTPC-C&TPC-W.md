| 指标                 | 作用                                       | 单位       | 类型    | 论文                                       |
| ------------------ | ---------------------------------------- | -------- | ----- | ---------------------------------------- |
| 流量指标TPMC           | 流量指标描述了系统在执行Payment、Order-status、Delivery、Stock-Level这四种交易的同时，每分钟可以处理多少个New-Order交易。所有交易的响应时间必须满足TPC-C测试规范的要求。流量指标值越大越好。 | 订单数/min  | TPC-C |                                          |
| 性价比Price/tpmC      | 测试系统价格（指在美国的报价）与流量指标的比值。性价比越小越好          | $/tpmC   | TPC-C |                                          |
| 响应时间 response time | 系统响应处理新订单操作的时间                           | second   | TPC-C | TPCC-UVa: an open-source TPC-C implementation for global performance measurement of computer systems |
| Think Time         | 处理多个新订单之间相隔的时间                           | second   | TPC-C |                                          |
| Latency            | 使用不同的资源分区方案时，每个应用程序在第一级缓存测量的平均数据访问延迟     | ms       | TPC-C | Dynamic Resource Allocation for Database Servers Running on Virtual Storage |
| WIPS               | 在购物模式下服务器每秒处理web交互的数目                    | web交互数/s | TPC-W |                                          |
| WIPSb              | 在浏览模式下服务器每秒处理web交互的数目                    | web交互数/s | TPC-W |                                          |
| WIPSo              | 在购物模式下服务器每秒处理web交互的数目                    | web交互数/s | TPC-W |                                          |
| COST OF PER WIPS   | 衡量web服务器性价比                              | $ / WIPS | TPC-W |                                          |
| SpeedUp            | 衡量多线程处理器对提高吞吐量的有效性，加速后CPI / 加速前CPI       | %        | TPC-W | An Architectural Evaluation of Java TPC-W |

