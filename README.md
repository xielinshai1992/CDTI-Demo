# CDTI-Demo

#### 介绍
座舱显示交通信息（Cockpit Display of Traffic Information）Demo。

软件采用PyQt5-GUI框架和Python3.6开发。

主要功能为创建网络端口监听并接收上游发送的ADS-B应用处理数据，主要包括以下四类：

基本空中交通态势感知（Basic Airborne Situation Awareness，简称：AIRB）

目视间隔进近（Visual Separation on Approach，简称：VSA）

场面态势感知（Surface Situation Awareness，简称：SURF）

高度层变更程序（In-Trail Procedure，简称：ITP）

#### 软件架构
1.主界面UI cdti_mainform.py

2.主函数 cdti_form.py

3.ARINC661协议数据接口 a661_api.py

4.辅助工具模块 geography_analysis.py

5.网页加载 map_surf.html、js文件夹


#### 使用说明

1.安装pyqt5三方库后，python运行cdti_form.py

2.监听并接收上游发送的ADS-B应用处理数据
