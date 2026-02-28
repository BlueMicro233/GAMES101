# 大纲
只包含 Rendering 相关的部分，几何造型不感兴趣所以没做（

> [!NOTE]
> GAMES101 的课程作业在对应标题内容的下一节课放出，并且在下一节课通常会有重要知识补充。

> 例如 hw3 需要的法线计算实际上是在 Lecture 10 Geometry 1 (Introduction) 的前半部分介绍的，而不是在 Lecture 09 Shading 3 (Texture Mapping Cont.) 的部分。

- hw1：**旋转矩阵**和**透视投影矩阵**。
  
  - Lecture 01 Overview of Computer Graphics
  - Lecture 02 Review of Linear Algebra
  - Lecture 03 Transformation
  - Lecture 04 Transformation Cont.
 
<p align="center">
  <img src="https://github.com/BlueMicro233/GAMES101/blob/main/hw1/images/output1.png" width="234" height="238">
  <img src="https://github.com/BlueMicro233/GAMES101/blob/main/hw1/images/output2.png" width="234" height="238">
  <img src="https://github.com/BlueMicro233/GAMES101/blob/main/hw1/images/output3.png" width="234" height="238">
</p>
    
- hw2：**光栅化**和 **Z-Buffer** 算法。
  - Lecture 05 Rasterization 1 (Triangles)
  - Lecture 06 Rasterization 2 (Antialiasing and Z-Buffering)

  <img src="https://github.com/BlueMicro233/GAMES101/blob/main/hw2/output.png" width="234" height="238">

- hw3：**图形流水线**、**着色器**、**纹理映射**、**局部光照模型（Blinn-Phong）等**
  - Lecture 07 Shading 1 (Illumination, Shading and Graphics Pipeline)
  - Lecture 08 Shading 2 (Shading, Pipeline and Texture Mapping)
  - Lecture 09 Shading 3 (Texture Mapping Cont.)

<p align="center">
  <img src="https://github.com/BlueMicro233/GAMES101/blob/main/hw3/images/output_normal.png" width="230" height="230">
  <img src="https://github.com/BlueMicro233/GAMES101/blob/main/hw3/images/output_phong.png" width="230" height="230">
  <img src="https://github.com/BlueMicro233/GAMES101/blob/main/hw3/images/output_texmappedwithphong.png" width="230" height="230">
  <img src="https://github.com/BlueMicro233/GAMES101/blob/main/hw3/images/output_bump.png" width="230" height="230">
  <img src="https://github.com/BlueMicro233/GAMES101/blob/main/hw3/images/output_displacement.png" width="230" height="230">
</p>

- hw5：**递归式光线追踪** - **光线方程 $r(t) = \vec{o} + t \vec{d}$ 与成像平面**、**光线-三角形求交**算法（Moller-Trumbore 算法）

  - Lecture 13 Ray Tracing 1

<p align="center">
  <img src="https://github.com/BlueMicro233/GAMES101/blob/main/hw5/image/binary.png" width="640" height="480">
</p>

# 关于
GAMES101 是最好的中文图形学课程，不接受反驳。

当国内多数本科院校还在普遍教授很多逻辑结构都是碎的理论知识、老掉牙的图形 API、连专业术语翻译都和主流不接轨的时候，GAMES101 给了全国绝大部分的本科图形学课程一巴掌，让它们知道什么叫**现代计算机图形学**！！！

闫老师的授课给人一种亲切和有趣感，这种拉近听众与学科之间距离是很多**课程**难以做到的（当然也有图形学本身就散发魅力的原因）。由于图形学的确有难度，有趣和好玩的体验其实蛮重要的。

虽然笔者在两年多以前就接触到了这个神课，并且刷了不止一遍。但是作业还真没认真做过，由于之前上高中并没有时间配环境和写代码，现在得赶紧补上（（（

# 构建
这些作业经过我的验证都能在最新的 **Windows 11 (x86)** 和 **macOS 26 Tahoe (aarch64)** 上跑通。（它们之间只有 CMakeList.txt 的差异，这个可以询问 LLM 帮助解决）

持续施工中...
