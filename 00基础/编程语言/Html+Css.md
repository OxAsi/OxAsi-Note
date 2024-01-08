# HTML
## HTML基础
* 结构标签
```html
<html>
</html>



<head>
</head>

<title>
</title>  

<body>
</body>

```
* 文档声明
```html
<!DOCTYPE html>
```
* 字符集
```html
<meta charset="UTF-8"/>
```
* lang语言种类
```html

```
## 常用标签
* 标题标签
```html
<h1>这是一个标题</h1>
```
* 段落标签
```html
<p>这是一个段落标签</p>
```
* 换行标签
```html
<br/>
```
* 文本格式化标签
    * 加粗
    ```html
    <strong></strong>
    <b></b>
    ```
    * 倾斜
    ```html
    <em></em>
    <i></i>
    ```
    * 删除线
    ```html
    <del></del>
    <s></s>
    ```
    * 下划线
    ```html
    <ins></ins>
    <u></u>
    ```
* 盒子标签
```html
<div></div>
<span></span>
```
* 图像标签
```html
<img src="url"/>
```
* 相对路径 绝对路径
* 超链接标签
```html
<a href="url" target="方式">文本或图片</a>
```
* 注释
```html
<!-- 这是一个注释 -->
```
* 特殊字符
```html
空格符 &nbsp;
大于号 &lt;
小于号 &gt;
```
* 表格标签
```html
<table>
    <tr>
        <td></td>
    </tr>
</table>
```
* 列表标签
```html
<ul>
    <li></li>
    <li></li>
    <li></li>
</ul>

<ol>
    <li></li>
    <li></li>
    <li></li>
</ol>

<dl>
    <dt></dt>
    <dt></dt>
    <dt></dt>
</dl>
```
* 表单标签
```html
<form action="url" method="提交方式" name="表单名称">
    <input type="属性值" value="值"/>
</form>
```
# CSS
* css代码样式
```css
<style>
    h1{
        color: blue;
        font-size: 100px;
    }
</style>
```
* 基础选择器
    * 标签选择器
        ```css
        h1{
            color: blue;
        }
        ```
    * 类选择器
        ```css
        .class{
            color: blue;
        }
        ```
    * id选择器
        ```css
        #id{
            color: red;
        }
        ```
    * 通配符选择器
        ```css
        *{
            color: green;
        }
        ```
* CSS字体属性
```css
p{
    font-family: "微软雅黑";
    font-size: 20px;
    font-weight: bold;
    font-style: normal;
}
```
* CSS文本属性
```css
div{
    text-decoration: underline;
    text-indent: 10px;
    line-height: 20px;
}
```
* CSS引入方式
    * 行内样式表（行内式）
    ```css
    <style>
        div{
            color: red;
        }
    </style>
    ```
    * 内部样式表（嵌入式）
    ```css
    <div style="color: red; font-size: 20px;">哈哈哈</div>
    ```
    * 外部样式表（链接式）
    ```css
    <link rel="stylesheet" href="css_ulr">
    ```
