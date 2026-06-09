momo-finance/
├── src/
│   ├── app/
│   │   ├── (main)/           # 主页面组
│   │   │   ├── page.tsx      # 首页 - AI 聊天
│   │   │   ├── goals/        # 目标管理页
│   │   │   ├── insights/     # 财务洞察页
│   │   │   └── profile/      # 个人设置页
│   │   ├── api/              # API 路由
│   │   │   ├── chat/         # AI 对话
│   │   │   ├── transactions/ # 交易记录
│   │   │   └── monthly-review/
│   │   ├── globals.css       # 全局样式
│   │   └── layout.tsx        # 根布局
│   ├── components/
│   │   ├── cards/            # 卡片组件
│   │   ├── chat/             # 聊天界面
│   │   ├── modals/           # 弹窗
│   │   └── navigation/        # 导航
│   ├── lib/
│   │   ├── ai/               # AI Pipeline
│   │   ├── supabase/         # 数据库客户端
│   │   ├── store.ts          # Zustand 状态管理
│   │   └── utils.ts          # 工具函数
│   └── types/                # TypeScript 类型
├── supabase/
│   └── schema.sql            # 数据库 Schema
├── package.json
├── tailwind.config.ts       # 设计系统配置
└── README.md
