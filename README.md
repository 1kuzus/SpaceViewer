# SpaceViewer
SpaceViewer是一个可以直观展示哪些文件或文件夹占用了绝大部分磁盘空间的小程序。  


关于目录大小统计模式：  
实时模式将即时计算每个文件夹的大小，适用于查看较为轻巧的目录；而统计C盘、D盘、C:\Windows等根目录或低级目录时，将会发生卡顿。  
预存模式提前统计计算机上的文件树，查询时从预存文件中调用。  
更新或首次创建预存文件将花费几分钟的时间。  


快捷键及说明：  
Ctrl+O	选择目录；指定一个目录并查看此目录下的空间占用情况。  
Ctrl+E	在Windows文件资源管理器中打开当前目录。  
Ctrl+R	更新当前目录的预存信息；小范围、快速的更新预存文件，而不是进行全盘扫描。需要在预存模式下使用。  
Backspace	返回上级目录。  


SpaceViewer Low-Res是为分辨率较低的显示设备制定的，功能与标准版完全相同。可共用同一个预存文件。  

请不要随意修改此文件夹内的其他目录名、文件名和文件位置。  


了解更多：  
有些文件夹中，占用空间过小的文件与文件夹会被分别打包到<其余文件/文件夹>中，以整体的形式显示占用空间大小。尽管总和可能会占用较大空间。  
出于对显示效果的考虑，本程序默认划分线的短项不会小于总长的7%，此设定会使得一些小占比文件显示得更大。  
事实上，导致实时模式卡顿的不是文件大小过大，而是文件数量过多。  
预存模式下如果发现显示数据有明显错误，可能是当前目录内容已经发生变化，可尝试按Ctrl+R更新当前目录的预存信息。  


1kuzus
