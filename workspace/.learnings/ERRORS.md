# Errors Log

错误和问题记录。

## 如何使用

当发生以下情况时，记录错误：
- 命令返回非零退出码
- 异常或堆栈跟踪
- 意外的输出或行为
- 超时或连接失败

## 记录格式

```markdown
## [ERR-YYYYMMDD-XXX] skill_or_command_name

**Logged**: ISO-8601 timestamp
**Priority**: high
**Status**: pending
**Area**: frontend | backend | infra | tests | docs | config

### Summary
简要描述失败情况

### Error
\`\`\`
实际错误消息或输出
\`\`\`

### Context
- 尝试的命令/操作
- 使用的输入或参数
- 相关的环境细节

### Suggested Fix
可能的解决方案

### Metadata
- Reproducible: yes | no | unknown
- Related Files: path/to/file.ext

---
```

## 错误条目

（暂无）