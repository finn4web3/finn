<h1 align="center">Hi, I'm Finn 👋</h1> 
<h3 align="center">🚀 Web3 DevOps Engineer | Python Automation | Blockchain Infrastructure</h3>

<div align="center" style="margin: 1em 0;">
  <button onclick="toggleLang()" style="padding: 8px 16px; font-size: 16px;">🌐 Switch to 中文</button>
</div>

<div id="lang-en">

## 🇬🇧 About Me (English)

I’m **Finn**, a Web3 infrastructure specialist helping blockchain teams deploy, monitor, and scale reliably with **Kubernetes**, **CI/CD**, and **Python** automation.

### 💼 What I Do
- Deploy and maintain full nodes (Ethereum, Bitcoin, Cosmos)
- Build Kubernetes & Docker-based infra environments
- Set up CI/CD pipelines (GitLab CI / Jenkins)
- Configure Prometheus + Grafana for monitoring
- Automate node health checks and infra tasks with Python
- Operate securely on AWS / Alibaba Cloud

</div>

<div id="lang-zh" style="display: none;">

## 🇨🇳 关于我（中文）

我是 **Finn**，一名专注于 **Web3 基础设施运维** 与 **Python 自动化开发** 的 DevOps 工程师。

### 💼 我擅长的工作
- 部署与维护主流公链节点（Ethereum / Bitcoin / Cosmos）
- 构建基于 Kubernetes 和 Docker 的链上服务环境
- 搭建 CI/CD 流水线（GitLab CI / Jenkins）
- 配置 Prometheus + Grafana 监控系统
- 使用 Python 编写自动化脚本和节点运维工具
- 熟练运维 AWS / 阿里云等主流云平台

</div>

---

## 🧰 Tech Stack

**DevOps**: Linux · Docker · Kubernetes · GitLab CI · Jenkins  
**Blockchain**: Ethereum · Bitcoin · Cosmos · RPC/Archive nodes  
**Monitoring**: Prometheus · Grafana · Loki  
**Cloud**: AWS · Alibaba Cloud · IAM · VPC · Security Groups  
**Automation**: Python · Bash · FastAPI · web3.py

---

## 🧪 Projects

| Project               | Description / 描述                          |
|-----------------------|---------------------------------------------|
| 🟢 `eth-node-deployer` | Deploy ETH nodes in one click / 一键部署 ETH 节点 |
| 📊 `chain-node-monitor` | Dashboards for ETH/BTC/Cosmos 节点监控     |
| ⚙️ `web3-node-api`     | Node health API using FastAPI               |
| 🧪 `py-chain-utils`    | Python 脚本集合，支持节点维护与数据分析     |

---

## 🤝 Let’s Work Together

**I’m open to**:
- Freelance Web3 DevOps / Cloud Ops work
- Web3 团队基础设施自动化支持
- 长期远程合作 / 顾问合作

📨 Email / 邮箱: **finn4web3@protonmail.com**  
💬 Telegram: [@finn4web3](https://t.me/finn4web3)  
🌐 GitHub: [github.com/finn4web3](https://github.com/finn4web3)

---

_"Automating Web3 from the ground up."_  
_"自动化构建下一代区块链基础设施。"_  

<script>
function toggleLang() {
  const en = document.getElementById('lang-en');
  const zh = document.getElementById('lang-zh');
  const button = event.target;
  if (en.style.display === 'none') {
    en.style.display = 'block';
    zh.style.display = 'none';
    button.innerText = '🌐 Switch to 中文';
  } else {
    en.style.display = 'none';
    zh.style.display = 'block';
    button.innerText = '🌐 Switch to English';
  }
}
</script>
