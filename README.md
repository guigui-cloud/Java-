# Java-  
物联网191 谢宇翔 2019311448  
Java课程作业项目仓库

# 阅读程序

## 实验目的
用类描述计算机中的CPU的速度和硬盘的容量

## 实验过程
1.创建Test文件、包package1、主类Test和其他类CPU、HardDisk、PC

2.依次对类CPU、HardDisk、PC、Test进行处理，使CPU类具备获取CPU速度的功能，HardDisk类有获取容量的功能，而PC类使PC具有前两类处理过后的CPU属性和HardDisk属性，并创建输出这两个属性的方法。

3.运行Test

## 核心方法  
1.  
```  
public void setSpeed(int m) {
		this.speed = m;
	}
	int getspeed() {
		return speed;
	}  
```  
2.  
```  
public void setAmount(int m) {
		this.amount = m;
	}
	public int getAmount() {
		return amount;
	}  
```  
3.  
```  
public void setCPU(CPU c) {
		this.CPU = c;
	}
	public void setHardDisk(HardDisk h) {
		this.HD = h;
	}
	public void show() {
		System.out.println("CPU速度"+CPU.getspeed());
		System.out.println("硬盘容量"+HD.getAmount());
	}  
```  


## 实验结果
    CPU速度2200
    硬盘容量200  
    

## 实验感想
通过本次实验，我有如下感想：

1.创建主类和其他类时候的区别；

2.通过UML图对全局设计有了更清晰的思路

3.在创建方法的时候根据其用途确定其类型
