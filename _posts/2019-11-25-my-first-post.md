---
title: 如何编写第一个C++程序
categories:
- C++
excerpt: |
  编写C++程序是相对简单的
feature_text: |
  ## 多种多样的main函数
  我们可以使用很多种main函数，根据不同的需要选择不同的声明方式
feature_image: "https://picsum.photos/2560/600?image=733"
image: "https://picsum.photos/2560/600?image=733"
---

# 编写主函数
## 主函数的形式
1、一般使用的形式
``` c++
int main()
{
    return 0;
}
```
2、带有命令行参数的形式
``` c++
int main(int argc, char* argv[])
{

}
```
## 完善函数体
我们需要在函数体内完成我们要做的任务，比如一个简单的hello world程序
``` c++
#include <stdio.h>

int main()
{
    printf("Hello World!\n");
    return 0;
}
```