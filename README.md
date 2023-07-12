# common
一个js的通用代码库
因一些项目上使用的代码，多多少少总会在别的项目上有需求，故将一些值得独立出来的全局方法做成一个通用代码库保存备忘。

除GetQueryValue()外，其他方法均为原创。

requestNetworkV1方法重点介绍：

一直以来在js里请求网络对本人来说都是一件烦恼的事，因为每次都会因为各种类型的请求而写出千奇百怪的代码，毫无标准可言，本人自己也倍感尴尬。故一直想将js里请求网络这件事做成一个通用方法来使用。
现在，他来了。他支持GET、POST方法，能应对绝大部分请求需求，实现了一个方法应对各种需求如：最基本的发送文本、文件、对接json接口 到 对接RESTful风格接口等，
再也不为请求网络这件事操（浪费）心（时间）了。

本方法通过包装jquery.ajax参数实现。

参数解释和使用方法在注释里都写的很详细，一看就懂。本方法已在实际项目服役过一段时间质量有保障。



