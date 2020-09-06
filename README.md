# HHU_course 河海大学，计算机专业课程资料
**阅读须知：这个Repo尽可能整理了HHU CS专业课的学习资料（包括一些课程的难易程度、口碑和部分往年试题），主要是为了方便学弟学妹们对课程有个初步认识，其中很多内容仅代表个人观点，所有内容仅供学习交流使用，请勿违犯法律和校规！<br>
资料包百度云地址：<br>
大三及以前：https://pan.baidu.com/s/1NlRYO8dC-WitwmrRu6nd-g 提取码：fmu3<br>
大四上：https://pan.baidu.com/s/1ugnU4ZPX2OWnN0tyeNTxmg 提取码：ww8v<br>
PS: 一些同学贡献给本项目的资料我已经全部上传到仓库对应课程的文件夹内了，欢迎大家一起PR**<br>
<br>
**转载时请注明出处！https://github.com/Servon-Lee/HHU_course<br>
如果对您有帮助请给一个⭐star, thx!**

## 大四上
**信息检索系统（选修）**<br>
  
> &emsp;&emsp;这门课真的不是教你怎么用百度Google(捂脸哭，感觉比较偏向做文本的东西，又好像跟NLP有点关系。我当时在考托福和GRE，手头上事比较多，跟自己的爱好不太一致无奈选的这门课，上课基本没怎么去（不要学我，里面有些知识点还是蛮有用的，比如tf-idf等等），最后不考试，只需要做项目，老师给了四个题（如下），任选一个就可及格，但分数只有60-70左右，由于这门课是选修，很多人就做了一个，年级均分67.16。选修课虽然不算GPA，但是均分会算的。Gap一年的出国党不但看GPA还要看均分(唉，无奈做了三个题，吹了一波卷积神经网络，还对题目里的tf-idf算法提出了改进意见（虽然我也不知道自己的想法对不对，吹就完事了），最后成绩90，排名第一。要提高均分的可以多做几个题。PS: 上课偶尔点名<br>
&emsp;&emsp;四个题：
1. 试按tf-idf算法在剔除一些常用词后给出文本中术语的统计算法和程序，并按降序进行排列。<br>
2. 试编制首先对文档建立inverted file，然后进行检索的算法和程序。<br>
3. 试给出检查文本中有错误的单词，并进行纠错的算法和程序。<br>
4. 试编制一个爬虫算法和程序。(我当时写的是一个全自动登录河海大学URP教务系统，查询各科成绩、每学期绩点、平均分、总绩点和总平均分。<br>

> &emsp;&emsp;项目需求1：因为教务系统的学生端只能查询总绩点和平均分，无法查询每学期单独的绩点和平均分，本程序可分学期进行计算。<br>
> &emsp;&emsp;项目需求2：因为教务系统在登录时需要人工输入验证码，本程序使用卷及神经网络对验证码进行破解，只需输入账号密码即可登录。)<br>
> &emsp;&emsp;源码详见另外一个[project](https://github.com/Servon-Lee/HHU_crawl_score)<br>

**认识实习**<br>
> 1个学分，学校附近某企业的老师来授课，上课带着写一个基于Android的百度地图Simple版本，大部分功能都带着我们实现了，跟着写就能及格，剩下的一些功能需要自己完善，最后考察老师让同学互查，低于95的把成绩直接报给班长，高于95的给老师检查（刚开始老师定的checkpoint是90，>=90的需要给老师检查，因为报完成绩就可以溜了，好多同学直接就报85-89，后来要找老师检查的人太多了，checkpoint就提高到了95，所以，不要着急报成绩，多拿0.5个绩点😂）<br>

**计算机系统综合课程设计**<br>
> 随便做一个啥系统都行，这个课设时间很多同学都在准备考研，取巧的方法就是拿往年做过的项目修修改改，有时间的同学可以选择毕设预研（就是提前开始做一些毕设的内容，毕设迟早都要做，我觉得蛮好）<br>

**虚拟现实（选修）**<br>
> 这个课和大三上的多媒体概论是同一位老师教的，所以上课风格类似。授课内容个人觉得比较偏向理论、疏于实践，比如VR概论、刚体变换、光学、人类视觉感知、建模等，没有讲如何使用Unity3D这些软件。最后结课可以选择考试（半开卷，可以带一张A4纸）或者组队做一个小的VR程序并在课堂上汇报。上课偶尔点名，经常叫人回答问题，考试和考研的时间接近。总体来说，课程难度不大，考试内容基本是往年原题，均分较高。<br>

**软件需求工程（选修）**<br>
> 内容和软件工程有交叉，个人对软件相关的课程不感兴趣，因时间问题只能无奈选择，我们今年上课点名次数不多（听往届学姐说经常点名），好像是三次，上课会交大概三四次的当堂作业（基本上也就是考试题），最后的结课考试开卷，内容基本在PPT上都能找到，给分较高。<br>

**大数据处理与开发实践**<br>
> 交五次实践报告：<br>
熟悉常用的Linux操作和Hadoop操作、熟悉常用的HDFS操作、熟悉常用的HBase操作、NoSQL和关系数据库的操作比较、MapReduce初级编程实践。<br>
跟着实验指导书操作就好了，五个实验可以不做完，但是the more the merrier. 最后考察是老师挨个检查，随便做几个比较熟的实验，最好把命令背下来当场敲代码，边敲边解释为什么要这么写，给他一种你是大佬的错觉(本来就是大佬的当我没说)，他会当场给你评分。尽量早点找老师检查，不要拖到最后一天，老师的脾气随时间指数级增长，而且最后检查的人太多，可能就给你一两分钟的演示时间，发挥不好就凉。<br>
<br>

## 大三下
**数字图像处理（选修）**<br>
> 文件夹里有：PPT+论文写作要求。老师讲课非常OK，有意向做CV的建议选修。这门课会经常点名，一学期点五次左右，但是老师非常Nice，允许有几次不到。课程内容非常充实，有大作业+期末考试。大作业是写一篇关于CV方向比较前沿/流行的内容，占30分。只要愿意付出时间一定会有收获的！最最最重要的成绩：总体来说给分挺高的，期末考试卷面总分110，给了大家10分的缓冲，可带一张A4纸（有的考场老师比较有原则，说A4就A4，说一张就一张，你带A3就让你裁一半，带两张就上交一张），因为考前会划考点（对！不是划重点，是划考点！）讲道理一张A4纸绝对足够了（PS：我已经整理好了，看文件包吧）。总而言之，满分不难。<br>

**数据库系统原理**<br>
> 课程难度中规中矩，考前复习很重要考前复习很重要考前复习很重要！<br>
> 课设：个人实践部分很简单，熟悉SQL语法之后照着老师发的实验指导书敲一遍就行了。团队实践我记得当时是和软件工程的课设结合在一起了，相当于一个小组两周做一个proj，难度因人而异。<br>

**软件工程**<br>
> 看课件，课堂作业好好做，会计入平时分。考前会划重点，再看看往年题。<br>

> 课设：需要先写一个规划安排，大概内容就围绕整个一周时间是怎么规划的，采用什么开发模式，比如敏捷开发就可以扯一扯站立会议、结对编程。团队课设内容同上。<br>

**Linux操作系统与应用（选修）**<br>
> 总成绩 = 平时课堂成绩 + 课程论文 + presentation. 老师讲课比较幽默，一看就是个技（程）术（序）男（猿）出身，上课点名用他自己的程序（系统只开放几分钟，有密码，一般会写在黑板上或口头说，emmmm还会在愚人节跟我们开玩笑- -可能这就是真正的程序员吧）。最后的presentation是学生+老师共同打分（没错还是用他自己的系统），会给前十名同学每人一本书作为奖励。<br>

**计算机网络与互联网**<br>
> 上课认真听，王老师讲课还是不错的。课后作业认真做，对考试帮助比较大。感觉往年试卷作用不大，毕竟老师在考前就主动发给我们了。。。可能意思是：你们尽管复习，考到算我输。<br>
PS: 感谢小王同学贡献的[计算机网络知识框架(面向考试)](计算机网络/计算机网络知识框架(面向考试).html) <br>
> 课设：忘记了。。。反正不难就完事了<br>

**软件体系结构**<br>
> 我好像没去过几次课（反面教材，学弟学妹千万不要学习我），开卷考试，但是考试~~千万不要抄书~~，要抄老师的PPT。往年的大牛学长抄书最后险过，绩点掉的太快就像龙卷风。<br>

**模式识别（英）（选修）**<br>
> 一开始我还以为是全英文授课，想着刚好练练听力。。。后来发现真的是我想多了，只是English PPT，老师讲中文。上课内容涉及到了Machine Learning的一些基础算法，想往这方面发展的同学可以好好学。最后考核就是做presentation，对做过比赛的同学来说比较简单，我看好多同学都是把之前比赛的东西修修改改就拿上来了。<br>

**云计算应用开发实践**<br>
> 一门神奇的课，学校没教过云计算（选修除外），甚至连导论都没有，然后就要求必修云计算实践？？？大概内容就是学习docker+k8s，搭建平台。<br>
<br>

个人觉得选修课的老师都比必修讲的好。。。仅代表个人观点。不要你觉得，我要我觉得。<br>
<br>

**以下是某17级老学长上完大三下之后做的一点点补充：**<br>

**数据库**<br>
> 老师不提供他上课使用的新PPT。往年真题很重要，我们17级考的全是原题，最后两百人里有一半是90+，不及格的总共就7个人。于是你会惊喜的发现自己的绩点涨了0.02结果年级排名一点没变。<br>

**计算机网络**<br>
> 这次是近年来最简单的一张试卷了。但我依旧没考好，因为考前一直在啃王道的计网书，花了很多时间看了一些考研可能会考但是期末考压根就不可能考的内容。因此，如果你想期末拿高分，那复习一定要做有效的复习，要做面向往年试卷的复习。<br>

**软件工程**<br>
> Lee学长分享的软工文件包里的内容太杂了，其实考完试会发现，还是只有往年真题最有用，能帮你捡回几分。简答题问你，基线是什么并举三个例子，我却只记得它的洋名叫BaseLine，脑子里一片空白，刹那间，不禁让人回想起一年前考计组时它问你总线是什么的那个夏天。结果考完试我一看，人傻了，书上课上PPT上都没有讲基线的例子，我还是百度得来了仨。总之软工的试卷，大题起码还会考一些往年的真题，至于选择题跟填空题，虽然也是有几道原题，但我感觉考得很偏。试卷难是一方面，另一方面是大家的复习时间都很短。两周之内三门专业课，明明放暑假在家的时候就可以开始复习，好多人还是拖到返校之后才开始，更有甚者考完计网才开始复习软工，复习时间只有短短的三天。试卷难，时间短，考试的时候我看的出来，大家考得都很痛苦。<br>

**软件体系结构**<br>
> 打印Lee学长的缩影版PPT就可以了。不过一共是五十张，打印费用可能有点贵。我是在家蹭邻居家的打印机打完了带过来的。发卷子的时候，大家一看就十道问答题孤零零地挤在试卷左上角，不禁相视一笑，然后一个个的手都要抄断了，基本上都是一个半小时才交卷。<br>
<br>

## 大三上
**操作系统**<br>
> 个人感觉两个老师教的都不错，其中一位就是上面提到的技术男。操作系统的重要性就不多说了，难度也不多说了。看到往年学长学姐一直传下来的05年的期末试卷突然对操作系统心生敬意。<br>

**操作系统实践课**<br>
> 看老师发的指导书就行了。 PS: 因为这个实践课是最后一周，很多童鞋都来问我是不是交了作业就可以不去了。我们当年是张YF老师，每节实践课都有作业（我记得是当天写完交给学委），最XX的是他上课随机点名（我记得是点三次，有时候早上八点就点。。。）  <br> 

**多媒体概论**<br>
> 上课回答问题会加分，把握住机会，不要不好意思。考试可带1张A4纸，看看资料包吧，都有整理好的。<br>

**人工智能**<br>
> 我的印象里就是上课很无聊，写过一篇关于中文房间的论文，仅此而已。<br>

**编译原理**<br>
> 感觉这门课挺难，考试不算特别难。考前看看资料包里的往年试卷有buff加成。<br>

**微机原理与接口技术**<br>
> 感觉老师比较佛系，考前看看资料包里的往年真题。<br>
实践：用汇编写程序，源码都在资料包里。<br>

**以下是某17级老学长上完大三上之后做的一点点补充：**<br>

**操作系统**<br>
> 今年试卷大改革，老师在最后一节课上笑眯眯地跟我们讲，听说你们有些优秀的学长学姐会给你们分享往年真题啊。于是今年的期末考上不再有往年真题，考试考了整个宇宙，你会觉得划的考点和试卷上的题目完全是两样东西，更窒息的是题目还是中英文双版。河海致用楼，一跃解君愁。<br>

**操作系统实践课**<br>
> zyf早上八点就会点名，今年一共点了三次，分别是周一，周三和周四。如果你迟到错过了点名，可以去办公室找他补签到。我们今年就是一堆人去补签到，队伍都出了办公室排到走廊了。补签到的时候他会问你课设做到哪了，遇到了什么问题，这就算是一次检查。顺带的他还会问你绩点多少，保研or考研，也会给你提点建议，其实还是蛮好的。每个人都必须被他检查一次，要么是去他办公室补签到的时候，要么是最后一节课他自己来找那些没有补过签到次次全勤的好孩子。总之汇报一下课设进度，问你一下未来规划，这就算是检查了。<br>

**编译原理课设**<br>
> 做两个或三个实验，可以自己写也可以从网上找源码，重要的是要搞明白代码是怎么写出来的，因为老师要挨个检查。就是你实验都做好了，就可以举手，然后选一个实验，将代码主体思想和主要函数讲给老师听。讲的过程中一定要自信，声音要洪亮，给老师留下一个好印象。讲完后会给你打个等级，当然最后实验报告的电子版才是最重要的，我汇报拿的A-，结果交了实验报告之后最终成绩出来是个中等我整个人直接裂开。<br>
<br>

## 大二下

**计算机组成与体系结构**<br>
> 一定要背概念！背概念！背概念！说好的填空题，结果考试时：总线是___________。 XX是_________。这难道不是我理解的简答题吗？？？<br>

**软件开发环境**<br>
> 就是学习JSP，听说17级开始人脸签到、上课在线答题了。。。<br>

**算法与数据结构**<br>
> 程序 = 算法 + 数据结构. 保研面试和找工作涉及最多的一门课，非常非常非常重要！对自己负责，不要为了拿高分投机取巧。资料仅供参考<br>

**移动互联网应用开发（选修）**<br>
> 写一个Android程序。<br>

**移动互联网应用开发实践**<br>
> 个人实践就是熟悉安卓编程，参考老师提供的指导书。团队实践利用老师提供的设备和教程源码做就好了，每个模块都有源码，编程过程就像搭积木，没有难度。<br>
<br>

时间关系就先写到这里，感觉大二上之前的应该不是特别需要吧。。。大家需要的话给我留言，需求量大我再补充。<br>
<br>
**资料包百度云地址：<br>
大三及以前：https://pan.baidu.com/s/1NlRYO8dC-WitwmrRu6nd-g 提取码：fmu3<br>
大四上：https://pan.baidu.com/s/1ugnU4ZPX2OWnN0tyeNTxmg 提取码：ww8v<br>
转载时请注明出处！https://github.com/Servon-Lee/HHU_course<br>**<br>
**以上仅代表个人观点，如果对您有帮助请给一个⭐star，欢迎各路大神补充！**<br>
