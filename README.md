# opencv_matchTemplate
基于Qt和opencv的模板匹配使用
使用的软件版本为：
  Qt 5.15.0 ；mingw 32位
  opencv 4.6.0 32位
PS：需要注意编译器与opencv库的位数要对应。
这是pro文件中对opencv库的引用，需要配置好对应的环境才能正常调用。
#opencv
INCLUDEPATH += D:\Qt\opencv\opencv-4.6.0-build-32\install\include
LIBS += D:\Qt\opencv\opencv-4.6.0-build-32\install\x64\mingw\lib\libopencv_*.dll
