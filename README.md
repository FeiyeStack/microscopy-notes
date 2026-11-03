# 光学显微镜原理 · 图文精读

iBiology *Microscopy Series* 的中文学习笔记：**9 章正文、187 张原片截图、9 张自己画的原理图**。
只整理"光学 + 探测器"这一条线——细胞生物学与荧光探针化学已剔除。

在线读：<https://feiyestack.github.io/microscopy-notes/>

## 这本书讲了什么

把 26 小时的课压成一条因果链：

> 光 → 折射/透镜 → 显微光路（无限远校正 + 柯勒照明）→ 物镜 NA → 衍射 → PSF
> → 分辨率 0.61λ/NA → 采样 → 相机 → 数字图像

每一节是「一句话结论 → 原片截图 → 关系图 → 易错点」，章末 3 道自测题。

## 目录

| | 章节 | 一句话 |
|---|---|---|
| — | [前言](preface.html) | 怎么读、速查表、出处与许可 |
| 01 | [光与折射](ch01-light.html) | 折射把球面波重新会聚，焦点其实是个艾里斑 |
| 02 | [显微光路与柯勒照明](ch02-path.html) | 无限远校正 + 柯勒照明，两条共轭面各管一件事 |
| 03 | [物镜与像差](ch03-objective.html) | NA 一个数定分辨率/亮度/光锥角 |
| 04 | [衍射与点扩散函数](ch04-diffraction.html) | 点不是点，是沙漏形的 PSF |
| 05 | [分辨率与采样](ch05-resolution.html) | 光学定极限，采样定"采不采得到" |
| 06 | [相机与数字图像](ch06-camera.html) | 光学已定，相机只负责采信 |
| 07 | [对比度四法](ch07-contrast.html) | 暗场/相差/偏振/DIC 各自把什么变成明暗 |
| 08 | [荧光与先进光路](ch08-fluorescence.html) | 共聚焦、双光子、光片、TIRF 的共同目标 |
| 09 | [超分辨](ch09-superres.html) | 三条路拆 200 nm 天花板 |

## 怎么用

直接打开 [index.html](index.html)（或上面的在线地址）；左侧目录可跳章，点图片可放大，`Ctrl+P` 可直接存 PDF。

阅读路线建议：01 → 02 → 03 → 04 → 05 → 06 先把主干打通，07–09 按需要看。

## 出处与许可

- **原片**：[iBiology Microscopy Series](https://www.ibiology.org/online-biology-courses/microscopy-series/)
  （Science Communication Lab），官方视频见其 [YouTube 频道](https://www.youtube.com/@scicommlab)；
- **截图来源**：187 张截图逐帧取自上述 YouTube 官方视频（720p）；
- **国内镜像**：[B站 搬运合辑 BV1e6Ks6CEaJ](https://www.bilibili.com/video/BV1e6Ks6CEaJ)，
  仅作备用链接与回看跳转；
- **许可**：截图与视频 © iBiology，依 CC BY-NC-ND 3.0 用于个人学习；中文解说、章节结构、
  9 张原理图为本次整理所作。**非官方、未授权、不盈利**；版权方认为不合适，告知即删。

## 关于这个仓库

本仓库是发布产物（静态 HTML + 图片），由本地 `build_pages.py` 生成后推送。
源 Markdown、截图原始文件与生成脚本不在本仓库内。

关系图（`assets/fig/` 下的 d1–d9）不是从原片描的，而是用薄透镜追迹、德拜积分等公式算出来再画的，
图注里的数值就是脚本输出，可以逐条核对。
