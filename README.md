YangqLoader
===========

一个可以加载swf，图片等显示对象和文本，二进制数据等非显示对象的工具类， 简单易用

使用方法如下：

//加载可显示对象
var loader:MultifunctionalLoader = new MultifunctionalLoader();

//加载文本或者二进制数据
var loader:MultifunctionalLoader = new MultifunctionalLoader(false);

//注册函数回调
loader.registerFunctions(completeHandler,errorHandler);
//开始加载
loader.load(url);

//加载显示对象complete后的回调函数
function completeHandler(dp:DisplayObject):void
{

}

//加载文本或者二进制数据complete的回调函数
function completeHandler(data:*):void
{

}

//errorMsg，错误信息，方便出错调试
function errorHandler(errorMsg:String):void
{

}
