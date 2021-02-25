# Gson 兼容库
在Gson源码基础上增加兼容处理（与官方版本完全一致） 
## 使用方法
```java
{
	//开启兼容模式
	 Gson.setStrictMode(false);//默认为严苛模式
	 /*兼容模式下或自动忽略数据类型与报文不符的字段**/
	 /******************************************/
	 //建议使用方法
	 Gson.setStrictMode(BuildConfig.DEBUG);
	 
}
```
