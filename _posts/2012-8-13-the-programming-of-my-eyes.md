---
layout: post
title: 我眼中的编程
---

编程是我们将一个问题分解成一个个独立的、可计算的部分，然后再通过一系列符合逻辑的运算得到一个结果,那就是该问题的答案---即通过三个步骤来使用计算机解决一个现实问题：1，定义数据结构; 2，设计算法; 3，代码实现; 4，输入数据，得到结果。

一个经典的例子：
hello.c


	#include <stdio.h>

	int main(int argc, char **argv)
	{
		char *str = "hello world!";

		printf("%s\n", str);
		return 0;
	}


我们想让电脑显示一串字符，就需要先准备一个字符串，即str所指向的字符串，它是由ascii码组成的一段数据，计算机可以通过读取它的数值得到对应的字母。下面的‘printf‘是一个标准c库函数，标准c库函数是一些已经被之前的程序员所实现的常用的功能函数，比如输入输出、循环、字符串操作，这样我们编程序的时候就不需要再重复编写那些已经被改进的很成熟的函数了。printf函数读取传入的参数str，将ascii码的值相对应的字母一一打印在屏幕上面，经过这些步骤，我们就使用计算机完成了一件工作：显示一句话。


好奇号火星探测器它是受人指挥的，在一亿公里外为人类探索未知的世界，如此浩大的一个工程是由先进可靠的计算机系统支持的，其中就包括著名的实时操作系统---vxworks
电脑的操作系统其实就是一个非常复杂的程序，我们输入想要让好奇号执行的动作，操作系统调用系统内部的一些功能，驱动机器设备，最终完成行走，或者是采集岩石样本的功能。

一个好的程序员可以完成100个一般程序员能完成的工作，不在于工作时间的长短，而在于工作的质量。