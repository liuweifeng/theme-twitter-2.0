这是一个 Jekyll-Bootstrap 的博客主题，在 <https://github.com/gdagley/theme-twitter-2.0> 的基础上修改，更新 Twitter Bootstrap 到最新版（v2.1.1），增加中文本地化、代码高亮支持

具体使用方法请参考 <http://jekyllbootstrap.com> 。

#安装


    rake theme:install git="https://github.com/liuweifeng/theme-twitter-2.0"
#代码高亮
默认使用 [Google Code Prettify](http://code.google.com/p/google-code-prettify/)。
也可以使用Pygments的代码高亮方案，在`default.html`中增加
    
    <link href="{{ ASSET_PATH }}/css/syntax.css" rel="stylesheet">
    
   即可。