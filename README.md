# CareerIntent - AI 原生职业智能平台

## 项目概述
CareerIntent 是一个基于 AI 原生"意图驱动型"的职业发展系统，旨在帮助用户进行职业转型、面试准备和技能提升。

## 完成功能

### 1. 职业转型闭环
- 完善了职业转型流程，添加了"路线规划"和"实战训练"步骤
- 确保流程可重新开始：完成转型闭环后点击"职业转型"，会重新进行可行性评估

### 2. 面试安排闭环
- 添加了"专项补强"步骤
- 添加了"模拟实训"步骤
- 添加了"录用预测"步骤

### 3. 雷达图优化
- 修复了雷达图坐标轴过长问题
- 修复了雷达图背景和标注错位问题
- 确保能力雷达图与转型可行性评估保持一致

### 4. 数据可视化
- 补充了管理视图中的折线图（合同率趋势）
- 补充了管理视图中的饼图（职位分布）

### 5. 交互优化
- 处理非核心关键词输入，显示提示信息
- 优化了简历内容，使"原内容"和"AI 润色后"更贴近真实

### 6. 界面优化
- 欢迎界面重构：添加了AI头像，优化了布局和样式
- 输入框调整：增加了高度，优化了样式和位置
- 顶部导航栏优化：将工作台按钮从输入框下方移动到登录按钮左侧
- 移除了aside元素的底部边框，优化了视觉效果

### 7. 项目发布
- 使用PinMe工具将项目发布到IPFS网络
- 初始化了Git仓库并推送到GitHub

## 技术实现

### 前端技术栈
- HTML5 + CSS3 + JavaScript (ES6+)
- CSS Flexbox 和 Grid 布局
- SVG 图表绘制（折线图）
- CSS conic-gradient（饼图）
- JavaScript DOM 操作和事件处理
- CSS 动画和过渡效果
- 响应式设计

### 核心功能模块
- 智能对话系统
- 职业转型流程
- 面试准备流程
- 能力雷达图
- 数据看板
- 简历优化工具

## 发布信息

### 项目文件路径
- 主文件：`UI/index.html`
- 相关资源：同一目录下的静态资源

### 发布 URL
- https://pinme.eth.limo/#/preview/U2FsdGVkX1_MIo_qN-bQT0kX3KSfbugFrs8LmG7ocZGnGiRyZsFbSmSNNrCwMek7ZWiubo8Mzn36WecsiSO72mOgZsNIxIBYLp2JKRLD6pWhvyjR7AMyr9yB0lACR2c2Wcy9KhSVSugnHYplwU-Jxg
- https://pinme.eth.limo/#/preview/U2FsdGVkX1_ixAzYX1qPxy0TPlEs6ty7_2iuXFWL4eP9Hxq3bdKTO_cvPN7UEjozF8RMB6ELeO83nYQrmMAP3wXPax1vjjT3FaysO3WhFtMq_V1B3KwHqljMJ1H5Pfo_NklR_Au0spSu7TlAnj4xNQ

#### 预览 URL
- https://fceef13e.pinit.eth.limo
- https://369146d7.pinit.eth.limo

## 项目结构
```
/AI即时软件/
├── UI/
│   └── index.html          # 主页面文件
├── web/                    # Vue 项目目录
│   ├── dist/               # 构建输出目录
│   ├── src/                # 源代码
│   └── package.json        # 项目配置
└── doc/                    # 文档目录
    ├── 设计/               # 设计文档
    ├── 资料/               # 参考资料
    └── 需求文档/           # 需求文档
```

## 使用说明
1. 访问发布 URL 或本地运行 `python3 -m http.server 8000` 后访问 `http://localhost:8000`
2. 通过左侧导航栏或聊天界面的引导卡片进入不同功能模块
3. 按照流程指引完成职业转型、面试准备等任务
4. 输入关键词获取 AI 辅助建议，非核心关键词会显示提示信息

## 后续优化方向
- 增强 AI 对话能力，支持更多自然语言交互
- 完善数据看板，添加更多可视化图表
- 优化移动端适配，提升响应式体验
- 增加用户认证和数据存储功能
- 扩展更多职业发展相关的功能模块

## 开发团队
- 开发时间：2025年
- 技术栈：前端原生开发 + AI 集成
- 发布平台：PinMe IPFS 托管

---

**文档生成时间：** 2025年12月30日