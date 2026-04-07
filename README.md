# Preliminary Study of Simulator - 仿真场景生成器

## 项目目标
根据导师要求，开发一个**仿真环境生成器**，主要支持：
- **MuJoCo**（MJCF XML 文件自动生成）
- **Isaac Sim**（USD 场景文件 + Replicator）

目标：通过程序化/参数化方式快速生成大量多样化仿真场景，用于机器人强化学习训练，提升场景数量和多样性。

## 当前进度
- [x] 仓库初始化
- [ ] 环境安装与测试
- [ ] 文献调研
- [ ] 手动创建场景实践
- [ ] 自动生成器开发

## 项目结构（建议）
preliminary-study-of-simulator/
├── docs/                  # 调研报告、笔记、设计文档
├── mujoco_scenes/         # MuJoCo 相关场景文件和生成器
├── isaac_scenes/          # Isaac Sim 相关场景和脚本
├── generator/             # 核心生成器代码
├── experiments/           # 测试实验和训练脚本
├── notebooks/             # Jupyter notebooks（快速测试）
├── requirements.txt
├── README.md
└── .gitignore

## 安装指南
（后续会补充）

## 参考资源
- MuJoCo 官方文档
- Isaac Sim + Isaac Lab 官方文档
- Infinigen-Sim（强烈推荐）

## 联系
导师：xxx  
开发者：novice857（准研究生）
