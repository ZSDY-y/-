# 不熟点
## variables
    float占4bit，double占8bit
    数值加f或F即为float内型

    bool只占1byte，但实际要1bit

    char 1bit，int 4bit，long long  8bit，long在4~8之间，是编译器

    sizeof；
## 命名规则
    大小写区分，不能用关键字
    只能用字母，数字，下划线
    第一个字符，不用数字
## 字符串
    字符，''与"",用字符与字符串；
    字符与整数，（int）与(char)，强制
    转义字符，"\n"输出"\\n",两个\\才能输出一个
    水平制表符，\t,更整齐
    char与string（用#include<string>）;不用[],string

## bool
    1.0代表真假（非0代表真）
    true与false

    比较大小本质是bool
        如>,<,>=,<=
        真为1，错误为0；
    
    ！，&&，||，！为非。运算为0，1

    if判断本质是0，1
## 运算
    ++与--得前置，a=b++(先赋值 后++);a=++b;
    ’/‘运算，int/int得int
        /1.0就行
    '%',定有整数，%0无
## 三目运算符
    （ x? a:b ）;
    x判断，
    返回值，正确，a；错误，b；
## switch case
    switch(变量x){
        case x(数字，x的大小)：
        运行；
        break；
        。。。。。。
    }
## 指针
    int *p;
    p为地址，*p为数据，&a，a的地址；
    指针4节（32位）
    null，不可访问
## 结构体
    
## 引用
    int &a=b;
    一定要初始化；
    不可改；
## 其他
    sizeof用（）；
   
    