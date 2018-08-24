# How to create github page
1.  you must have one github account. for example, my github account is 'liuyangjason'
2.  create one empty github repo whose name is <your github name>.github.io'. for example, the repo name is 'liuyangjason.github.io' to me.
3.  create one jekyll based project locally.
   ~~~JEKYLL
   jekyll new liuyangjason.github.io
   ~~~
4.  run following commands
    * cd liuyangjason.github.io
    * git init
    * git add .
    * git commit -m "comments"
    * git remote add origin https://github.com/liuyangjason/liuyangjason.github.io
    * git push -u origin master
5.  access your github page : https://liuyangjason.github.io