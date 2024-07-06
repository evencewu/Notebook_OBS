# git代理设置

```bash
#使用socks5代理（推荐）
git config --global http.https://github.com.proxy socks5://127.0.0.1:7890
#使用http代理（不推荐）
git config --global http.https://github.com.proxy http://127.0.0.1:7890
```