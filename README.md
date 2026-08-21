# CodeType - 多语言代码打字练习

一个类似 speedcoder.net 的代码打字练习工具，通过打字练习编程思维。支持 GitHub 仓库导入，覆盖 Rust / Python / JavaScript / Go / Java / C++ 等多种编程语言。

## 功能特性

- **多语言示例片段**：内置 11 个精选代码片段，覆盖 6 种编程语言，分入门/进阶/高级三个难度
- **GitHub 仓库导入**：输入任意 GitHub 仓库地址，浏览并选择其中的代码文件进行练习
- **虚拟键盘与指法提示**：完整 QWERTY 键盘布局，9 种手指分区颜色标注，当前按键实时高亮
- **实时统计**：用时、CPM（每分钟字符数）、WPM（每分钟单词数）、准确率、错误次数、进度条
- **历史记录**：自动记住最近 3 个 GitHub 仓库地址，下次打开自动填充
- **最佳成绩**：每个片段的最佳 CPM 自动保存在本地
- **代码高亮**：正确字符绿色，错误字符红底，当前位置闪烁光标
- **可折叠键盘**：键盘固定在底部，可收起获得更大代码视野

## 使用方法

直接用浏览器打开 `index.html` 即可使用，无需安装任何依赖。

```bash
# 克隆仓库
git clone https://github.com/purejoy415/CodeType.git
cd CodeType
# 用浏览器打开
open index.html  # macOS
# 或直接双击 index.html
```

## 技术栈

- 纯原生 HTML / CSS / JavaScript，无框架依赖
- GitHub API 获取仓库文件树
- raw.githubusercontent.com 获取文件内容
- localStorage 本地存储历史记录和最佳成绩

## 支持的编程语言

Rust · Python · JavaScript · TypeScript · Go · Java · C · C++ · HTML · CSS · JSON · Markdown · Shell · Ruby · PHP · Swift · Kotlin

## 项目结构

```
CodeType/
├── index.html      # 主应用（单文件，包含所有 HTML/CSS/JS）
└── README.md       # 说明文档
```

## 打字指法说明

| 手指 | 负责按键 |
|------|----------|
| 左手小指 | ` 1 Q A Z Tab Caps Shift Ctrl |
| 左手无名指 | 2 W S X |
| 左手中指 | 3 E D C |
| 左手食指 | 4 5 R T F G V B |
| 右手食指 | 6 7 Y U H J N M |
| 右手中指 | 8 I K , |
| 右手无名指 | 9 O L . |
| 右手小指 | 0 P ; [ ] ' \ - = / Backspace Enter Shift |
| 大拇指 | Space |

## License

MIT
