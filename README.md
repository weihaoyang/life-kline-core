# 八字大运流年趋势与 K 线数据 · life-kline core

本仓从 [知几排盘](https://github.com/weihaoyang/qimen-llm-chart) 提取 TypeScript 计算与测试。人生 K 线包含基于规则的可解释分数，不代表已验证的预测模型。大运方向对照《三命通会》卷二；红艳、流霞见《神峰通考》扫描数据与论文。可视化逻辑部分移植自 life-kline，Apache-2.0 许可及 NOTICE 见 LICENSES。

```sh
npm install
npm run patch:3meta
npm test
npm run typecheck
```

运行前执行依赖补丁；共享时间、排盘模块一并保留，尚未发布 npm 包。入口为 `src/lib/research/trend.ts`。

## 研究与案例

[研究论文、版本对照与证据边界](https://github.com/weihaoyang/qimen-llm-chart/blob/main/docs/research/calculation-audit-paper.md)；独立测试见 `src/lib/research/trend.test.ts`。古籍影像不随仓库提供，使用条件见[影像权利记录](https://github.com/weihaoyang/qimen-llm-chart/blob/main/docs/research/sources/RIGHTS.md)。

## 授权

代码 [GPL-3.0-only](LICENSE)，依赖与移植代码许可证见 `LICENSES/`；来源及版本见[第三方声明](https://github.com/weihaoyang/qimen-llm-chart/blob/main/docs/THIRD_PARTY_NOTICES.md)。
