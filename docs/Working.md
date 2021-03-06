# 主要功能

- 时间处理与状态管理
  - [X] 定期保存快照
  - [X] 事件处理异常时恢复状态
- 事件和状态的存储支持
  - 数据库支持
      - [X] 内存
      - [X] SQLite
      - [X] Mysql
      - [X] Postgresql
      - [X] Mongo
  - 存储策略
      - [X] Shared Table or Collection
      - [X] One Id One Table or Collection
      - [X] One Type One Table or Collection
- 存储通用功能
  - [X] 存储结构自动迁移
  - [ ] 可导出存储结构迁移脚本
- 全球化与本地化
  - [X] 框架
  - [ ] 替换现有所有文本
  - [X] 支持启动时配置
- [X] Minions
- 事件处理广播器与接收器
  - [X] 基于Orleans直接调用
  - [X] RabbitMQ
- 事件与状态序列化
  - [X] Json
  - [ ] Binary
- Claptrap Design
  - [X] 全局 Design
  - [X] 启动时变更 Design
- 导出查看
  - [X] 导出 Json
  - [X] 导出 Markdown
  - [ ] 关系图展示
- [ ] 配置文件式设计 Design
- 单元测试
  - [X] 覆盖率80%以上
  - [ ] 覆盖主要的异常抛出情况
- 指标监控
  - [X] 事件处理器
  - [X] Claptrap生命周期
  - [X] 存储迁移状态
  - [X] 存储使用
  - [ ] 链路追踪
- 开发工具
  - [X] 项目模板  
- 代码样例
  - [X] [单体式运行](https://github.com/newbe36524/Newbe.Claptrap.Examples/tree/master/src/Newbe.Claptrap.OutofOrleans)
  - [X] [Orleans 结合](https://github.com/newbe36524/Newbe.Claptrap.Examples/tree/master/src/Newbe.Claptrap.ArticleManager)
  - [ ] Minions
