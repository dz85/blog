# Blog

## References

### Linux

- [Linux From Scratch 官网 - 内含中文版资料](https://www.linuxfromscratch.org/)
  > `Linux From Scratch (LFS)` is a project that provides you with step-by-step instructions for building your own custom Linux system, entirely from source code.
  >
  > `Beyond Linux From Scratch (BLFS)` is a project that continues where the LFS book finishes. It assists users in developing their systems according to their needs by providing a broad range of instructions for installing and configuring various packages on top of a base LFS system.
- google.com

### SaaS

- [12-factors - 内含中文版资料](https://12factor.net/zh_cn/)
  > 如今，软件通常会作为一种服务来交付，它们被称为网络应用程序，或软件即服务（SaaS）。12-Factor 为构建如下 SaaS 应用提供了方法论：
  > 使用标准化流程自动配置，从而使新的开发者花费最少的学习成本加入这个项目。
  >
  > - 和操作系统之间尽可能的划清界限，在各个系统中提供最大的可移植性。
  > - 适合部署在现代的云计算平台，从而在服务器和系统管理方面节省资源。
  > - 将开发环境和生产环境的差异降至最低，并使用持续交付实施敏捷开发。
  > - 可以在工具、架构和开发流程不发生明显变化的前提下实现扩展。
  >
  > 这套理论适用于任意语言和后端服务（数据库、消息队列、缓存等）开发的应用程序。

### Frontend

#### CSS

- [w3 Named Colors](https://www.w3.org/TR/css-color-4/#color-keywords)
  > CSS 的 16 种命名颜色最初来自 VGA 调色板，然后被采用到 HTML 中：
  >
  > name | description
  > ------------ | -------------
  > aqua| 浅绿色
  > black| 黑色
  > blue| 蓝色
  > fuchsia| 紫红色
  > gray| 灰色
  > green| 绿色
  > lime| 石灰
  > maroon| 栗色
  > navy| 海军蓝
  > olive| 橄榄色
  > purple| 紫色
  > red| 红色
  > silver| 银色
  > teal| 蓝绿色
  > white| 白色
  > yellow| 黄色
  >
  > 其余大部分来自 X11 颜色系统的一个版本，在 Unix 派生系统中用于为控制台指定颜色，然后被采用到 SVG 中。

- [w3 - named colors defined by SVG 1.1](https://www.w3.org/TR/SVG11/types.html#ColorKeywords)
  >
  > ```javascript
  > $$('.color-keyword-value').map($tr => [...$tr.parentElement.parentElement.children].map($td => $td.textContent)).map(([, a, b]) => [a, b.match(/\d+/g)]).filter(([, b]) => b[0]===b[1] && b[1]===b[2]).sort(([, b1], [, b2]) => b1[0]-b2[0])
  > ```
