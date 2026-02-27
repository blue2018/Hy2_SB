# Sing-box 一键部署脚本
Sing-box 自动化部署工具，支持HY2协议

## ✅ 一键部署命令
Hy2+Ech / VLESS + HttpUpgrade + Argo：
```bash
curl -fsSL -H "Cache-Control: no-cache" https://raw.githubusercontent.com/blue2018/Hy2_SB/refs/heads/main/hy2_ech_argo.sh -o /usr/local/bin/hy2_ech_argo.sh && chmod +x /usr/local/bin/hy2_ech_argo.sh && hy2_ech_argo.sh
```
TEST:
```bash
bash -c "$(curl -fsSL -H "Cache-Control: no-cache" https://raw.githubusercontent.com/blue2018/Hy2_SB/refs/heads/main/test.sh?$(date +%s))"
```
