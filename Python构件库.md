# 17.1 Python构件库
<br/>

&emsp;&emsp;PKPM-BIM软件中的外部数据下包含【Python构件库功能】，可通过打开BIMBase文件夹，找到PythonScript文件夹并打开，找到Python环境文件夹，安装Python相关插件，Python安装及建模方方法，详见Python参数化建模手册。

&emsp;&emsp;01）Python语言编写的非参数化模型可以直接同步到PKPM-BIM的绘图区中；

&emsp;&emsp;02）Python语言编写的参数化组件库会同步到参数化组件库中；在参数化组件库中对图库进行管理和方式。

:-: ![](images/p1.png)

&emsp;&emsp;（1）载入参数化组件

&emsp;&emsp;将硬盘里的参数化组件载入到工程模型中，并进行管理。

&emsp;&emsp;导入构件：将写好的参数化构件的.py文件编译为模型并导入到工程环境中。注：只有参数化的组件才能导入到实例模板库中。

&emsp;&emsp;在实例预览区可以查看组件的样图、名称、实例数量。

&emsp;&emsp;编辑模板属性：修改该模板及和该模板下的实例的属性。

&emsp;&emsp;布置构件：布置一个该模板同属性的实例。

:-: ![](images/p2.png)

 &emsp;&emsp;勾选框：可以用来多选组件。

&emsp;&emsp;（2）设置Python路径

&emsp;&emsp;默认情况下无需修改，如果遇到问题，请设置为Python绝对路径或者联系售后人员。