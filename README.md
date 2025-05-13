# $`\textcolor{#a8cf36}{\text{TsingsiaOUTPUT}}`$
## $`\textcolor{#58cc84}{\text{———————————}}`$$`\textcolor{#40dda0}{\text{简介}}`$$`\textcolor{#58cc84}{\text{—————————}}`$
- 我的门户仓库  [![Static Badge](https://img.shields.io/badge/%E9%97%A8%E6%88%B7%E4%BB%93%E5%BA%93-TsingsiaOutput-a8cf36)](https://github.com/zju1229/Tsingsia229_OUTPUT)
## 仓库拓扑图

```mermaid
graph LR
  subgraph Private
    A[Tsingsia Private Part] -->|S229| B[Tsingsia229仓库]
    A -->|S516| C[Tsingsia516仓库]
  end
  D{Tsingsia Gate} -->|PASS| A
  D -->|FAIL| E[Tsingsia OUTPUT]
  subgraph Public Github
    E -->|尝试访问| D
    E -->|G1| F[个人主页 zju1229]
    F -->|G1| E
  end
  G[Visitors] --> E
  G --> F
```

```mermaid
graph LR
  A[Tsingsia516] --> B[Pointset Topology]
  A --> C[Mathematical Analysis]
  A --> D[General Physics]
  E[zju1229] -->|编写| A
```

```mermaid
graph LR
  A[Tsingsia229] --> G[Ass01]
  A --> B[Ass02]
  A --> C[Ass03]
  A --> D[Proj1 Mandelbrot]
  E[zju1229] -->|编写| A
  A --> F[抽卡]
```
---

## ——————————————————GATE————————————————
### ———————Part B 境内———————
- [S229](https://github.com/zju1229/Tsingsia229/tree/main)  [![Static Badge](https://img.shields.io/badge/%E7%A7%81%E6%9C%89%E4%BB%93%E5%BA%93-Tsingsia229-6699ff)](https://github.com/zju1229/Tsingsia229)  ->229仓库(CS)
- [S516](https://github.com/zju1229/Tsingsia516/tree/main) [![Static Badge](https://img.shields.io/badge/%E7%A7%81%E6%9C%89%E4%BB%93%E5%BA%93-Tsingsia516-58cc12)](https://github.com/zju1229/Tsingsia516)
->516仓库(MATH)

---

### ———————Part C 出境——————— 
- [G1](https://github.com/zju1229) [![Static Badge](https://img.shields.io/badge/%E4%B8%AA%E4%BA%BA%E4%B8%BB%E9%A1%B5-zju1229-cc99ff)](https://github.com/zju1229) ->首页
- [G11](https://github.com/BukSeong/58Glory) ->共享区
