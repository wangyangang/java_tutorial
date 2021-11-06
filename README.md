# java_tutorial

在一个java文件中可以写多个class，但是只能有一个是public的，而且要求public的类必须与源文件同名。

javadoc可以根据文档注释，生成html类型的api文档，用法：

javadoc -d myhello -encoding UTF-8 -charset UTF-8 -author -version HelloWorld.java

-encoding和-charset防止乱码
