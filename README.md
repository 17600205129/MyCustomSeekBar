
实现结果
 
  ![实现效果](https://github.com/525642022/MyCustomSeekBar/blob/master/myseekbarlibrary/5s_seek.gif)
  
  实现博客
  https://www.jianshu.com/p/e16189e8cf78
  
简单引用


	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
	
	

	dependencies {
	        implementation 'com.github.525642022:MyCustomSeekBar:Tag'
	}
  
  自定义属性介绍
  
       <!-- 渐变色开始色值-->
        <attr name="startColor" format="color|reference" />
        <!-- 渐变色中间色值-->
        <attr name="centerColor" format="color|reference" />
        <!-- 渐变色结束色值-->
        <attr name="endColor" format="color|reference" />
        <!-- 渐变条背景-->
        <attr name="bgColor" format="color|reference" />
        <!-- 文字颜色-->
        <attr name="textColor" format="color|reference" />
        <!-- 拖动园点颜色-->
        <attr name="circleColor" format="color|reference" />
        <!-- 文字大小-->
        <attr name="textSize" format="dimension|reference" />
        <!-- 进度条高度-->
        <attr name="height" format="dimension|reference" />
        <!-- 拖动条半径-->
        <attr name="radius" format="dimension|reference" />
        <!-- 为圆形的时候的 内半径-->
        <attr name="minRadio" format="dimension|reference" />
        <!-- 为条形的时候的 中心距离上部距离-->
        <attr name="top" format="dimension|reference" />
        <!-- 为条形的时候的 下面文字距离上部距离-->
        <attr name="textTop" format="dimension|reference" />
  
 
