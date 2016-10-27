# AndroidTVLauncherForEclipse
移植于https://github.com/JackyAndroid/AndroidTVLauncher，
原项目运行是用AndroidStudio编译的，因为公司电脑无法运行AS，所以花了一点时间把项目移植到Eclipse上
##########
主工程是：Launcher
其余项目均为library
全部下载到电脑后 再导入到Eclipse中，注意修改一下依赖关系
另外我的compiled sdk是android 7.0，所以如果想要正确运行，你也需要下载并使用android7.0的SDK
###########
另外因为原项目中使用到了jiecaoplayer：https://github.com/lipangit/JieCaoVideoPlayer
而这个库又引用到了ijkplayer：https://github.com/Bilibili/ijkplayer
ijkplayer项目并没提供编译好的jar包以及so库，所以我这里就将视频播放相关的代码注释掉了
