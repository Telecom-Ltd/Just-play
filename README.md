<div align="center">

# `JUST PLAY` // NETWORK TOOLKIT

**Configuration · Automation · Experimentation**

[![Platform](https://img.shields.io/badge/Quantumult%20X-111827?style=flat-square&logo=apple&logoColor=white)](./QuantumultX.conf)
[![Platform](https://img.shields.io/badge/Surge-111827?style=flat-square&logo=apple&logoColor=white)](./Surge%20Pro.conf)
[![JavaScript](https://img.shields.io/badge/JavaScript-111827?style=flat-square&logo=javascript&logoColor=F7DF1E)](./iOS15_Weather_AQI_US.js)
[![Status](https://img.shields.io/badge/STATUS-EXPERIMENTAL-22D3EE?style=flat-square)](https://github.com/Telecom-Ltd/Just-play)

</div>

<div align="center">

> A compact workspace for network configurations, rule engineering, and utility scripts.
>
> 一个用于网络配置、规则工程和脚本工具的轻量化工作台。

</div>

---

## `01` / SYSTEM OVERVIEW

`Just-play` is a developer-oriented collection of configuration files and scripts for experimenting with network tooling. The repository keeps commonly used resources in a compact, inspectable format so they can be reviewed, adapted, and tested across supported environments.

`Just-play` 是一个面向开发者的配置与脚本集合，用于实验和管理网络工具相关功能。该仓库将常用资源整理为简洁且易读的结构，便于在不同环境中查看、适配和测试。

```text
┌──────────────────────────────────────────────────────────────┐
│  JUST PLAY                                                   │
│  ├─ CONFIG       Rule sets for network tooling              │
│  ├─ SCRIPT       JavaScript utility experiments             │
│  └─ WORKFLOW     Inspect → Adapt → Test → Iterate            │
└──────────────────────────────────────────────────────────────┘
```

## `02` / MODULES

| Module | File | Purpose |
| :--- | :--- | :--- |
| **Quantumult X** | [`QuantumultX.conf`](./QuantumultX.conf) | Configuration and rule collection |
| **Surge** | [`Surge Pro.conf`](./Surge%20Pro.conf) | Surge-oriented configuration |
| **Utility Script** | [`iOS15_Weather_AQI_US.js`](./iOS15_Weather_AQI_US.js) | Weather and AQI enhancement logic |

| 模块 | 文件 | 用途 |
| :--- | :--- | :--- |
| **Quantumult X** | [`QuantumultX.conf`](./QuantumultX.conf) | 配置与规则集合 |
| **Surge** | [`Surge Pro.conf`](./Surge%20Pro.conf) | Surge 配置文件 |
| **脚本工具** | [`iOS15_Weather_AQI_US.js`](./iOS15_Weather_AQI_US.js) | 天气和 AQI 增强脚本 |

## `03` / CAPABILITIES

```yaml
configuration:
  - readable rule files
  - platform-oriented templates
  - personal customization

scripting:
  - JavaScript utility logic
  - lightweight automation experiments
  - inspectable and adaptable source

workflow:
  - review before use
  - test in an isolated environment
  - iterate according to platform and network conditions
```

```yaml
配置:
  - 可读性强的规则文件
  - 面向平台的模板
  - 适合个性化调整

脚本:
  - JavaScript 实用逻辑
  - 轻量自动化实验
  - 易于查看和适配

工作流:
  - 使用前审查
  - 在隔离环境中测试
  - 根据平台与网络条件迭代优化
```

## `04` / QUICK DEPLOYMENT

### Quantumult X

1. Open Quantumult X.
2. Import [`QuantumultX.conf`](./QuantumultX.conf).
3. Review the rules and adjust them for your environment.
4. Reload the configuration and verify the result.

### Surge

1. Open Surge.
2. Import [`Surge Pro.conf`](./Surge%20Pro.conf).
3. Validate the configuration before enabling it.
4. Apply, test, and tune as required.

### Script

Open [`iOS15_Weather_AQI_US.js`](./iOS15_Weather_AQI_US.js), review its logic, and adapt it to the target platform and use case before execution.

### Quantumult X / Surge 使用说明

1. 打开 Quantumult X 或 Surge。
2. 导入对应的配置文件。
3. 根据当前设备和网络环境进行必要调整。
4. 重新加载并检查实际效果。

### 脚本说明

打开 [`iOS15_Weather_AQI_US.js`](./iOS15_Weather_AQI_US.js)，先确认逻辑，再根据目标平台和使用场景进行适配和测试。

## `05` / ENGINEERING NOTES

- Treat every configuration as environment-dependent.
- Validate rules and scripts before daily or production use.
- Keep local backups before replacing an existing configuration.
- Check compatibility after changing the proxy tool or operating system version.
- Prefer small, reversible changes when debugging behavior.

- 将每一份配置视为依赖具体环境的内容。
- 在正式或长期使用前，务必验证规则与脚本。
- 在替换已有配置前保留本地备份。
- 更换代理工具或操作系统版本后，检查兼容性。
- 调试时优先采用小规模、可回滚的修改方式。

## `06` / DISCLAIMER

> The contents of this repository are collected from public internet sources and are provided for learning, research, and personal experimentation. Availability, correctness, compatibility, and continued maintenance are not guaranteed.
>
> 本仓库中的内容均整理自公开网络资源，仅用于学习、研究和个人实验。其可用性、正确性、兼容性及后续维护均不作保证。

Please review applicable laws, platform terms, and the original content licenses before using or redistributing any file. The maintainer is not responsible for issues caused by unverified configurations or scripts.

请在使用或分发任何文件前，检查相关法律、平台条款以及原始内容许可。维护者不对未经验证的配置或脚本导致的问题承担责任。

## `07` / ROADMAP

- [ ] Add version history and change notes
- [ ] Improve per-platform documentation
- [ ] Add configuration screenshots and examples
- [ ] Organize reusable rule modules
- [ ] Expand bilingual documentation

- [ ] 增加版本历史与更新说明
- [ ] 完善各平台文档说明
- [ ] 增加配置截图和使用示例
- [ ] 整理可复用的规则模块
- [ ] 扩展中英文双语支持

---

<div align="center">

`BUILD SMALL. TEST CAREFULLY. ITERATE CONSTANTLY.`

`构建简洁，谨慎测试，不断迭代。`

<sub>Just Play · A practical toolkit for network tinkering and developer workflows.</sub>
<sub>Just Play · 面向网络调试与开发工作流的实用工具包。</sub>

</div>
