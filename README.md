# 关于本站

> ⚠️本站由**哔哩哔哩** @乗芷 搭建，采用docsfiy、github。未经允许不可擅自转发！！！
>
> md编辑：Typora
>
> 虽然说这个页面很小，但是是托管在GitHub上面的
>
> ## 个人联系方式

mail：wulitian2@outlook.com、wulitian2@gmail.com、18065180083@163.com

WeChat💬：H-Wu5301(备注来意）     QQ：2158924331(备注来意)     可以找我聊天🥰

QQ🐧群：519183126                        GitHub：wlw333554             项目：czweb

# 应用寻找

watt toolkit：[点我下载(蓝奏云密码：1234)](https://wwn.lanzouy.com/b01v4iz1g)

Typora(破解版)：[点我下载(蓝奏云密码：54dj)](https://wwen.lanzout.com/iM5Zl32bb4jg)

## Typora破解教程

1.在官网下载最新版Typora：[官网](https://typoraio.cn/)

2.点击开始15天试用，然后关闭

3.找到Typora安装目录，打开Typora\resources\window.html文件 在< head > 标签后加上以下代码：

<style>
         /* 选择 body 下一级的所有具有 role="button" 的 div，但排除那些在 content 内部的 div[role="button"] */
         /* body > div[role="button"]:not(content div[role="button"]) 存在冗余 */
         /* body > div[role="button"] 已经限定了选择 body 的直接子元素 div，并且这些 div 具有 role="button" 属性。 */
         /* :not(content div[role="button"]) 试图排除某些元素，但由于 content div[role="button"] 不是 body 的直接子元素，这部分实际上没有效果。 */
         body>div[role="button"] {
             visibility: hidden;
         }
 </style>
4.打开Typora\resources\page-dist\static\js\Licenselndex.****.****.chunk.js文件，进入后用ctrl+f 查找：`e.hasActivated="true"==e.hasActivated,`，将其改为：`e.hasActivated="true",`

5.找到Typora\resources\page-dist\static\js\0.99879679.chunk.js文件(未测)
在第二行添加如下代码：

`// 创建一个新的 div 元素`
`var div = document.createElement('div');`

`// 给 div 添加一个唯一的 ID`
`div.id = 'myOverlay';`

`// 设置 div 的样式`
`div.style.position = 'fixed';`
`div.style.top = '0';`
`div.style.left = '0';`
`div.style.width = '100vw'; // 使用 100% 宽度`
`div.style.height = '100vh'; // 使用 100% 高度`
`div.style.backgroundColor = 'rgb(54,59,64)'; // Night主题背景色`
`div.style.zIndex = '9999'; // 确保 div 在最上层`

`// 将 div 添加到 body 中`
`document.body.appendChild(div);`

`//window.resizeTo(1, 1); // 将窗口缩小大小，可要，也可以不要`

`// 设置定时器，在 360 毫秒后删除 div ，并关闭页面`
`setTimeout(function () {`
    `var overlay = document.getElementById('myOverlay');`
    `if (overlay) {`
        `overlay.remove(); // 删除 div`
    `}`

    // 点击关闭按钮，关闭页面
    //document.querySelector('.text-btn').click(); //未激活关闭按钮
    document.querySelector('.default-btn.secondary-btn').click(); //激活后关闭按钮

`}, 360); // 360 毫秒后关闭弹窗`

6.没了
