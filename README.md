## Motd_For_Minecraft ##

通过UDP协议获取MCPE的服务器状态

接口地址：`https://api.52craft.cc/v1/motd/`

请求方式：`GET/POST`

### 请求参数 ###

参数|示例|描述
-|-|-
ip|mc.52craft.cc|服务器IP地址
port|2020|服务器端口

### 返回参数 ###

参数|示例|描述
-|-|-
code|200|接口响应状态码
status|online|服务器状态
ip|mc.52craft.cc|返回查询IP
port|2020|返回查询端口
real|222.22.333.22|真实IP地址
location|北京省 联通|线路所在位置
motd|BorderLands In Minecraft|服务器广播内容Motd
agreement|389|协议版本
version|1.14.30|客户端版本
online|3|服务器在线人数
max|10|服务器人数上限
gamemode|Survival|游戏模式
delay|64|连接服务器延迟(ms)

示例：https://api.52craft.cc/v1/motd/?ip=mc.52craft.cc&port=2020

手动滑稽[滑稽]
