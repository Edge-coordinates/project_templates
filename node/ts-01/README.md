# Edge_Blog
 一个前后端分离的Blog系统

文件组织形式
``` 
cms/
├── modules/             #模块目录
│   ├── auth/            #权限管理模块
│   │   ├── controllers/ #控制器目录
│   │   ├── models/      #模型目录
│   │   ├── policies/    #策略目录
│   │   └── routes/      #路由目录
│   ├── post/            #文章管理模块
│   │   ├── controllers/ #控制器目录
│   │   ├── models/      #模型目录
│   │   ├── policies/    #策略目录
│   │   └── routes/      #路由目录
│   └── user/            #用户管理模块
│       ├── controllers/ #控制器目录
│       ├── models/      #模型目录
│       ├── policies/    #策略目录
│       └── routes/      #路由目录
├── config/              #配置文件目录
│   ├── database.js      #数据库配置文件
│   ├── middleware.js    #中间件配置文件
│   └── server.js        #服务器配置文件
├── public/              #公共资源目录
├── tests/               #测试文件目录
├── utils/               #公共工具函数目录
├── app.js               #应用入口文件
└── package.json         #项目依赖文件
```