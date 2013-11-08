#cwm-recovery-6.0.3.7中文源码
================================================================================================
##作者：APAR(雨伞_先生)
##微博：[@雨伞_先生](http://weibo.com/APAR)
================================================================================================

##源码说明：

1、采用Ruby生成字库方法汉化（感谢最初做出汉化代码的大神）

2、加入了时间和电量显示

3、针对MTK进行了部分修改(参考了```Xs```的代码，mtk备份部分的判断代码参考了```老杨```的修改)

	a、支持MTK平台备份（可备份boot及recovery分区）

	b、添加MTK USB挂载代码以支持MTK平台USB挂载模式

4、在Device里添加```BORAD_RECOVEY_USE_CHINESE := true```使用汉化字库编译

5、在Device里添加```BOARD_USE_CUSTOM_RECOVERY_FONT := \"chinese/font_15x24.h\"```来改变默认字体大小

6、在Device里添加```BOARD_USE_FB2PNG := true```可定义使用fb2png在recovery下截屏

7、在Device里添加```BOARD_USE_AROMA_FILE_MANAGER := true```可编译Aroma文件夹管理器

8、移植了6044的彩虹界面及滑动触摸，需要在Device里添加```BOARD_RECOVERY_SWIPE := true```调用

PS:加入的备份格式tgz貌似还有点问题，修改中～～
   高级备份还需要修改，目前用不了～～
