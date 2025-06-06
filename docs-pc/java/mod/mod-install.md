---
title: Minecraft Mod安装
sidebar_position: 1
---

# Minecraft Mod安装

> **本指南将帮助您轻松掌握各类Mod加载器的安装方法，让您的Minecraft世界焕然一新！**

## 什么是Mod加载器？

Mod加载器是Minecraft的**核心扩展工具**，它使游戏能够加载和运行第三方修改（Mod）。没有加载器，绝大多数Mod都无法运行。目前主流的Mod加载器包括Forge、Fabric等，它们各有特点，适用于不同需求。

:::warning

只有安装了mod加载器才能安装mod且mod与加载器版本匹配。[**视屏教学**](https://search.bilibili.com/all?keyword=mc+mod%E5%AE%89%E8%A3%85)

:::

:::tip 提示
如果你有启动器（HMCL，PCL则可以在启动器的下载选项中选择mod）
![1](.\assets\pcl.jpg)
![1](.\assets\hmcl1.jpg)
![1](.\assets\hmcl2.jpg)
:::

## 🔧 Forge 安装教程

### 适用场景

- 大型整合包和经典Mod
- 深度修改游戏机制的Mod
- 需要高度兼容性的项目

### 安装步骤

1. **下载Forge安装器**

   - 访问官方站点：[https://files.minecraftforge.net](https://files.minecraftforge.net)
   - 选择与您Minecraft版本匹配的Forge版本
   - 下载推荐版本（Recommended）的安装器
2. **运行安装器**

   ```bash
   # Windows系统：
   双击下载的.jar文件运行
   
   # macOS/Linux系统：
   在终端执行：java -jar 下载的文件名.jar
   ```
3. **选择安装选项**

   - 选择"Install client"（客户端安装）
   - 确认Minecraft安装路径正确
   - 点击"OK"开始安装
4. **启动游戏**

   - 打开Minecraft启动器
   - 在配置文件中选择新创建的"Forge"配置
   - 启动游戏验证安装

### 安装Mod

1. 下载Mod文件（.jar格式）
2. 将文件放入游戏目录的`mods`文件夹：
   ```
   Windows: %appdata%\.minecraft\mods
   macOS: ~/Library/Application Support/minecraft/mods
   Linux: ~/.minecraft/mods
   ```
3. 启动Forge版本的游戏

> ⚠️ 注意：不同Mod可能需要特定Forge版本，请仔细阅读Mod说明

## 🧵 Fabric 安装教程

### 适用场景

- 轻量级优化Mod（如钠、锂）
- 快速更新的Mod
- 需要高性能的玩家

### 安装步骤

1. **安装Fabric Loader**

   - 访问官方站点：[https://fabricmc.net/use](https://fabricmc.net/use)
   - 选择您的Minecraft版本
   - 下载Fabric安装器（.exe或.jar）
2. **运行安装器**

   ```bash
   # 所有平台通用方法：
   java -jar fabric-installer.jar
   ```

   - 选择Minecraft版本
   - 确保选中"Create profile"（创建配置文件）
   - 点击"Install"
3. **安装Fabric API**

   - 下载Fabric API：[https://www.curseforge.com/minecraft/mc-mods/fabric-api](https://www.curseforge.com/minecraft/mc-mods/fabric-api)
   - 将下载的.jar文件放入`mods`文件夹
4. **启动游戏**

   - 在启动器中选择"Fabric"配置文件
   - 启动游戏验证安装

### 推荐工具

- **Mod Menu**：提供游戏内Mod管理界面
- **Fabric Capes**：支持自定义披风
- **Sodium**：显著提升游戏帧率

## 🌐 其他加载器选项

### Quilt

- Fabric的改进分支
- 更好的Mod兼容性
- 安装方式类似Fabric
- 官网：[https://quiltmc.org](https://quiltmc.org)

### LiteLoader

- 轻量级脚本Mod支持
- 可与Forge共存
- 适用于轻量修改
- 官网：[https://www.liteloader.com](https://www.liteloader.com)

### Rift (1.13)

- 已停止更新
- 仅适用于1.13版本的临时方案

## 🚀 专业技巧

1. **多版本共存**



   通过创建不同启动配置，实现多个Mod环境共存
2. **Mod管理工具推荐**

   - **CurseForge App**：官方Mod管理工具
   - **GDLauncher**：开源跨平台启动器
   - **MultiMC**：高级多实例管理
3. **冲突解决步骤**

   1. 移除所有Mod
   2. 逐个添加Mod测试
   3. 检查游戏日志查找错误
   4. 查看Mod依赖要求
   5. 尝试更新或更换版本

## ❓ 常见问题解答

### Q：Forge和Fabric能同时安装吗？

可以！但**不能同时运行**。通过创建不同的启动配置，您可以轻松切换。

### Q：为什么安装后游戏崩溃？

常见原因：

- Mod版本与游戏版本不匹配
- 缺少必要依赖Mod
- Mod之间存在冲突
- 分配的内存不足



### Q：哪里可以安全下载Mod？

推荐平台：

- [CurseForge](https://www.curseforge.com/minecraft/mc-mods)
- [Modrinth](https://modrinth.com)
- [MC百科](https://www.mcmod.cn)（中文）

## 结语

掌握Mod加载器是开启Minecraft无限可能的第一步！根据您的需求选择Forge或Fabric，遵循本指南的步骤操作，您将很快建立自己的模组世界。遇到问题时，请参考故障排除部分或访问Mod社区获取支持。

**温馨提示：** 定期备份您的存档和Mod配置，避免意外损失！

