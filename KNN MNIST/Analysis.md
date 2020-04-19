#计算机科学与技术201807班陈文扬 U201814680
KNN算法实现步骤
步骤1  计算测试对象到训练集中每个对象的距离
步骤2  按照距离的远近排序
步骤3  选取与当前测试对象最近的K的训练对象，作为该测试对象的邻居
步骤4  统计这K个邻居的类别频率
步骤5  K个邻居里频率最高的类别，即为测试对象的类 
表3-1  测试结果统计表
  测试序号   K值	  错误数	  错误率
  1	        1	    347	    0.0347
  2	        3	    326	    0.0326
  3	        5	    371	    0.0371
  4	        7	    349	    0.0349
  5	        9	    353	    0.0353
  6	        11	  369	    0.0369
  7	        13	  370	    0.0370
  8       	15	  387	    0.0387
  9	        17	  396	    0.0396
训练集总数：60000
测试集总数：10000
平均错误率约为0.0363。在MNIST的此例识别中，更改K值对KNN算法识别正确率略有影响，当K值为1、3、7、9时错误率略低。
 