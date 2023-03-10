# IntervalTree-Visualization
可视化区间树插入、删除、查询过程。

## 主界面
![image](https://img-blog.csdnimg.cn/caac8b8b4ff14a468aa1c84abce17d6f.png#pic_center)

## 操作
在使用某个模块功能时，该模块对应的按钮需要被按下。
+ 1、插入区间
  + 以序列的形式插入，从第一个值起，两两一对，代表闭区间的左右端点。
    + 例：序列 1 2 3 5 6 8 表示三个序列[1,2], [3, 5], [6, 8]。
    + 应该输入偶数个值，且区间的左端点小于等于右端点。
    + 点击“插入区间列表”将从左到右向区间树中插入结点。
+ 2、查询区间
  + 输入需要查询的区间，点击“查询区间”。
    + 若有重叠区间，则返回一个答案，查找路径由蓝色虚线框标识，重叠区间由黄色虚线框标识。
    + 若无重叠区间，使用蓝色虚线框标识查找路径。
+ 3、删除区间
  + 鼠标点击想要删除的结点，若点中，结点高亮显示，并且在左侧显示结点信息，再点击“确认”进行删除。
  + 点击“删除全部”删除整棵区间树。
+ 4、视图缩放
  + 英文模式下，在键盘上敲击小写字母i可以放大视图，小写字母o可以缩小视图。
    
