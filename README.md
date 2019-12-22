# BinderNotes
本工程对android的binder主要代码进行注释、说明
Binder是android系统的精华，包括kernel驱动以及应用层框架

##kernel驱动代码结构：
drivers/android
    -Kcong
    -Makefile
    -binder.c
    -binder_alloc.c
    -binder_alloc.h
    -binder_alloc_selftest.c
    -binder_trace.h
include/uapi/linux/android
    -binder.h

本文亦奖按照binder源码结构，对核心源码文件逐一进行注解
