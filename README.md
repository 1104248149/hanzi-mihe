# 汉字谜盒 🧩

基于 **DeepSeek AI** 的互动猜字谜 Web 游戏。

## 功能

- 🤖 AI 智能出题、判题、给提示
- 📋 会话管理（多轮对话、历史记录）
- 🎨 简洁美观的 Web 界面

## 快速开始

```bash
# 安装依赖
pip install -r requirements.txt

# 设置 DeepSeek API Key
# Windows:
set DEEPSEEK_API_KEY=your_api_key_here
# macOS/Linux:
export DEEPSEEK_API_KEY=your_api_key_here

# 启动服务
python main.py
```

打开浏览器访问 `http://localhost:8000` 即可开始游戏。

## 技术栈

- **后端**: FastAPI + Uvicorn
- **前端**: HTML + CSS + JavaScript
- **AI**: DeepSeek API (deepseek-v4-pro)
