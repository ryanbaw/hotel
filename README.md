## 无线点餐平台  （有需要完善的地方）

___包括两个部分，前台客户端和后台管理。___  
  
* 采用技术：Servlet+JSP+JDBC+MYSQL数据库(C3P0链接池) 遵循MVC开发模式  
  * mysql 数据库设计：  
      * 餐桌表
	  * 菜类别表
	  * 菜品种表
	  * 订单表      (订单基本信息)
	  * 订单明细表  (主要是菜品种)  
	      * 订单表与餐桌表关系约束
		  * 订单明细与订单表关系约束
		  * 订单明细与菜信息关系约束  
		    
 
___需要导入的jar包：___  
![jar包](https://github.com/libenhe/hotel/blob/master/READMEimg/jar.jpg)   
  
* 用户前台功能包括：  
  * 选定餐桌
  * 查看菜系
  * 选中菜品加入购物车
  * 下单结账  
    
* 用户后台管理功能包括：  
  * 餐桌管理(包括添加、退桌、搜索功能)
  * 菜系管理(包括更新、删除、添加、搜索功能)
  * 菜品管理(包括更新、删除、添加、搜索功能)
  * 餐厅订单(包括查看订单详情、结账功能)    
    
___项目文档结构如图：___  
  
![jar包](https://github.com/libenhe/hotel/blob/master/READMEimg/project.jpg)  
    


	  
 
