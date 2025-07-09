<div align="center">

# Ollama Chat Home
<img src="https://img.picgo.net/2025/07/09/b10b8e4856010fe59cb5a3b8fb469c0c4a4ec994d036da05.png" alt="OllamaChatHome" border="0" width="70" height="70">

⭐ 一个基于Ollama API的赛博朋克风格聊天网页 ⭐

</div><br>



## 功能特点

- 🎨 赛博朋克风格UI设计，带霓虹灯效果
- 🤖 支持多种Ollama模型(Qwen3 4B等)
- 📝 内置Markdown渲染支持
- ⚙️ 顶部Bing搜索栏，作为浏览器首页使用
- 📌 预设prompt管理功能
- 📱 响应式设计，适配不同设备

## 安装与使用

### 前置要求

1. 确保已安装并运行[Ollama](https://ollama.ai/)
2. 默认API地址为`http://localhost:11434`
3. 安装好模型，如Qwen3:4b
```bash
ollama run qwen3:4b
```
### 快速开始

1. 克隆本仓库或下载代码
2. 直接在浏览器中打开`index.html`

## 配置说明

### API设置

- **API地址**: 默认为`http://localhost:11434`
- **API密钥**: 可选，用于认证

### 模型管理

1. 从下拉菜单中选择模型
2. 点击"设为默认"保存偏好

### Prompt预设

- 内置多种预设(日常助手、翻译助手、猫娘等)
- 可添加自定义预设
- 支持保存当前prompt内容

## 技术栈

- HTML5 & CSS3
- JavaScript (ES6+)
- [Marked.js](https://marked.js.org/) - Markdown渲染
- Ollama API

## 部署到GitHub Pages

1. Fork此项目
2. 进入仓库的Settings → Pages
3. 选择部署分支(通常是main或master)
4. 选择部署目录(如果是根目录则保留/)
5. 点击Save，等待部署完成
6. 访问提供的github.io链接即可使用

## 其他

可访问Releases下载打包版本

## 截图

<img src="https://img.picgo.net/2025/07/09/cebfd5ceebc1ed8d4d79ef5a0f12825eeae5fd7f1a73d8ce.png" alt="示例" border="0">

## 许可证

MIT License

## 贡献

欢迎提交Issue和Pull Request