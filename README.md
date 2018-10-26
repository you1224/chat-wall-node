# Hi上墙 服务端+pc展示

项目主要分3部分
1、websocket服务 -wsServer
2、api服务 -apiServer 
3、pc端页面 -src 

# 目标功能

> wsServer (websocket服务 兼容小程序使用ws)
- [x] 启动websocket服务 -- 完成
- [x] 文本消息处理 -- 完成

> apiServer (api服务 数据库使用mysql)
- [ ] 签到接口
- [ ] 登录接口
- [ ] 获取成员列表
- [ ] 发送消息
- [ ] 获取消息列表

> src (pc端页面 由于特效依赖jQuery 使用gulp创建多页应用)
- [x] fullPage滚动切换页面 -- 完成
- [x] websocket连接 -- 完成
- [x] 文本消息处理 -- 完成
- [x] 弹幕
- [ ] 签到墙
- [ ] 抽奖

## 有问题

Welcome PR or Issue！

## 项目运行

```
git clone https://github.com/leesipeng/chat-wall-node.git  

cd chat-wall-node

npm install  或 yarn(推荐)

npm run dev

```


