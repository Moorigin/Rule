# Rule

> 免责声明：该项目仅供个人学习、交流，请勿用于非法用途，请勿用于生产环境  

## AI
- 人工维护
- 描述：文件包含了Claude、Gemini、OpenAI的规则。
- 使用说明：Surge使用RULE-SET，Sing-Box使用"format": "source"，Clash使用behavior: classical
### Surge
```
https://cdn.jsdelivr.net/gh/Moorigin/Rule@master/Surge/AI.list
```
### Sing-Box
```
  {
    "tag": "AI",
    "type": "remote",
    "format": "source",
    "url": "https://cdn.jsdelivr.net/gh/Moorigin/Rule@master/Sing-Box/AI.json",
    "download_detour": "AperNet"
  },
```
### Clash
```
  AI:
    type: http
    behavior: classical
    url: https://cdn.jsdelivr.net/gh/Moorigin/Rule@master/Clash/AI.yaml
    path: ./Rules/AI.yaml
    interval: 86400
```

## Apple
- 人工维护
- 描述：文件包含了Apple, Inc的域名。
- 使用说明：RULE-SET
### Surge
```
https://cdn.jsdelivr.net/gh/Moorigin/Rule@master/Surge/Apple.list
```

## iCloud
- 人工维护
- 描述：文件包含了iClude的规则。
- 使用说明：RULE-SET
### Surge
```
https://cdn.jsdelivr.net/gh/Moorigin/Rule@master/Surge/iCloud.list
```

## AsiaMedia
- 人工维护
- 描述：文件包含了Abema、Bahamut、DMM、HBO Asia、Netflix等规则。
- 使用说明：RULE-SET
### Surge
```
https://cdn.jsdelivr.net/gh/Moorigin/Rule@master/Surge/AsiaMedia.list
```
