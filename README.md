# Rondo Desktop

## 网络请求清单

### 交易所与行情

| 域名 | 官方 |
|---|---|
| `okx.com` | ✅ |
| `binance.com` | ✅ |
| `hyperliquid.xyz` | ✅ |
| `backpack.exchange` | ✅ |
| `finance.yahoo.com` | ✅ |

### 券商本地网关

这两个是**本机进程**，app 只连 `127.0.0.1`，不直接连券商域名。

| 域名 | 官方 |
|---|---|
| `ibkr.com` | ✅ |

IBKR 网关（`127.0.0.1:28256`）自己连 `ibkr.com`；富途 OpenD（`127.0.0.1:11111`）连哪些域名由富途
客户端决定，不在本 app 的代码里。

### 按需下载（只在第一次用到该功能时）

| 域名 | 下载内容 | 官方 |
|---|---|---|
| `interactivebrokers.com` | IBKR Client Portal Gateway | ✅ |
| `adoptium.net` | Java 程序 （启动 IBKR） | ✅ |
| `futunn.com` | 富途 OpenD | ✅ |

### 自动更新

| 域名 | 官方 |
|---|---|
| `github.com` | ✅ |
| `githubusercontent.com` | ✅ |
