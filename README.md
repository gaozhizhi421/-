
首届国际“远见杯”元智能数据挑战大赛-智能建造赛道比赛数据

1. 数据集介绍：
    比赛提供根据在标准范围内随机选取的数值生成，作为输入图片的灰度图包含15项参数信息，分别为初始孔隙率、固有渗透率、温升增长系数、水灰比、混凝土密度、比热容、热传导系数、初始饱和度，以及受火后1分钟、2分钟、4分钟、6分钟、8分钟、25分钟和30分钟时的火荷载温度。输出图片是三通道RGB彩色图像，RGB三个通道像素值分别代表可由上述15个参数通过数值计算获得的饱和度、孔压和温度信息。比赛数据分为训练集和测试集两部分，训练集提供5000组输入图片及5000张输出图片；测试集仅提供3组输入图片。其中，文件inputpic.zip中为输入图片，文件outputpic1.zip&outputpic2.zip中为输出图片，文件testpic.zip中为测试图片。
2. 评分细节：
    预测结果得分由预测图片与真图相似度以及根据图片计算所得在300s、900s和1500s时孔隙压力和温度随深度变化曲线和最大孔隙压力与时间变化曲线与数值计算结果相比较。
3. 输出结果要求：
    对于测试集的预测结果，以JPG格式编码，数据覆盖范围及分辨率须与已提供的图片（测试集输出图片）标准相同。
参赛队伍需建立预测数据文件夹，命名为Predict。Predict文件夹内根据测试集数据组数（每个文件夹包含一组输出图片及相关结果），建立数量相同的预测数据文件夹，其中子文件夹名称与测试集中数据序号一致（1，2，3），每个子文件夹包含1张JPG格式的RGB图片（格式与已提供的图片一致）和4个txt格式的预测数据。其中，预测图片的文件名与子文件名序号一致为“p1.jpg”、“p2.jpg”或“p3.jpg”；4个txt文件名分别为“300s.txt”、“900s.txt”、“1500s.txt”和“pgmax.txt”。最后，参赛队伍将Predict文件夹打包成zip压缩包并提交。

本比赛数据集由以下文章提供：Predicting the Pore-Pressure and Temperature of Fire-Loaded Concrete by a Hybrid Neural Network, DOI: 10.1142/S0219876221420111

如果本数据集对您的研究有用，请在您的出版物中引用以下文章:

@article{IJCM2022,
author = {Zhang, Yiming and Gao, Zhiran and Wang, Xueya and Liu, Qi},
title = {Predicting the Pore-Pressure and Temperature of Fire-Loaded Concrete by a Hybrid Neural Network},
journal = {International Journal of Computational Methods},
pages = {2142011},
year = {2022},
 Note= {doi:10.1142/S0219876221420111}
}

@Article{ES2014,
  Title                    = {{Model-based risk assessment of concrete spalling in tunnel linings under fire loading}},
  Author                   = {Zhang, Yiming and Zeiml, Matthias and Pichler, Christian and Lackner, Roman},
  Journal                  = {Engineering Structures},
  Year                     = {2014},
  Pages                    = {207-215},
  Volume                   = {77}
}

@Article{ES2017,
  Title                    = {{Fast assessing spalling risk of tunnel linings under RABT fire: From a coupled thermo-hydro-chemo-mechanical model towards an estimation method}},
  Author                   = {Zhang, Yiming and Zeiml, Matthias and Maier, Marcus and Yuan, Yong and Lackner, Roman},
  Journal                  = {Engineering Structures},
  Year                     = {2017},
  Pages                    = {1-19},
  Volume                   = {142}
}
