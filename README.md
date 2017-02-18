# FireTeam
一个进击的小团队

## 工程文件树状图说明

```shell

.
├── Base.lproj							: 基础系统控件
├── CustomKit								: 自定义 UI 相关控件
├── FutureController					
│   ├── Common							: 公用特性控制器
│   ├── FuturePage						: 特性控制器 ( 页面或者特性划分 )
│   │   └── ExampleController			: 示例控制器
│   │   │		├── Model						
│   │   │	 	├── View
│   │   │	 	└── ViewController.swift		: 控制器 ( 存放在文件夹外 )
├── Global								: 全局文件夹
├── DataBase								: 本地数据库
├── Libraries								: 库文件源码
└── SupportFile							: 系统支持文件
│   └── AppDelegate.swift            : 应用代理类
└── Tool                             : 工具类

```