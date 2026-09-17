# 北大张泽民团队、上海交大汪希鹏团队及李子逸联合利用单细胞多组学+多色免疫荧光技术揭示卵巢癌多组织单细胞分辨率图谱

> 更新时间：2026-09-17 (UTC+8)

卵巢癌病理亚型中最常见的是高级别浆液性卵巢癌（HGSOC），超过75%的HGSOC患者首次发现时病情已进展至晚期，并伴有广泛的恶性腹水和网膜转移。尽管大多数患者能从手术+铂类化疗+贝伐珠单抗的联合治疗中显著获益，但仍有一部分患者的整体生存率并没有得到明显改善。此外，卵巢癌腹水中的成纤维细胞可以通过激活肿瘤细胞的 JAK-STAT信号通路进而促进肿瘤生长。因此，一个涵盖多组织位点的高分辨率单细胞图谱对于理解卵巢癌，特别是其网膜转移灶及腹水的免疫微环境极为重要。

7月24日，上海交通大学医学院附属新华医院汪希鹏教授团队、北京大学生物医学前沿创新中心张泽民教授团队以及上海市免疫学研究所Florent Ginhoux组博士后李子逸合作，在 Nature Cancer 期刊发表了题为：Single-cell analyses implicate ascites in remodeling the ecosystems of primary and metastatic tumors in ovarian cancer 的研究论文。该研究通过结合单细胞转录组测序（10x Genomics），单细胞TCR测序 （10x Genomics），多色免疫荧光（AKOYA）技术，发现腹水中记忆T细胞对肿瘤原发灶及网膜转移灶免疫微环境的关键重塑作用，并揭示了肿瘤组织和腹水中巨噬细胞功能表型和发育起源的异质性，为深入理解卵巢癌进展中恶性腹水的关键作用以及探索靶向肿瘤腹水的免疫治疗策略提供了全新的思路和数据平台。
研究结果
1. 通过对五个位点scRNA-seq分析呈现卵巢癌高分辨率景观

作者首先对来自14例上皮性卵巢癌患者的原发灶、网膜转移灶、腹水、外周血以及盆腔淋巴结等39个样本进行了10x Genomics单细胞转录组测序，通过对5个部位样本内细胞类群的比较，结果发现，原发灶和转移灶中有相同的肿瘤细胞亚克隆 ，肿瘤细胞更偏好于扩散到腹膜腔，肿瘤细胞亚克隆是腹膜转移的致瘤群体。

2. 肿瘤和腹水间不同T细胞亚群间的谱系关系

接下来作者分析了不同部位样本内T细胞类群的组成情况，发现在实体肿瘤组织中主要富集耗竭T细胞(Tex)及调节性T细胞(Treg)等免疫抑制型T细胞，而腹水中富集的则多为效应T细胞(Teff)和记忆T细胞(Tcm/Tem)。尽管在所有病人的腹水样本中均可以检测到肿瘤细胞的存在，但结果表明，腹水微环境并未呈现出肿瘤内部的强烈免疫抑制性状态。

为了深入探索肿瘤和腹水中T细胞类群的发育关系，作者结合单细胞TCR测序数据（10x Genomics），对10种不同类型T细胞进行追踪和定量分析，发现肿瘤组织中浸润的Tex细胞与腹水中富集的CD8+GZMK+Tem之间存在高度TCR共享。进一步分析发现，相较于原发灶，腹水中的Tem细胞更倾向与转移灶中的Tex细胞共享TCR。此外，肿瘤中Tex细胞与腹水中Tem细胞之间的联系与其与肿瘤中Tem细胞之间的联系是互相排斥的。由于终末分化Tex细胞具有不可逆转的细胞状态和较差的组织迁移能力，因此以上结果提示腹水中的CD8+GZMK+Tem细胞具有浸润至肿瘤组织中并直接转化为Tex细胞的能力。研究人员在CD4+T细胞的分析中也发现了类似的现象，腹水中的CD4+Tcm与肿瘤组织中的CD4+CXCL13+Th1样细胞同样存在高度TCR共享，揭示其很可能是肿瘤组织中Th1样细胞的前体来源。综合分析显示腹水中富集的记忆T细胞是肿瘤浸润终末状态T细胞极为重要的补充池，揭示了腹水在塑造肿瘤微环境中发挥的关键作用。

3. 卵巢癌腹水及肿瘤组织微环境中不同功能表型和发育来源的巨噬细胞

肿瘤相关巨噬细胞(TAM)是肿瘤免疫微环境中不可或缺的部分，发挥着重要的免疫调控作用。基于不同的组织来源特征，作者将巨噬细胞亚群分为肿瘤富集的巨噬细胞(TeMac)和腹水富集的巨噬细胞(AeMac)两大类群。通过比较两群巨噬细胞的功能发现，TeMac高表达VEGFA及CCL3、CXCL12等细胞因子，具有较强的T细胞招募能力。AeMac则上调LYVE1及CD163等组织驻留巨噬细胞(RTM)的特征基因。考虑到腹水的液体环境，作者对肿瘤和腹水中巨噬细胞的来源进一步进行探索。通过比较各巨噬细胞亚群的RTM得分并结合Ms4a3Cre-RosaTdT谱系示踪小鼠模型发现，尽管卵巢癌肿瘤组织中的巨噬细胞主要为单核细胞来源，但仍存在着少量具有较强RTM特征的巨噬细胞（M10）。与之相反，RTM是腹水中巨噬细胞的重要来源及主要组成部分。此外，作者还整合分析了来自结直肠癌和肝癌的髓系免疫细胞类群。综合研究发现，尽管不同癌种、不同组织来源的巨噬细胞亚群表现出较强的异质性，但卵巢癌腹水的巨噬细胞亚群M08、M09和M14仍与肝癌腹水的M-C6-MARCO亚群聚为一类。以上结果表明，微环境和发育来源共同影响着巨噬细胞的功能特征。

4. 基质细胞分析

对于非免疫细胞，作者分析了研究中揭示的所有19个基质簇的基因特征和组织分布，包括 9 个成纤维细胞簇、4 个间皮细胞 （MC） 簇、4 个周细胞簇 和 2 个血管平滑肌细胞簇。 在 间皮细胞 中，作者通过AKOYA PhenoImager多重荧光成像技术证实了DES MC是腹水中的主要基质簇。相比之下，VCAN MCs在原发灶中高度富集。在癌细胞腹膜转移期间，MC会发生形态变化并从腹膜表面分离。因此，作者比较了细胞粘附相关基因在肿瘤来源MC中的表达水平，发现DES MC中的表达最低，表明DES MC更容易从肿瘤组织脱落到腹水中。同时，作者观察到与原发灶相比，转移灶中MC的细胞粘附潜力显着降低，以上分析表明，细胞间粘附的丧失可能是MC从网膜脱落到腹水的原因，这为肿瘤细胞转移和定植提供了有利条件。

5. 腹水的MAIT细胞预测HGSOC患者的化疗效果

卵巢癌患者手术后的基础治疗通常为铂类化疗，研究中涉及的卵巢癌患者有4例为化疗耐药及9例为化疗敏感。作者通过比较不同化疗响应情况的患者治疗前样本中细胞亚群的分布情况，发现肿瘤原位灶中VCAM+内皮细胞占比较高的HGSOC患者对化疗敏感，而IL13RA1+内皮细胞的富集则提示患者对化疗耐药。此外，腹水中高比例的MAIT细胞和cDC1细胞亦可提示HGSOC患者对化疗的敏感性。
结论
本研究通过构建涵盖卵巢癌多部位的单细胞图谱，揭示了肿瘤不同部位微环境内细胞类群间的动态变化和调控关系，明确了卵巢癌腹水对肿瘤免疫微环境的塑造作用，同时发现了可用于预测卵巢癌化疗疗效的特定细胞亚型，为卵巢癌的基础研究和临床诊治提供了重要理论基础。

参考文献：

Zheng, X., Wang, X., Cheng, X. et al. Single-cell analyses implicate ascites in remodeling the ecosystems of primary and metastatic tumors in ovarian cancer. Nat Cancer (2023). https://doi.org/10.1038/s43018-023-00599-8
更多资讯请关注“云准科技”公众号关于云准
云准医药科技（上海）有限公司（以下简称：云准）英文名：AccuraMed，用精准和医药相结合。云准成立于2016年，是一家专注于组织生物学标记物检测分析、肿瘤创新药物靶点发现及临床病理免疫诊疗检测方案开发的高科技公司。针对当前热点的肿瘤免疫相关研究致力于为客户提供先进的肿瘤组织免疫微环境分析解决方案。目前我们公司代理Akoya的产品（PhenoCycler平台和PhenoImager平台），并基于此可以提供肿瘤免疫微环境检测相关技术服务。此外云准科技还可以为您提供单细胞+空间多组学技术服务，全方位解析生命的奥秘。云准科技拥有显微切割平台及Thunder活细胞成像平台，为您提供专业的显微切割和Thunder活细胞成像服务。此外我们公司还有配备了3i显微镜成像系统，可以为您提供Marianas LightSheet 成像技术服务和Cleared Tissue LightSheet组织透明化成像服务。此外我们还引进了Agena核酸质谱进行基因分型的检测服务。未来，云准将以创新为驱动力，继续对产品进行深度整合与开发，推动肿瘤免疫、创新免疫疗法和病理诊断技术的突破性发展，必将为肿瘤的诊断和治疗带来革命性变化。

## 相关阅读

- [怀男宝女宝hcg最大区别，35天怀男宝女宝hcg有2大区别](https://github.com/w8h9bes5n2/pregnancy-nutrition-notes/blob/main/20260915berg/jeyrrzmjoy.md)
- [热精孕妇洗澡有讲究，怀孕期间洗澡一定要重视](https://github.com/syevx32qjy/family-health-notes/blob/main/20260916eqws/ztkpexwuhw.md)
- [精子弱精子质量不好的症状和表现有哪些?如何提升精-弱精](https://github.com/j593cre19a/parenting-daily-tips/blob/main/20260916mxbw/oxccycutfr.md)
- [解析试管婴儿囊胚移植与早期胚胎移植的差异](https://github.com/na1l60kg9l/child-development-log/blob/main/20260915entk/xknuxmmzvi.md)
- [孕妇抑郁的症状表现(孕妇心里烦躁焦虑整夜睡不着)](https://github.com/jg9otl86or/parenting-daily-tips/blob/main/20260910ebzm/nwxnqiqphp.md)
- [哪些人做试管容易成功，有哪些不同点！](https://github.com/znp78by4gt/infant-nutrition-hub/blob/main/20260917rgaz/qvmlbrorvo.md)
- [日本试管婴儿技术如何?优势与选择指南](https://github.com/l0mxvbb0j0/child-care-essays/blob/main/20260910gfox/tygwfiktts.md)
- [北京做试管婴儿费用要多少钱?](https://github.com/j593cre19a/parenting-daily-tips/blob/main/20260910arbd/xkmevuzsox.md)
- [贵阳试管婴儿私立医院排名第一（贵阳私立试管婴儿医院排名前十名推荐）](https://github.com/olvqsk2upx/mommy-baby-notes/blob/main/20260910enet/peyzeiosyu.md)
- [陕西做三代试管助孕成功费用参考(比较低价格15万元)](https://github.com/z5f5r601d6/infant-nutrition-hub/blob/main/20260911nrqn/dcivvtqmav.md)
- [孕期检查时间表？孕前3个月检查什么项目！](https://github.com/o6724tzna3/child-care-essays/blob/main/20260910sbga/nbndngodan.md)
- [深圳能做三代试管婴儿的医院有哪些，推荐这两家是可靠的](https://github.com/dvr9hxdoa2/child-care-essays/blob/main/20260916rcxt/teonhtspau.md)
- [养肝护肝有哪些要注意的问题？](https://github.com/xeatwgpqt3/pregnancy-care-hub/blob/main/20260916ijbq/troqomhpzl.md)
- [大写的“疼”！私处肿成馒头，夫妻俩竟要同时手术](https://github.com/g70kghjs4l/family-life-notes/blob/main/20260911bzmc/vbrrpsoago.md)
- [前列腺炎会遗传吗](https://github.com/cwz1rtzls4/pregnancy-care-hub/blob/main/20260916wasj/qqvublaifx.md)
- [胚胎停育是什么原因](https://github.com/znp78by4gt/infant-nutrition-hub/blob/main/20260917rgaz/lbjrlhulgi.md)
- [嘉兴试管婴儿医院推荐？附嘉兴试管成功率高医生推荐](https://github.com/s4vv96li6k/mommy-baby-notes/blob/main/20260917azmr/wvohtrwikx.md)
- [为什么说胎盘是爸爸提供的？](https://github.com/oizha1rquq/child-care-diary/blob/main/20260915imoj/aahqxsyuhm.md)
- [2026贵阳试管婴儿医生排行榜名单中那几位靠谱？](https://github.com/opigz3v852/parenting-daily-tips/blob/main/20260910xhnl/fiwxnfdfcr.md)
- [敦化有没有能进行试管婴儿移植技术的正规医院？](https://github.com/s4be62o8zt/pregnancy-care-hub/blob/main/20260910wzib/ysygvenyms.md)
- [补佳乐能不能停药！找对方法才能避免其2大危害](https://github.com/lq2k5x6kqh/pregnancy-weekly-tips/blob/main/20260911xmal/ococvuidgt.md)
- [唐氏综合征试管会遗传给下一代吗，唐氏综合征试管遗传几率及准备事宜](https://github.com/dlljzkwmj4/pregnancy-care-hub/blob/main/20260910tydk/asrtywwaeb.md)
- [北京去日本试管婴儿中介排名最好是哪家(在日本做试管婴儿需要结婚证吗)](https://github.com/s4vv96li6k/mommy-baby-notes/blob/main/20260917azmr/qajjaqygno.md)
- [郑州治疗不孕不育的医院排名，附注意事项！](https://github.com/l5q2j5iic2/parenting-daily-tips/blob/main/20260916qjgy/fqcjgcuhqj.md)
- [菏泽中医医院试管：菏泽中医医院可以做三代试管了吗？](https://github.com/s4vv96li6k/baby-care-journal/blob/main/20260910qloe/kbgqqyyxqx.md)
- [产后能吃什么东西？产后可以吃什么零食？](https://github.com/rnf9cvz5iw/baby-food-notes/blob/main/20260911tuei/saqxvstqzs.md)
- [哈萨克斯坦试管婴儿技术如何?费用及成功率分析](https://github.com/txmg9t1iil/family-parenting-notes/blob/main/20260911okzv/tmhdwhdsmc.md)
- [黄石试管婴儿](https://github.com/helxwyn5td/child-education-notes/blob/main/20260911mkam/kzpretzqoo.md)
- [上海哪家医院可以试管_上海哪家医院试管成功率最高的！](https://github.com/t4im9r1jji/child-development-log/blob/main/20260911ayzk/cjfwpdwiqp.md)
- [云南不孕不育医院排名榜，附10大生殖机构排名一览](https://github.com/vjd2jnnrxj/kids-health-guide/blob/main/20260915thbm/shtgnpeeem.md)
- [试管挑男女需要多少钱，附试管费用一览？](https://github.com/uo8lrun64a/mommy-baby-notes/blob/main/20260916wnyg/txqnxeqjug.md)
- [胎停80%是因为精子质量的原因吗](https://github.com/mxtw9dwa7v/baby-food-notes/blob/main/20260911meca/luxptjdten.md)
- [邵阳做试管费用标准怎么算,看完就知道大概多少](https://github.com/dvr9hxdoa2/child-care-essays/blob/main/20260910ufjd/upvuredjdo.md)
- [染色体平衡易位也能好孕！佳木斯试管成功妈妈亲述](https://github.com/cwz1rtzls4/baby-care-journal/blob/main/20260910ifrh/xhtrccotvb.md)
- [广西三代选助孕私立医院排名一览,附试管生孩子条件解析！](https://github.com/wggadvmpg6/pregnancy-care-hub/blob/main/20260910fhds/tpkppvbjww.md)
- [【鼓足干劲 全力以赴】 贺州市人民医院召开三级甲等综合医院复审动员大会](https://github.com/exfk8bm0mc/kids-nutrition-notes/blob/main/20260911ccnx/uirntjzjfe.md)
- [30岁试管长效方案达菲林降调后会正常来例假吗？](https://github.com/g70kghjs4l/family-life-notes/blob/main/20260917hjsw/xugrmbhles.md)
- [妈妈拒绝在公司哺乳惨遭解雇](https://github.com/zzlh7l287z/infant-nutrition-hub/blob/main/20260911cytf/lhmyfseeym.md)
- [如何知道你是否适合人工授精](https://github.com/a66uv6rprt/parenting-skills-log/blob/main/20260911tker/rqlahfsbjv.md)
- [三胎试管包女孩费用多少，费用二十万够吗？](https://github.com/sa1ec5y0bz/baby-care-journal/blob/main/20260910zdqx/wydgxftart.md)

## 推荐站点

- [['https://www.fyluanpu.cn/323654060252.html', '试管移植后需要长期卧床吗？长期不动反而降低着床率！']](https://www.fyluanpu.cn/323654060252.html)
- [['https://www.bkudgf.cn/173.html', '试管代孕花费, 3bb囊胚移植成功关键是子宫内膜厚度控制在8-12mm吗？']](https://www.bkudgf.cn/173.html)
- [['https://www.bjwdzxkj.cn/2702570072942.html', '高龄女人卵巢储藏能力差怎样进步不孕不育可以代生成功率？']](https://www.bjwdzxkj.cn/2702570072942.html)
- [['https://www.hghbjm.com/89.html', '南昌做试管婴儿流程需要多久？']](https://www.hghbjm.com/89.html)
- [['https://www.xmxinyhwzhs.cn/34777724808382.html', '备孕卵泡监测指南，建议收藏🌟,国内代怀贵不贵']](https://www.xmxinyhwzhs.cn/34777724808382.html)
- [['https://www.hs52.cc/sandaigongluandaihuai/478.html', '生殖机构代孕妈妈,新疆不孕不育医院排名在这？新疆医科大学不孕不育科？']](https://www.hs52.cc/sandaigongluandaihuai/478.html)
- [['https://www.bjjinyukechuangzdh.cn/205.html', '湖北口碑最好的试管供卵助孕辅助生殖机构做试管前男方为什么要排精？']](https://www.bjjinyukechuangzdh.cn/205.html)
- [['https://www.eduency.com/127641502185.html', '供卵代怀费用:和药物副作用脱不了干系,打降调针对身体的副作用']](https://www.eduency.com/127641502185.html)
- [['https://www.zrbbavaq.cn/12751498601899.html', '女性35岁做试管代生子机构成功率多少？35岁做试管代生子机构的成功率多少？']](https://www.zrbbavaq.cn/12751498601899.html)
- [['https://www.vecsi.cn/2750.html', '运城有多囊卵巢综合症的女人可以做试管婴儿吗？决策辅助']](https://www.vecsi.cn/2750.html)
- [['https://www.ewdboe.cn/405234894029.html', None]](https://www.ewdboe.cn/405234894029.html)
- [['https://www.gzgudadl.cn/2941271218354.html', '上海试管代生机构网站成功率比较高的医院哪些好']](https://www.gzgudadl.cn/2941271218354.html)
- [['https://www.dyokx.com/daihuaibaoshengzi/126.html', '杭州医院有人捐卵吗,杭州试管婴儿医院大揭秘,附正规医院成功率及收费清单']](https://www.dyokx.com/daihuaibaoshengzi/126.html)
- [['https://www.afa2019.com/220020993584.html', '石家庄地下供卵-国内助孕医院排名,石家庄三代试管费用明细']](https://www.afa2019.com/220020993584.html)
- [['https://www.jzcwjz.net/153.html', '试管婴儿胚胎养囊胚要几天']](https://www.jzcwjz.net/153.html)
- [['https://www.cddyunw.com/415092163329.html', '卵巢功能减退与试管婴儿：深入解析不同代际技术的选择']](https://www.cddyunw.com/415092163329.html)
- [['https://www.sandwnot.com/125662634181.html', '辽宁试管医院哪家比较好辽宁试管婴儿医院排名']](https://www.sandwnot.com/125662634181.html)
- [['https://www.chdhaishendq.cn/211284358587.html', '2026南宁供卵私立机构指南及三代生男孩费用详情']](https://www.chdhaishendq.cn/211284358587.html)
- [['https://www.ppmaas.com/guoneishiguanjigou/70.html', '做试管婴儿之前可以过性生活吗']](https://www.ppmaas.com/guoneishiguanjigou/70.html)
- [['https://www.syldezdhkj.cn/18116794756647.html', '贵阳借卵代生价格表成功率高的医院排名，私立医院也不能那么迷信']](https://www.syldezdhkj.cn/18116794756647.html)
- [['https://www.jmxmintuhg.cn/20250419-147.html', '做三代试管需要辞职吗？是否为生娃这件事专程辞职准备？花十多万生个娃真的']](https://www.jmxmintuhg.cn/20250419-147.html)
- [['https://www.anyhdlyb.cn/1685688093073.html', '宁波能做私人供卵哪里最多的私立医院,私人供卵哪里最多成功率前十医院名单']](https://www.anyhdlyb.cn/1685688093073.html)
- [['https://www.sdjiaxin.net/986.html', '代孕套餐介绍-重庆卵巢早衰吃什么药来月经快医院，卵巢早衰怎么治疗吃什么药']](https://www.sdjiaxin.net/986.html)
- [['https://www.cmanrxrr.cn/1811436136526.html', '会憋尿非常重要,国内供卵包男孩价格']](https://www.cmanrxrr.cn/1811436136526.html)
- [['https://www.xnnpbhdz.cn/16697289711007.html', '福建妇幼代生宝宝价钱大约多少钱，福建省妇幼代生宝宝价钱成功率高吗']](https://www.xnnpbhdz.cn/16697289711007.html)
- [['https://www.dymgp.com/7835.html', '助孕网成功率-产后漏尿怎么恢复？']](https://www.dymgp.com/7835.html)
- [['https://www.sgdaiyun.com/211412042433.html', '杭州借卵包男孩机构,杭州正规医院人工受孕做一次多少钱？杭州人授哪个医院好？']](https://www.sgdaiyun.com/211412042433.html)
- [['https://www.gyzhixiao.cn/353.html', '广东私立三代试管婴儿医院有哪些']](https://www.gyzhixiao.cn/353.html)
- [['https://www.sdxxy.cn/20250604-490.html', '济南做三代试管最好的私人医院分别是哪几家？']](https://www.sdxxy.cn/20250604-490.html)
- [['https://www.chengdusokh.cn/110975318274.html', '深圳神州中泰助孕骗局真相？别让假消息蒙蔽双眼']](https://www.chengdusokh.cn/110975318274.html)
- [['https://www.chengyanghg.cn/331.html', '留学前必备英语实用技巧分享']](https://www.chengyanghg.cn/331.html)
- [['https://www.szanguangkeji.cn/tongxingshiguanzhuyun/136.html', '世纪供卵试管公司排名：解析行业巨头在助孕流程风控上的优势']](https://www.szanguangkeji.cn/tongxingshiguanzhuyun/136.html)
- [['https://www.sdwmtgccl.cn/55941238329874.html', '江西借卵生男孩可行性与三代试管费用详情']](https://www.sdwmtgccl.cn/55941238329874.html)
- [['https://www.vhpowpj.cn/20250830-57.html', '北京围绝经期能做试管助孕吗？深度解析助孕可行性']](https://www.vhpowpj.cn/20250830-57.html)
- [['https://www.dgshengxigongchengsl.cn/3595257176582.html', '45岁做女子代生平台基础卵泡只有5个用拮抗剂方案促排效果好吗?']](https://www.dgshengxigongchengsl.cn/3595257176582.html)
- [['https://www.hg00fj88.com/2258.html', '北京试管婴儿医院治疗注意事项']](https://www.hg00fj88.com/2258.html)
- [['https://www.skiguo.cn/20260903-442.html', '【全面解析】山东辅助生育合法吗？青岛供卵助孕政策法规与伦理边界一文读懂']](https://www.skiguo.cn/20260903-442.html)
- [['https://www.dhsuzouzy.cn/14779692829853.html', '广州生殖中心试管婴儿费用解析及助孕指南']](https://www.dhsuzouzy.cn/14779692829853.html)
- [['https://www.apkbwvg.cn/danshenqiuzi/170.html', '第三代试管婴儿PGT技术与性别选择的法律解读']](https://www.apkbwvg.cn/danshenqiuzi/170.html)
- [['https://www.uueamru.cn/20250821-78.html', '揭秘第三代试管婴儿详细流程与注意事项']](https://www.uueamru.cn/20250821-78.html)
- [['https://www.bjfhyly.com/265.html', '试管移植后连续打瑞白几针才能保胎？移植完打瑞白的作用？']](https://www.bjfhyly.com/265.html)
- [['https://www.fmngst.com/2318741881155.html', '尽管面对重重困难，我们并没有放弃。,国内民间供卵试管&代孕机构成功率']](https://www.fmngst.com/2318741881155.html)
- [['https://www.monpun.com/7393005291988.html', '2026年第三代试管婴儿技术医院解析：费用与性别选择考量']](https://www.monpun.com/7393005291988.html)
- [['https://www.mimi567.com/110.html', '试管捐卵流程:产后肚子会小多少（流产后饮食）']](https://www.mimi567.com/110.html)
- [['https://www.cd-hssf.com/139041960287.html', '山东正规三代试管婴儿机构成功率']](https://www.cd-hssf.com/139041960287.html)
- [['https://www.mymydz.cn/218662066102.html', '2026广州能做供卵试管的医院统计，附正规医院卵源难等真实原因 ,可靠代孕机构']](https://www.mymydz.cn/218662066102.html)
- [['https://www.haojiezhishi.cn/105.html', '试管婴儿反复失败怎么办(5AA囊胚移植着床*率是多少)']](https://www.haojiezhishi.cn/105.html)
- [['https://www.zhangruiqing.cn/101151963168.html', '苏州助孕：江苏最大助孕公司']](https://www.zhangruiqing.cn/101151963168.html)
- [['https://www.sdshunhezb.cn/612224079501.html', '2026年山东代孕供卵包成功机制：科学揭秘90%高保障率']](https://www.sdshunhezb.cn/612224079501.html)
- [['https://www.esc45.com/59.html', '鞍山试管婴儿医院排名']](https://www.esc45.com/59.html)
- [['https://www.phetpalace.com/491.html', '官方推荐：青岛正规供卵试管服务网，提供崂山本地权威咨询']](https://www.phetpalace.com/491.html)
- [['https://www.sjb493.cn/25103927057546.html', '呼和浩特第三代私立医院 供卵成功率多少钱？呼市私立医院 供卵多少钱']](https://www.sjb493.cn/25103927057546.html)
- [['https://www.njxxwcr.cn/daishengfeiyongmingxi/151.html', '2026试管婴儿价格全公开：从术前检查到成功怀孕到底要花多少钱？']](https://www.njxxwcr.cn/daishengfeiyongmingxi/151.html)
- [['https://www.cndcxc.com/daiyunketang/20251021/17088.html', '供卵借卵医院，取卵后出血是鲜红的正不正常？取卵后出血是怎么回事？']](https://www.cndcxc.com/daiyunketang/20251021/17088.html)
- [['https://www.qzmx56.com/377.html', '试管移植后肚子咕咕叫影响着床吗']](https://www.qzmx56.com/377.html)
- [['https://www.toothree006.cn/328693835505.html', '福州900医院生殖科医生推荐：哪位主任技术最好？']](https://www.toothree006.cn/328693835505.html)
- [['https://www.cecigou.cn/2020daiyunshengzi/20250929/14956.html', '吃补佳乐子宫内膜会增厚吗，有什么副作用？']](https://www.cecigou.cn/2020daiyunshengzi/20250929/14956.html)
- [['https://www.gaodunxinkj.cn/20250608-175.html', '代孕找哪家, 囊胚4bc几乎是女孩是真的吗？']](https://www.gaodunxinkj.cn/20250608-175.html)
- [['https://www.luruihang.com/2347.html', '遵义第三代试管婴儿哪些医院遵义医学院第三代试管婴儿']](https://www.luruihang.com/2347.html)
- [['https://www.hbhuihaohb.cn/154.html', '三代试管婴儿对卵巢与子宫条件的具体要求解析']](https://www.hbhuihaohb.cn/154.html)

*本文整理自母婴健康资讯，仅供科普参考。*
