####	定位

- ##### 定位模式

  - 固定定位 fixed
    - 不保留位置
    - 完全脱标
    - 以浏览器为准
  - 绝对定位 absolute
    - 完全脱标
    - 不占位置
    - 没有父亲以浏览器为准
    - 有父亲以父亲左上角为准
  - 相对定位 relative
    - 占有位置
    - 脱标
    - 以原来位置左上角
  - 静态定位 static

- ##### 边偏移

  - top
  - left
  - right
  - bottom

- ##### 小问题

  - 子绝父相 
  - 盒子居中: 50% + margin -盒子一半
  - absolud fix float 转换为inline-block

#### Css高级技巧

- ##### 显示和隐藏 display

  - 隐藏 display: none; 

    - 不保留位置

    - visibility 保留位置

  - 显示 display: block;

- ##### Overflow

  - hidden 溢出隐藏
  - scroll 总是显示滚动条
  - auto 需要时显示滚动条 

- ##### 鼠标样式 cursor

  - pointer 小手 
  - text 选择
  - move 十字架
  - default 默认

- ##### 轮廓线 outline

  - none 取消轮廓线

- ##### 防止拖拽文本域

  - resize ：none

- ##### vertical-align 控制图片和文字位置（行内块）

  - 四线
    - 顶线
    - 中线
    - 基线
    - 底线
  - middle和display：解决图片底部3px缝隙

- ##### 溢出文字隐藏(1+2+4)

  - white-space: nowrap 不换行
  - overflow: hidden 
  - text-overflow: clip 不显示 ...
  - text-overflow:ellipsis 显示...

- ##### CSS精灵技术 

  - 小图合大图 
  - 减少服务器压力
  - background-position来使用

- ##### 滑动门

  - a+span





































