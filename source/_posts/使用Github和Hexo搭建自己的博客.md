---
title: 使用Github和Hexo搭建自己的博客
date: 2018-04-06 19:06:05
tags:
---
 <P>1.使用命令行进入一个安全目录，比如<small style="background-color:aqua">cd ～/.Desktop</small>或者<small style="background-color:aqua">cd ~/.Documents</small>,(注意不要在根目录)</p>
 <p>2.在 GitHub 上新建一个空 repo，repo 名称是「你的用户名.github.io」（请将你的用户名替换成真正的用户名）</p>
 <p>3.命令行输入<small style="background-color:aqua">npm install -g hexo-cli</small>，安装 Hexo</p>
 <p>4.命令行输入<small style="background-color:aqua">hexo init myBlog</small></p>
 <p>5.命令行输入<small style="background-color:aqua">cd myBlog</small></p>
 <p>6.命令行输入<small style="background-color:aqua">npm i</small></p>
 <p>7.命令行输入<small style="background-color:aqua">hexo new </small>+你的微博标题，你会看到一个 md 文件的路径</p>
 <p>8.<small style="background-color:aqua">start xxxxxxxxxxxxxxxxxxx.md </small>，编辑这个 md 文件，内容自己想（Ubuntu 系统用<small style="background-color:aqua">xdg-open xxxxxxxxxxxxxxxxxxx.md </small></p>
 <ul>9.命令行输入<small style="background-color:aqua">start _config.yml </small>，编辑网站配置
    <li>(1)把第 6 行的 title 改成你想要的名字</li>
    <li>(2)把第 9 行的 author 改成你的大名</li>
    <li>(3)<把最后一行的 type 改成 <small style="background-color:aqua">type: git</small>/li>
    <li>(4)在最后一行后面新增一行，左边与 type 平齐，加上一行 <small style="background-color:aqua">repo: 仓库地址</small> （请将仓库地址改为「你的用户名.github.io」对应的仓库地址，仓库地址以 git@github.com: 开头你知道吧？不知道？不知道的话现在你知道了）</li>
    <li>(5)第 4 步的 repo: 后面有个空格，不要眼瞎。</li>
 </ul>
 <p>10.命令行输入<small style="background-color:aqua">npm install hexo-deployer-git --save</small>,安装 git 部署插件</p>
 <p>11.命令行输入<small style="background-color:aqua">hexo deploy</small></p>
 <p>12.进入「你的用户名.github.io」对应的 repo，打开 GitHub Pages 功能，如果已经打开了，就直接点击预览链接</p>
<p>13.你现在应该看到了你的博客！</p>
 