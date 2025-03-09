# 中文学术自述文档LaTeX模板

天下人苦Word久矣。这是一个用于研究生复试、自荐信或其他学术场合的中文自述文档LaTeX模板，采用XeLaTeX编译，支持中文排版。

## 特点

- 规范的学术文档格式
- 优雅的中文排版与字体设置
- 采用中文数字编号的小节标题

## 使用方法

### 环境要求

- TeX发行版：TeX Live、MiKTeX或MacTeX
- 编译方式：XeLaTeX

### 编译步骤

1. 安装所需的LaTeX包和字体
2. 使用XeLaTeX编译：
   ```
   xelatex template.tex
   ```

### 模板结构

模板包含以下主要部分：
- 个人基本信息（姓名、学校、专业等）
- 政治表现
- 外语水平
- 业务和科研能力
- 研究计划
- 总结

## 自定义

### 字体设置

模板提供了两种设置中文字体的方式：
1. 直接指定字体（需系统安装对应字体）：
   ```latex
   \setCJKmainfont{Source Han Serif CN}[AutoFakeBold=true]
   ```

2. 使用ctex包自动配置（推荐）：
   ```latex
   \usepackage[UTF8]{ctex}
   ```

### 页面设置

可通过修改geometry包参数来调整页边距：
```latex
\geometry{
  top=2.54cm,
  bottom=2.54cm,
  left=3.18cm,
  right=3.18cm
}
```

## 许可

MIT License
