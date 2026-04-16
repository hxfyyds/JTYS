<div align="center">
  <h1>🏥 家庭医生 '智'护银龄 3.0</h1>
  <p>基于改进YOLOv8的360°全景人体行为识别系统 | 聚焦智能医疗与养老监护场景</p>

  <!-- 项目数据徽章，自动同步仓库数据，无需手动修改 -->
  <p>
    <img src="https://img.shields.io/github/stars/hxfyyds/JTYS?style=flat-square&color=brightgreen" alt="GitHub stars">
    <img src="https://img.shields.io/github/forks/hxfyyds/JTYS?style=flat-square&color=blue" alt="GitHub forks">
    <img src="https://img.shields.io/github/last-commit/hxfyyds/JTYS?style=flat-square&color=orange" alt="最后提交">
    <img src="https://img.shields.io/github/license/hxfyyds/JTYS?style=flat-square" alt="开源协议">
    <br>
    <img src="https://img.shields.io/badge/Python-3.8+-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python版本">
    <img src="https://img.shields.io/badge/YOLOv8-ultralytics-FF6C37?style=flat-square" alt="YOLOv8">
    <img src="https://img.shields.io/badge/PyTorch-2.0+-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
    <img src="https://img.shields.io/badge/OpenCV-4.x-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
  </p>
</div>

---

## 📌 项目背景
我国老龄化进程加快，独居老人、空巢老人的居家安全问题日益突出，跌倒、突发疾病无人发现是老年人居家最大的安全隐患。

**家庭医生 '智'护银龄 3.0** 专为养老场景打造，基于改进YOLOv8深度学习框架，实现360°全景监控下的老年人日常行为实时识别与异常行为预警，无需穿戴设备，非接触式守护老人居家安全，可广泛应用于家庭独居老人监护、社区养老中心、养老院智能监控等场景。

## ✨ 核心功能亮点
- 🎯 **多场景行为精准识别**：支持跌倒、起身、坐卧、行走、长时间静止、突发倒地等10+种老年人常见行为检测，识别精度≥95%
- 📹 **360°全景无死角监控**：支持多路摄像头同时接入，兼容家用监控摄像头、电脑摄像头、USB摄像头，实现全区域覆盖
- ⚡ **毫秒级实时异常预警**：检测到跌倒、长时间静止等异常行为时，立即触发预警，可对接短信、微信、APP推送等多种通知方式
- 📊 **全维度数据可视化**：配套可视化管理后台，直观展示老人活动轨迹、行为频次统计、异常事件记录，方便家属/护工查看
- 🚀 **多设备轻量化部署**：支持电脑本地运行、边缘设备（Jetson Nano/树莓派）部署、服务器云端部署，低配置设备也能流畅运行
- 🧩 **全流程工具链支持**：提供从数据标注、模型训练、模型优化到部署落地的全套工具，新手也能快速上手二次开发

## 🛠️ 核心技术栈
| 技术领域 | 具体选型 |
|----------|----------|
| 核心检测算法 | 改进YOLOv8s 目标检测/行为识别模型 |
| 深度学习框架 | PyTorch 2.0+ |
| 视频流处理 | OpenCV 4.x |
| 后端服务 | Flask / FastAPI |
| 前端可视化 | Vue3 + Element Plus |
| 数据标注工具 | LabelImg / LabelMe |
| 模型部署 | ONNX Runtime / TensorRT |
| 数据存储 | SQLite / MySQL |

## 🚀 快速上手（3步跑通项目）
### 1. 环境配置
#### 方式一：pip一键安装（推荐新手）
```bash
# 1. 克隆仓库到本地
git clone https://github.com/hxfyyds/JTYS.git
cd JTYS

# 2. 创建并激活虚拟环境（可选，推荐）
conda create -n jtys python=3.9
conda activate jtys

# 3. 一键安装所有依赖
pip install -r requirements.txt
