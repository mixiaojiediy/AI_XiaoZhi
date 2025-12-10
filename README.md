<h1 align="center">AI_XiaoZhi</h1>
<div align="center">
<a href="https://github.com/mixiaojiediy/AI_XiaoZhi/stargazers"><img src="https://img.shields.io/github/stars/mixiaojiediy/AI_XiaoZhi" alt="Stars Badge"/></a>
<a href="https://github.com/mixiaojiediy/AI_XiaoZhi/network/members"><img src="https://img.shields.io/github/forks/mixiaojiediy/AI_XiaoZhi" alt="Forks Badge"/></a>
<a href="https://github.com/mixiaojiediy/AI_XiaoZhi/pulls"><img src="https://img.shields.io/github/issues-pr/mixiaojiediy/AI_XiaoZhi" alt="Pull Requests Badge"/></a>
<a href="https://github.com/mixiaojiediy/AI_XiaoZhi/issues"><img src="https://img.shields.io/github/issues/mixiaojiediy/AI_XiaoZhi" alt="Issues Badge"/></a>
<a href="https://github.com/mixiaojiediy/AI_XiaoZhi/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/mixiaojiediy/AI_XiaoZhi?color=2b9348"></a>
<a><img src="https://img.shields.io/github/license/mixiaojiediy/AI_XiaoZhi?color=2b9348" alt="License Badge"/></a>
</div>
<div align="center">
<i>喜欢这个项目吗？请考虑给 Star ⭐️ 以帮助改进！</i>
</div>

---

>**项目简介**：一个语音对话盒子

## 项目说明 


### 1.3D_Model

本项目提供了完整的3D打印文件，所有文件位于 `1.3D_Model` 目录下：

- **壳体.step** - 设备外壳主体结构
- **底盖.step** - 设备底部盖板
- **按键.step** - 按键组件

所有文件均为STEP格式，可直接用于3D打印或导入CAD软件进行编辑。

#### 使用说明

1. 下载所需的STEP文件
2. 使用3D打印切片软件（如Cura、PrusaSlicer等）打开文件
3. 根据您的3D打印机设置合适的打印参数
4. 建议打印材料：PLA或ABS
5. 打印完成后进行组装
   
   
### 4.Hardware

本项目提供两种硬件版本，所有电路设计文件位于 `4.Hardware` 目录下：

#### WIFI版本
- **位置**：`4.Hardware/WIFI_Board/`
- **文件说明**：
  - `AI_XiaoZhi_WIFI.SchDoc` - 原理图文件
  - `AI_XiaoZhi_WIFI.PcbDoc` - PCB布局文件
  - `AI_XiaoZhi_WIFI.PrjPcb` - Altium Designer项目文件
- **状态**：✅ 已打板验证

#### 4G版本
- **位置**：`4.Hardware/4G_Board/`
- **文件说明**：
  - `AI_XiaoZhi_4G.SchDoc` - 原理图文件
  - `AI_XiaoZhi_4G.PcbDoc` - PCB布局文件
  - `AI_XiaoZhi_4G.PrjPcb` - Altium Designer项目文件
- **状态**：✅ 已打板验证

> **注意**：所有设计文件使用 Altium Designer 格式，需要使用 Altium Designer 或兼容软件打开。









