
编译
多源码文件编译、一个.mk编译多个目标文件、编译静、动态库
1、将每个文件添加到android.mk中
2、使用系统提供的函数处理
LOCAL_C_ALL_FILES :=$(call all-c-files-under)

如何引入系统库、如何阴影第三方库、如何引用静态库、如何引用动态库
1、