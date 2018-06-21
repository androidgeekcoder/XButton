# XButton
XButton取代各种shape文件
参考图片

![](https://github.com/zhxhcoder/XButton/blob/master/screenshots/xbutton.png)

~~~
    <com.zhxh.android.xbuttonlib.XButton
        android:id="@+id/XButton4"
        android:layout_width="100dp"
        android:layout_height="40dp"
        android:layout_marginLeft="112dp"
        android:layout_marginStart="112dp"
        android:layout_marginTop="204dp"
        android:text="圆角矩形 "
        android:textColor="@color/colorPrimary"
        app:XangleCorner="2dp"
        app:XstrokeColor="@color/colorPrimary"
        app:XstrokeWidth="1dp"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
~~~

实体的圆角矩形，需要配置三个字段
~~~
        app:XangleCorner="2dp"   //表示圆角
        app:XdefaultColor="@color/colorPrimary" //正常颜色
        app:XpressedColor="@color/colorPrimaryDark" //按压后的颜色
~~~

空心圆角矩形，需配置两个字段

~~~
        app:XangleCorner="2dp"   //表示圆角
        app:XstrokeColor="@color/colorPrimary" //表示边框颜色
        app:XstrokeWidth="1dp"               //表示边框宽度
~~~

