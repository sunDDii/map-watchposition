# map-watchposition
使用腾讯地图API，实时获取当前地理位置
简要说明：
1.使用腾讯地图API首先获取密钥key和referer；
2.js引入地址：https://3gimg.qq.com/lightmap/components/geolocation/geolocation.min.js ；
3.var geolocation = new qq.maps.Geolocation();实例化map；
4.注意点在，如果用微信浏览器打开去获取地理位置的话请先用"WeixinJSBridgeReady"做监听，不然不能实时获取到地理位置。
另外：
HTML5 有地理位置获取api，但只针对于安卓可以正常使用，10.0苹果版本需要协议为https的才可以获取到地理定位.所以不兼容。
在HTML5 plus对象中也有实时获取地理位置的方法http://www.html5plus.org/doc/zh_cn/geolocation.html#plus.geolocation.watchPosition；
拉取腾讯地图数据时比较慢，尚未找到解决办法，求指导。
