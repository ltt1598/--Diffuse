# 太极图形课S1-Sparse Matrix示例程序-Diffuse
## 背景简介
本文实现了两个简单的离散热度场扩散运动。分别对显式和隐式的扩散方式进行了模拟。

## 成功效果展示
![diffuse demo](./data/diffuse.gif)
## 整体结构（Optional）
```
├── data
│   └── diffuse.gif
├── images
├── .gitignore
├── README.md
├── LICENSE
├── diffuse_explicit.py
├── diffuse_explicit_2.py
├── diffuse_implicit.py
├── diffuse_explicit_profiling.py
└── requirements.txt
```

## 运行方式
运行环境：

```
[Taichi] version 0.8.3, llvm 10.0.0, commit 021af5d2, win, python 3.8.10
```

按键

- `Space` : 暂停/继续
- `i` : 运行时导出图片/停止导出（导出的图片会存放在./images/目录下）
- `r` : 重置