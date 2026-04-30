# sublime_thinkphp5

[![GitHub stars](https://img.shields.io/github/stars/chenbool/sublime_thinkphp5)](https://github.com/chenbool/sublime_thinkphp5/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/chenbool/sublime_thinkphp5)](https://github.com/chenbool/sublime_thinkphp5/network)
[![License](https://img.shields.io/github/license/chenbool/sublime_thinkphp5)](https://github.com/chenbool/sublime_thinkphp5/blob/master/LICENSE)

> Sublime Text 语法提示插件，支持 ThinkPHP5 框架

## 功能特性

| 特性 | 说明 |
|------|------|
| 代码片段 | 166+ 个代码片段 |
| 完整覆盖 | 覆盖 ThinkPHP5 核心功能 |
| 智能提示 | 支持 Tab 键快速补全 |
| 调试函数 | 内置常用调试方法 |

## 安装

| 工具 | 安装文档 |
|------|----------|
| Sublime Text | [sublime 安装教程](https://github.com/chenbool/sublime_thinkphp5/wiki/Sublime%E5%AE%89%E8%A3%85) |
| VS Code | [vscode 安装教程](https://github.com/chenbool/sublime_thinkphp5/wiki/vscode%E5%AE%89%E8%A3%85) |

## 演示

![1](./demo.gif)

![1](./demo2.gif)

![vscode](http://www.thinkphp.cn/Uploads/editor/2018-03-31/5abe9d671554c.png)

## 代码片段总览

| 分类 | 数量 | 说明 |
|------|------|------|
| Controller | 9 | 控制器相关 |
| Model | 9 | 模型关联 |
| DB | 44 | 数据库操作 |
| Request | 36 | 请求对象 |
| Route | 15 | 路由配置 |
| Cache | 7 | 缓存操作 |
| Cookie | 5 | Cookie 操作 |
| Session | 5 | 会话操作 |
| Log | 10 | 日志操作 |
| Validate | 6 | 验证器 |
| View | 2 | 视图渲染 |
| URL | 3 | URL 构建 |
| Bug | 4 | 调试函数 |
| File | 3 | 文件操作 |

## 核心功能详解

### 控制器 (Controller)

| 触发词 | 说明 |
|--------|------|
| `_initialize` | 初始化方法 |
| `assign` | 模板变量赋值 |
| `beforeActionList` | 前置操作列表 |
| `error` | 错误页面 |
| `redirect` | 重定向 |
| `remember` | 记住URL |
| `success` | 成功页面 |
| `view` | 渲染视图 |

### 数据库 (DB)

| 触发词 | 说明 |
|--------|------|
| `db` | 实例化数据库 |
| `table` | 指定表名 |
| `where` | 查询条件 |
| `field` | 指定字段 |
| `order` | 排序 |
| `limit` | 限制数量 |
| `page` | 分页 |
| `find` | 查询单条 |
| `select` | 查询多条 |
| `insert` | 插入数据 |
| `update` | 更新数据 |
| `delete` | 删除数据 |
| `query` | 原生查询 |
| `execute` | 原生执行 |
| `join` | 关联查询 |
| `union` | 联合查询 |
| `group` | 分组 |
| `having` | 条件分组 |
| `lock` | 锁机制 |
| `distinct` | 去重 |
| `alias` | 别名 |
| `comment` | 注释 |

### 模型关联 (Model)

| 触发词 | 说明 |
|--------|------|
| `hasOne` | 一对一关联 |
| `belongsTo` | 归属关联 |
| `hasMany` | 一对多关联 |
| `hasManyThrough` | 远距离一对多 |
| `belongsToMany` | 多对多关联 |
| `morphMany` | 多态关联 |
| `toArray` | 转换为数组 |
| `toJson` | 转换为JSON |
| `with` | 预加载 |

### 请求 (Request)

| 触发词 | 说明 |
|--------|------|
| `param` | 请求参数 |
| `get` | GET 参数 |
| `post` | POST 参数 |
| `request` | 请求参数 |
| `isAjax` | 是否 AJAX |
| `isGet` | 是否 GET |
| `isPost` | 是否 POST |
| `isPut` | 是否 PUT |
| `isDelete` | 是否 DELETE |
| `isMobile` | 是否手机 |
| `isCli` | 是否 CLI |
| `ip` | 获取IP |
| `module` | 模块名 |
| `controller` | 控制器名 |
| `action` | 操作名 |
| `url` | URL |
| `pathinfo` | PATH_INFO |
| `root` | 入口文件 |

### 路由 (Route)

| 触发词 | 说明 |
|--------|------|
| `get` | GET 路由 |
| `post` | POST 路由 |
| `put` | PUT 路由 |
| `delete` | DELETE 路由 |
| `any` | 任意路由 |
| `group` | 路由分组 |
| `domain` | 域名路由 |
| `bind` | 绑定模型 |
| `alias` | 路由别名 |
| `miss` | 路由 miss |
| `resource` | REST 资源 |
| `pattern` | 变量规则 |
| `rule` | 路由规则 |

### 缓存 (Cache)

| 触发词 | 说明 |
|--------|------|
| `cache` | 缓存设置 |
| `cacheget` | 获取缓存 |
| `cacheset` | 设置缓存 |
| `cacherm` | 删除缓存 |
| `cacheinc` | 缓存自增 |
| `cachedec` | 缓存自减 |
| `cacheclear` | 清空缓存 |

### 日志 (Log)

| 触发词 | 说明 |
|--------|------|
| `log` | 日志写入 |
| `logerror` | 错误日志 |
| `loginfo` | 信息日志 |
| `logwarning` | 警告日志 |
| `logdebug` | 调试日志 |
| `lognotice` | 通知日志 |
| `logcritical` | 临界日志 |
| `trace` | 页面Trace |

### 验证器 (Validate)

| 触发词 | 说明 |
|--------|------|
| `is` | 验证方法 |
| `in` | 区间验证 |
| `regex` | 正则验证 |
| `dateformat` | 日期格式 |
| `gt` | 大于验证 |
| `token` | 令牌验证 |

### 调试 (Bug)

| 触发词 | 说明 |
|--------|------|
| `debug` | 调试变量 |
| `dump` | 打印变量 |
| `abort` | 中止执行 |
| `404` | 404错误 |

## 使用示例

```php
// 数据库查询
Db::name('user')->where('id', 1)->find();

// 模型关联
$user->hasMany('orders')->select();

// 请求参数
request()->param('name');

// 缓存操作
Cache::get('key');

// 路由定义
Route::get('hello/:name', 'index/hello');
```

## 相关项目

| 项目 | 仓库地址 |
|------|----------|
| ThinkPHP5 语法提示 | https://github.com/chenbool/sublime_thinkphp5 |
| Yaf 语法提示 | https://github.com/chenbool/sublime_yaf |
| Swoole 语法提示 | https://github.com/chenbool/sublime_swoole |

## 交流群

- QQ 群：484043598

## License

MIT License
