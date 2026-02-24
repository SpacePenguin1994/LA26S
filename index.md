---
layout: home
title: 主页
nav_exclude: true
seo:
  type: 课程
  name: 线性代数
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- {% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %} -->

## 关于本课程

线性代数是学习自然科学的一门重要基础数学课程，其研究的对象是线性空间（又称向量空间）和线性空间之间的线性映射（又称线性变换）。更具体的来说，我们研究如下的线性方程：

- $a_1x_1 + a_2x_2 + \cdots + a_nx_n = b$,

和如下的线性变换：

- $(x_1,\ldots,x_n)\rightarrow a_1x_1 + a_2x_2 + \cdots + a_nx_n$

实际上，其几乎是所有数学领域的基础。 在这门课中，我们将从解方程组$A\mathbf{x}=\mathbf{b}$出发，引入并介绍关于矩阵$A$的四个重要子空间，进一步展现线性代数的基本定理。

关于课程介绍和课程要求的更多信息请关注[课程信息](syllabus.md)。

## 课程基本信息

**主讲人:** [杨启哲](https://basics.sjtu.edu.cn/~yangqizhe/), qzyang(at)shnu.edu.cn

**课程时间地点:** 
- 对于2025级计算机科学与技术师范本科1班的学生：
  - 周二第8-9节，奉贤3教楼512 (1-16周)
  - 周五第3-4节，奉贤3教楼412 (2-16周，双周)
- 对于2025级计算机科学与技术师范本科2班的学生：
  - 周二第6-7节，奉贤3教楼512 (1-16周)
  - 周五第3-4节，奉贤3教楼412 (1-15周，单周)


 更多信息可以关注 [课程安排](schedule.md).

## 期末考试

期末考试的具体信息会随着学期的进展进行公布。

## 课程反馈

我们建立了一个长期的课程反馈问卷:

- [《线性代数》课程调查问卷](https://www.wjx.cn/vm/YUMtljS.aspx)

欢迎大家提出关于本课程的问题或建议。



## 之前的课程资料

- [2025年春季学期](https://www.la2025s.spacepenguin.com.cn)
- [2024年春季学期](https://www.la2024s.spacepenguin.com.cn)

## 课程通知

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

