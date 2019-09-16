# 第四次课：项目演示

## 一、项目开发

#### 1. 新建项目

克隆全栈数据云框架

```
git clone https://git.dev.tencent.com/ryn/nova-admin.git
```

> （没有权限就下载技术群里的源码包）

#### 2. 安装依赖

使用vscode打开项目文件夹，使用

```
npm i 
```

安装项目依赖

#### 3. 修改配置

从config文件夹赋复制config.dream.ts到src/app/，并改名为config.ts

#### 4. 启动项目

```
ng s -o
```

#### 5. 登录后台

在src/app/目录下的app.service.ts中查看项目用户名和密码，进行登陆

#### 6. 创建test子模块

右键modules文件夹，在终端中打开，使用指令

```
ng g m test
```

创建test子模块

#### 7. 添加新项目（模块）的账号密码

在src/app/目录下的app.service.ts中添加新模块（新项目）的账号密码等，此时，新的账号密码登陆以后默认只有**系统设置**和**开发者管理**这两个模块

#### 8. 后续配置

* 在providers文件夹中新建项目配置文件test.ts，配置好相关信息

* 在providers/cloud.ts文件中新增this.schemasExtend(TestSchemas)

* 在src/app/routes/目录下新建项目路由文件test.route.ts，配置好相关信息

* 在app-routing.module.ts文件中新增路由配置信息

#### 9. 模块新建完毕

重新登陆，刚才新建的模块就出来了，之后可以在后台直接操作

#### 10. 需要安装仪表盘，查看数据库

```
npm i -g parse-dashboard
```

#### 11. 查看postgreSql数据库

```
parse-dashboard --appId dream --masterKey DreamTest666 --serverURL https://server.hopecent.com/dream/parse
```

然后在浏览器中访问 localhost:4040 

## 二、基础功能使用

mark

## 三、高级组件使用

mark

## 四、部署上线

mark



## 五、项目管理

#### 需求签订

* 要去在合同签订的同时，签订需求确认书

#### 账号申请

* 域名
* 服务器
* 微信类
* SSL（https）
* 应用商店
* 云存储

#### 绘图

* 思维导图
* 数据字典
* 甘特图
* 功能分解

#### 进度管理和汇报

* 每日严格按照进度进行项目开发
* 每日工作汇报给上级

#### 安全备份

* 每日代码提交到云

#### 测试部署

* 部署到显示后，设置服务器每日镜像进行备份