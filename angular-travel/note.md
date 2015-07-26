正确使用Controller

1,不要试图去复用controller,一个控制器一般只负责一小块试图

2,不要在controller中操作dom,可以使用directive

3,不要在controller中做数据格式化,ng有很好用的表单控件

4,不要在controller中做数据过滤操作,可以使用$filter


