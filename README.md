# windows-node-spawn-cli

在 Windows 上让 Node 脚本稳定调用 pnpm/npm 等 `.cmd`/`.ps1` 垫片 CLI。**优先复用标准轮子 `cross-spawn`，不要自造直调方案。**

## 适用对象

- DeepSeek Harness（DSH）用户：一个可由 AI agent 按需自动加载的 skill，克隆即用、无需构建。
- Windows 上写 Node 脚本调用 pnpm/npm 的开发者

## 目录结构

    windows-node-spawn-cli/
    ├── SKILL.md    技能入口与工作流

## 安装

    # GitHub
    git clone https://github.com/hpsks416/windows-node-spawn-cli.git "$env:USERPROFILE\.dsh\skills\windows-node-spawn-cli"
    # 或 Gitee（国内直连）
    git clone https://gitee.com/hpsks416/windows-node-spawn-cli.git "$env:USERPROFILE\.dsh\skills\windows-node-spawn-cli"

克隆后 DSH 自动重新发现，无需构建。

## License

MIT License. See [LICENSE](LICENSE).
