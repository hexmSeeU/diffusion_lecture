# Diffusion Lecture Notes

这是一个关于扩散模型与 Flow Matching 的 LaTeX 讲义项目。

## 项目结构

- `main.tex`: 主入口文件。
- `tex/preamble.tex`: 宏包、命令与版式设置。
- `tex/chapters/`: 各章节内容。

## 编译

在项目根目录运行：

```powershell
xelatex main.tex
```

如需生成目录并确保交叉引用正确，通常需要连续编译两次：

```powershell
xelatex main.tex
xelatex main.tex
```

## 版本控制

仓库只跟踪 LaTeX 源文件和必要的说明文件。编译产生的中间文件、PDF、编辑器配置和临时文件均通过 `.gitignore` 忽略。
