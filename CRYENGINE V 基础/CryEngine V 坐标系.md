# 坐标系统

## 概述

默认情况下，CRYENGINE使用Z轴向上的世界坐标系。
当直接使用坐标轴的辅助线框操作对象，可以改变不同的坐标系来操作对象。
可以直接通过坐标系工具栏改变坐标系。

图1:坐标系工具栏  
![](http://docs.cryengine.com/download/attachments/23308619/Toolbars_Coordinates.png?version=2&modificationDate=1456752532000&api=v2)

	

|# |	坐标系	  |	 描述												|
|--|--------------|-----------------------------------------------------|
|1 |   视图坐标系 |	在正交视图下使用，始终具有x/y坐标系（即：只能移动x轴，y轴）	|
|2 |   本地坐标系 |  使用物体的轴心进行操作									|
|3 |   父坐标系   |	使用对象的父级对象的轴心方向作为参考						|
|4 |   世界坐标系 |	使用世界坐标系的三维轴进行操作							|

## 视图坐标系 
和正交视图相关，在透视视图下相当于世界坐标系  
图2：
![](http://docs.cryengine.com/download/attachments/23308619/View%20coords.jpg?version=2&modificationDate=1457694053000&api=v2)

## 本地坐标系
In the picture below, only the cube has been rotated. Note how the axes are aligned to the cube.

使用所选择对象原本的轴心方向来移动/旋转/缩放。
在下图中，只有立方体被旋转。注意坐标轴如何被对齐到立方体的。
图3：
![](http://docs.cryengine.com/download/attachments/23308619/Local%20Coords.jpg?version=2&modificationDate=1457694647000&api=v2)

## 父坐标系
In parent mode, the order of the selection of objects determines the coordinates of which to rotate the selection around. The first object selected becomes the pivot point of which the orientation for translation/rotation/scaling is controlled.
Icon
This is a moving object concept, so it cannot be explained with a still picture.

## 世界坐标系

Uses the world's axis orientation for translation/rotation/scaling.
The Axis Gizmo always stays aligned with the world coordinate system. 
Icon
This is a moving object concept, so it cannot be explained with a still picture.