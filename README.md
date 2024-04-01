# 简介
本项目基于[@Toperlock/sing-box-geosite](https://github.com/Toperlock/sing-box-geosite)转换程序和[@Loyalsoldier/clash-rules](https://github.com/Loyalsoldier/clash-rules)的规则集，自动生成sing-box Source Format规则集，适用于clash的用户迁移至sing-box 使用 GitHub Actions 北京时间每天早上 6:30 自动构建，保证规则最新。

# 规则文件地址及使用方式

## 在线地址地址
- **直连域名列表 direct.json**：
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/direct.json](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/direct.json)
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/direct.srs](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/direct.srs)
- **代理域名列表 proxy.json**：
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/proxy.json](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/proxy.json)
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/proxy.srs](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/proxy.srs)
- **广告域名列表 reject.json**：
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/reject.json](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/reject.json)
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/reject.srs](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/reject.srs)
- **私有网络专用域名列表 private.json**：
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/private.json](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/private.json)
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/private.srs](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/private.srs)
- **Apple 在中国大陆可直连的域名列表 apple.json**：
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/apple.json](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/apple.json)
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/apple.srs](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/apple.srs)
- **iCloud 域名列表 icloud.json**：
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/icloud.json](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/icloud.json)
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/icloud.srs](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/icloud.srs)
- **[慎用]Google 在中国大陆可直连的域名列表 google.json**：
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/google.json](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/google.json)
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/google.srs](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/google.srs)
- **GFWList 域名列表 gfw.json**：
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/gfw.json](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/gfw.json)
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/gfw.srs](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/gfw.srs)
- **非中国大陆使用的顶级域名列表 tld-not-cn.json**：
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/tld-not-cn.json](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/tld-not-cn.json)
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/tld-not-cn.srs](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/tld-not-cn.srs)
- **Telegram 使用的 IP 地址列表 telegramcidr.json**：
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/telegramcidr.json](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/telegramcidr.json)
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/telegramcidr.srs](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/telegramcidr.srs)
- **局域网 IP 及保留 IP 地址列表 lancidr.json**：
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/lancidr.json](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/lancidr.json)
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/lancidr.srs](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/lancidr.srs)
- **中国大陆 IP 地址列表 cncidr.json**：
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/cncidr.json](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/cncidr.json)
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/cncidr.srs](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/cncidr.srs)
- **需要直连的常见软件列表 applications.json**：
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/applications.json](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/applications.json)
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/applications.srs](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/applications.srs)
- **OpenAI及相关AI地址列表 OpenAI.json**：
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/OpenAI.json](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/OpenAI.json)
  - [https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/OpenAI.srs](https://raw.githubusercontent.com/binam05/sing-box-geosite/main/Loyalsoldier_clash_rules/OpenAI.srs)

## 使用方式
规则集配置提供`json`和`srs`两种格式可以使用。
提供了一个sing-gox的规则集示例[sing-gox.json](https://github.com/binam05/sing-box-geosite/blob/main/sing-box.json)，可以直接使用。需要修改里面的`你的节点`和相应的节点配置，另外`你的直连域名`可以修改需要直连的域名，根据需要选择。


# sing-box-geosite

在links.json添加规则集，自动生成 sing-box Source Format。fork后自己添加想要转换的规则集，请生成token填写到仓库设置里让GitHub Actions有权限修改你的仓库

规则集源文件写法eg:

```json
{
  "tag": "geosite-wechat",
  "type": "remote",
  "format": "source",
  "url": "https://raw.githubusercontent.com/Toperlock/sing-box-geosite/main/wechat.json",
  "download_detour": "auto"
}
```

# 

# 致谢（排名不分先后）
[@Toperlock](https://github.com/Toperlock)

[@Loyalsoldier](https://github.com/Loyalsoldier)

[@izumiChan16](https://github.com/izumiChan16)

[@ifaintad](https://github.com/ifaintad)

[@NobyDa](https://github.com/NobyDa)

[@blackmatrix7](https://github.com/blackmatrix7)

[@DivineEngine](https://github.com/DivineEngine)
