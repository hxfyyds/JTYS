<div align="center">
  <img src="【你的项目logo图片链接，没有可以先去掉这行】" alt="项目logo" width="120" height="120">
  <h1>🏥 家庭医生 '智'护银龄 3.0</h1>
  <p>基于改进YOLOv8的360°全景人体行为识别系统 | 聚焦智能医疗与养老监护场景</p>

  <!-- 精美的项目徽章（自动生成，无需手动更新） -->
  <p>
    <img src="https://img.shields.io/github/stars/hxfyyds/JTYS?style=flat-square&color=brightgreen" alt="GitHub stars">
    <img src="https://img.shields.io/github/forks/hxfyyds/JTYS?style=flat-square&color=blue" alt="GitHub forks">
    <img src="https://img.shields.io/github/license/hxfyyds/JTYS?style=flat-square" alt="GitHub license">
    <img src="https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python" alt="Python">
    <img src="https://img.shields.io/badge/YOLOv8-ultralytics-orange?style=flat-square" alt="YOLOv8">
    <img src="https://img.shields.io/badge/PyTorch-2.0+-ee4c2c?style=flat-square&logo=pytorch" alt="PyTorch">
  </p>
</div>

---

## 📖 项目简介
家庭医生'智'护银龄3.0是一个面向**养老机构、社区医院、家庭独居老人**的智能监护系统。基于改进的YOLOv8目标检测框架，实现360°全景监控下的人体行为实时识别，能够精准检测跌倒、起身、长时间静止等异常行为，及时发出预警，为老年人的安全保驾护航。

本项目提供了从**模型训练、数据标注、模型部署到前端交互**的全流程工具链，开箱即用，可快速部署到边缘设备。

## ✨ 核心功能
- 🎯 **高精度行为识别**：支持跌倒、行走、坐卧、起身、长时间静止等10+种老年人常见行为检测
- 📹 **360°全景监控**：支持多路摄像头同时接入，实现无死角监控
- ⚡ **实时预警**：异常行为发生时，立即通过短信/APP推送报警信息
- 📊 **数据可视化**：直观展示老人活动轨迹、行为统计数据
- 🚀 **边缘部署**：支持部署在Jetson Nano、树莓派等边缘设备，低延迟运行
- 🧩 **模块化设计**：易于扩展新的行为识别模型和报警方式

## 🛠️ 技术栈
| 领域 | 技术 |
|------|------|
| 目标检测 | YOLOv8 (ultralytics) |
| 深度学习框架 | PyTorch |
| 后端框架 | Flask / FastAPI |
| 前端界面 | Vue3 + Element Plus |
| 数据标注 | LabelImg / LabelMe |
| 部署方式 | Docker / ONNX Runtime |
| 数据库 | SQLite / MySQL |

## 🚀 快速开始
### 1. 环境安装
```bash
# 克隆仓库
git clone https://github.com/hxfyyds/JTYS.git
cd JTYS

# 创建虚拟环境
conda create -n jtys python=3.8
conda activate jtys

# 安装依赖
pip install -r requirements.txt
