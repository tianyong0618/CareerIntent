# 项目初始化与核心架构实现计划

## 1. 项目初始化
- 使用 Vite 创建 Vue 3 项目，目标目录：`/Users/tianyong/Documents/works/workspace/hp/公司文档/AI调研/AI即时软件/web`
- 安装必要依赖：
  - Tailwind CSS（样式框架）
  - Pinia（状态管理）
  - Animate.css（动画效果）
  - Vue Router（可选，用于未来扩展）

## 2. 项目结构创建
按照要求创建以下文件结构：
```
src/
├── stores/
│   └── useIntentStore.js       # 意图管理状态
├── components/
│   ├── atoms/                  # 原子组件
│   │   ├── RadarChart.vue      # 雷达图组件
│   │   ├── JobCard.vue         # 岗位卡片组件
│   │   └── ChatWindow.vue      # 聊天窗口组件
│   └── IntentInput.vue         # 意图输入组件
├── views/
│   └── Home.vue                # 主工作台
└── styles/
    └── main.css                # 全局样式
```

## 3. 核心架构实现

### 3.1 Pinia 状态管理 (useIntentStore.js)
- 定义用户意图状态：`userDescription`
- 管理活跃卡片流：`activeTasks` 数组
- 实现意图解析 Mock 逻辑
- 处理卡片联动状态

### 3.2 主页面布局 (Home.vue)
- 实现极简设计，中央大输入框
- 支持深色/浅色模式切换
- 实现磨砂玻璃质感
- 动态渲染卡片流

### 3.3 意图输入组件 (IntentInput.vue)
- 大尺寸输入框设计
- 支持回车触发
- 加载动效实现

## 4. 场景一实现
- 用户输入意图后，输入框上移
- 显示“AI 正在解析意图...”动效
- 动态生成三张卡片：[能力画像]、[岗位匹配]、[表达力提升方案]
- 卡片采用水平平铺/瀑布流布局

## 5. 样式与动画
- 实现深色/浅色模式切换
- 卡片的平滑插入和切换动画
- 磨砂玻璃效果应用
- 加载动效设计

## 6. 后续场景实现计划
场景二和场景三将在场景一完成后逐步实现，包括卡片联动、交互扩展等功能。