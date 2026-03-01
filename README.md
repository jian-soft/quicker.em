
# 说明

在原版quicker.em的基础上，做了一些符合自己习惯的修改。

我关注的功能：
1. 自动生成.c文件模板
2. 自动生成.h文件模板
3. 自动生成函数头注释
4. 结构体定义模板

# 安装方法

我使用的SI版本为4.00.0113。

1. 将quicker.em拷贝到本地
2. 打开base工程，将quicker.em添加到base工程


# 原版全部支持的功能如下


quicker.em for source insigned

co      弹窗配置语言和姓名

hi      文件顶部注释中新增modification

pn      弹窗定义bugID

abg     添加开始和结束注释行并附带bugID

dbg     删除开始和结束注释行并附带bugID

mbg     修改开始和结束注释行并附带bugID

{       单作用域补全

wh      补全while(){}

else    补全else{}

#ifd    弹窗定义#ifdef

#ifn    弹窗定义#ifndef

#if     弹窗定义#if

cpp     补全兼容C/C++宏定义

if      补全if(){}

ef      补全else if(){}

ife     补全if(){}else{}

ifs     补全if(){}else if(){}else{}

for     弹窗输循环变量名补全for(){}

sw      弹窗输入case数补全switch-case

case    补全单个case语句

do      补全do{}while();

st      弹窗输入结构体名补全_T_STRU

en      弹窗输入枚举名补全_ENUM

fi      弹窗置顶输入文件备注信息

fu      弹窗补全函数备注和格式

tab     弹窗提示替换空格数和是否全部替换

ap      弹窗提示带bugID和描述的双行注释

hd      一键补全头文件注释和兼容C/C++结构

ab      补全待bugID的add注释begin

ae      补全待bugID的add注释end

db      补全待bugID的delete注释begin

de      补全待bugID的delete注释end

mb      补全待bugID的modify注释begin

me      补全待bugID的modify注释end