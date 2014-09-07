=================================
Epigrams on Programming 编程警句
=================================

译者说
======

正如第72句所言*An adequate bootstrap is a contradiction in terms.*，需要解释的笑话多多少少有些悖论的影子。解释笑话总是件吃力不讨好的事，一来容易隐射说笑话的人说得不高明，二来容易隐射听笑话的人反应不够快。

可这吃力不讨好的事，我偏要来做一发。一来这笑话是外国笑话，难免中外笑点不同；二来这笑话是三十年前的笑话，笑点不一定是这个时代的笑点；三来，最大的幸福，莫过于有人告诉我说“你这句话解释错了，原意应该是如此如此”。

*Epigrams on Programming* 作者是 `Alen Jay Perlis <http://en.wikipedia.org/wiki/Alan_Perlis>`_ ，美国计算机科学家，程序员中的上古巨神，因在编程语言中的早期探索和获得首届图灵奖闻名。

*Epigrams on Programming* 发表于 `ACM SIGPLAN Notices, Volume 17 Issue 9, September 1982 <http://portalparts.acm.org/950000/947955/fm/frontmatter.pdf?ip=198.55.120.199&CFID=552884859&CFTOKEN=85666119>`_

耶鲁大学网站上刊登的本文以 `Epigrams in Programming <http://www.cs.yale.edu/homes/perlis-alan/quotes.html>`_ 为题。Epigrams on Programming比Epigrams in Programming多了10条meta-epigram。

正文小标题为译者所加的。

举烛公子
wengshiwei@gmail.com
20140905

正文
====

Preface 前言
-------------

The phenomena surrounding computers are diverse and yield a surprisingly rich base for launching metaphors at individual and group activities. Conversely, classical human endeavors provide an inexhaustible source of metaphor for those of us who are in labor within computation. Such relationships between society and device are not new, but the incredible growth of the computer's influence (both real and implied).lends this symbiotic dependency a vitality like a gangly youth growing out of his clothes within an endless puberty.

The epigrams that follow attempt to capture some of the dimensions of this traffic in imagery that sharpens, forcuses, clarifies, enlarges and beclouds our view of this most remarkable of all roans' artifacts, the computer.

Epigrams 警句
--------------

1
~~~~

原文::

   One man's constant is another man's variable.

翻译::

   吾之常量，彼之变量。

2
~~~~~

原文::

   Functions delay binding: data structures induce binding. Moral: Structure data late in the programming process.

翻译::

   函数推迟绑定；数据结构导致绑定。寓意：(编程中)推迟数据结构化的时间。

3
~~~~~

原文::

   Syntactic sugar causes cancer of the semi-colons.

翻译::

   语法糖导致分号癌。

吐槽:

   Python说，我没有分号癌！

4
~~~~~

原文::

   Every program is a part of some other program and rarely fits.

翻译::

   每个程序都是其他程序不合适的一部分。

5
~~~~~

原文::

   If a program manipulates a large amount of data, it does so in a small 
   number of ways.

翻译::

   如果一个程序用于处理大量数据，它就没几种选择了。

6. 
~~~~~

原文::

   Symmetry is a complexity reducing concept (co-routines include sub-routines); seek it everywhere.

翻译::

   对称性有助于减少复杂度（协程包含例程）。对称性无处不在。

.. glossary::

	sub-routines
		和通常所见的function、method、procedure是同义词，使用return返回。**co-routines** 使用yield。

7. 
~~~~~

原文::

   It is easier to write an incorrect program than understand a correct one.

翻译::

   写错误的程序比理解正确的程序简单。

8 
~~~~~

原文::

   A programming language is low level when its programs require attention
    to the irrelevant.

翻译::

   任何编程语言在处理无关事务时都是低级语言。

9 
~~~~~

原文::

   It is better to have 100 functions operate on one data structure than 10
    functions on 10 data structures.

翻译::

   用100个函数操作一个数据结构比仅用10个函数但是操作10个不同的数据结构要好。

10 
~~~~~

原文::

   Get into a rut early: Do the same processes the same way. Accumulate 
   idioms. Standardize. The only difference (!) between Shakespeare and you 
   was the size of his idiom list - not the size of his vocabulary.

翻译::

   早立规矩：同样方式做的同样处理。积累固定用法(idiom)。标准化。你和莎士比亚的唯一区别是成语(idiom)量——不是词汇量。


吐槽:

	idiom有两个意思，可惜不能都翻译成“成语”。

11 
~~~~~

原文::

   If you have a procedure with 10 parameters, you probably missed some.

翻译::

   如果你写了一个需要10个参数的函数，你或许还漏了什么。

12 
~~~~~

原文::

   Recursion is the root of computation since it trades description for time.

翻译::

   递归是计算之母。她用描述换取时间。

13 
~~~~~

原文::

   If two people write exactly the same program, each should be put in 
   micro-code and then they certainly won't be the same.

翻译::

   如果两个人用低级语言写同一个程序，它们显然不会相同。

14 
~~~~~

原文::

   In the long run every program becomes rococo - then rubble.

翻译::

   程序终将成为洛可可，然后是碎石。

.. glossary::

	Rococo
		洛可可，起源于18世纪法国的艺术风格。华而不实，过度装饰。

吐槽:

	这句话原型应该是::

 		But this long run is a misleading guide to current affairs. 
 		In the long run we are all dead - John Maynard Keynes

 		这种长远的眼光对当下事物是一种误导。长远来看，我们都要要死的 - 凯恩斯（经济学家，不要说没听过这个名字。。。）

15 
~~~~~

原文::

   Everything should be built top-down, except the first time.

翻译::

   凡事都应该自顶向下，除了第一次。

16 
~~~~~

原文::

   Every program has (at least) two purposes: the one for which it was 
   written and another for which it wasn’t.

翻译::

   程序都有至少两个目的：一个是写它的目的，另一个不是。

17 
~~~~~

原文::

   If a listener nods his head when you're explaining your program, wake 
   him up.

翻译::

   如果有人听你讲解程序时点头了，把他叫醒。

18 
~~~~~

原文::

   A program without a loop and a structured variable isn't worth writing.

翻译::

   没有循环和结构变量的程序不值得写。

吐槽:

	这句话原型应该是::

		The unexamined life is not worth living for a human being - Socrates

		未经审视的生活是不值度过 - 苏格拉底

19 
~~~~~

原文::

   A language that doesn't affect the way you think about programming, is
    not worth knowing.

翻译::

   没有影响你思考编程的语言不值得学。

20 
~~~~~

原文::

   Wherever there is modularity there is the potential for misunderstanding: 
   Hiding information implies a need to check communication.

翻译::

   模块是误解之源；信息隐藏预示沟通的必要。

吐槽:

	这句话原型应该是::

		Wherever there is a will there is a way.

		有志者事竟成。

21 
~~~~~

原文::

   Optimization hinders evolution.

翻译::

   优化阻碍进化。

22 
~~~~~

原文::

   A good system can't have a weak command language.

翻译::

   好系统无坏指令。

23 
~~~~~

原文::

   To understand a program you must become both the machine and the program.

翻译::

   要理解一段程序，你得同时成为机器和这段程序。

24 
~~~~~

原文::

   Perhaps if we wrote programs from childhood on, as adults we'd be able to 
   read them.

翻译::

   从童年开始写程序，长大了就能读懂了。

25 
~~~~~

原文::

   One can only display complex information in the mind. Like seeing, 
   movement or flow or alteration of view is more important than the static 
   picture, no matter how lovely.

翻译::

   脑海中只能呈现复杂的信息。就像视觉，无论静止的画面多么美丽，变化更加重要。

26 
~~~~~

原文::

   There will always be things we wish to say in our programs that in all 
   known languages can only be said poorly.

翻译::

   程序中总有些话，所有已知的语言都不能很好的表达。

吐槽:

	何不把programs改成love letter，千言万语道不尽我对你的爱云云。

27 
~~~~~

原文::

   Once you understand how to write a program get someone else to write it.

翻译::

   一旦你理解了怎么写某个程序，让别人去写它吧。

28 
~~~~~

原文::

   Around computers it is difficult to find the correct unit of time to 
   measure progress. Some cathedrals took a century to complete. Can you 
   imagine the grandeur and scope of a program that would take as long?

翻译::

   很难找到合适的时间单位来衡量计算机领域内的进展。有些教堂建了一个世纪。
   你能想象写了一个世纪的程序的雄伟壮丽吗？

29 
~~~~~

原文::

   For systems, the analogue of a face-lift is to add to the control graph 
   an edge that creates a cycle, not just an additional node.

翻译::

   系统的整容是在控制图上加一条边，而不是新的节点。

.. glossary::

	Control graph
		`Control flow graph <http://en.wikipedia.org/wiki/Control_flow_graph>`_, 描述程序运行逻辑。其node是顺序执行的基本单元，edge表示跳转。

30 
~~~~~

原文::

   In programming, everything we do is a special case of something more 
   general - and often we know it too quickly.

翻译::

   编程中，我们常常过快的了解到，所做的都是普遍情况的特例，

31 
~~~~~

原文::

   Simplicity does not precede complexity, but follows it.

翻译::

   简单不先于复杂，而在复杂之后。

32 
~~~~~

原文::

   Programmers are not to be measured by their ingenuity and their logic but 
   by the completeness of their case analysis.

翻译::

   应该用案例分析来评价程序员，而不是他们的机智和逻辑。

33 
~~~~~

原文::

   The 11th commandment was "Thou Shalt Compute" or "Thou Shalt Not Compute" 
   - I forget which.

翻译::

   第11条戒律是“你应计算”或“你不应计算”-我忘了。

吐槽:

	The 11th commandment说法来自摩西十诫(Ten Commandments)的。Thou是古英语you，shalt是古英语第二人称should。

34 
~~~~~

原文::

   The string is a stark data structure and everywhere it is passed there is 
   much duplication of process. It is a perfect vehicle for hiding 
   information.

翻译::

   字符串是个朴实的数据结构，所有使用它的地方总是出现雷同的处理流程。字符串是信息隐藏的完美工具。

吐槽:

	彼时的string一定是pass-by-value的

35 
~~~~~

原文::

   Everyone can be taught to sculpt: Michelangelo would have had to be 
   taught how not to. So it is with the great programmers.

翻译::

   每个人都能学习雕塑，只有米开朗基罗希望学习过雕塑的禁忌。伟大的程序员同理。

36 
~~~~~

原文::

   The use of a program to prove the 4-color theorem will not change 
   mathematics - it merely demonstrates that the theorem, a challenge for a
    century, is probably not important to mathematics.

翻译::

   用程序证明四色定理不会改变数学-这不过证明了，这个持续了一个世纪的挑战，对数学不太重要。

37 
~~~~~

原文::

   The most important computer is the one that rages in our skulls and ever 
   seeks that satisfactory external emulator. The standardization of real 
   computers would be a disaster - and so it probably won't happen.

翻译::
   
   最重要的计算机莫过于那个在我们头颅中咆哮着寻求一个能使它满足的外部模拟器的玩意儿。
   而真实电脑的标准化对于这个目的是种灾难，所以它可能永远不会发生。


38 
~~~~~

原文::

   Structured Programming supports the law of the excluded muddle.

翻译::

   结构化编程支持混乱排除定律（排乱律？）。

.. glossary::

	Law of excluded middle
		排中律，The law of the excluded muddle模仿的。排中律指对于任何命题P，P或非P一定为真。

39 
~~~~~

原文::

   Re graphics: A picture is worth 10K words - but only those to describe 
   the picture. Hardly any sets of 10K words can be adequately described 
   with pictures.

翻译::

   回复 图形学：一张图片等价于描述图片的一万个字。从一万个字任取一部分都无法用图片充分描述。

40 
~~~~~

原文::

   There are two ways to write error-free programs; only the third one works.

翻译::

   有两种写出完全正确的程序的方法，其中的第三种有效。

吐槽:
	
	王声老师在文学院四大才子排行第九 - 苗阜

41 
~~~~~

原文::

   Some programming languages manage to absorb change, but withstand progress.

翻译::

   一些编程语言试图接受变化，却拒绝进步。

42 
~~~~~

原文::

   You can measure a programmer's perspective by noting his attitude on the 
   continuing vitality of FORTRAN.

翻译::

   通过程序员对延续FORTRAN的态度判断他的观点。

43 
~~~~~

原文::

   In software systems it is often the early bird that makes the worm.

翻译::

   软件系统中，早起的鸟儿，造虫子。

44 
~~~~~

原文::

   Sometimes I think the only universal in the computing field is the 
   fetch-execute-cycle.

翻译::

   有时，我想计算领域唯一通用的就是“取址-执行”循环。

45 
~~~~~

原文::

   The goal of computation is the emulation of our synthetic abilities, not 
   the understanding of our analytic ones.

翻译::

   计算的目标是对综合能力的模拟，而不是对分析能力的理解。


.. glossary::

	`Analytic–synthetic distinction <http://en.wikipedia.org/wiki/Analytic%E2%80%93synthetic_distinction, http://plato.stanford.edu/entries/analytic-synthetic/>`_
		The analytic–synthetic distinction (also called the analytic–synthetic dichotomy) is a conceptual distinction, used primarily in philosophy to distinguish propositions (in particular, statements that are affirmative subject–predicate judgments) into two types: analytic propositions and synthetic propositions. Analytic propositions are true by virtue of their meaning, while synthetic propositions are true by how their meaning relates to the world. 

		分析-综合二分是一种概念区分，主要在哲学上用以将命题（更具体的，是肯定的主谓判断陈述）分为两类：分析命题和综合命题。
		
		分析命题靠其自身的意义为真。(e.g. 人皆会死)
		综合命题靠其自身的意义与世界的关系为真。（e.g. Python是最受欢迎的语言）

46 
~~~~~

原文::

   Like punning, programming is a play on words.

翻译::

   编程是文字的游戏，犹如双关。

47 
~~~~~

原文::

   As Will Rogers would have said, "There is no such thing as a free variable.”

翻译::

   威尔·罗杰斯可能会说“世上无自由变量。”

吐槽:

   这句话原型应该是::

      In the early days of the Indian Territory, there were no such things as birth 
      certificates. You being there was certificate enough. - Will Rogers

48 
~~~~~

原文::

   The best book on programming for the layman is "Alice in Wonderland"; but 
   that's because it's the best book on anything for the layman.

翻译::

   外行最好的编程书是《爱丽丝梦游仙境》，因为对任何外行最好的书是《爱丽丝梦游仙境》。

49 
~~~~~

原文::

   Giving up on assembly language was the apple in our Garden of Eden: 
   Languages whose use squanders machine cycles are sinful. The LISP machine 
   now permits LISP programmers to abandon bra and fig-leaf.

翻译::

   放弃汇编语言是我们伊甸园里的禁果。浪费机器周期的语言有罪。LISP机器允许LISP程序员扯下遮羞布。

吐槽:

	这句话改编伊甸园的故事——偷吃禁果，获得羞耻心，用无花果叶(fig-leaf)遮住生殖器。

50 
~~~~~

原文::

   When we understand knowledge-based systems, it will be as before - except 
   our finger-tips will have been singed.

翻译::

   我们理解了基于知识的系统，什么都不会改变——除了指尖会烧焦。

51 
~~~~~

原文::

   Bringing computers into the home won't change either one, but may 
   revitalize the corner saloon.

翻译::

   把电脑带回家里，两者都不会改变，倒是能复兴角落的沙龙。

52 
~~~~~

原文::

   Systems have sub-systems and sub-systems have sub-systems and so on ad 
   infinitum - which is why we're always starting over.

翻译::

   系统有子系统，子系统又有孙系统，子子孙孙无穷匮也。所以我们常重新开始。

53 
~~~~~

原文::

   So many good ideas are never heard from again once they embark in a 
   voyage on the semantic gulf.

翻译::

   大量的好想法，一旦准备穿越语义鸿沟，就失声了。

54 
~~~~~

原文::

   Beware of the Turing tar-pit in which everything is possible but nothing 
   of interest is easy.

翻译::

   留心图灵焦油坑——能力无损，乐趣毫无

.. glossary::

	`Turing tarpit <http://en.wikipedia.org/wiki/Turing_tarpit>`_
		图灵焦油坑。用来描述那些计算能力与常规语言等价，而使用起来十分困难的语言。比如著名的 `brainfuck <http://en.wikipedia.org/wiki/Brainfuck>`_

55 
~~~~~

原文::

   A LISP programmer knows the value of everything, but the cost of nothing.

翻译::

   LISP程序员知道世间万物的值但不知道它们的开销。

56 
~~~~~

原文::

   Software is under a constant tension. Being symbolic it is arbitrarily 
   perfectible; but also it is arbitrarily changeable.

翻译::

   软件有恒定的张力。从符号角度看，可以任意趋向完美；同样，也可以任意多变。

57 
~~~~~

原文::

   It is easier to change the specification to fit the program than vice 
   versa.

翻译::

   让需求适应程序比反过来容易得多。

58 
~~~~~

原文::

   Fools ignore complexity. Pragmatists suffer it. Some can avoid it. 
   Geniuses remove it.

翻译::

   笨蛋无视复杂性。实用者忍受它。有人能回避它。天才去除它。

59 
~~~~~

原文::

   In English every word can be verbed. Would that it were so in our 
   programming languages.

翻译::

   英语里每个词都能做动词。但愿编程语言中也能如此。

60 
~~~~~

原文::

   Dana Scott is the Church of the Lattice-Way Saints.

翻译::

   达纳·斯科特是格(lattice)圣徒教会。

吐槽:

	恶搞的耶稣基督后期圣徒教会（The Church of Jesus Christ of Latter-day Saints）

	达纳·斯科特(Dana Scott)，美国科学家，1976年图灵奖得主，提出非决定自动机。

61 
~~~~~

原文::

   In programming, as in everything else, to be in error is to be reborn.

翻译::

   在编程中同在其它过程中一样，错误意味重生。

62 
~~~~~

原文::

   In computing, invariants are ephemeral.

翻译::

   计算中，不变量转瞬即逝。

63 
~~~~~

原文::

   When we write programs that "learn", it turns out we do and they don’t.

翻译::

   我们写”会学习“的程序，结果是我们在学习。

64 
~~~~~

原文::

   Often it is means that justify ends: Goals advance technique and 
   technique survives even when goal structures crumble.

翻译::

   常常是手段应证了结果；目标会促进技术，技术会存活下来，即使目标造成了崩溃。

65 
~~~~~

原文::

   Make no mistake about it: Computers process numbers - not symbols. We 
   measure our understanding (and control) by the extent to which we can 
   arithmetize an activity.

翻译::

   别弄错了：计算机处理的是数字，而不是符号。我们通过对一项活动算术化的程度评价理解力（和控制力）。

66 
~~~~~

原文::

   Making something variable is easy. Controlling duration of constancy is
    the trick.

翻译::

   生成变量容易，控制不变的时限难。

67 
~~~~~

原文::

   Think of all the psychic energy expended in seeking a fundamental 
   distinction between "algorithm" and "program”.

翻译::

   想一想在寻找“算法”和“程序”的本质区别上花了多少心思。

68 
~~~~~

原文::

   If we believe in data structures, we must believe in independent (hence 
   simultaneous) processing. For why else would we collect items within a 
   structure? Why do we tolerate languages that give us the one without the 
   other?

翻译::

   如果我们相信数据结构，我们必须要相信（同时存在的）独立的数据处理。有什么理由要把东西收集到结构之中？为什么我们要容忍只提供二者之一的语言？

69 
~~~~~

原文::

   In a 5 year period we get one superb programming language. Only we can't 
   control when the 5 year period will begin.

翻译::

   我们将在五年内得到一门极好的语言，只是不能控制这五年何时开始。

70 
~~~~~

原文::

   Over the centuries the Indians developed sign language for communicating 
   phenomena of interest. Programmers from different tribes (FORTRAN, LISP, 
   ALGOL, SNOBOL, etc.) could use one that doesn't require them to carry a 
   blackboard on their ponies.

翻译::

   印第安人用了几个世纪演化出交流有趣现象的符号语言。不同部落(FORTRAN、LISP、ALGOL、SNOBL等)的程序员可以使用不需要他们随身携带黑板的那种。

71 
~~~~~

原文::

   Documentation is like term insurance: It satisfies because almost no one 
   who subscribes to it depends on its benefits.

翻译::

   文档就像人寿保险，人们满足于不指望从中受益。

72 
~~~~~

原文::

   An adequate bootstrap is a contradiction in terms.

翻译::

   充分的引导明显是悖论。

.. glossary::

	bootstrap
		to set up or achieve using minimal resources
		
		bootstrap这个词不知道该怎么翻译，它指的是依靠自己、用很少的资源发展起来。所以和adequate是矛盾的。

73 
~~~~~

原文::

   It is not a language's weaknesses but its strengths that control the 
   gradient of its change: Alas, a language never escapes its embryonic sac.

翻译::

   控制变化的梯度是语言的优点，而不是弱点。哎，语言不会从胚囊中逃走。

74 
~~~~~

原文::

   It is possible that software is not like anything else, that it is meant 
   to be discarded: that the whole point is to always see it as soap bubble?

翻译::

   软件有可能是四不像，有可能注定被清除。关键就在于把它当作肥皂泡。

75 
~~~~~

原文::

   Because of its vitality, the computing field is always in desperate need 
   of new cliches: Banality soothes our nerves.

翻译::

   充满活力的计算领域，总是迫切需要新的陈词滥调：陈词滥调使我们安神。

76 
~~~~~

原文::

   It is the user who should parameterize procedures, not their creators.

翻译::

   用户决定过程的参数，不是程序员。

77 
~~~~~

原文::

   The cybernetic exchange between man, computer and algorithm is like a 
   game of musical chairs: The frantic search for balance always leaves one 
   of the three standing ill at ease.

翻译::

   控制论像抢椅子游戏一样交换人、计算机和算法：疯狂地寻找平衡总使站着的那位不自在。

78 
~~~~~

原文::

   If your computer speaks English it was probably made in Japan.

翻译::

   说英语的电脑产自日本。

79 
~~~~~

原文::

   A year spent in artificial intelligence is enough to make one believe in 
   God.

翻译::

   学一年人工智能足够使一个人信上帝了。

80 
~~~~~

原文::

   Prolonged contact with the computer turns mathematicians into clerks and 
   vice versa.

翻译::

   长时间接触电脑将数学家变成书记员，反之亦然。

81 
~~~~~

原文::

   In computing, turning the obvious into the useful is a living definition 
   of the word "frustration”.

翻译::

   计算领域中，把明显的东西变成有用的东西，是挫折的同义词。

82 
~~~~~

原文::

   We are on the verge: Today our program proved Fermat's next-to-last 
   theorem!

翻译::

   我们的程序证明费马倒数第二定律的日子即将到来。

.. glossary::

	Fermat's Last Theorem

		费马大定理，也叫费马最终定理。当整数n大于2时，x^n+y^n=z^n无整数解。

83 
~~~~~

原文::

   What is the difference between a Turing machine and the modern computer? 
   It's the same as that between Hillary's ascent of Everest and the 
   establishment of a Hilton hotel on its peak.

翻译::

   图灵机和当代计算机的区别是什么？这类似于艾德蒙·希拉里攀登珠穆朗玛峰和在峰顶上造希尔顿酒店。

.. glossary::

	Hillary

		艾德蒙·希拉里，可证明的记录中最早成功攀登珠穆朗玛峰峰顶的人之一。

84 
~~~~~

原文::

   Motto for a research laboratory: What we work on today, others will first 
   think of tomorrow.

翻译::

   研究实验室座右铭：我们今天所研究的，正是他人明天首先想到的。

85 
~~~~~

原文::

   Though the Chinese should adore APL, it's FORTRAN they put their money on.

翻译::

   尽管中国人应该崇拜APL语言，他们却把钱压在FORTRAN上。

86 
~~~~~

原文::

   We kid ourselves if we think that the ratio of procedure to data in an 
   active data-base system can be made arbitrarily small or even kept small.

翻译::

   如果我们认为有效的数据库系统中过程和数据的比值可以设置的足够小或者保持很小，那是跟自己开玩笑。


87 
~~~~~

原文::

   We have the mini and the micro computer. In what semantic niche would the 
   pico computer fall?

翻译::

   我们有小型机和微型机。那么微微型机在哪个语义壁龛中？

88 
~~~~~

原文::

   It is not the computer's fault that Maxwell's equations are not adequate 
   to design the electric motor.

翻译::

   麦克斯韦方程不足以设计电动机不是计算机的错。

89 
~~~~~

原文::

   One does not learn computing by using a hand calculator, but one can 
   forget arithmetic.

翻译::

   用手动计算器无法学会计算，却可以忘记算术。

90 
~~~~~

原文::

   Computation has made the tree flower.

翻译::

   计算让树开花。

吐槽:

	我猜这句话也可以翻译成：计算让母猪上树。

91 
~~~~~

原文::

   The computer reminds one of Lon Chaney - it is the machine of a thousand 
   faces.

翻译::

   计算机让我回想起某个朗·钱尼——它是千面的机器。

.. glossary::

	Lon Chaney (Sr.)，

		朗·钱尼，美国无声电影演员。

	Lon Chaney, Jr.

		小朗·钱尼，美国演员，前者的儿子。

92 
~~~~~

原文::

   The computer is the ultimate polluter. Its feces are indistinguishable 
   from the food it produces.

翻译::

   计算机是最终的污染源，无法区别它生产的食物和它的排泄物。

93 
~~~~~

原文::

   When someone says "I want a programming language in which I need only say 
   what I wish done," give him a lollipop.

翻译::

   如果有人说“我想要一门语言，只需要说出目标就够了”，给他棒棒糖。

94 
~~~~~

原文::

   Interfaces keep things tidy, but don't accelerate growth: Functions do.

翻译::

   接口保持事物整洁，不能加速成长。函数可以。

95 
~~~~~

原文::

   Don't have good ideas if you aren't willing to be responsible for them.

翻译::

   如果你不想为它们负责的话，就别出好主意。

96 
~~~~~

原文::

   Computers don't introduce order anywhere as much as they expose 
   opportunities.

翻译::

   计算机展示机会，却从不介绍订单

97 
~~~~~

原文::

   When a professor insists computer science is X but not Y, have compassion 
   for his graduate students.

翻译::

   当教授坚持计算机科学是X而不是Y时，要同情他的研究生。

98 
~~~~~

原文::

   In computing, the mean time to failure keeps getting shorter.

翻译::

   计算领域，平均失效时间单调递减。

99 
~~~~~

原文::

   In man-machine symbiosis, it is man who must adjust: The machines can’t.

翻译::

   人机共生中，调整的必须是人，机器做不到。

100 
~~~~~

原文::

   We will never run out of things to program as long as there is a single 
   program around.

翻译::

   只要周围还有一个程序，我们就不会耗尽需要编程的东西。

101 
~~~~~

原文::

   Dealing with failure is easy: Work hard to improve. Success is also easy 
   to handle: You've solved the wrong problem. Work hard to improve.

翻译::

   失败很容易处理：努力奋斗，追求进步。成功也很容易处理：你解决了错误的问题。努力奋斗，追求进步。

102 
~~~~~

原文::

   One can't proceed from the informal to the formal by formal means.

翻译::

   无法用形式的方法从非形式到达形式。

103 
~~~~~

原文::

   Purely applicative languages are poorly applicable.

翻译::

   纯粹的应用语言不可用。

104 
~~~~~

原文::

   The proof of a system's value is its existence.

翻译::

   存在是对系统价值的证明。

105 
~~~~~

原文::

   You can't communicate complexity, only an awareness of it.

翻译::

   复杂性只可意会不可言传。

106 
~~~~~

原文::

   It's difficult to extract sense from strings, but they're the only 
   communication coin we can count on.

翻译::

   从字符串中领会感觉很难，但这是我们唯一指望的交流硬币。

107 
~~~~~

原文::

   The debate rages on: Is PL/I Bactrian or Dromedary?

翻译::

   争论热点：PL/I是大夏人还是单峰骆驼？

108 
~~~~~

原文::

   Whenever two programmers meet to criticize their programs, both are silent.

翻译::

   每当程序员面对面批评他们的程序时，都沉默了。

109 
~~~~~

原文::

   Think of it! With VLSI we can pack 100 ENIACs in 1 sq.cm.

翻译::

   想想吧！有了超大规模集成电路，我们能在1平方厘米里放100个ENIAC。

110 
~~~~~

原文::

   Editing is a rewording activity.

翻译::

   编辑是值得做的。

111 
~~~~~

原文::

   Why did the Roman Empire collapse? What is the Latin for office 
   automation?

翻译::

   罗马帝国为何崩塌？办公自动化用拉丁语怎么说？

112 
~~~~~

原文::

   Computer Science is embarrassed by the computer.

翻译::

   计算机使计算机科学羞愧。

113 
~~~~~

原文::

   The only constructive theory connecting neuroscience and psychology will 
   arise from the study of software.

翻译::

   研究软件将发现连接神经科学和心理学的建构理论。

114 
~~~~~

原文::

   Within a computer natural language is unnatural.

翻译::

   计算机内自然语言不自然。

115 
~~~~~

原文::

   Most people find the concept of programming obvious, but the doing 
   impossible.

翻译::

   大家都发现编程的概念如此显然，就是做不到。

116 
~~~~~

原文::

   You think you know when you learn, are more sure when you can write, even 
   more when you can teach, but certain when you can program.

翻译::

   （翻译不出）

117 
~~~~~

原文::

   It goes against the grain of modern education to teach children to program
   . What fun is there in making plans, acquiring discipline in organizing 
   thoughts, devoting attention to detail and learning to be self-critical?

翻译::

   儿童编程教学与现代教育背道而驰。制订计划，整理思路，获得知识，关注细节，学会自我批评，这些有什么乐趣？

118 
~~~~~

原文::

   If you can imagine a society in which the computer-robot is the only 
   menial, you can imagine anything.

翻译::

   如果你能想象所有仆人都是计算机机器人的世界，那么你能想象任何事情。

119 
~~~~~

原文::

   Programming is an unnatural act.

翻译::

   编程是非自然的。

120 
~~~~~

原文::

   Adapting old programs to fit new machines usually means adapting new 
   machines to behave like old ones.

翻译::

   把旧程序调节的适应新机器，往往意味着，把新机器调节的像老机器。

121 
~~~~~

原文::

   In seeking the unattainable, simplicity only gets in the way. If there 
   are epigrams, there must be meta-epigrams.

翻译::

   简单妨碍我们追求得不到的东西。如果有警句，一定有元警局。

122 
~~~~~

原文::

   Epigrams are interfaces across which appreciation and insight flow.

翻译::

   警句是欣赏和洞见的接触面。

123 
~~~~~

原文::

   Epigrams parameterize auras.

翻译::

   警句为气氛提供参数。

124 
~~~~~

原文::

   Epigrams are macros, since they are executed at read time.

翻译::

   警句是宏，在阅读时执行。

125 
~~~~~

原文::

   Epigrams crystallize incongruities.

翻译::

   警句使不协调一览无余。

126 
~~~~~

原文::

   Epigrams retrieve deep semantics from a data base that is all procedure.

翻译::

   警句是从只有过程的数据库中获取的深层语义。

127 
~~~~~

原文::

   Epigrams scorn detail and make a point: They are a superb high-level 
   documentation.

翻译::

   警句蔑视细节，并且自认为是高级文档。

128 
~~~~~

原文::

   Epigrams are more like vitamins than protein.

翻译::

   警句更像维生素而不是蛋白质。

129 
~~~~~

原文::

   Epigrams have extremely low entropy.

翻译::

   警句的熵极低。

130 
~~~~~

原文::

   The last epigram? Neither eat nor drink them, snuff epigrams.

翻译::

   最后一条？警句既不能吃也不能喝，用来闻。
