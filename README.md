# car

智能车项目工作仓库（英飞凌 AURIX TC264）。

## 目录结构

```
car/
├── README.md       本文件
├── .gitignore      忽略规则
└── TC264_Library/  逐飞 TC264 开源库（本地参考，不入库）
```

`TC264_Library/` 是逐飞科技 TC264 开源库的本地检出，保留自己的 `.git` 历史，
用于查阅例程与驱动，**不纳入本仓库**（见 `.gitignore`）。

- 上游地址：<https://gitee.com/seekfree/TC264_Library>
- 协议：GPLv3

## 开发环境

| 项目 | 说明 |
| --- | --- |
| MCU | Infineon TC264（AURIX™ 双核） |
| IDE | AURIX™ Development Studio（ADS），实测版本 1.9.12 |
| 编译器 | TASKING TriCore v6.3r1 |
| 调试器 | 逐飞 DAP / 板载下载器 |

## 后续计划

- [ ] 建立自己的 ADS 工程（`src/`、`code/` 等）
- [ ] 加入电机、舵机、摄像头/电磁循迹驱动
- [ ] 参数整定与赛道调试记录

## 说明

本仓库从空仓库开始搭建，逐飞库仅作本地参考，不随仓库分发。
