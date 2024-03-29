If you think there is anything missing from the book list, please feel free to send your suggestions and explanations to ffzdshz@gmail.com.
---
# 关于数据的说明（see supplementary data of [the paper](https://academic.oup.com/pnasnexus/article/2/3/pgad060/7059125) for the English version）
## 整体思想
本数据共收录了2001部学术名著，涵盖了九个学科：数学、物理学、化学、生命科学、哲学、经济学、心理学、政治学、社会学，目标是用书籍来表征自牛顿出版《自然哲学的数学原理》（1687年）至维特根斯坦的《哲学研究》出版（1953年）这267年间这九个学科的智力成果，并通过书籍的出版时间和出版地点数据分析学术史的时空特征。

这些书籍要么是这些领域的经典著作，要么是在这九个学科中做出杰出贡献的杰出人物的代表作。我们通过了解每一位杰出人物对各个学科的贡献以及他们的出版物情况，确定这些贡献体现在他们的哪些著作中，从而筛选出这2001部书籍。如果一位杰出人物并没有出版任何书籍或者他出版的书籍并不能反映他的全部重要成果，我们考虑使用他的论文进行替代，因此，实际上，这2001部著作并不全是书籍，而是包含了150篇论文，但为了叙述方便，下文中使用“著作”一词时，指代的是书籍或论文。
## 数据的收集
### 时间跨度的确定
我们对时间跨度的选择具有一定象征意义。1687 年是牛顿出版《自然哲学的数学原理》的年份，这本书被认为是科学史上最重要的著作之一，它的诞生标志着物理学伟大革命时代的到来，牛顿结束了一个旧时代，开启了一个新时代。正如凯恩斯所说：“牛顿不是理性时代的第一人。他是最后一位魔法师，最后一位巴比伦人和苏美尔人。”

另一方面，在18世纪之前，科学的诸多领域还未形成，即便已经形成，也发展缓慢，通常需要经过几十年才能出现几部有影响力的著作，而一定时间跨度内著作数量过少会带来分析上的困难，即便可以分析，其结果也没有多大参考价值，因为它对偏差非常敏感，多收录一部伦敦的书而少收录一部巴黎的书，可能对结果产生巨大影响。

因此，在牛顿出版《自然哲学的数学原理》这个时间点前后开始我们的数据收集，是比较合理的。

对于结束时间的选择，我们考虑了一下几方面因素：
- 随着时间的推移，学术成果的展现与传播逐渐不再依赖于书籍，而是以学术论文为主。实际上，进入19世纪后，数学领域已经出现了许多著名期刊，如克莱尔期刊，人们选择首先在期刊上发表自己的最新学术研究，物理学、化学和生命科学也是一样，因为19世纪是真正的科学家开始职业化的世纪。不过，他们当中的大多数人还是会选择通过书籍系统地论述、总结自己的研究，当然也会通过书籍发布新成果。在20世纪上半叶，连这一点也有所变化，已经有许多职业科学工作者不撰写书籍，只发表论文，这也是本数据集中出现了少量论文的原因。不过领域内的大师还是会出版一些经典著作。在社会科学领域，直到20世纪上半叶，人们仍然十分愿意用书籍来呈现自己的成果，因为社会科学领域的研究成果往往无法用较短的篇幅全部体现出来，因此重大成果往往是先在论文中提出想法，进而通过书籍进行详细说明，并且也是通过书籍来实现更广泛的传播的。第二次世界大战之后，各国建立起覆盖面更广的国民教育体系，受高等教育的群体人数大幅增加，进行学术研究者人数也大幅增加，不论是自然科学的研究者，还是社会科学的研究者，他们中的绝大多数都不撰写书籍了，只写论文，就连领域内的顶尖人物，许多也只通过论文展现自己的成果了。因此，在这样的逐渐转变中，通过书籍来衡量人类智力成果，已经越来越不适用。
- 离当下越近的学术思想，越难以说清楚它是否可以被评价为经典、是否明显推动了人类进步，因为这些成果还有待时间检验，这就给书籍的选择带来很大难度。
- 随着学术出版行业的不断集中以及通讯、交通的不断发展，出版商的所在地（出版地）与学术活动所在地的关联越来越弱。首先，20世纪以来，学术出版业的大规模收购兼并越来越多，市场份额不断向头部集中，许多书籍由少数几家出版商出版，因而这些书籍所标记的出版地都是相同的，但这并不意味着这些学术活动都是在这个地点产生的，这只是作者不得不选择这些出版商的结果。其次，随着通讯、交通、物流的不断发展，异地出版书籍不再是一件不方便的事情，因此出版社所在地已经不再重要，也不再能反映书籍所对应的学术活动是在哪里产生的。

以上三点，说明收录出版时间离现在太近的书籍意义不大，这种无意义大概从上世纪四十年代开始凸显，到上世纪六十年代则已经十分突出，所以我们的数据的结束时间也应该在这个时间区间之内。

而1953年是20世纪最重要的哲学家之一，维特根斯坦的第二本代表性著作《哲学研究》出版的时间。许多人认为维特根斯坦之后哲学已经“死了”。同时，1953年，威拉德·冯·奥曼·蒯因出版了他的论文集《从逻辑的观点看》，收录了《论何物存在》《经验主义的两个教条》等重要文章，是蒯因诸多重要著作中的第一部。因此，和开始的时间一样，结束的时间也具有一定象征意义。不过，这个结束时间只是意味着我们的分析最晚可以到哪里，实际上我们可以选取267年间任意其中的一段合适的时间区间来进行分析。

数据的收集截止到20世纪50年代对政治学和社会学这两门社会学科来说是不太合适的。二战之后，现代政治科学和社会学的大发展才刚刚开始。生命科学在1953年迎来了一个突破之后，也进入了大发展时期，但其成果主要是以论文来体现的。不过，考虑整体的九个学科和前述的三个因素，数据的收集截止到20世纪50年代是一个大致合适的选择。
### 收录标准
为了避免收集的数据过于偏重名气很大的人，一个杰出人物我们最多选取他的六部著作。但仍然有少数人突破了这一限制，因为这些人物重要的著作实在太多，难以压缩到六部及以下。他们是：爱因斯坦（8部）、亥姆霍兹（7部）、马克思（7部）以及欧拉（7部）。

关于人物最好的介绍来自于百科全书网站[Encyclopedia.com](https://www.encyclopedia.com/)，其它考察人物的网站还有[维基百科](https://en.wikipedia.org/wiki/Main_Page)、大不列颠百科全书网站[Britannica.com](https://www.britannica.com/)等。
### 书籍的确定
下面分别简要叙述每个学科的情况，并对确定收录哪些著作时所使用的资料进行概述。
#### 物理学
本数据共收集了350部物理学著作。除了一般的领域外，物理学中还收录了天文学的著作。物理学的数据中不包括地球物理这一领域。我们收录的第一本物理学著作是牛顿的《自然哲学的数学原理》（Newton’s _Mathematical Principles of Natural Philosophy_, London, 1687），这也是所有领域著作中的第一本。 最后的著作是莫尔斯和费什巴赫合著的《理论物理方法》（_Methods of Theoretical Physics by Philip McCord Morse and Herman Feshbach_, New York, 1953）。

物理学部分，主要参考的学术史书籍为卡约里的《物理学史》，以及剑桥科学史丛书中的《19世纪物理学概念的发展》。天文学方面参考了伏古勒尔的《天文学简史》。

此外，我们还参考了维基百科页面[List of theoretical physicists](en.wikipedia.org/wiki/List_of_theoretical_physicists)和[List of important publications in physics](en.wikipedia.org/wiki/List_of_important_publications_in_physics)，以及[List of astronomers](en.wikipedia.org/wiki/List_of_astronomers)。
#### 数学
本数据共收集了290部数学著作。我们收录的第一本数学著作是雅各布·伯努利的《关于无穷级数及其有限和的算术命题》（Jakob Bernoulli ’s _Positiones arithmeticae de seriebus infinitis earumque summa finita_, Basel, 1689），这是他从1689年到1705年出版的五本关于无穷级数的小册子的第一本。最后的著作是阿尔福斯的《复分析》（Ahlfors’s _Complex Analysis_, New York, 1953）、勒雷的《双曲型微分函数》（Leray’s _Hyperbolic Differential Equations_, Princeton, 1953）和丹齐格的《线性规划笔记》（Dantzig’s _Notes on linear programming_, Santa Monica, 1953）。

数学部分，除了一般的部分之外，还包含了概率论、统计学与应用数学的著作。主要参考的学术史书籍有：莫里斯·克莱因的《古今数学思想》、菲利克斯·克莱因的《数学在19世纪的发展》。

此外，我们参考了网站The Story of Mathematics上的页面[List of Important Mathematicians & Timeline](www.storyofmathematics.com/mathematicians.html)、圣安德鲁斯大学数学与统计学院开发维护的数学史档案网站MacTutor上的[数学年表](mathshistory.st-andrews.ac.uk/Chronology/index/)和对数学家们的介绍。还有维基百科页面[List of important publications in mathematics](en.wikipedia.org/wiki/List_of_important_publications_in_mathematics)、[List of important publications in statistics](en.wikipedia.org/wiki/List_of_important_publications_in_statistics)等。
#### 化学
本数据共收集了179部化学著作。所有关于原子结构的科学进展算在物理学中而不是化学中，而生物化学领域的书籍被算在生命科学里。我们收录的第一本化学著作是斯塔尔编辑的《土质物理学》（Becher’s _Physica subterranea_, Leipzig, 1703），这是他的老师贝歇尔撰写并于1669年出版的书籍。在斯塔尔编辑的这个版本中，他在书中附上了他自己的作品——Specimen Beccherianu，系统地提出了燃素说。最后的著作是英戈尔德的《有机化学的结构与机理》（Ingold’s _Structure and Mechanism in Organic Chemistry_, Ithaca, 1953）、弗洛里的《高分子化学原理》（Flory’s _Principles of Polymer Chemistry_, Ithaca, 1953）和皮策的《量子化学》（Pitzer’s _Quantum Chemistry_, New York, 1953）。

化学部分，主要参考的学术史书籍为柏廷顿的《化学简史》和山冈望的《化学史传——化学史与化学家传》。

此外，我们还参考了维基百科页面[List of important publications in chemistry](en.wikipedia.org/wiki/List_of_important_publications_in_chemistry)。
#### 生命科学
本数据共收集了197部生命科学著作。生命科学由许多主题相互关联但相对松散、各自独立发展的子领域组成。我们这里的生命科学，除了一般的领域之外，还包含了博物学中的植物学和动物学，还有一些生理学的著作，但不包含任何偏医学领域的著作。尽管生命科学的诸多领域都跟地质学有关，但我们这里排除了所有地质学著作。我们收录的第一本生命科学著作是约瑟夫·皮顿·德·悌宇列弗的《植物学原理，或植物识别方法》（Joseph Pitton de Tournefort’s _Eléments de botanique, ou Méthode pour reconnaître les Plantes_, Paris, 1694）。最后的著作是沃森和克里克在Nature上发表的《核酸的分子结构：脱氧核糖核酸的结构》（Molecular Structure of Nucleic Acids: A Structure for Deoxyribose Nucleic Acid）和尤金·奥杜姆、霍华德·奥杜姆合著的《生态学基础》（_Fundamentals of Ecology_ by Eugene Odum and Howard Odum, Philadelphia, 1953）。

生命科学部分，主要参考的学术史书籍为迈尔的《生物学思想发展的历史》、玛格纳的《生命科学史》，以及剑桥科学史丛书中的《19世纪的生物学和人学》和《20世纪的生命科学史》。

此外，我们还参考了维基百科页面[Bibliography of biology](en.wikipedia.org/wiki/Bibliography_of_biology)。
#### 经济学
本数据共收集了234部经济学著作。我们收录的最早的经济学著作是配第的《政治算数》（Petty’s _Political Arithmetic_, London, 1690）和巴贲的《论贸易》（Barbon’s _A Discourse of Trade_, London, 1690）。最后的著作是弗里德曼的《实证经济学论文集》（Friedman’s _The Methodology of Positive Economics_, Chicago, 1953）、汉森的《凯恩斯指南》（Hansen’s _A Guide To Keynes_, New York, 1953）和海尔布罗纳的《世俗的哲学家》（Heilbroner’s _The Worldly Philosophers_, New York, 1953）。

经济学部分，主要参考的学术史书籍为熊彼特的《经济分析史》，这是一本极好的资料，对经济学家的列举很全面，并且会提到经济学家们的主要著作，但由于其成书较早（1954年），熊彼特也并未完成这部作品，因此这部书缺少离20世纪50年代比较近的较新的经济学。另一个参考是凯恩斯为一些经济学家写的人物传记。

此外，我们还参考了网站[The History of Economic Thought](www.hetwebsite.net/)上关于经济学思想流派的介绍，这是另一个重要参考源。还有维基百科页面[List of important publications in economics](en.wikipedia.org/wiki/List_of_important_publications_in_economics)。
#### 心理学
本数据共收集了174部心理学著作。心理学家艾宾浩斯说：“心理学有一个漫长的过去，但只有短暂的历史。”心理学的数据中收录的著作主要是现代心理学的作品，近代早期一些哲学心理学的著作，包括被称为经验主义心理学、理性主义心理学和联想主义心理学的部分作品，被算在哲学里，而不是心理学里。但作为理性主义心理学的一部分，洛采的作品被划分为心理学而不是哲学。贝恩作品也被划分为心理学。总而言之，在我们这里，现代心理学的开端是1850年代，这个学科最早出现的作品是洛采的《医学心理学》（Lotze’s _Medical Psychology or Physiology of the Soul_, Leipzig, 1852）。最后的著作是艾森克的《心理学的使用和滥用》（Eysenck’s _Uses and Abuses of Psychology_, London, 1953）、斯金纳的《科学与人类行为》（Skinner’s _Science and human behavior_, New York, 1953）、沙利文的《精神病学的人际关系理论》（Sullivan’s _Interpersonal theory of psychiatry_, New York, 1953）以及希尔加德和艾特金森合著的《心理学导论》（_Introduction to Psychology_ by Ernest Hilgard and Richard Atkinson, New York, 1953）。

心理学部分，主要参考的学术史书籍为黧黑的《心理学史》和舒尔兹的《现代心理学史》。
#### 政治学
本数据共收集了135部政治学著作。我们所说的政治学，主要指的是被认为属于“政治哲学”的那一类书籍、现代政治科学相关书籍以及历史上的政治人物为某种政治目的所写的小册子。我们收录的第一本政治学著作是洛克的《政府论》（Locke‎’s _Two Treatises of Government_, London, 1689）。最后的著作是施特劳斯的《自然权利与历史》（Strauss’s _Natural Right and History_, Chicago, 1953）和伊斯顿的《政治系统》（Easton’s _The Political System_, New York, 1953）。

政治学部分，主要参考的学术史书籍有：萨拜因的《政治学说史》、施特劳斯的《政治哲学史》，以及《剑桥十八世纪政治思想史》和《剑桥二十世纪政治思想史》。

此外，我们还参考了维基百科页面[List of political philosophers](en.wikipedia.org/wiki/List_of_political_philosophers)。
#### 社会学
本数据共收集了129部社会学著作。社会学的数据不包含任何人类学的著作。一般认为，孔德的实证哲学是社会学的开端。我们收录的第一本社会学著作是孔德的《实证哲学教程》（Comte’s _Course of Positive Philosophy_, Paris, 1830）。最后的著作是尼斯贝特的《对社区的追求》（Nisbet’s _The Quest for Community: A Study in the Ethics of Order and Freedom_, New York, 1953）。

主要参考的学术史书籍为夏尔·亨利·屈安、弗朗索瓦·格雷勒、洛南·埃尔武埃合著的《社会学史》。

我们还参考了参考了西华盛顿大学社会学和人口学教授 Ed Stephan 制作的[A Sociology Timeline from 1600](edstephan.org)；国际社会学协会选出的[Books of the XX Century](www.isa-sociology.org/en/about-isa/history-of-isa/books-of-the-xx-century)；维基百科页面[Bibliography of sociology](en.wikipedia.org/wiki/Bibliography_of_sociology)。
#### 哲学
本数据共收集了313部哲学著作。我们收录的第一本哲学著作是马勒伯朗士的《关于宗教和形而上学的探讨》（Malebranche’s _Dialogues on Metaphysics and Religion_, Paris, 1688），最后的著作是图尔敏的《科学哲学：导论》（Toulmin’s _The Philosophy of Science: An Introduction_, London, 1953）、奎因的《从逻辑的观点看》（_From a Logical Point of View_, Cambridge, USA, 1953）和维特根斯坦的《哲学研究》（Wittgenstein’s _Philosophical Investigations_, Oxford, 1953），其中《哲学研究》是我们收录的最后一本著作。

哲学部分，除了一般的部分之外，还包含了逻辑学和科学哲学的著作，以及在心理学发展史早期被称为“哲学心理学”这一类型的作品。主要参考的学术史书籍有：梯利的《西方哲学史》、斯通普夫的《西方哲学史》、托马斯·鲍德温的《剑桥哲学史（1870～1945）》，以及《劳特里奇哲学史（第五卷）：英国哲学和启蒙时代》《劳特里奇哲学史（第六卷）：德国唯心主义时代》《劳特里奇哲学史（第七卷）：19世纪哲学》《劳特里奇哲学史（第八卷）：20世纪大陆哲学》《劳特里奇哲学史（第久卷）：20世纪科学、逻辑和数学哲学》《劳特里奇哲学史（第十卷）：20世纪意义、知识和价值哲学》。其中，梯利的《西方哲学史》最为重要，这本书列出了所介绍哲学家们的重要著作，就这一点来说这是一部很好的参考书，不过介绍的哲学家仍然不够全面。

此外，我们还参考了维基百科页面[List of important publications in philosophy](en.wikipedia.org/wiki/List_of_important_publications_in_philosophy)和[Timeline of Western philosophers](en.wikipedia.org/wiki/Timeline_of_Western_philosophers)等。
#### 综合性
除了每个学科的专门的学术史书籍之外，我们还参考了一些综合性的学术史书籍，包括亚·沃尔夫（Abraham Wolf）的《十六、十七世纪科学、技术和哲学史》和《十八世纪科学、技术和哲学史》，以及《剑桥科学史：现代早期科学》、《剑桥科学史：18世纪科学》、《剑桥科学史：近代物理科学与数学科学》、《剑桥科学史：现代社会科学》、剑桥科学史丛书中的《科学与启蒙运动》以及查尔斯·默里的《文明的解析》。
### 书目元数据
在确定了书籍之后，我们确定每一本书的书目元数据。我们收集的书籍数据是这本书籍的第一版的数据。比如，海德格尔的《存在与时间》，德语原版于1927年由出版商Max Niemeyer在哈雷出版，而这部书的英文版于1962年由纽约的出版商Harper and Row出版，那么我们记录的数据是1927年首次出版的德语原版的数据。

在持续更新版本、扩充或修订内容的书籍，也只记录第一版的信息。分多卷出版的书籍，通常只收录第一卷的信息，不重复收集。

通常，一本书的扉页上会记录这本书的书名、作者、出版地、出版年份和出版商信息。我们记录了每一本书的出版时间和出版地点以及作者，部分书籍含有出版商的信息。
#### 书目元数据的来源
互联网档案（[Internet Archive](https://archive.org/)）、[WorldCat](https://www.worldcat.org/)、[The Online Books Page](https://onlinebooks.library.upenn.edu/)、[Wikisource](https://wikisource.org/wiki/Main_Page)、[古登堡计划](https://www.gutenberg.org)等数字图书馆可能会提供我们需要的书籍版本的扉页图片或者出版信息。一些数学领域的书籍信息可能来自于密歇根大学历史数学合集（[The University of Michigan Historical Mathematics Collection](https://quod.lib.umich.edu/u/umhistmath/)）。一些生命科学领域的书籍信息可能来自于BHL（[Biodiversity Heritage Library](https://www.biodiversitylibrary.org/)）。

许多经典书籍的首个版本目前在一些私人收藏家手里，而不是在各大图书馆中，因而也没有被各大图书馆数字化。不过，可以通过一些拍卖品网站（如古旧书籍交易网站[BIBLIO](https://www.biblio.com/)）获得这些书籍的扉页图片，私人收藏家在拍卖这些书籍的时候会提供书籍的详细信息或者清晰的书籍照片。

一些期刊的信息，比较系统的可以查询的网站是德国联合期刊目录（[German Union Catalogue of Serials](https://zdb-katalog.de/index.xhtml), ZDB），但仅限于德语期刊。

但作为更简单的方式，我们直接通过谷歌搜索书籍名称来获得所有相关网站上的信息，搜索结果可能将我们引导至以上提到的网站，或者其它任何可能提供准确信息的网站，从而获得关于我们想要的书籍版本的数据。
#### 关于出版年份
在过去的一些时期，印刷业普遍采取的做法是将某年接近冬季出版的书的出版年份写成下一年。比如，叔本华的《作为意志和表象的世界》是在1818年12月出版的，但这本书的扉页记录的出版年份是1819年。

由于本数据所记录的出版年份一部分来自于书籍的扉页信息，一部分来自于各种网站上关于该书出版状况的描述，因此在出版年份上并没有统一标准，本数据中书籍所记录的年份，可能是扉页上记录的年份（那么它既有可能是真正出版的年份，也有可能比真正出版的年份晚一年），也可能是真实的出版年份（那么它就有可能跟扉页上记录的年份不一致）。

这种误差最多是一年，努力确定每本书的最准确的出版年份是不必要的。
#### 关于出版商名称
许多历史悠久的出版商会修改它的名字，或者在不同的时间在其出版书籍的扉页上使用不同的简称，但实际上它们代表同一家出版商。本数据的1851部书中，有1157部书包含有出版商的数据，我们对出版商的名称做了统一修正，同一家出版商使用相同的简称，

而这个简称有可能跟那本书上所印刷的名称不完全一致。比如，“Longman, Orme, Brown, Green and Longmans”“Longman, Brown, Green and Longmans”“Longman, Green, Longman, Roberts and Green”“Longmans, Green & Co.”这些简称，我们统一使用“Longman”来代表。
#### 关于出版地点
书籍的出版地点指的是书籍出版商的总部所在地。

一些历史悠久的书籍出版商可能会搬迁总部的位置，或者在其它城市建立分部，或者将其国外业务独立出去，这会影响到其出版书籍的扉页上标记的地点。

比如，麦克米伦出版社1843年在伦敦成立，出版的书籍扉页上标记的地点为伦敦。1896年，麦克米伦将其美国业务出售给布雷特家族，麦克米伦美国公司成立，其出版的书籍扉页上标记的地点为纽约。

再比如，牛津大学出版社之前被称为“The Clarendon Press”，在设立伦敦办事处后，在伦敦出版的书籍被标记为“Oxford University Press”出版的书籍，在牛津出版的书籍仍被标记为“The Clarendon Press”出版的书籍。1896年，牛津大学出版社成立北美分部，分部出版的书籍扉页上标记的地点则为纽约。

书籍扉页上所标记的地点可能有多个，这是因为出版商可能有多个“总部”，他们出版的书籍会在两个地方同步出版。这时，我们将选取其中的一个地点作为这本书的出版地，有可能是最靠前的地点，也有可能是跟书籍作者关联更大的地点。比如，弗洛伊德的《梦的解析》，于1899年由出版商Franz Deuticke出版，扉页上写的出版地为“Leipzig und Wien”（德语，意为“Leipzig and Vienna”），而弗洛伊德在维也纳活动，因此选取的出版地为维也纳。

一些一开始匿名出版的书籍，为了躲避审查，可能会标记虚假的出版地点。比如霍尔巴赫的《自然的体系》，书籍扉页上写明的出版地点为“Londres”（法语，意为伦敦）。但实际上，这本书是在阿姆斯特丹出版的。对于这种情况或类似情况，我们记录的书籍出版地为书籍的真实出版地。
### 数据结构
- **时间**：该著作出版的年份。
- **著作**：该著作的名称。对于非英语书籍，可能使用原名称，也可能使用英文翻译的名称。
- **著作_中文**：著作名称对应的中文名称。难以找到对应中文名称或者难以翻译的，用原名称填充。
- **人物**：该著作的作者。有多名作者的，用“/”分开。
- **人物_中文**：著作作者对应的中文名。
- **学科**：该著作所属的学科。共有九个学科：数学、物理学、化学、生命科学、哲学、经济学、心理学、政治学、社会学。
- **类型**：著作的类型。有三种类型：（1）“0”：该著作为书籍。（2）“1”：该著作为论文。此时，“出版商”一栏所写的不是出版商名称，而是该论文所属的期刊名称。（3）“2”：该著作为某本书的一部分或者某系列书籍的一部分。如，泡利的《波动力学一般原理》，1933年作为Hans Geiger和Karl Scheel编辑的德国百科全书《物理手册》第42卷第1分册出版。此时，“出版商”一栏所写的不是出版商名称，而是该著作所在的书籍的名称。
- **出版地**：该著作的出版地点。如果著作类型为“0”，那么该地点为这本书的出版商的所在地。如果著作类型为“1”，那么该地点为论文所属的期刊的出版单位的所在地。比如，爱因斯坦的论文《论动体的电动力学》于1905年发表在《物理学年鉴》（Annalen der Physik）上，此时该期刊由莱比锡的出版商Johann Ambrosius Barth出版，因此这一著作的出版地就是莱比锡。如果著作类型为“2”，那么该地点为这部著作所在书籍的出版商的所在地。
- **备注**：关于该著作的一些说明。
