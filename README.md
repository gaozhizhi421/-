中文

首届国际“远见杯”元智能数据挑战大赛-智能建造赛道比赛数据

1. 数据集介绍：
混凝土材料受高温作用可能会发生爆裂，严重损害结构承载性能。爆裂与受火混凝土内部孔隙压力及温度演化密切相关，数值模型较为复杂，且计算时间长。本赛道比赛中，参赛队伍需根据：

	输入：包含混凝土材料参数、环境湿度与温度荷载复合信息的灰度图

	快速获得
	
	输出：描述混凝土饱和度、孔隙压力、温度时空信息的RGB图。

2. 评分细节：
预测结果得分由预测图片与真图相似度评价，比赛最终得分由初赛预测结果得分、报告及演示视频得分、答辩现场表现得分三部分构成，上述三部分得分占比分别为40%、30%、30%。

3. 输出结果要求：
对于测试集的预测结果，以JPG格式编码，数据覆盖范围及分辨率须与已提供的图片（测试集输出图片）标准相同。提交压缩包命名为Predict.zip。其中包含预测图片，图片的文件名与测试输入文件名序号一致为“p1.jpg”、“p2.jpg”......
最后，参赛队伍将Predict文件夹打包成zip压缩包并提交。

4. 本比赛数据集由以下论文提供：
Y. Zhang, Z. Gao, X. Wang, and Q. Liu, “Predicting the pore-pressure and temperature of fire-loaded concrete by a hybrid neural network,” International Journal of Computational Methods, ID. 2142011, 2022. doi:10.1142/S0219876221420111.

5. 如果本数据集对您的研究有用，请在您的出版物中引用以下文章:

[1] Y. Zhang, M. Zeiml, C. Pichler, and R. Lackner, “Model-based risk assessment of concrete spalling in tunnel linings under fire loading,” Engineering Structures, vol. 77, pp. 207–215, 2014.

[2] Y. Zhang, M. Zeiml, M. Maier, Y. Yuan, and R. Lackner, “Fast assessing spalling risk of tunnel linings under RABT fire: From a coupled thermo-hydro-chemo-mechanical model towards an estimation method,” Engineering Structures, vol. 142, pp. 1–19, 2017.

[3] Y. Zhang, Z. Gao, X. Wang, and Q. Liu, “Predicting the pore-pressure and temperature of fire-loaded concrete by a hybrid neural network,” International Journal of Computational Methods, ID. 2142011, 2022. doi:10.1142/S0219876221420111.

[4] Y. Zhang, Z. Gao, X. Wang, and Q. Liu, “Image representations of numerical simulations for training neural networks,” Computer Modeling in Engineering & Sciences. doi:10.32604/cmes.2022.022088.


Bib 格式：

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

@Article{CMES2022,
  Title                    = {Image representations of numerical simulations for training neural networks},
  Author                   = {Zhang, Yiming and Gao, Zhiran and Wang, Xueya and Liu, Qi},
  Journal                  = {Computer Modeling in Engineering & Sciences},
  Year                     = {2022},
  Note                     = {doi:10.32604/cmes.2022.022088}
}

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
English

The 1st International "Prospective" Meta-Intelligence Data Competition

-Data for Intelligent Construction Category

1. Introduction：
Concrete structures can experience explosive spalling when subjected to fire loading, greatly jeopardizing their load carrying capacity.  Spalling is closely correlated to the pore pressure and temperature evolution.  Numerical model (thermos-hydro-chemical model) for simulating spalling is generally complicated and time consuming.  In this competition section, the competitors shall use:

	input data: greyscale images storing the material properties, environmental moisture, and temperature loads

	to quickly obtain

	output data: RGB images storing the time-space distribution and evolution of saturation degree, pore pressure and temperature of fire loaded concrete.

2. Grading：
The basic grade is given based on the similarity of predicted image and original images.  The final grade will be composed by the basic grade, report grade and presentation grade, as 40%, 30% and 30%.

3. Predicted results：
The results are provided with JPG type files the resolution of which shall be the same as the output data.  A zip file includes the predicted JPG files shall be proposed in which the names of the JPG files shall be consistent with the names of the input image for predicting.

4. The data is built based on the following paper:
Y. Zhang, Z. Gao, X. Wang, and Q. Liu, “Predicting the pore-pressure and temperature of fire-loaded concrete by a hybrid neural network,” International Journal of Computational Methods, ID. 2142011, 2022. doi:10.1142/S0219876221420111.

5. When the data is helpful for you, please cite following papers in your future work.

[1] Y. Zhang, M. Zeiml, C. Pichler, and R. Lackner, “Model-based risk assessment of concrete spalling in tunnel linings under fire loading,” Engineering Structures, vol. 77, pp. 207–215, 2014.

[2] Y. Zhang, M. Zeiml, M. Maier, Y. Yuan, and R. Lackner, “Fast assessing spalling risk of tunnel linings under RABT fire: From a coupled thermo-hydro-chemo-mechanical model towards an estimation method,” Engineering Structures, vol. 142, pp. 1–19, 2017.

[3] Y. Zhang, Z. Gao, X. Wang, and Q. Liu, “Predicting the pore-pressure and temperature of fire-loaded concrete by a hybrid neural network,” International Journal of Computational Methods, ID. 2142011, 2022. doi:10.1142/S0219876221420111.

[4] Y. Zhang, Z. Gao, X. Wang, and Q. Liu, “Image representations of numerical simulations for training neural networks,” Computer Modeling in Engineering & Sciences. doi:10.32604/cmes.2022.022088.


Bib files：

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

@Article{CMES2022,
  Title                    = {Image representations of numerical simulations for training neural networks},
  Author                   = {Zhang, Yiming and Gao, Zhiran and Wang, Xueya and Liu, Qi},
  Journal                  = {Computer Modeling in Engineering & Sciences},
  Year                     = {2022},
  Note                     = {doi:10.32604/cmes.2022.022088}
}


