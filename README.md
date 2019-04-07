# emojiPlugin

emoji插件使用方式如下：</br>
1、引入emoji_bar.js以及emoji_bar.css</br>
2、创建一个textarea</br>
3、为textarea绑定emoji插件</br>
   $('textarea').addEmoji();</br>
4、支持自定义列数以及表情内容</br>
   $('textarea').addEmoji({ clomn:5 , emoji:['😀','😁','😂','🤣','😃','😄']});
