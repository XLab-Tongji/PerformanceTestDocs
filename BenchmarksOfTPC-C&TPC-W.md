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
| 吞吐量                | 定义为DUT发送的测试帧数与测试设备发送给它的测试帧数相等的最快速率       | 帧/s      | QoS   |                                          |
| 延迟                 | 对于存储和转发设备，它被定义为从输入帧的最后一位到达输入端口开始，到输出帧的第一位在输出端口出现时结束的时间间隔。对于位转发设备，它定义为当输入帧的第一位的末尾到达输入端口并在输出端口上出现输出帧的第一位的起始位置时开始的时间间隔。 | ms       | QoS   |                                          |
| 帧丢失率               | 定义为网络设备在稳定状态（恒定）负载下应该转发的由于缺乏资源而未被转发的帧的百分比。帧丢失率计算为（（input_count - output_count）* 100）/ input_count。 | %        | QoS   |                                          |
| 端到端                | DUT在不丢失任何帧的情况下处理的最长突发中的帧数。试验长度应至少2秒，并且应重复至少50次，并记录所记录的平均值。 | 帧数       | QoS   |                                          |
| http               | 页面加载时间                                   | ms       | QoE   |                                          |
| 视频                 | MOS-AV得分，范围= 2-5，其中5是最好的                 | 无        | QoE   |                                          |
| 音频和视频相关应用程序        | 其流量可能包括混合协议如语音、视频、文本、FTP、等等。衡量每一个协议的QoE非常重要，但是跨协议衡量同步性也非常重要，比如说音频和视频同步才能获得服务的高质量体验 |          | QoE   |                                          |
| 直接指标               | 原始信号指标、峰值信噪比、结构相似性、视频质量度量标准、 MOS等等       |          | QoE   |                                          |
| 间接指标               | 与内容无关但与影响用户对服务的感知，比如说启动时间、传送同步（在线游戏或视频回忆）、新鲜度（实际内容与接受内容的时间差） | ms       | QoE   |                                          |

