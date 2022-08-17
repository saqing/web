### 依赖管理
#### API
* oak

#### web
* pnpm create vite  // svelte-ts


设计
登录逻辑
* 客户连接钱包
* 客户签名
* 客户发送签名到后端获取JWT

付款逻辑
* 支付到智能合约
* 后端查账并缓存到 本地文件 (自己实现一个简单的KV数据库)

内容存储逻辑
* 跟随后端代码，放到 json 中，每次有新内容则发布新版本。

安全逻辑
* 环境变量
* 文件系统
* 网络访问


