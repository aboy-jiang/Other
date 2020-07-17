# Git代理设置和取消（全局）
```
git config --global http.proxy 'socks5://127.0.0.1:1080'
git config --global https.proxy 'socks5://127.0.0.1:1080'
```
```
git config --global --unset http.proxy
git config --global --unset https.proxy
```
