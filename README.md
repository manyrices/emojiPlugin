# emojiPlugin

emoji插件使用方式如下：
1、引入emoji_bar.js以及emoji_bar.css
2、创建一个textarea
3、为textarea绑定emoji插件
   例如：$('textarea').addEmoji();
4、支持自定义列数以及表情内容
  $('textarea').addEmoji({
    clomn:5,
    emoji:['😀','😁','😂','🤣','😃','😄']
  });
