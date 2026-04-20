---
title: 课程资料勘误
corrections:
  - title: "Lecture行列式讲义第2页笔误"
    date: "2026-03-09"
    thanks: "徐彤佳"
    content: |
      第2页三阶行列式的计算中，$\det(A)$的第五项$-a_{12}a_{23}a_{31}$应为$-a_{12}a_{21}a_{33}$，即公式应为:

      $$\det(A) = a_{11}a_{22}a_{33} + a_{12}a_{23}a_{31} + a_{13}a_{21}a_{32} - a_{11}a_{23}a_{32} - a_{12}a_{21}a_{33} - a_{13}a_{22}a_{31}$$
    
  - title: "Lecture讲义2第5页笔误"
    date: "2026-03-10"
    content: |
      第5页中第一个等式，消去矩阵乘以(8)的左侧系数矩阵，得到(10)的左侧系数矩阵应为：

      $$   \begin{bmatrix} 1 & 0 & 0 \\ -2 & 1 & 0 \\ 0 & 0 & 1 \end{bmatrix}\begin{bmatrix} 2 & 4 & -2 \\ 4 & 9 & -3 \\ -2 & -3 & 7\end{bmatrix} \begin{bmatrix}2 & 4 & -2 \\ 0 & 1 & 1 \\ -2 & -3 & 7 \end{bmatrix}.$$
  
  - title: "Lecture讲义3第4页笔误（3月23日再更新）"
    date: "2026-03-23"
    thanks: "徐彤佳"
    content: |
      第4页二阶矩阵的计算中，其逆矩阵必须满足应为：

      $$ A^{-1}A=I \quad \Longrightarrow \quad \begin{array}{rcc}ax+cy & = & 1 \\bx+dy & = & 0 \\az+cw & = & 1 \\ bz+dw & = & 0 \\ \end{array}$$ 
      
      第4页二阶矩阵的逆矩阵里，$x,y,z,w$ 的解缺少了一个系数，即：
      
      $$ x=\frac{1}{ad-bc}\cdot d,\ y=\frac{1}{ad-bc}\cdot (-b),\ z=\frac{1}{ad-bc}\cdot (-c),\ w=\frac{1}{ad-bc}\cdot a $$

  - title: "PPT课件2第20页笔误"
    date: "2026-03-16"
    thanks: "冯驰元"
    content: |
      第20页消元法解方程的矩阵形式中，应为：

      $$ \begin{bmatrix}
            2 & 4 & -2\\
            4 & 9 & -3\\
            2 & -2 & 4
        \end{bmatrix}\begin{bmatrix}
            x\\y\\z
        \end{bmatrix}=\begin{bmatrix}
            2\\8\\10
        \end{bmatrix}
        \qquad\Longrightarrow\qquad
        \begin{bmatrix}
            2 & 4 & -2\\
            0 & 1 & 1\\
            0 & 0 & 4
        \end{bmatrix}\begin{bmatrix}
            x\\y\\z
        \end{bmatrix}=\begin{bmatrix}
            2\\4\\8
        \end{bmatrix} $$
    
  -  title: "Lecture 7讲义第9页笔误"
     date: "2026-04-20"
     thanks: "鲁正仪"
     content: |
      第9页证明行交换不改变列秩的时候，比较应该是 $A$ 和 $A'$的第$k$个向量 $\mathbf{a}_k$和$\mathbf{a}'_k$：

      $$ \begin{aligned}
                    \mathbf{a}_k&=\begin{bmatrix}
                        a_{1k}&\ldots &{\color{red}a_{ik}}&\ldots &{\color{red}a_{jk}}&\ldots &a_{nk}
                    \end{bmatrix}^T\\  
                    \mathbf{a}'_k&=\begin{bmatrix}
                        a_{1k}&\ldots &{\color{red}a_{jk}}&\ldots &{\color{red}a_{ik}}&\ldots &a_{nk}
                    \end{bmatrix}^T
                \end{aligned} $$
      
      原来的版本下标有误，现已更正。

  -  title: "Lecture 8讲义第5页证明错误"
     date: "2026-04-20"
     content: |
      第5页关于引理 1.9 的 4: $(V^{\bot})^{\bot}=V$ 证明有误，新版本已经更正。
    
---
