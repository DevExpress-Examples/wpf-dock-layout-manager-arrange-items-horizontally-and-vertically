<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128642942/15.1.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T326786)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/MainWindow.xaml))
<!-- default file list end -->
# How to: Arrange Items Horizontally and Vertically 


To arrange DockLayoutManger items horizontally or vertically, use <a href="https://documentation.devexpress.com/#WPF/CustomDocument6824">Layout Group</a> objects. A LayoutGroup is a container that may contain different items:<br>
<p>- Other Layout Groups;<br>- <a href="https://documentation.devexpress.com/#WPF/CustomDocument6823">Layout Panels</a>;<br>- <a href="https://documentation.devexpress.com/#WPF/CustomDocument6825">Tabbed Groups</a>;<br>- <a href="https://documentation.devexpress.com/#WPF/CustomDocument6830">Document Groups</a>;<br>- <a href="https://documentation.devexpress.com/#WPF/CustomDocument7224">Layout Control Items</a>.<br><br></p>
<p>A layout group can arrange its items either horizontally or vertically. The orientation can be changed by setting the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfDockingLayoutGroup_Orientationtopic">LayoutGroup.Orientation</a> property.</p>
<p>In this example, we demonstrated how to build a layout with items arranged vertically and horizontally.</p>
<p><img src="https://raw.githubusercontent.com/DevExpress-Examples/how-to-arrange-items-horizontally-and-vertically-t326786/15.1.3+/media/852b4882-a7b9-11e5-80bf-00155d62480c.png"></p>
<p>For this, we used a combination of vertical and horizontal layout groups.</p>

<br/>


