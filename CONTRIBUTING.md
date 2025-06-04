# 贡献指南

感谢您对学生成果管理系统的关注！我们欢迎各种形式的贡献，包括但不限于功能开发、bug修复、文档改进、测试用例编写等。

## 贡献流程

1. 在GitHub上Fork本仓库
2. 克隆您的Fork到本地
   ```bash
   git clone https://github.com/YOUR_USERNAME/01-.git
   cd 01-
   ```
3. 创建新的分支
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. 进行开发和测试
5. 提交您的更改
   ```bash
   git add .
   git commit -m "feat: 添加了某功能"
   ```
6. 推送到您的Fork
   ```bash
   git push origin feature/your-feature-name
   ```
7. 创建Pull Request

## 分支命名规范

- `feature/*`: 新功能开发
- `bugfix/*`: Bug修复
- `docs/*`: 文档更新
- `test/*`: 测试相关
- `refactor/*`: 代码重构
- `style/*`: 代码风格调整（不影响功能）
- `chore/*`: 构建过程或辅助工具的变动

## 开发步骤

1. 确保您已经阅读了项目的README.md和开发指南
2. 在开始开发前，请先创建一个Issue描述您要解决的问题或添加的功能
3. 按照上述贡献流程进行开发
4. 确保您的代码符合项目的代码规范
5. 编写必要的测试用例
6. 提交Pull Request

## 提交规范

我们使用[Conventional Commits](https://www.conventionalcommits.org/)规范来格式化提交信息。

格式如下：
```
<type>(<scope>): <subject>

<body>

<footer>
```

其中：
- `type`: 提交类型，如feat, fix, docs, style, refactor, test, chore等
- `scope`: 影响范围，如组件名、文件名等（可选）
- `subject`: 简短描述
- `body`: 详细描述（可选）
- `footer`: 关闭issue等信息（可选）

示例：
```
feat(auth): 添加用户登录功能

实现了用户登录的前端界面和后端API

Closes #123
```

## Pull Request规范

1. 确保PR标题清晰地描述了您的更改
2. 在PR描述中详细说明您的更改内容、原因和影响
3. 关联相关的Issue
4. 确保所有CI检查都通过
5. 请求至少一位维护者进行代码审查

## 代码规范

请参考项目中的`.eslintrc`、`.prettierrc`等配置文件，确保您的代码符合项目的代码规范。

## 问题报告

如果您发现了bug或有新功能建议，请创建一个Issue。在创建Issue时，请使用提供的模板，并尽可能详细地描述问题或建议。

## 行为准则

请参阅我们的[行为准则](CODE_OF_CONDUCT.md)，以了解我们社区的行为标准。

## 许可证

通过贡献代码，您同意您的贡献将根据项目的许可证进行许可。
