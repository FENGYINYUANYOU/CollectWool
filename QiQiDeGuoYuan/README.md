# 琪琪的果园
## 入口
威信小程序：琪琪的果园

## 抓包
登录抓包后找链接**url**请求头：https://www.weiju123.com/  
1、获取**Cookie**内容 格式：PHPSESSID=XXXX  
2、获取**Body/JSON**内容： {"buildid":1,"hv":"1.02","aot":"AOTXXXX"} 只要aot的值
### 青龙使用 

### 变量
多账户用@分开
```
export qqck='PHPSESSID=XXXX@PHPSESSID=XXXX'
export qqaot='AOTXXXX@AOTXXXX'
```

### 拉取
```
ql raw https://raw.githubusercontent.com/CollectWoolTeam/CollectWool/main/QiQiDeGuoYuan/qqdgy.js
```

### 注意
**获取运行后不要再手动进入游戏**，因为授权Cookie会失效，每次登录都需要重新抓包。

## 来源
https://github.com/LubooC/Script/blob/main/QQDGY/qqdgy.js
https://gitee.com/xiecoll/radish-script/raw/master/qqdgy.js（现版本）
