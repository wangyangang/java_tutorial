# java_tutorial

在一个java文件中可以写多个class，但是只能有一个是public的，而且要求public的类必须与源文件同名。

javadoc可以根据文档注释，生成html类型的api文档，用法：

javadoc -d myhello -encoding UTF-8 -charset UTF-8 -author -version HelloWorld.java

-encoding和-charset防止乱码

数据类型：
	基本数据类型：
		数值型: 
			整数类型 byte short int long
			浮点类型 float double
		字符型: char
		布尔型: boolean
	引用数据类型：
		类(class) 注意：字符串在这里
		接口(interface)
		数组([])
