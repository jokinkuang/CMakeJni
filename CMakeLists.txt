cmake_minimum_required(VERSION 3.4.1)

add_library( # so文件名
             FirstJni
             # 动态还是静态链接库
             SHARED
             # 源代码
             src/main/jni/FirstJni.cpp )

