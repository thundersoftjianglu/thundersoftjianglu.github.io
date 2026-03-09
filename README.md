# CareLamp AI

AI 适老智能关怀灯 · 端侧多模态 AI Demo  
无感行为感知 + 主动情感陪伴 + 隐私闭环守护

这是一个纯前端静态演示站点（GitHub Pages），展示 ThunderSoft AIoT 团队针对银发群体的智能台灯概念：  
- 端侧实时跌倒检测（<5s 响应）  
- 行为模式学习 + 主动语音关怀  
- 完全本地隐私处理（无云端图像/语音上传）  
- 多模态融合（视觉姿态 + 语音 + 时序分析）

在线预览：  
🌐 https://thundersoftjianglu.github.io/

## 技术亮点

- **端侧主导架构**：NPU 推理（4-8 TOPS），延迟 <100ms，功耗 <10W  
- **跌倒检测**：YOLO-Pose/HRNet-tiny + 轻量 Transformer 时序模型  
- **主动关怀**：端侧行为模式学习 + 生成式语音（支持子女声音合成）  
- **隐私保护**：全本地闭环，仅匿名统计可选用于迭代  
- **前端实现**：纯 HTML/CSS/JS + Canvas 动画 + Mermaid 图表（无构建工具依赖）

## 快速预览截图

（你可以后续添加几张截图链接或直接嵌入）

- 首页外观与场景展示  
- 交互功能卡片翻转  
- Canvas 跌倒模拟动画  
- Mermaid 系统架构图

## 如何本地运行

1. Clone 仓库  
   ```bash
   git clone https://github.com/thundersoftjianglu/thundersoftjianglu.github.io.git