# python_final
Python期末项目   
#### [项目源代码URL](https://github.com/Kkrosslw/python-final-code)   
#### [Pythonanywhere URL](http://liwenkross.pythonanywhere.com)
#### 数据传递描述   
- 本项目共有5个url,其中包括首页、信息表单、信息表单网页跳转、全球分布图、各国门店数量排名。首页展现的是一个下拉框，用户可根据自己想看到内容点击并跳转到另一个页面；信息表单汇聚了世界上星巴克门店并且有下拉框，用户可根据自己的需要进行查看某个国家的星巴克在每个城市的分布量；全球分布图则主要展示星巴克门店在全球上的数量，主要以地图的方式呈现，用户可将鼠标放在地图上看某个地区的星巴克门店数量；各国门店数量排名则是由柱形图的形式呈现，用户可拉动滑动条查看数据。
- template用于存放前端页面呈现的html文档，static用于存放css样式文件，此外还有font文件夹用于存放字体图标样式文件，csv文件共2个，17级提供的html数据文件共2个
#### html文件描述   
- 用base.html文件作为网页的模板，以便后续继承    
- 用index.html作为首页的html文件（/index) 
- 用result2.html作为信息表单(/all)及信息表单点击后跳转(/city)的页面结果，可看到每个国家的星巴克门店数量   
- 以世界地图为模板，将数据结合起来，有数据交互的作用（/map）
- 用滚动的柱形图，呈现星巴克门店数量的排名（/country）
- 此外还有17级提供的两份html文档，以便数据分析   
#### python文档
- app.py文档为运行主文档，country.py、map.py为调用文档   
- 导入数据，进行数据清洗与分析
- 通过网址后缀进行数据交互
#### Web App动作描述   
 通过下拉选框进行对数据的清洗、分析、查看，用户选择进行交互数据的筛选，起到数据交互的效果
#### 页面
- [首页](http://liwenkross.pythonanywhere.com/)   
- [信息表单](http://liwenkross.pythonanywhere.com/all) 
- [信息表单内跳转](http://liwenkross.pythonanywhere.com/city)
- [全球分布图](http://liwenkross.pythonanywhere.com/map)
- [各国门店排名](http://liwenkross.pythonanywhere.com/country)
