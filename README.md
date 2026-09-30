<div align="center">

# 你好，我是 Marking 👋

**计算机视觉 · 嵌入式 AI 部署**
**Computer Vision · Embedded AI Deployment**

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)](https://isocpp.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)](https://opencv.org/)
[![ROS 2](https://img.shields.io/badge/ROS%202-22314E?style=flat-square&logo=ros&logoColor=white)](https://docs.ros.org/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://www.kernel.org/)
[![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)](https://cmake.org/)

<sub>中文 · <a href="#english">English</a></sub>

</div>

---

## 🔭 关于我 / About Me

- 🎯 方向：**目标检测**、**多目标跟踪**、**位姿解算**与**模型量化 / 端侧部署**。
- 📖 目前在做「**翻页检测**」：找书（书 + 手）→ 目标跟踪 → 翻页判定，跑通从数据到板端的完整链路。
- 🧪 也在把自训的 **YOLOv8 + DSConv 轻量骨干**（4 类，1.99 M 参数）从 PyTorch → ONNX → **RKNN int8** 量化，部署到 **RV1106（Luckfox Pico）** 板端。
- 🤖 写过 **RoboMaster 自瞄视觉**：灯条传统检测与神经网络检测并行，配 PnP 解算、EKF 预测与 ByteTrack 跟踪。
- 🧱 习惯把经典结构自己手写一遍 —— 比如从零实现 YOLOv8（Anchor-Free + DFL + Task-Aligned Assigner），而不是只调库。
- 🌱 正在补：C++ 工程化、CUDA / 算子优化、多传感器标定与融合。

## 🚀 精选项目 / Selected Projects

| 项目 | 说明 | 技术栈 |
| :--- | :--- | :--- |
| [**yolov8**](https://github.com/cpolarc/yolov8) | 从零手写 YOLOv8：模型结构与配置、DFL 边框回归、Task-Aligned 标签分配、损失与训练/推理流程 | `PyTorch` `Python` |
| [**rm**](https://github.com/cpolarc/rm) | RoboMaster 自瞄视觉（Mac 版）：传统灯条检测 + YOLO 检测、PnP 解算、EKF、BYTETracker、决策与配置模块 | `C++` `OpenCV` `Eigen` `CMake` |
| [**bishe**](https://github.com/cpolarc/bishe) | YOLO 检测 + ROS 2 集成：COCO→YOLO 数据转换、模型训练、pt→ONNX 导出、检测发布/订阅与 RViz 可视化 | `Python` `ROS 2` `RViz` |
| [**Armor_detect**](https://github.com/cpolarc/Armor_detect) | 装甲板检测早期版本：灯条配对、装甲板匹配、卡尔曼预测与 PnP 位姿解算 | `C++` `OpenCV` |

<details>
<summary>🧰 技能栈 / Tech Stack</summary>

| 分类 | 内容 |
| :--- | :--- |
| 语言 | Python、C++ |
| 深度学习 | PyTorch、Ultralytics YOLO、ONNX、RKNN（Rockchip NPU） |
| 视觉 | OpenCV、PnP / 相机标定、卡尔曼滤波、EKF、ByteTrack / SORT |
| 工程 | CMake、Linux、Git、ROS 2、RViz、Docker |

</details>

## 📊 GitHub 数据 / GitHub Stats

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=cpolarc&show_icons=true&hide_title=true&hide_rank=false&locale=cn&theme=algolia" alt="GitHub stats" />
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=cpolarc&layout=compact&exclude_repo=CV&locale=cn&theme=algolia" alt="Top languages" />

</div>

## 📫 联系我 / Contact

[![Email](https://img.shields.io/badge/Email-3550959735%40qq.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:3550959735@qq.com)

> 欢迎交流目标检测、跟踪与端侧部署相关的问题，也欢迎 Issue / PR。

---

<a id="english"></a>

## 🇬🇧 English

Hi, I'm **Marking** ([@cpolarc](https://github.com/cpolarc)) — a computer-vision engineer focused on **object detection, multi-object tracking, pose estimation, and embedded AI deployment**.

- 🔭 **Currently building:** a *page-turn detection* pipeline (find the book & hands → track → detect the page flip), from dataset to on-device inference.
- 🧪 **Also working on:** quantizing a self-trained **YOLOv8 + DSConv** model (4 classes, 1.99 M params) through PyTorch → ONNX → **RKNN int8**, deployed on an **RV1106 (Luckfox Pico)** board.
- 🤖 **Past work:** RoboMaster auto-aim vision — traditional light-bar detection running alongside a neural detector, with PnP pose solving, EKF prediction and ByteTrack.
- 🧱 I like re-implementing classic architectures from scratch (e.g. YOLOv8 with Anchor-Free heads, DFL regression and a Task-Aligned Assigner) instead of only calling libraries.

**Selected projects**

| Project | What it is | Stack |
| :--- | :--- | :--- |
| [**yolov8**](https://github.com/cpolarc/yolov8) | YOLOv8 written from scratch: model/config, DFL box regression, Task-Aligned label assignment, losses, training & inference | `PyTorch` |
| [**rm**](https://github.com/cpolarc/rm) | RoboMaster auto-aim vision: light-bar & YOLO detection, PnP solving, EKF, BYTETracker, decision module | `C++` `OpenCV` `Eigen` |
| [**bishe**](https://github.com/cpolarc/bishe) | YOLO detection + ROS 2 integration: dataset conversion, training, pt→ONNX export, detection pub/sub and RViz visualization | `Python` `ROS 2` |
| [**Armor_detect**](https://github.com/cpolarc/Armor_detect) | Earlier armor-detection version: light-bar pairing, armor matching, Kalman prediction, PnP | `C++` `OpenCV` |

📫 Reach me at **3550959735@qq.com** — happy to talk about detection, tracking or edge deployment.
