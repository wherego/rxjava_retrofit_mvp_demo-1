# rxjava_retrofit_mvp_demo
rxjava+retrofit+mvp sample  

使用mvp架构,结合rxjava+retrofit来请求豆瓣一个接口来演示三者结合的例子，并且对retrofit进行了二次封装。

##类文件说明：  
###mvp文件夹  
包含mvp的基类文件和继承文件。  
###HttpHelper.java  
对retrofit的二次封装类封装  
###DouBanRadioBean.java
豆瓣接口返回的Javabean
###RxRetrofitDemo.java
请求豆瓣的接口