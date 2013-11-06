#Cwm-recovery-6.0.3.7中文源码
================================================================================================
##作者：APAR(雨伞_先生)
##微博：[@雨伞_先生](http://weibo.com/APAR)
================================================================================================

##源码说明：

1、采用Ruby生成字库方法汉化（感谢最初做出汉化代码的大神）

2、针对MTK进行了部分修改(参考了Xs的代码，mtk备份部分的判断代码参考了老杨的修改)

	a、支持MTK平台备份（可备份boot及recovery分区）

	b、添加MTK USB挂载代码以支持MTK平台USB挂载模式

3、在Device里添加```BORAD_RECOVEY_USE_CHINESE := true```使用汉化字库编译

4、在Device里添加```BOARD_USE_CUSTOM_RECOVERY_FONT := \"chinese/font_15x24.h\"```来改变默认字体大小

5、在Device里添加```BOARD_USE_CUSTOM_EVENTS := true```打开按键振动

6、在Device里添加```BOARD_USE_FB2PNG := true```可定义使用fb2png在recovery下截屏

7、在Device里添加```BOARD_USE_AROMA_FILE_MANAGER := true```可编译Aroma文件夹管理器
