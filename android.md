##使用AppCompat添加OptionsMenu时的注意事项:##

-   重写Activity.onCreateOptionsMenu方法
-   定义一个menu的布局文件
-   **showAsAction**的命名空间应该为：http://schemas.android.com/apk/res-auto,否则无法在actionbar中显示菜单

##使用layer-list通过设置background来绘制View的边框##

##设置AppCompat的android:actionMenuTextColor属性，来自定义OptionsMenu的标题颜色##


##adb usb无法启动时，使用netstat -ano | grep 5037 查找与其通讯的进程并杀死即可##

##使用git shortlog -s -n 来统计开发人员的提交次数##