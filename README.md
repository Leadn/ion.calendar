# ion.calendar
一个很好用的日期选择控件
简介

Ion.Calendar 是一款基于 jQuery 和 Moment.js 的日期/日历选择器插件，功能上和常见的同类插件一样，因为是基于 Moment.js 的，所以支持多种日期格式。

浏览器兼容

IE	Chrome	Firefox	Opera	Safari
IE6+ ✔	Chrome ✔	Firefox ✔	Opera ✔	Safari ✔
使用方法

1、引入文件

<link rel="stylesheet" href="css/ion.calendar.css">
<script src="js/jquery.min.js"></script>
<script src="js/moment.min.js"></script>
<script src="js/moment.zh-cn.js"></script>
<script src="js/ion.calendar.min.js"></script>
2、HTML

<div id="calendar"></div>
4、JavaScript

$('#calendar').ionCalendar({
    lang: 'zh-cn'
});

配置

属性/方法	类型	默认值	说明
lang	字符串	en	语言
sundayFirst	布尔值	true	每周第一天，如果为 true，则星期天是第一天，如果为 false，则星期一为第一天
years	整数	80	显示多少个年份，也可以直接写入年份时间段，如 2010-2015
format	字符串	空	日期格式，如 YYYY-MM-DD 会显示成 2015-05-28
clickable	布尔值	true	如果为 false，则点击日期后不做任何事情
hideArrows	布尔值	false	隐藏箭头
startDate	字符串	空	开始时间
onClick	函数	false	回调函数，会根据日期格式返回相应的日期
onReady	函数	false	回调函数，会根据日期格式返回相应的日期
