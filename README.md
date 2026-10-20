# rules

Clash/mihomo 规则集（.mrs，behavior: domain）。

- `ai/Ai.mrs`：由 https://ddgksf2013.top/filter/Ai.yaml 转换（101 条 DOMAIN / DOMAIN-SUFFIX）
- `ai/Ai.domain.txt`：转换用的中间文本
- `apple/AppleIntelligence.mrs`：由 https://raw.githubusercontent.com/ddgksf2013/Filter/refs/heads/master/AppleIntelligence.list 转换（11 条 DOMAIN-SUFFIX，Apple Intelligence / Siri 相关域名）
- `apple/AppleIntelligence.domain.txt`：转换用的中间文本

重新生成：`mihomo convert-ruleset domain text ai/Ai.domain.txt ai/Ai.mrs`

重新生成 Apple Intelligence：`mihomo convert-ruleset domain text apple/AppleIntelligence.domain.txt apple/AppleIntelligence.mrs`

订阅链接：https://raw.githubusercontent.com/beihaijiandui-solon/rules/main/apple/AppleIntelligence.mrs
