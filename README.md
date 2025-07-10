# DubboMocker
DubboMocker是IDEA上的一款开发辅助工具插件，帮助开发者调试Dubbo客户端代码

## 场景
- 本地开发电脑无法连接集群注册中心
- Dubbo服务端未开发完成
- Debug 的代码调用了Dubbo接口，但是接口不可用
  
## 用法
在Dubbo接口上右键点击“Mock Dubbo Interface”，在弹窗中填写需要Mock的数据，无需重启项目，下次调用改接口时直接返回设置的Mock数据

![image](https://github.com/user-attachments/assets/d6e9665c-78be-4eae-8646-21d5048ba58e)
![image](https://github.com/user-attachments/assets/53e336ef-60df-4be3-8bc9-4c439c72ba0c)

## 配置
提供配置界面，灵活配置Mock 数据保存方式
![image](https://github.com/user-attachments/assets/e4ce3ed3-3b9f-4229-80a5-903a64709080)
