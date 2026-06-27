# 汉字谜盒 🧩

基于 **DeepSeek AI** 的互动猜字谜 Web 游戏，AI 智能出题、判题、给提示，支持多会话管理。

## 功能特性

- 🤖 **AI 智能出题** — 基于 DeepSeek 大模型随机出字谜，每次不重复
- ✅ **自动判题** — AI 判对错、给提示、揭谜底
- 📋 **多会话管理** — 新建/切换/删除会话，历史记录完整
- 🎨 **友好界面** — 简洁美观的 Web 前端

## 快速开始

### 前置要求

- Python 3.10+
- DeepSeek API Key（[免费申请](https://platform.deepseek.com/api_keys)）

### 安装与运行

```bash
# 1. 克隆仓库
git clone https://github.com/1104248149/hanzi-mihe.git
cd hanzi-mihe

# 2. 安装依赖
pip install -r requirements.txt

# 3. 配置 API Key
cp .env.example .env
# 编辑 .env 文件，填入你的 DEEPSEEK_API_KEY

# 4. 启动服务
python main.py
```

打开浏览器访问 **http://localhost:8000** 即可开始猜字谜！

### Windows 用户

也可以直接在 PowerShell 中设置环境变量后启动：

```powershell
set DEEPSEEK_API_KEY=your_api_key_here
python main.py
```

## 技术栈

| 层 | 技术 |
|------|----------|
| **后端** | FastAPI + Uvicorn |
| **前端** | HTML + CSS + JavaScript (原生) |
| **AI** | DeepSeek API (deepseek-v4-pro) |
| **序列化** | Pydantic + JSON |
