# Rule

> 免责声明：该项目仅供个人学习、交流，请勿用于非法用途，请勿用于生产环境  
### Surge  
- 使用说明：Surge使用RULE-SET，Sing-Box使用"source"，Clash使用"classical"  
- MAIN分支：
```
https://raw.githubusercontent.com/Moorigin/Rule/main/Surge/AI.list
```
- MAIN分支CDN：
```
https://cdn.jsdelivr.net/gh/Moorigin/Rule@main/Surge/AI.list
```
### Sing-Box  
- 在links.txt添加规则集，自动生成 sing-box Source Format。  
- 规则集源文件写法eg:  
```
{
  "tag": "WeChat",
  "type": "remote",
  "format": "source",
  "url": "https://raw.githubusercontent.com/Moorigin/Rule/main/Sing-Box/wechat.json",
  "download_detour": "USA"
}
```
