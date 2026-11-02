---
title: "QuickRef"
date: 2026-10-15T20:55:53+08:00
tags: ["server", "linux", "工具"]
---

# agent

## opencode

```bash
# 脚本安装
curl -fsSL https://opencode.ai/v2/install | bash

# npm 安装
npm install -g @opencode/cli
```

## hermes

```bash
curl -fsSL https://hermes-agent.nousresearch.com/install.sh | bash
```

## astrbot

```bash
# 安装
uv tool install astrbot --python 3.12

# 初始化（仅首次部署执行）
astrbot init

# 启动
astrbot run
```

# 代理

## sing-box

```bash
bash <(wget -qO- -o- https://github.com/233boy/sing-box/raw/main/install.sh)
```

## Xray

```bash
bash <(wget -qO- -o- https://github.com/233boy/Xray/raw/main/install.sh)
```

# 面板

## 1Panel

```bash
bash -c "$(curl -sSL https://resource.fit2cloud.com/1panel/package/v2/quick_start.sh)"
```

## MCSManager

> 重跑同一脚本即为更新。

```bash
sudo su -c "wget -qO- https://script.mcsmanager.com/setup_cn.sh | bash"
```

## Nginx UI

> 默认监听 `9000` 端口。

```bash
bash -c "$(curl -L https://cloud.nginxui.com/install.sh)" @ install -r https://cloud.nginxui.com/
```

# 运行环境

## uv

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

## Node.js

```bash
# 安装 nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash

# 载入 nvm（替代重启 shell）
\. "$HOME/.nvm/nvm.sh"

# 安装 Node.js 24
nvm install 24

# 验证
node -v   # 应输出 v24.x
npm -v    # 应输出 v11.x
```

