# UseEcharts
目的：用于个人 Echarts 功能的探索/学习/代码及图例运用心得

1.Echart 官网 ： 术语速查手册：  https://echarts.apache.org/zh/cheat-sheet.html 

2.ECharts 获取：
使用了 npm 的方式获取:  npm install echarts --save 


3.在 HTML 中使用最简单的 Echarts，需在 head 标签内加入 js 引入代码（使用其它图形代码也类似）：

    <script type="text/javascript" src="http://echarts.baidu.com/gallery/vendors/echarts/echarts-all-3.js"></script>    
    <script src="echarts.min.js"></script>
  
4.创建自己的 AK ：

A.错误提示:
百度未授权使用地图API，可能是因为您提供的密钥不是有效的百度LBS开放平台密钥，或此密钥未对本应用的百度地图JavaScriptAPI授权。您可以访问如下网址了解如何获取有效的密钥：http://lbsyun.baidu.com/apiconsole/key# 

B.解决方法:
进入链接 http://lbsyun.baidu.com/apiconsole/key#  后，在 "创建应用" 处新创一个 AK ，生成后复制自己的 AK，替换示例 HTML 文件中的原 AK 密码即可。
若还是出现提示，可删除 google 上的 cookies 再试。

参考来源：CSDN 
https://blog.csdn.net/weixin_43389331/article/details/95509853
https://blog.csdn.net/tojohnonly/article/details/86511344
