#Ruby_Dota

##故事梗概
原本准备给Ruby_Dota取名叫Ruby_3C.

3C的正确发音应该是3Chai,即菜、猜、拆。

- 菜。作为一个菜鸟先学习某知名类库的使用，这种学习是即插即用的，学到的知识可以直接应用到实际工作中。
- 猜。猜测其中的某个功能是如何实现的？增加学习者的动手能力，从使用者的角度考虑程序的设计。
- 拆。拆开这个类库，学习它的精典设计。成为高手的必经之路。

这个想法始于一次大庆开往北京的卧铺，床位狭窄，无法承载我伟岸的身躯，翻来覆去睡不着，有了3C的思路。

然而在书写的过程中发现没有必要讲解这些知名类库的使用，这些资料在搜索引擎中可以很容易的获取到。所以我决定去掉菜的部分，直接将猜和拆融合在一起。每个主题都会拆解一个开源类库的功能实现，是一次大的挑战，开发者需要完成一个又一个小的关卡才可以取得终极的胜利，就像Dota一样。

并且这个项目本来就是希望以Code Kata的方式来学习Ruby。Kata Kata，Dota Dota...

故命名为Ruby_Dota。

##安装环境

通过`http://www.ruby-lang.org/en/downloads/`找到不同的开发平台对应的安装方法。
安装完成后打开命令行，使用`ruby -v`测试是否安装成功

###改用taobao的镜像
由于国内网络的原因，在使用gem命令时会非常缓慢。如此可以改用taobao的镜像站。
可参考：`http://ruby.taobao.org`

###安装ri
最新的ruby安装包版本，无法挂载ri。可以使用以下命令,使得ri有效：

	gem install rdoc-data
	rdoc-data --install
	gem rdoc --all --overwrite
	
安装完成后，使用`ri Di`测试.
按键q可以退出ri

###开发环境
我个人喜欢Sublime Text。可到`http://www.sublimetext.com`自行下载