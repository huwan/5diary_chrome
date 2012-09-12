##吾志网 Chrome 浏览器扩展应用
=============

一个简单的[吾志网](http://5diary.com) Chrome 浏览器扩展应用。

其实，它就是一个大图标的书签。你可以在Chrome 浏览器打开新标签页面的应用程序中看到应用图标。

### 如何使用
-------------
#### 下载
  我用不同的图标，写了两个版本，仅仅是图标不一样而已。
  
  第一种图标：
  
![5diary](https://github.com/mengyingchina/5diary_chrome/blob/master/5diary/Timemachine_128.png)
	
[**下载 5diary.crx**](https://github.com/mengyingchina/5diary_chrome/blob/master/5diary.crx)

  第二种图标：
  
![5diarydotcom](https://github.com/mengyingchina/5diary_chrome/blob/master/5diarydotcom/5diary_128.jpg)

[**下载 5diarydotcom.crx**](https://github.com/mengyingchina/5diary_chrome/blob/master/5diarydotcom.crx)


#### 安装

  + 下载以上面以“crx“为后缀的扩展应用，并将其拖拽到 Chrome 浏览器中，按照提示安装即可。
  
  + 如果浏览器提示 “ **Chrome只可添加来自“网上应用商店”的扩展程序、应用程序和用户脚本** ”，则需要通过以下方法安装： 
    1. 访问 chrome://chrome/extensions/ 页面，或者点击Chrome右上角的扳手图标，选择工具->扩展程序，打开扩展程序；
    2. 将扩展应用拖拽到这个页面，按照提示安装即可。
  更多方法请参考 [这里][1] 。
    

#### 卸载
  
  打开新标签页面，选择应用图标，右键选择“从 Chrome 中删除”即可。
    
#### 想自己也写个？

写这个其实很简单。一个简单的网页“大图标书签“的源代码你可以参考文件夹下的代码。
其实就是准备两个不同大小的图标(一般是16\*16,128\*128 )用于显示，然后照着这个[manifest.json](https://github.com/mengyingchina/5diary_chrome/blob/master/5diary/manifest.json) 修改为你想写的网站信息即可。
	
更多请参考[Google Developers](https://developers.google.com/chrome/web-store/docs/get_started_simple)上面的文档。

### 更多的说明
-------------
  本扩展应用只是看到Chrome浏览器中许多应用都只是一个大图标的书签而已（我是想说很水，不过吧还是挺有用的），就参照官方教程写了这个扩展程序。因为没有Chrome web store的开发者帐号（收费的说），这个程序不能放到官方应用商店上，因为只是玩玩，所以也就这样吧。
  另，有如下声明：
  + 本程序未经吾志拔拔麻麻授权，**与吾志网官方无关**，仅个人娱乐而已，仅因为我喜欢吾志而已。
  + 应用图标等各种与版权有关的，均归原版权所有者所有。
  + 如果还剩下其它的版权，使用 “[DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE][2]” 这个奇葩许可证许可。
  
  
[1]: http://www.geekpark.net/read/view/161039

[2]: http://sam.zoy.org/wtfpl/COPYING
