# my-note-of-MATH
self study/ 其实是为了防止被自家数学老师炸死

<div align="center">

# 📚 My Note of MATH

> **个人数学笔记 — IGCSE / A-Level / Further Math**
>
> 完整知识体系 + 详细例题 + 考点分类整理

[![Mathematics](https://img.shields.io/badge/Subject-Mathematics-005B96?style=for-the-badge&logo=mathworks&logoColor=white)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub](https://img.shields.io/badge/maintained%20with-❤️-ff69b4?style=flat-square)]()

</div>

- **开源与分享**：所有内容都以 **MIT** 许可证开放，任何人可以自由使用与分享。


---
# 配方法（详细讲解）

配方法是代数中的一种恒等变形技巧，核心是**将二次式写成完全平方加常数**的形式。

## 一、基础公式

完全平方公式：
\[
(a \pm b)^2 = a^2 \pm 2ab + b^2
\]

对于 \(x^2 + bx\)：
\[
x^2 + bx = \left(x + \frac{b}{2}\right)^2 - \left(\frac{b}{2}\right)^2
\]

## 二、一般步骤（\(ax^2 + bx + c\)，\(a \neq 0\)）

1. **提取二次项系数**：
   \[
   ax^2 + bx + c = a\left(x^2 + \frac{b}{a}x\right) + c
   \]

2. **括号内配方**：
   \[
   x^2 + \frac{b}{a}x = \left(x + \frac{b}{2a}\right)^2 - \left(\frac{b}{2a}\right)^2
   \]

3. **代回整理**：
   \[
   ax^2 + bx + c = a\left(x + \frac{b}{2a}\right)^2 + \frac{4ac - b^2}{4a}
   \]

## 三、典型例子

### 例1：\(x^2 + 6x + 5\)
\[
x^2 + 6x + 5 = (x^2 + 6x + 9) - 9 + 5 = (x+3)^2 - 4
\]

### 例2：\(2x^2 - 8x + 3\)
\[
2(x^2 - 4x) + 3 = 2[(x-2)^2 - 4] + 3 = 2(x-2)^2 - 5
\]

### 例3：\(-x^2 + 4x - 1\)
\[
-(x^2 - 4x) - 1 = -[(x-2)^2 - 4] - 1 = -(x-2)^2 + 3
\]

## 四、主要应用

### 1. 解二次方程
例：\(x^2 + 4x - 5 = 0\)  
\((x+2)^2 - 9 = 0 \Rightarrow (x+2)^2 = 9 \Rightarrow x = 1 \text{ 或 } x = -5\)

### 2. 求二次函数最值（顶点）
\(y = 2x^2 - 8x + 3 = 2(x-2)^2 - 5\)，顶点 \((2,-5)\)，最小值 \(-5\)。

### 3. 推导求根公式
从 \(ax^2+bx+c=0\) 配方得：
\[
\left(x + \frac{b}{2a}\right)^2 = \frac{b^2-4ac}{4a^2}
\]
开方即得：
\[
x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}
\]

### 4. 判断正负、化简圆方程等

## 五、注意事项

- \(a \neq 1\) 时**必须**先提取 \(a\)。
- 一次项系数为负时，一半也是负的。
- 开方时不要忘记 \(\pm\)。

## 六、练习题

1. \(x^2 + 10x - 3\) → \((x+5)^2 - 28\)
2. \(3x^2 - 12x + 7\) → \(3(x-2)^2 - 5\)
3. 解 \(x^2 - 6x + 2 = 0\) → \(x = 3 \pm \sqrt{7}\)
4. 求 \(y = -2x^2 + 8x - 5\) 的最大值 → \(-2(x-2)^2 + 3\)，最大值 \(3\)

---
