# Shadowrocket Rules Mirror

自动镜像 [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script) 的 `rule/Shadowrocket` 目录。

- 同步频率：每 6 小时
- 同步方式：仅在上游规则实际变更且校验通过时提交
- 失败保护：上游下载、目录或规则校验失败时，不会覆盖现有规则
- 请勿手动编辑 `Shadowrocket/`；下次同步会以官方上游为准
- 任意仓库更新也会触发一次安全的同步检查

## Shadowrocket 使用

在配置的“规则”中新增 `RULE-SET`，策略按规则用途选择。例如 TikTok：

```
https://raw.githubusercontent.com/643591978ling/shadowrocket-rules-mirror/main/Shadowrocket/TikTok/TikTok.list
```

规则文件的目录和文件名保持与上游一致。