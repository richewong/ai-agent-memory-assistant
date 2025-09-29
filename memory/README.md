﻿# Memory 文件夹索引

## 项目信息
- **项目名称**: 记忆库 (Memory System)
- **索引版本**: 1.0.0
- **最后更新**: 2025-09-27
- **记忆入口**: memory/memory.md
- **核心用途**: AI Agent 持续记忆系统

## 文件夹结构

### memory/
├── memory.md                    # 主记忆文件
├── README.md                    # 记忆文件夹索引
├── rules/                       # 规则文件夹
│   └── project.md               # 项目模板规则
├── preferences/                 # 偏好文件夹
│   └── development.md           # 开发偏好
├── history/                     # 历史文件夹
│   └── project-history.md       # 项目历史模板
├── changelog/                   # 更新日志模块 (按需启用)
│   └── changelog.md             # 当前项目更新日志
├── decisions/                   # 决策记录模块 (按需启用)
│   └── decisions.md             # 当前项目决策记录
├── docs/                        # 文档管理模块 (按需启用)
│   └── docs.md                  # 当前项目文档索引
├── notes/                       # 开发笔记模块 (按需启用)
│   └── notes.md                 # 当前项目开发笔记
├── prompts/                     # AI提示词模块 (按需启用)
│   └── prompts.md               # 当前项目提示词库
├── roadmap/                     # 项目路线图模块 (按需启用)
│   └── roadmap.md               # 当前项目路线图
└── templates/                   # 模板文件库
    ├── changelog-template.md      # 更新日志模板
    ├── changelog-example.md       # 更新日志示例
    ├── decisions-template.md      # 决策记录模板
    ├── decisions-example.md       # 决策记录示例
    ├── docs-template.md           # 文档模板
    ├── docs-example.md            # 文档示例
    ├── notes-template.md          # 开发笔记模板
    ├── notes-example.md           # 开发笔记示例
    ├── prompts-template.md        # 提示词模板
    ├── prompts-example.md         # 提示词示例
    ├── roadmap-template.md        # 路线图模板
    └── roadmap-example.md         # 路线图示例

## 记忆系统特点

### 核心功能
- **会话记忆**: 记录当前会话状态和进度
- **项目记忆**: 保存项目长期状态和演进历史
- **上下文恢复**: 解决会话中断和项目交接问题
- **知识积累**: 持续积累技术知识和经验

### 按需启用规则
1. **changelog/**: 项目有版本更新时启用
2. **decisions/**: 有技术决策时启用
3. **docs/**: 需要详细文档时启用
4. **notes/**: 学习记录时启用
5. **prompts/**: AI辅助开发时启用
6. **roadmap/**: 项目规划时启用

### 使用流程
1. 识别需要启用的功能模块
2. 从templates/复制对应模板到功能文件夹
3. 根据项目需求自定义内容
4. 定期维护和更新记忆内容

## 文件说明

### 核心文件
- **memory.md**: 项目长期记忆档案，包含项目概述、个性化规则、核心商业模式等
- **rules/**: 存放项目规则和模板规范
- **preferences/**: 存放个人偏好和开发习惯
- **history/**: 存放项目历史记录和模板
- **templates/**: 存放各种文档模板

### 模板文件
- **changelog.md**: 更新日志模板，用于记录项目版本更新
- **roadmap.md**: 路线图模板，用于规划项目发展
- **decisions.md**: 决策记录模板，用于记录技术决策
- **notes.md**: 开发笔记模板，用于记录学习笔记和经验
- **prompts.md**: 提示词模板，用于AI辅助开发
- **docs.md**: 文档模板，用于项目文档管理

## 使用指南

### 项目初始化
1. 复制 `memory/` 文件夹到新项目
2. 根据项目需求修改 `memory.md`
3. 使用相应的模板文件创建项目文档
4. 根据 `rules/` 中的规范进行开发

### 模板使用
1. 选择相应的模板文件
2. 复制模板内容到新文件
3. 根据项目需求填写模板内容
4. 保存到相应的项目目录

### 记忆管理
1. 定期更新 `memory.md` 中的项目信息
2. 在 `history/` 中记录项目历史
3. 在 `notes/` 中记录学习笔记
4. 在 `decisions/` 中记录重要决策

## 文件关系

### 依赖关系
- `memory.md` ← 所有模板文件
- `rules/` ← 项目模板规则
- `preferences/` ← 开发偏好
- `history/` ← 项目历史
- `templates/` ← 各种模板

### 引用关系
- 所有模板文件都引用 `memory.md` 作为记忆入口
- 模板文件之间可以相互引用
- 项目文档可以引用模板文件

## 维护要求

### 更新频率
- **memory.md**: 项目重大变更时更新
- **rules/**: 规则变更时更新
- **preferences/**: 偏好变更时更新
- **history/**: 项目里程碑时更新
- **templates/**: 模板优化时更新

### 版本管理
- 使用语义化版本号
- 记录每次更新的内容
- 保持向后兼容性

### 备份保护
- 定期备份重要文件
- 使用版本控制管理
- 保护敏感信息

## 扩展说明

### 自定义模板
- 可以根据项目需求创建自定义模板
- 模板应该遵循统一的格式规范
- 模板应该包含必要的元数据

### 模板优化
- 根据使用反馈优化模板
- 保持模板的通用性和实用性
- 定期更新模板内容

### 记忆扩展
- 可以根据项目需求扩展记忆内容
- 保持记忆内容的准确性和时效性
- 定期清理过时的记忆内容

## 联系方式
- **项目路径**: C:\Users\admin\1\test1
- **记忆文件**: memory/memory.md
- **最后更新**: [更新日期]




