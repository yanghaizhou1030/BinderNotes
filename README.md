# BinderNotes
本工程对android的binder主要代码进行注释、说明<br>
Binder是android系统的精华，包括kernel驱动以及应用层框架<br>

## kernel驱动代码结构
drivers/android<br>
<tab>--Kcong<br>
<tab>--Makefile<br>
<tab>--binder.c<br>
<tab>--binder_alloc.c<br>
<tab>--binder_alloc.h<br>
<tab>--binder_alloc_selftest.c<br>
<tab>--binder_trace.h<br>
include/uapi/linux/android<br>
<tab>--binder.h<br>

本文亦奖按照binder源码结构，对核心源码文件逐一进行注解
