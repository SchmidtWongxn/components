# components
我自己写的一些常用的组件，存放于这里，方便查找。

## 一点思考
### q: 为什么我要自己做一些组件，而且还是很低级常见的组件？<br>
正如我刚刚上面讲的，正因为常用，所以要保留。<br>
但是低级的话就仁者见仁了。<br>
平时在做特效啊等等的过程中不忍心就纪录下来好了。<br>
<br>
### q: 为什么不用 bootstrap 等等封装好的东西？<br>
有时候总会碰到别人没有封装的定制化的私有的东西。<br>
前端总是推崇小而美的。<br>

## 注意
只兼容到IE9+，并且没有加各种css兼容前缀。<br>
需要用的时候直接用 `autoprefixer` 跑一下兼容到指定版本就行<br>
<br>
1、tab 切换组件  -->  tab <br>
2、数字滚动特效  -->  num-roll <br>
3、jQuery 的 AJAX 扩展  -->  jQuery-extend/ajax-loading.js <br>
4、仿微信音乐播放的组件  -->  voice-player <br>
5、图片放大镜的组件  -->  pic-magnifying <br>
6、加载条动画（voice-player 里已用过，再抽离出来）  -->  lading-bar <br>
7、增加一个 cookie 操作方法集合

### 2016年3月7日更：
开始整理一些东西，发现之前的一些代码写的好低级。。先提交上来好了