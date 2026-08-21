# CodeType - 算法代码打字练习

一个类似 speedcoder.net 的代码打字练习工具，通过打字练习经典算法与数据结构。支持 GitHub 仓库导入，内置 90 道经典手撕代码题。

## 功能特性

- **90 道经典题目**：数据结构 / 算法 / 深度学习三大分类，每类分入门 / 进阶 / 高级，共 90 题
- **纸墨双主题**：🖋️ 墨主题（暗色护眼）/ 📜 纸主题（亮色高对比），一键切换自动保存
- **注释自动跳过**：代码注释只显示不输入，专注代码逻辑
- **语法高亮**：关键字 / 字符串 / 数字 / 函数 / 类型分别着色，正确 / 错误 / 未输入三色区分
- **GitHub 仓库导入**：输入任意 GitHub 仓库地址，浏览文件树选择代码练习
- **虚拟键盘指法**：QWERTY 布局，9 区手指颜色标注，当前按键实时高亮
- **记录与进度**：每次练习自动保存历史记录，每道题记录最佳成绩，总进度 + 分类进度条
- **实时统计**：用时 / CPM / WPM / 准确率 / 错误数 / 进度条

## 题库分类

| 分类 | 语言 | 入门 | 进阶 | 高级 |
|------|------|------|------|------|
| 数据结构 | Rust | 数组、链表、栈、队列、哈希表、双指针、滑动窗口、前缀和... | 二叉树、BST、堆、图、并查集、Trie、单调栈/队列... | AVL、线段树、树状数组、跳表、LRU、AC自动机、红黑树... |
| 算法 | C | 排序、二分查找、递归、分治、贪心、DFS、BFS、DP基础... | 快排、归并、拓扑排序、KMP、背包、LCS、Dijkstra、Prim... | 区间DP、数位DP、状压DP、最大流、强连通分量、莫队、计算几何... |
| 深度学习 | Python | 感知机、线性回归、逻辑回归、激活函数、损失函数、梯度下降、反向传播... | CNN、RNN、LSTM、Attention、Transformer编码器、优化器、BatchNorm、Dropout... | 完整Transformer、BERT、GPT、ResNet、U-Net、GAN、VAE、强化学习、GNN、扩散模型 |

## 使用方法

直接用浏览器打开 `index.html` 即可，无需安装依赖。

```bash
git clone https://github.com/purejoy415/CodeType.git
cd CodeType
open index.html
```

## 在线访问

开启 GitHub Pages 后访问：`https://purejoy415.github.io/CodeType/`

## 技术栈

- 纯原生 HTML / CSS / JavaScript，单文件应用
- GitHub API 获取仓库文件树
- localStorage 本地存储主题、历史记录、最佳成绩、学习进度

## 项目结构

```
CodeType/
├── index.html      # 主应用（单文件，包含所有 HTML/CSS/JS）
└── README.md
```

## License

MIT
