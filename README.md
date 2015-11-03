#single-page-switch
原理：

* 显示当前页，隐藏其他页面。
* 链接href属性对应标签ID（同锚记链接），实现页面切换，回退链接需要在标签添加data-direction="reverse"。

调用：

    $.mySinglePageCut({
      'ele' : $('a[href^="#"]'),    //触发元素
      'speed' : 400                 //切换速度毫秒
    });