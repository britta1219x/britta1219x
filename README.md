# 你好，我是 Britta 👋

软件工程专业大四学生。

我做贴近系统层的东西：**用 C / eBPF 做底层监控、用 Ansible 做基础设施自动化，
也折腾 LLM 工具**——从头到尾自己做完，带测试、带 CI，不止是跑个 demo。

## 代表项目

### 🔭 [procwatch](https://github.com/britta1219x/procwatch)
一个用 C 写的 eBPF 进程监控工具。
- 独立的 `execve` 与 `openat` 两个 BPF 监控程序：分别盯进程执行和敏感路径的文件访问，并统计丢弃的事件
- 单元测试 + Makefile 构建
- GitHub Actions CI：在 Linux 上构建 BPF 监控程序（包括 bpftool 的处理）

### 🏗️ [ansible-web-cluster](https://github.com/britta1219x/ansible-web-cluster)
一套用 Ansible 端到端自动化的高可用 Web 集群。
- Nginx 节点 + Keepalived VIP 故障切换
- 按 role 组织：inventory、roles 和一个 `site.yml` 入口，一条命令部署

### 🧪 [llm-prompt-lab](https://github.com/britta1219x/llm-prompt-lab)
我的 LLM 提示词实验室，把提示词、评测和小工具放在一起，让实验可复现，
而不是只留在聊天记录里。目前有：一个中文写作教练提示词、它配套的评测集，
和一个用 Python 写的 prompt linter。

## 工具箱

`C` · `eBPF / Linux` · `Python` · `Ansible` · `Nginx` · `Keepalived` · `GitHub Actions`

## 正在做的

- 打磨 procwatch：更严格的路径校验、更完整的事件统计
- 把 llm-prompt-lab 从初始骨架长成一套带评测的提示词集

📫 在 GitHub 上找我：[@britta1219x](https://github.com/britta1219x)
