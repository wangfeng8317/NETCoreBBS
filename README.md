# NETCoreBBS
ASP.NET Core Light forum NETCoreBBS

ASP.NET Core + EF Core Sqlite + Bootstrap 

.NET Core 跨平台轻论坛

[live demo](http://dotnet.link/)

## 开发

1. `git clone https://github.com/linezero/NETCoreBBS.git`
2. 使用 Visual Studio 2017 打开 `NetCoreBBS.sln` 
3. 点击 `调试->开始调试` 即可运行起来,或者直接点击工具栏上的`NetCoreBBS`即可。

注意：默认为80端口，可能会和本地端口冲突，可以到Program.cs 中更改 `.UseUrls("http://*:80")`,然后更改启动URL既可。


## 功能

1. 节点功能
1. 主题发布
2. 主题回复
3. 主题筛选
3. 用户登录注册
4. 主题置顶
5. 后台管理

## License
NETCoreBBS is licensed under [MIT](LICENSE).
