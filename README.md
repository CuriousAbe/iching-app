# 易经算卦应用（长期本地版）

## 启动
```bash
cd /root/.openclaw/workspace/iching-app
python3 -m http.server 8899
```
打开 `http://<你的IP>:8899`

## 特性
- 三枚铜钱法六爻起卦
- 本卦/变卦展示
- 本地历史记录（localStorage）
- PWA 离线可用（Service Worker）

## 长期稳定使用建议
1. 固定本地服务端口（8899）
2. 用 systemd/pm2 守护运行
3. 外网长期访问建议绑定自己的域名 + Cloudflare Tunnel（固定域名）
