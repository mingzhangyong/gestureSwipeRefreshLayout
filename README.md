# gestureSwipeRefreshLayout

带手势识别的SwipeRefreshLayout，解决在SwipeRefreshLayout中嵌套有左右滑动的控件，在使用中手势冲突问题。

例如SwipeRefreshLayout中嵌套有左右滑动的banner图时，在滑动banner时左右和上下滑动冲突问题。

###使用方法
###Step 1. Add the JitPack repository to your build file
####Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
###Step 2. Add the dependency

	dependencies {
		compile 'com.github.mingzhangyong:gestureSwipeRefreshLayout:1.1'
	}
	

剩下的就是用GestureSwipeRefreshLayout代替SwipeRefreshLayout。（记得布局文件中也要修改）
