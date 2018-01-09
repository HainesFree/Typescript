# TypeScript入门教程
## 1.概念
 >它是`JavaScript`的一个超集,支持变量和方法拥有自己的数据类型
## 2.安装

    $ npm install -g typescript
    $  npm --version
    2.15.1
 ## 3.编译
 ```
 tsc filename.ts   
```
>一旦编译成功，就会在相同目录下生成一个同名 js 文件，你也可以通过命令参数来修改默认的输出名称。
默认情况下编译器以ECMAScript 3（ES3）为目标但ES5也是受支持的一个选项。TypeScript增加了对为即将到来的ECMAScript 6标准所建议的特性的支持。
## 4.第一个程序：Hello World
>首先，我们创建一个 index.html 文件：
```
<!DOCTYPE html> 
<html> 
<head> 
<meta charset="utf-8"> 
<title>Learning TypeScript</title>
</head> 
<body> 
    <script src="hello.js"></script>
</body> 
</html>
```
>创建 hello.ts 文件， *.ts 是 TypeScript 文件的后缀，向 hello.ts 文件添加如下代码：
```
alert('hello world in TypeScript!');
```
>接下来，我们打开命令行，使用 tsc 命令编译 hello.ts 文件：
```
$ tsc hello.ts
```
>在相同目录下就会生成一个 hello.js 文件，然后打开 index.html 运行此程序，便可以查看结果
## 5.JavaScript 与 TypeScript 的区别
>TypeScript 是 JavaScript 的超集，扩展了JavaScript 的语法，因此现有的 JavaScript 代码可与 TypeScript 一起工作无需任何修改，TypeScript 通过类型注解提供编译时的静态类型检查。
TypeScript 可处理已有的 JavaScript 代码，并只对其中的 TypeScript 代码进行编译。
## 6.TypeScript的语法特性
* 类型
* 类 
* 模块 Modules
* 类型注解 Type annotations
* 编译时类型检查 Compile time type checking 
* Arrow 函数 (类似 C# 的 Lambda 表达式)

