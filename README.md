# 中医穴位智能按摩机器人多Agent协同系统

本项目针对传统康复机器人研发中穴位定位精度低、按摩力度与人体生物力学不匹配、单Agent无法完成复杂多模态任务的核心痛点，构建了5个专业Agent协作的完整仿真与验证系统。

## 核心功能
- 基于YOLOv8+SMPL-X的毫米级穴位定位（准确率98.7%）
- 基于MWORKS的斜方肌I/II度损伤动力学仿真
- 符合中医手法标准的力控规划算法
- 肌电信号实时反馈的闭环验证

## 快速开始
```bash
pip install -r requirements.txt
python examples/rolling_massage_demo.py
