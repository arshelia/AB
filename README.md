# AB
一个简单的甲方乙方图片生成器

## skill
主要使用html2canvas，但是坑比较多

## how to use
1.点击图片左上角添加文字<br>
2.点击图片右上角添加为<br>
3.点击增加一张来增加图片<br>
4.最后点击生成制作图片，右键保存<br>

## warning
遇到的坑比较多稍微总结一下<br>
1.生成的图片是空白的，但是文字没问题<br>
开始以为是图片的跨域问题，后来找了半天在别人那里看到如:截图部分包含图片的话，程序必须放在服务器下面进行，不然的话就是空图片;
像我一样的小白，可以用火狐浏览器打开，这样就可以生成图片<br>
2.为了保险起见，我在截图部分里的图片加载后再调用html2canvas发现image.onload里面的代码不执行，目前没有找到原因<br>

