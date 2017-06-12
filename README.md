# 数字证书的主动测量及有效性及有效性分析
## 研究背景和意义
以食为天，食以安为先，全社会一直在关注这样一个问题：如何才能更加有效的规范和引导企业在生产过程中保障产品质量？如何让消费者购买的食物变得更加的安全可靠？
进入新世纪，农产品质量安全问题日趋严重，已严重威胁到人们的生命安全。面对严峻的农产品质量安全形势，发达国家纷纷要求进口到该国的农产品必须具有可追溯性。2001年以来，我国十分重视农产品质量安全可追溯制度建设及可追溯系统的研究、引进和建立，全国各地陆续开展了建立可追溯系统的试点工作，并取得了丰硕的成绩。追溯是指通过登记的识别码，对商品或行为的历史和使用或位置予以追踪的能力。可追溯性是指利用已记录的标记追溯产品的历史、应用情况、所处场所或类似产品或活动的能力。追溯系统一般涉及信息记录、采集、交换、传递、追踪等环节。建立农产品质量安全农产品质量追溯系统[3]，可以提高农产品质量安全突发事件的应急处理能力；提高政府管理部门对农产品质量安全的监管效率；增强消费者的安全感；提高生产企业诚信意识和生产管理水平；提升我国农产品的国际竞争力。
## 国内外研究现状
我国溯源系统的研究始于2002年,而此时欧美发达国家的农产品溯源系统已开始发挥作用，并且目前已建立起相对比较完善、涵盖面广、具有统一性的农产品溯源系统体系。就我国目前的情况来看，农产品溯源系统在仍处于试点阶段，各省各市起步时间和系统体制不完全相同，并且农产品溯源系统基本只普及到各试点的超市范围[4]。
目前，国内较有影响力的农产品溯源系统平台主要有五个：上海食用农副产品质量安全信息查询系统、北京市农业局食用食品质量安全追溯、世纪三农“食品安全溯源管理系统”、中国肉牛全程质量安全追溯管理系统、国家蔬菜质量安全追溯体系。它们从识别码、存储信息、到网络查询系统等各方面都不完全统一，
## 主要开发任务
本次课程设计所解决的主要问题是如何通过设计一个切实可行的软件系统解决农产品安全质量溯源手段落后的现状[10]。所涉及的主要内容包括：开发一个能够及时追溯农产品源头系统，功能包括：设计开发农产品二维码溯源系统的前端，即消费者，实现二维码的信息查询、设计开发农产品二维码溯源系统的后端，即溯源企业，完成农产品生长过程中信息的录入，如：产地、温度、种植时间、施肥时间、肥料名称、肥料用量、农药喷洒时间、农药名称等。
我们有系统管理员、用户、生产企业、监管部门四个实体，对溯源系统的角色分配，每个角色进行各项功能的完成。系统管理员授权给企业，管理员对产品信息及企业信息进行管理，用户可以查询产品信息。基于Java语言的MyEclipse工具与JDBC的系统，使用MYSQL作为后台数据库，通过前后台的传递信息实现信息的自动化管理。形成一种主动的、协作的、开放的管理模式，既节省资源，又不受空间限制。围绕这个目标，应用平台的开发设计必须突出坚持管理内容与技术手段相结合，以内容为主的主体性要求；既要立足当今先进技术，又要考虑未来技术发展的前瞻性要求；适应于各种软硬件环境，兼顾不同系统要求，适用于不同水平用户群的通用性要求；以尽可能低廉的投入而获得尽可能高效的经济效益的经济性要求。

## 总结 
随着我国经济的发展和百姓健康意识的提高，日益突出的农产品安全问题 日益受到人们的关注。近几年来，国内外爆发的各种食品安全问题，尤其是农产品质量安全问题让大家对所购买到的农产品心存疑虑。建立农产品溯源系统是保障农产品安全的有效手段，通过二维码手机识别农产品标签，能够使市民便捷的查询到农产品的相关信息。同时，通过溯源系统的建设可以加强对农产品生产销售企业的安全监管，保证农产品从生产到销售整个过程的安全性。在做毕业设计和论文的时候我主要完成了一下几个方面的工作：
1、总结国内外相关领域的研究现状，阐述了该课题设计的必要性。还了解了二维码基本概念和二维码生成原理。
2、运用Java和MySQL相结合建立平台。
3、对前端的开发。用户不仅可以扫二维码查看产品信息，也能进入网站输入二维码上的编号进行查询。
4、通过自己建立的数据库表进行建立后台数据库。这个过程是通过用Java语言编程实现的。
5、设计和实现了农产品二维码溯源系统。主要就是做了交互的平台，让人使用起来更方便。