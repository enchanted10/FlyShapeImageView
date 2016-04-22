#FlyShapeImageView

这是一个拥有圆角和圆形功能的ImageView

###Demo


![](/image/1.png)

--

###Gradle
```
dependencies {
	compile 'com.recker.flyshapeimageview:flyshapeimageview:1.0'  
}

```

--

###Usage

**圆形**

```java
<com.recker.flyshapeimageview.ShapeImageView
	android:layout_width="150dp"
	android:layout_height="150dp"
	android:src="@drawable/yu"
	app:shape_mode="circle"
	app:frame_width="3dp"
	app:frame_color="@android:color/holo_red_light"/>
	
```

**圆角**

```java
<com.recker.flyshapeimageview.ShapeImageView
	android:layout_width="150dp"
	android:layout_height="150dp"
	android:src="@drawable/yu"
	app:shape_mode="shape"
	app:frame_width="3dp"
	app:frame_color="@android:color/holo_red_light"
	app:round_radius="10dp"/>

```







