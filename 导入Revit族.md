# 导入Revit族
<br/>

【导入Revit族】菜单界面如图16.9\-1所示；

该插件的主要功能是在不考虑参数驱动的情况下，将Revit族转到PKPM-BIM中，**操作步骤如下：**

1\. 确保revit关闭。

2. 点击Revit\-Revit.exe软件进行安装，如图16.9\-1所示

![](file:///C:\Users\pkpm\AppData\Local\Temp\ksohtml8136\wps244.jpg)

图16.9\-1Revit安装图标

安装界面如图16.9\-2所示，点击Install即可

![](file:///C:\Users\pkpm\AppData\Local\Temp\ksohtml8136\wps245.jpg)

图16.9\-2 Revit安装界面

3.启动revit,会发现菜单栏多了一个菜单栏，里面有两个工具，其中一个是“导出族至DB”，如图16.9\-3所示

![](file:///C:\Users\pkpm\AppData\Local\Temp\ksohtml8136\wps246.jpg)

图16.9\-3 Revit安装界面

4 点击该工具，界面如如图16.9\-4所示：

![](file:///C:\Users\pkpm\AppData\Local\Temp\ksohtml8136\wps247.jpg)

图16.9\-4 Revit安装界面

点击“选择族文件”按钮，可以选择多个族文件，选中的族文件会显示在下面。

然后点击“选择中间文件存放的文件夹按钮”，选择导出db的位置。

对每一个族文件的每一个族类型均会导出一个db文件，譬如选择了三个族文件，里面分别有1个族类型，2个族类型，5个族类型，最后导出的db文件个数为8个。

5. 在PKPM-BIM端启动导入族命令，显示对话框，然后选中一个第4步骤导出的db文件，点击导入即可。