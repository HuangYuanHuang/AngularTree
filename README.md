# AngularTree
Angualr 树形层级架构
  ![image](https://github.com/HuangYuanHuang/AngularTree/blob/master/tree.png)
数据初始化
~~~javascript
main.init = function () {    
    main.canvas.init();       
    main.treeNode = new treeNode(1, "中国", "",  [
    new treeNode(2, "湖南", "", [     
        new treeNode(4, "长沙", "", [], 3, 2), 
           new treeNode(5, "邵阳", "", [    
              new treeNode(9, "武冈", "", [], 4, 5),            
              new treeNode(10, "洞口", "", [], 4, 5)], 3, 2) ], 2, 1),
        new treeNode(12, "湖北", "", [], 2, 1), 
        new treeNode(3, "上海", "", [
            new treeNode(6, "浦东", "", [], 3, 3),         
            new treeNode(7, "徐汇", "", [], 3, 3),  
            new treeNode(8, "宝山", "", [], 3, 3)], 2, 1),   
        new treeNode(13, "北京", "", [  
            new treeNode(16, "中关村", "", [], 3, 13)], 2, 1)], 1, -1); 
  }
~~~
