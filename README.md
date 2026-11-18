# STM32 学习与作业工程仓库

本仓库用于存放我个人学习 STM32 过程中的代码工程以及课程作业。

## 🛠️ 开发环境

- **主控芯片**：STM32F103C8T6 (ARM Cortex-M3)
- **代码生成**：STM32CubeMX
- **代码编辑**：Visual Studio Code (搭配 C/C++、Keil Assistant 插件)
- **编译与烧录**：Keil MDK-ARM (ARMCC)
- **调试工具**：ST-Link V2

## 📂 目录结构

- `1-1/`：LED 500ms
- `1-2/`：LED 500ms（无DELAY）
- `1-3/`：LED 按键
- `1-5/`：LED 按键（进阶）

## 🚀 如何运行/编译

1. **查看引脚配置**：使用 STM32CubeMX 打开目录下的 `.ioc` 文件。
2. **编译下载**：使用 Keil MDK 打开 `MDK-ARM` 文件夹下的 `.uvprojx` 工程文件，点击 `F7` 编译，连接 ST-Link 后按 `F8` 烧录。
3. **日常编写**：直接使用 VSCode 打开本仓库根目录进行代码编写（已配置好 `c_cpp_properties.json` 消除红线报错）。

## ⚠️ 仓库说明

- 本仓库已配置 `.gitignore`，**不会上传**官方底层驱动库 (`Drivers/`)、Keil 编译产生的临时文件及可执行文件（如 `.hex`, `.o`, `MDK-ARM/` 等）。
- 拉取本仓库代码后，如果在本地无法编译，请使用 CubeMX 重新点击一次 `GENERATE CODE` 以生成底层依赖。

---
*Created by [lixinguxue] on 2026.*