修改Github 给你项目设定的语言

比如你有一个php项目，如果里面有过多的js,css，html代码，github就会给你的项目设定的语言为js,css,html, 而不是你的项目语言

那怎么来设置呢？ 只需要建立一个文件 .gitattrbutes

里面添加 *.js lingist-language=php

后面的php改为你项目的语言，这个可以添加多行 然后上传到项目的根目录，那么Github就会自动更改为你设定的语言
