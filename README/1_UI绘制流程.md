## UI绘制流程

* 绘制起始位置：
ViewRootImpl#performTraversals():<br>

  * performMeasure();//测量
  * performLayout();//布局
  * performDraw();//绘制

* Measure流程：<br>
查看ViewRootImpl#performMeasure(int childWidthMeasureSpec,int childHeightMeasureSpec);




