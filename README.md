# 求是潮技术研发中心后端入门

## 简介

这是供求是潮技术研发中心使用的后端开发入门教程。以 LAMP 为主。

LAMP 指的是 Linux Apache MySQL PHP（原先是Perl，现在也有Python），作为后端开发者，最重要的就是 PHP 以及 MySQL 了。尽管 PHP 有许多问题，但由于历史原因和占有率原因，我们还是必须对其有一定的掌握。另一方面，由于 PHP 极易上手，也比较适合初学者做网站开发。一个程序员多掌握几门语言（尤其是占有率这么大的语言）是没有什么坏处的。

但是也正由于 PHP 的简单易用，很容易写出有问题的代码，尤其是和 PHP自身的一些“坑”相结合时，更可能产生严重的问题。不过一切归根到底都是程序员自身的问题，只要我们有足够的意识，很多问题就能够避免。事实上，有很多大型网站、项目（例如 WordPress 、 维基百科、 Facebook ）都是使用 PHP 开发的。

此外，这里还会简要介绍一些 nginx 服务器的知识。nginx 也是一个比较常用的网页服务器，并且在某种程度上比 Apache 更易用、拓展性更强。

最后，这里有一个小建议：后端程序员不能只会后端，最好要对前端也有一定的了解，如 Ajax 技术等。否则，与前端合作时会非常困难。

既名“入门”，本文档只是一份让你对后端知识有个开始的大概了解。本入门的子目录中包括了一些常见问题、经验分享，并且提供了一些有用的链接以供参考，希望能以此帮助你少走一些弯路。

## 目录
### General
1. [动态网站的架构]

### PHP
1. [安装与配置](PHP/安装与配置.md)
1. [快速入门](PHP/快速入门.md)
1. [字符串操作与正则表达式](PHP/字符串操作与正则表达式.md)
1. [代码重用与函数](PHP/代码重用与函数.md)
1. [使用MySQL数据库](PHP/使用MySQL数据库.md)

### MySQL
1. [简介与安装配置](MySQL/简介与安装配置.md)

## 链接

以下是一些我们认为还可以的教程或参考资料。再次强调， tutorial 不同于 doc ， __不能__ 将这些教程作为工具书使用。

* [W3school](http://www.w3school.com.cn/)
  有名的网站制作教程， W3Schools.com 的中文版（两者没有直接关系），虽有很多不足但作为入门还是可以借鉴的。另外，即使是后端，也请浏览一下 W3school 中的 HTML/CSS 部分，至少要有一个基本的了解。
* [Introduction to the Internet and the World Wide Web](http://www.cs.sfu.ca/CourseCentral/165/common/guide/)
  Greg Baker (@Simon Fraser University) 为一门网页制作入门课撰写的教程，以 HTML 为主，也涉及了动态网页（不过并非使用 PHP ），英文，零基础。

PHP 作者所著的 _Programming PHP_ 也是一本不错的参考书，大部头，详细讲述了一些设计意图、历史原因，让你理解为何 PHP 会是现在这个样子，如果希望对 PHP 有更深入的理解，不妨一看。

PHP 官方文档（注意，有些服务器上运行的是 PHP 5.3 ，与最新的 5.5 版有一些区别，写代码和部署时需要注意）

* [PHP Manual](http://www.php.net/manual/en/)

在你写了一段时间 PHP ，对 PHP 有了一定的理解，甚至开始抱怨一些特性的时候，不妨看看这篇博客，这是有关 PHP 缺点的最全面的概述，了解它们可以让你更好地避开 PHP 的“坑”，了解 PHP 的局限性，写出更可靠的代码，并正确判断 PHP 的适用场景，在 _有必要_ 的时候选择其他语言：

* [PHP: a fractal of bad design](http://me.veekun.com/blog/2012/04/09/php-a-fractal-of-bad-design/)

## 作者
求是潮技术研发中心：

* <a href="https://github.com/Delostik" target="_blank">Delostik</a>
* <a href="https://github.com/Hexcles" target="_blank">Hexcles</a>
* <a href="https://github.com/Senorsen" target="_blank">Senorsen</a>

## 授权协议
[署名-非商业性使用-相同方式共享 3.0 中国大陆 (CC BY-NC-SA 3.0 CN)](http://creativecommons.org/licenses/by-nc-sa/3.0/cn/)

## Contributing
有任何意见和建议，请在 Issue 中提醒我们；如果想更改或添加页面，您可以考虑给我们发起一个 Pull Request ，我们将会检查并应用您的 PR 。

