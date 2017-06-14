# 个人博客说明

**Elevenbeans' blog powed by [Hexo](https://hexo.io/).**

博客地址: <http://elevenbeans.github.io>

## Screenshot

![](https://raw.githubusercontent.com/elevenBeans/Grocery/master/contactLogo/ScreenShot.png)

## Theme

博客的重点主要还是在文字，所以极简主义风格是我喜欢的。

我的主题为 [PolarBear](https://github.com/frostfan/hexo-theme-polarbear), a light theme base on Even, designed by Giuem.

想要获取更多主题：参见 [Hexo Themes](https://hexo.io/themes/)。

## Content OverView

### Categories

+ Tech 
	+ [管中窥豹，一叶知秋：用 GA 得出几个和掘金社区相关的有趣结论](http://elevenbeans.github.io/2017/06/08/GA-for-juejin/) *2017-6-9*
	+ [移动端浏览器调试方法汇总](http://elevenbeans.github.io/2017/06/06/%E7%A7%BB%E5%8A%A8%E7%AB%AF%E6%B5%8F%E8%A7%88%E5%99%A8%E8%B0%83%E8%AF%95%E6%96%B9%E6%B3%95%E6%B1%87%E6%80%BB/) *2017-6-6*
	+ [全栈开发实例：如何独立开发/发布一个WebAPP](http://elevenbeans.github.io/2017/05/16/%E6%92%B8%E4%BA%86%E4%B8%80%E4%B8%AA%E6%8A%95%E7%A5%A8App/) *2017-5-16*
	+ [URL Scheme 主动唤起 APP 问题踩坑](http://elevenbeans.github.io/2016/08/18/URL-Scheme-%E5%94%A4%E8%B5%B7%E9%97%AE%E9%A2%98%E8%B8%A9%E5%9D%91/) *2016-8-18*
	+ [由 $(document).ready 发散开去](http://elevenbeans.github.io/2016/06/03/DomReady/) *2016-6-3*
	+ [JS 中的小技巧汇总](http://elevenbeans.github.io/2016/05/19/js%20%E4%B8%AD%E7%9A%84%E5%B0%8F%E6%8A%80%E5%B7%A7%E6%B1%87%E6%80%BB/) *2016-5-19*
	+ [Scroll 事件处理之 throttle 和 debounce](http://elevenbeans.github.io/2016/05/05/scroll%E4%BA%8B%E4%BB%B6%E5%A4%84%E7%90%86%E4%B9%8B-throttle-%E5%92%8C-debounce/) *2016-5-5*
	+ [CSS 中的垂直居中法](http://elevenbeans.github.io/2016/05/04/css-%E4%B8%AD%E7%9A%84%E5%9E%82%E7%9B%B4%E5%B1%85%E4%B8%AD%E6%B3%95/) *2016-5-4*
	+ ...

+ Life
	+ [2016-2017 小结](http://elevenbeans.github.io/2017/06/12/summary-of-my-2016-2017/) *2017-6-14*
	+ [开源精神, 从我做起](http://elevenbeans.github.io/2017/04/10/%E5%BC%80%E6%BA%90%E7%B2%BE%E7%A5%9E%E4%BB%8E%E6%88%91%E5%81%9A%E8%B5%B7/) *2017-4-10*
	+ [话不多说先上车](http://elevenbeans.github.io/2017/02/09/%E6%88%BF%E5%AD%90/) *2017-2-9*
	+ [1024](http://elevenbeans.github.io/2016/10/24/1024/) *2016-10-24*
	+ [Hello, Ctrip!](http://elevenbeans.github.io/2016/08/08/helloCtrip/) *2016-8-8*
	+ ...


### Contact

重要的 social 信息我觉得是必不可少的。然而，本主题并未提供这个 widget，Contact 是我自己自定义的 widget。包括：

+ [Github](https://github.com/elevenBeans)
+ [GMail](mailto://elevenbeansf2e@gmail.com)
+ [Facebook](https://www.facebook.com/profile.php?id=100001896103903)
+ [Sina](http://weibo.com/2381593582/profile?topnav=1&wvr=6)

如何自定义？

方法很粗暴，在主题配置文件(_config.yml) 中直接写代码了 =,=

```html
widget_custom:
    title: Contact
    content: 
      <div style="display:inline-block;background:#333;border-radius:12px;width:24px;height:24px">
        <a href="https://github.com/elevenBeans" target="_blank">
          <img style="position:relative;left:4px" src="img/github.png" />
        </a>
      </div>
      <div style="display:inline-block;background:#d14836;border-radius:12px;width:24px;height:24px">
        <a href="mailto://elevenbeansf2e@gmail.com" target="_blank">
          <img style="position:relative;left:4px" src="img/mail.png" />
        </a>
      </div>
      <div style="display:inline-block;background:#4267b2;border-radius:12px;width:24px;height:24px">
        <a href="https://www.facebook.com/profile.php?id=100001896103903" target="_blank">
          <img style="position:relative;left:4px" src="img/facebook.png" />
        </a>
      </div>
      <div style="display:inline-block;background:#ff8140;border-radius:12px;width:24px;height:24px">
        <a href="http://weibo.com/u/2381593582" target="_blank">
          <img style="position:relative;left:4px" src="img/weibo.png" />
        </a>
      </div>
```

### Tags

标签：即对于博文的话题的分类聚合

## At last

如果觉得博客中的文章对你有帮助的话，给个 star 吧亲～