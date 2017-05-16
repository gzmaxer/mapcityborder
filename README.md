# mapcityborder
百度地图省市县边界区域作图
说明，本文章是参考了酸奶小妹的改写的，原文在 http://www.ui-love.com/baidumap/city/Boundary.html

有几个人问起多个县市轮廓的，分享一下。

多个县市轮廓的效果如这个url所示:

http://www.yyue.org/file/bound.html

 
注意，百度地图api 1.1才支持这个功能,在1.2中是不支持的。

相关说明可以参考

http://dev.baidu.com/wiki/map/index.php?title=Class:%E5%9F%BA%E7%A1%80%E7%B1%BB/Boundary

此类以像素表示一个城市区域。注意：该类只适用于1.1版本。

方法

方法	描述
get(name, callback)	name: 查询省、直辖市、地级市、或县的名称
callback:执行查询后，数据返回到客户端的回调函数，数据以回调函数的参数形式返回。 返回结果是一个boundaries数组，数据格式如下： arr[0] = "x1, y1; x2, y2; x3, y3; ..." arr[1] = "x1, y1; x2, y2; x3, y3; ..." arr[2] = "x1, y1; x2, y2; ..."


原文发表于cnblogs
http://www.cnblogs.com/ribba/archive/2011/10/20/2218637.html

　　
