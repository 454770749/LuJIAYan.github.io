---
layout: default
title:  "2017年-12月-31日-Python和Ruby语言对比.md"
categories: posts rwd
image:
  teaser: 帆船.jpg
  feature: 帆船.jpg
---

<img border="0" src="/images/页面LOGO_meitu_1.jpg" alt="Pulpit rock" width="304" height="228">

# 一、异同对比选择
###  1.Python和ruby的相同点：
    1. 都强调语法简单，都具有更一般的表达方式。python是缩进，ruby是类basic的表达。<br> 
    2.都大量减少了符号。<br>
	3. 都是动态数据类型。<br> 
	4. 都是有丰富的数据结构。<br> 
    5. 都具有C语言扩展能力，<br>
	6. 都具有可移植性，比perl的可移植性更好。<br>
	7. 也都可以作为嵌入语言。<br> 
	8. 都是面向对象的语言<br>
	9. 都可以作为大项目的开发工具。<br> 
    10. 都有丰富的库支持。也有最宽松的版权许可，除了一些工具属于GNU世界。<br> 
	11. 都有lisp特色的eval函数，也都能把函数作为参数。也有图形界面的ruby的专门编辑器。都获得了广泛的c库的支持。如qt、gtk、tk、SDL、FOX等，ruby计划实现SWIG接口。
     都有完善的文档。<br>
</p>

###  2、和python相比ruby的优点：

	1. 具有正则表达式和嵌入html的功能。python也有正则表达式，但没有ruby的应用方便和广泛。python的嵌入html项目才刚起步。ruby还有apache的mod模块。ruby本身也实现和很多unix工具，如racc，doctools。比python更亲近Linux。<br> 
	2. 比python功能更完整的面向对象的语法。<br> 
	3. ruby的整个库都是具有类继承的结构。<br>
	4. 他的基本的数据类型和运算符都是可以重载的。<br> 
    5. ruby主要的功能都是通过对象的方法调用来实现的，而不是函数。python也在向这方面发展，但没有ruby做的彻底。<br>
	6. ruby的类是更规范的单继承，还有接口等概念的实现。<br>
	7. python可以实现在列表内的条件语句、循环语句，而ruby用“块”的方式来实现这个功能，比python的更灵活，更具有通用性。<br> 
	8. ruby具有类似lisp的彻底的函数方式的条件语句、循环语句等。语句的表达能力更强。<br> 
	9. 附带一些unix工具，如racc等。。<br> 
 
</p>
	
###   3、和python相比ruby的不足：


<p>   最大的不足正是因为ruby的强大所引起的。它没有python的简单性好。比较复杂的面向对象语法、“块”语法的引入、正则表达式的引入、一些简写标记都增加了语言的复杂性。

- python的缩进表达方式比ruby的basic的表达方式更让人悦目，ruby程序的满眼的end让人不舒服。当然，ruby认为end的方式比python更先进。

- ruby还没有python的“自省”的能力，没有从程序文件中生成文档的能力。

- ruby没有国际化的支持。国际化支持在ruby的计划中。这是因为ruby的历史比python要短造成的。

- ruby没有类似jython的东西。</p>

### 4、python和ruby的语言的
    1.从简单的就是好的来说，选python是没错的。python适合寻找简单语言的人，这很可能造成python更流行，因此也有更多的支持。但如果要追求更强大的语法功能，则ruby是好的选择。因为ruby和python的哲学有很多相似的地方，先从python入手，尽量用python，如果python的能力不足了，可以在找ruby。

    2.ruby和python的比较，就像五笔和拼音输入法的比较。拼音作为入门的输入法和长久使用的输入法都没有问题。五笔适合更高要求的情况。如果追求性能的不妨学学ruby。对编程语言感兴趣，想了解各种编程概念的学ruby也会很兴奋。
    

## 二、两者各有特点
<b>1、Python从语法上来说更质朴一些，而Ruby更性感一些</b><br><br>

- Python的语法相对其他脚本语言来说，没有太多花巧的地方，显得比较死板一点，其实从Python强制代码缩进也可以看出来Guido设计语言的取向。语法死板的一面就是不容易玩出来更性感的东西，比方说Rails这样的框架，另外Python也无法做DSL这样的事情，但是语法死板的另一面就是比较规范，相对来说，更加适应软件开发的工程性要求，更容易组织大规模的团队进行开发。

Ruby的语法非常灵活，Matz设计ruby的出发点也是为了coding for fun，因此可以用ruby玩出来很多花样，运用足够的技巧，可以用Ruby写出来逼近自然语言的DSL，对于程序员来说，玩ruby确实充满了乐趣。Rails能在ruby社区诞生，而不是Python社区诞生绝对和编程语言有直接的关系。不过ruby语法灵活的另一面就是编程实现风格的多样性，这对于大规模团队的协作和管理是一个挑战。


<b>2、Python的解析器实现更成熟，第三方库质量高</b><br><br>

- Ruby1.9解析器尽管已经有了很大的性能提升和很多新的功能，但是从源代码实现的角度来说，基本上是通过在Ruby1.8源代码上打patch来增加功能的。从源代码的结构来说，Ruby的实现太古老了，Ruby扩展起来比较困难，只能不断打patch。这也是为什么现在Ruby社区涌现出来那么多新的Ruby解析器实现的原因。从很大程度上来说，这制约了Ruby的发展速度。相对而言，Python解析器更成熟，也比较稳定。

- 在第三方类库的数量上来说，Ruby并不比Python少，但是高性能高质量久经考验的第三方类库Python要明显比Ruby多，事实上很多Ruby的第三方类库都不太成熟，因此这也很大程度上制约了Ruby的发展。


<b>3、Python的应用领域非常广泛，而Ruby目前主要局限在在Web领域</b><br><br>

- Python应用的领域非常广泛，除了web开发以外，还被广泛用在服务器后端的高性能服务器实现，服务器后端的各种密集运算，全文检索，各种文本处理，系统管理等等，另外桌面应用领域wxPython也是一个很成熟的跨平台GUI框架。对于某些特殊的应用，比方说调用操作系统内核API，Python也可以完成的很好，比方说大量小文件的实时同步方案，就是用Python直接调用linuxKernel的inotify特性来实现的。所以可以说Python是软件开发领域的瑞士军刀，什么事情都可以做。

- 正是由于Ruby解析器和Ruby类库的制约，Ruby的应用主要局限在Web开发领域，目前Ruby的应用还无法延伸到web开发领域以外的很多地方。据说豆瓣早期就考虑过Ruby on Rails，但是因为Ruby不能做其他事情，而Python可以大包大揽，最后放弃Ruby选择了Python。


<b>4、在Web领域Ruby是王者</b><br><br>

- 随着互联网应用更进一步渗透到软件开发的各个领域，其实web开发占整个软件行业开发的比重也是越来越大。尽管Ruby在其他领域很受制约，但是在Web开发领域就是绝对的王者了。Rails框架的领先程度已经远远甩开了任何一个潜在的竞争对手十万八千里。因此尽管Ruby可能有这样那样的问题，但是说到Web开发，Rails几乎就是无可争议的唯一选择。

- 而Python尽管十分全面，却偏偏在web开发领域不彰，web框架虽然众多，却没有一个真正可以挑大梁，Django虽然在Python社区比较流行，但很多方面也有缺陷。现在的互联网应用往往都是多种语言混合编程，Ruby在Web以外的缺陷也可以用其他语言来弥补。


<b> 5、Python的包管理不如Ruby</b><br><br>

- 尽管Python的第三方类库更高质量更成熟，但是Python社区缺乏Ruby Gem这样一个良好的包管理软件和包发布的网站。因此应用的构建显得不如Ruby那么方便，那么人性化。特别是在类库的版本升级上，就会遇到很多麻烦，不如Ruby Gem那么简单。

- 不过总的来说，Python和Ruby还是相似度极高的两种编程语言，即使两种编程语言都学习一下也不会浪费太多时间。如果我个人选择的话，会首选用Rails来构建web应用，再根据情况选择Python或者Java处理一些服务器后端的运算。总之，未来还是一个混合编程的时代，我们需要多了解一些编程工具，然后根据需要看菜吃饭才行。


<h3>总结</h3>

然后针对于Python跟Ruby在朋友的建议下还给出了如下一些参考意见:<br>

1.  Python也被称为是一门清晰的语言。因为它的作者在设计它的时候，总的指导思想是，对于一个特定的问题，只要有一种最好的方法来解决就好了。Python语言是一种清晰的语言的另一个意思是，它的作者有意的设计限制性很强的语法，使得不好的编程习惯（例如if语句的下一行不向右缩进）都不能通过编译。这样有意的强制程序员养成良好的编程习惯。Python在其他部分的设计上也坚持了清晰划一的风格，这使得Python称为一门易读性、易维护性好，并且被大量用户所欢迎的、用途广泛的语言。

同一个问题用Python几个人分别写写出来的代码会很相近。但Ruby则设计思想不一样，用它写出来的程序太过于灵活，不同的人写出来可能相差会很大。<br>

 2.  Ruby英文文档极度缺乏，中文文档就更不用说。Python社区相对成熟，也有一大堆的资料。<br>

最后给出Python的几个网站<br>

 1. http://www.python.org/- Python 的官方网站<br>

 2. http://python.cn/- Python 中文社区<br>

 3. http://www.codeplex.com/Wiki/View.aspx?ProjectName=IronPythonPython For Dot Net 的网站<br>

Ruby的几个网站<br>

1. www.ruby-lang.org/zh_CNRuby中文官方网站<br>

2. http://www.rubystudy.com/bbs/tag.php?name=RubyRuby中文学习交流社区<br>

3. http://ruby-lang.guo.cc/Ruby在线参考手册<br>
