## coolview 骚气的跑马灯
骚过s8

支持自定义颜色，速度，旋转方向，边框宽度，圆角大小


### s8
![s8](https://github.com/android-notes/coolview/blob/master/s8.gif?raw=true)


### 效果图
![效果](https://github.com/android-notes/coolview/blob/master/img.gif?raw=true)

### 例子

```html
<?xml version="1.0" encoding="utf-8"?>
<com.wanjian.view.CoolView xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#fff"
    app:border_width="8dp"
    app:radius="20dp"
    app:speed="1.5"
    tools:context="com.example.wanjian.cooooooool.MainActivity">

    <ScrollView
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center_horizontal"
            android:orientation="vertical"
            android:padding="20dp">


            <com.wanjian.view.CoolView
                android:layout_width="150dp"
                android:layout_height="150dp"
                android:background="#f00"
                app:border_width="10dp"
                app:colors="@drawable/colors"
                app:radius="80dp"
                app:speed="1">

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_gravity="center"
                    android:background="#e6930d"
                    android:padding="20dp"
                    android:text="圆环/顺时针旋转/自定义颜色"
                    android:textColor="#666" />

            </com.wanjian.view.CoolView>

            <com.wanjian.view.CoolView
                android:layout_width="150dp"
                android:layout_height="150dp"
                android:layout_marginTop="10dp"
                android:background="@mipmap/ic_launcher_round"
                app:border_width="10dp"
                app:colors="@drawable/colors"
                app:radius="80dp"
                app:speed="-1">

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_gravity="center"
                    android:layout_margin="20dp"
                    android:background="#e6930d"
                    android:text="圆环/逆时针旋转/自定义颜色"
                    android:textColor="#666" />

            </com.wanjian.view.CoolView>


            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_marginTop="10dp"
                android:text="圆形/顺时针旋转/自定义颜色/快速旋转"
                android:textColor="#666" />

            <com.wanjian.view.CoolView
                android:layout_width="100dp"
                android:layout_height="100dp"
                app:border_width="50dp"
                app:colors="@drawable/colors"
                app:radius="50dp"
                app:speed="5" />


            <com.wanjian.view.CoolView
                android:layout_width="300dp"
                android:layout_height="100dp"
                android:layout_marginTop="10dp"
                app:border_width="3dp"
                app:radius="10dp"
                app:speed="1.5">

                <TextView
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:background="#e6930d"
                    android:gravity="center"
                    android:text="顺时针旋转/默认颜色"
                    android:textColor="#666" />
            </com.wanjian.view.CoolView>

            <com.wanjian.view.CoolView
                android:id="@+id/coolview"
                android:layout_width="300dp"
                android:layout_height="100dp"
                android:layout_marginTop="10dp"
                app:border_width="3dp"
                app:radius="10dp"
                app:speed="1.5">

                <TextView
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:background="#e6930d"
                    android:gravity="center"
                    android:text="加减速"
                    android:textColor="#666" />
            </com.wanjian.view.CoolView>

        </LinearLayout>
    </ScrollView>
</com.wanjian.view.CoolView>


```
