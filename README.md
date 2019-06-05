# Photo-Wake-Up
对”Photo Wake-Up: 3D Character Animation from a Single Photo“论文的简单实现

smpl部分调用现有模型即可，并渲染得到深度图，法线图等


主要用过动态规划与中值坐标（tps效果似乎更好）计算点之间的对应关系



在构建深度图时采取的直接映射，没有使用论文中的方法（先求边缘点，再用最小二乘解内部点深度值）

![Alt text](/photo/duiy1.jpg "原图")
![Alt text](/photo/duiy2.jpg "smpl")

得到的3d模型效果并不好

正面<img src="/photo/xiaog.jpg" width="200">

侧面<img src="/photo/xiaog2.jpg" width="200">

背面<img src="/photo/xiaog3.jpg" width="200">
