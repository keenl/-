# 第5章　功能设计

##   <a id="&#x7B2C;5&#x7AE0;&#x3000;&#x529F;&#x80FD;&#x8BBE;&#x8BA1;"></a>

软件的功能，从本质上说就是对数据进行输入、加工、输出的过程。对于面向数据库的软件，由于是以数据库为核心的，可以理解为两个方面，一是数据的收集与处理；一是围绕数据库对其中的数据进行的4大操作，即增加、删除、修改、查询，简称增删改查（对应SQL语句的4个处理数据的关键字：Insert, Delete, Update, Select）。所有面向数据库的软件功能，都可以概括成从数据库中读出数据（Select），经过用户一定的操作，或经过程序一定的加工，再写入数据库（Insert, Delete, Update）。

