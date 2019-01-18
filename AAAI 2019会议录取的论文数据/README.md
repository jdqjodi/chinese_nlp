# chinese_nlp

笔试题.B - 数据挖掘：
基于AAAI 2019会议录取的论文数据，从中提取出所有的：1.作者名；2.机构名；3.论文标题的主题分布（注：分析来源数据不局限于提供的pdf链接，可以利用论文原文、摘要，乃至网上现有的其他相关信息或数据；）

rough notes
choice of stanford nlp tagger
biggest drawback do not chunk both first and last names
research organizations in brackets made finding relevant organizations easier
would have been ideal to split each entry at their indices seen in the pdf but for loop took a while, so processed entire pdf as one string; sacrificed ability to link tagged words back to each entry lost a lot of information that way
failed to capture a lot of names the first round, if had more time merging 'O' and 'ORGANIZATION' back into sentences and ran again might find more names? I haven't tried but iterative processes might help

very interesting, but if i had more time to read up nlp i would've chosen something else to modify and use besides the stanford core nlp tagger haha

