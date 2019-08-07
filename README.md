# c++
1.首先进入欢迎界面，让用户输入不同选择，进入不同选项
1.1. 0 -- 退出 
1.2. 1 -- 增加职工
1.3. 2 -- 删除职工
1.4. 3 -- 显示所有职工信息
1.5. 4 -- 修改职工信息
1.6. 5 -- 查找职工
1.7. 6 -- 按职工编号进行排序
1.8. 7 -- 清空文档
2.退出- 退出管理系统
3.增加职工，添加新职工，可以批量添加多个职工，职工分为普通员工、经理以及总裁
4.删除职工，可以按照职工编号进行删除职工
5.显示所有职工信息，先判断文件是否存在或是否清空，如果存在并且有记录的情况下，展示文件内记录内所有职工的信息
6.修改职工信息，可以按照用户输入的职工编号，修改职工新的信息，并保存到文件中
7.查找职工信息，查找有两种方式，一个按职工编号查找，一个按姓名查找，如果用户查找的内容不为空显示该职工信息，如果为空提示不存在要查找的职工
8.按职工编号进行排序，用户可以将输入的所有职工按照职工编号进行升序或者降序排列，并存入文件
9.清空文档，可以将文件内当前的记录全部清空。


本案例设计到的知识点为：面向对象中的封装、继承、多态以及文件IO流，在设计中有Worker职工的基类，以及分别派生类为普通员工、经理、以及总裁，基类中有纯虚函数子类分别作了实现。然后有个文件管理类，对用户做出不同的选择分别做不同的处理。可以对系统进行基本的增删改查功能。
