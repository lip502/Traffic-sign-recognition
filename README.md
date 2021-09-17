# 基于MATLAB交通标志识别（GUI界面，论文）

#### 介绍
一、参考设计思路【图片可自定义，含GUI可视化界面】

1.读入图片，根据路标的颜色进行大致的分割
这是数据库中的二值图像，路标很多，所以选择几种典型的，我选择了的是：三角形（黄色）和圆形（红色）的，对应着禁止路标，警示路标，以及提示路标
2.然后是直方图灰度增强，这一步很重要，没这一步效果很不明显。
3.图像二值化，去除小干扰
4.内部填充，形成一个白色的圆
5.边界提取，一个圆形的白线


#### 软件架构
软件架构说明


#### 安装教程

1.  xxxx
2.  xxxx
3.  xxxx

#### 使用说明

1.  xxxx
2.  xxxx
3.  xxxx

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
