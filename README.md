# meta-rules

Meta 系（Facebook/Instagram/WhatsApp/Threads/Oculus/Messenger/Meta AI）域名规则集，mihomo/Clash rule-providers 用。

```yaml
rule-providers:
  meta-rules:
    type: http
    url: https://raw.githubusercontent.com/pwremilk/meta-rules/main/meta-rules.list
    interval: 86400
    format: text

rules:
  - RULE-SET,meta-rules,美国自动
```

来源: v2fly/domain-list-community，每日 07:30 CST 自动重新生成。
