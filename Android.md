#### 第一章 Android基础入门

- 通信技术
  - 1G 2G 3G 4G
- Android起源
- 体系结构
  - 应用程序
  - 框架
    - VIEW
    - ACTIVITY MANAGER
    - NOTIFICATION MANAGER
  - 核心类库
  - Linux内核
- Dalvik虚拟机
  - 给予寄存器
  - 编译后文件 .dex .odex  

#### 第二章 UI布局

- 六大布局
  - 线性布局 LinearLayout
    - orientation 
      - vertical(垂直)
      - horizontal(水平)
    - weight 权重
  - 相对布局 RelativeLayout
  - 帧布局 FrameLayout
    - 图层设计
    - 默认显示在左上角
  - 表格布局 TableLayout
    - 于TableRow配合
  - 绝对布局 AbsoluteLayout
  - 网格布局 GridLayout
- 样式

  - 类似CSS
  - styles.xml
- 主题
- 国际化

#### 第三章 Activity

- 生命周期
  - 启动 运行 暂停 停止 销毁
- 启动模式
  - standard
  - singleTop 在顶部就不放入新的activity
  - singleTask 清除要启动的activity以上的activity
  - singleInstance 单独开辟任务栈
- Intent
  - 显式意图
  - 隐式意图
- Activity 数据传递
  - putExtra() 放入
  - getStringExtra()
- Activity 数据回传
  - startctivityForResult 
  - setResult
  - onActivityResult

#### 第四章 数据存储

- 文件存储
  - 内部存储
    - openFileOutput（）
    - openFileInput（）
  - 外部存储
- SharedPreferences
- XML
  - XML序列化
  - DOM解析
  - SAX解析
  - PULL解析