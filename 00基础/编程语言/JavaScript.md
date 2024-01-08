# ECMAScript
## 添加文件
* 内部
```html
<script>
    alert("hello world")
</script>
```
* 外部
```html
<script src="javascript.js"></script> 
```
* 内联
```html
    <button onclick="alert(hello world)">click</button>
```
## 基本语法
* 注释
```javascript
// 这是一个注释
/*
    xxx
    xxx
    xxx
*/
```
* 输出
```javascript
// 向body中输出内容
document.write("xxxxxx")
// 弹窗警告对话框
alert("xxxxxx")
// 控制台输出
console.log("xxxxxx")
```
* 输入
```javascript
//对话框输入
prompt("提示信息：")
```
* 变量
```javascript
let xxx
```
##  数据类型
* 基本数据类型
    * nubmer    数字型
    * string    字符串型
    * boolean   布尔型
    * undefined 未定义型
    * null      空类型
* 引用数据类型
    * object    对象
    * function  函数
    * array     数组

## 流程控制
* 算术运算符
* 赋值运算符
* 一元运算符
* 比较运算符
* 逻辑运算符
## 控制循环
* if
```javascript
if(条件){
    满足条件要执行的代码
}
```
* if...else
```javascript
if(条件){
    满足条件要执行的代码
}else{
    不满足条件执行的代码
}
```
* 三元运算符
```javascript
条件 ? 满足条件执行的代码 : 不满足条件执行的代码
```
* switch
```javascript
switch(数据){
    case 1:
        xxxx
        break
    case 2:
        xxxx
        break
    default:
        break

}
```
* while
```javascript
while(条件){
    要执行的代码
    变化量
}
```
* continue break

* for
```javascript
for(声明变量;循环脚尖;变化值){
    循环体
}
```
## 数组
```javascript
let arr = [数据1, 数据2, 数据3]

arr[0]
arr[1]
```
## 函数
```javascript
//函数声明
function say(){
    document.write("hello world")
}

//函数使用
say()
```
## 对象
```javascript
// 对象声明
let 对象名 = {
    属性名 : 属性值，
    方法名 : 函数
}

// 对象使用
console.log(对象名.属性名)
```
* 内置对象
# Web APIs
## DOM（文档对象模型）
* 获取DOM对象
```javascript
document.querySelector("css选择器")
```
* 修改文本内容
```javascript
let box = document.querySelector("css选择器")
box.innerText = "更正文本"
box.innerHTML = "<h3>更正文本</h3>"
```
* style属性
## BOM（浏览器对象模型）

## jQuery

## Ajax

## Node.js


