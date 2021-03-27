# IP地址查询地理位置

分享几个免费IP地址查询API接口

1.IP地址查询接口：http://apis.juhe.cn/ip/ipNew?ip=112.112.11.11&key=1wdh1ueeub12eb
要先去 https://www.juhe.cn/docs/api/id/1 申请APPKEY
返回数据格式
{
    "resultcode": "200",
    "reason": "查询成功",
    "result": {
        "Country": "中国",
        "Province": "江苏省",
        "City": "无锡市",
        "Isp": "电信"
    },
    "error_code": 0
}


2.新浪的IP地址查询接口：http://int.dpool.sina.com.cn/iplookup/iplookup.php?format=js
新浪这个应该说是最不错的。并且返回的数据类型为可以自定义格式（默认为纯文本格式，根据format的参数定义，还可以返回JS、Json格式）。

3.新浪多地域测试方法：
http://int.dpool.sina.com.cn/iplookup/iplookup.php?format=js&ip=219.242.98.111

4.搜狐IP地址查询接口（默认GBK）：http://pv.sohu.com/cityjson

5.搜狐IP地址查询接口（可设置编码）：http://pv.sohu.com/cityjson?ie=utf-8

6.搜狐另外的IP地址查询接口：http://txt.go.sohu.com/ip/soip


私人测试用的  http://123.206.219.164/json?ip={IP} ，http://123.206.219.164/json 不保证一直可用

