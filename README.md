# 停止更新。实际增长比模型都快，搞毛

# 世界各国新冠肺炎疫情拟合与预测（每日更新）
所用的拟合模型有sigmoid和tanh的线性组合，sigmoid，tanh，如果前一个拟合模型收敛不了就跳到下一个模型。

感谢丁香园提供的世界各国确诊数据，github地址 https://github.com/BlankerL/DXY-COVID-19-Data 。

# nCOVID-19_Data_Study
A study on confirmed case number of nCOVID-19

This repository includes simple curve fits by country using the daily confirmed cases number. 

Three functions are used to fit curves: arctan, sigmoid, and a linear combination of arctan and sigmoid.

Data comes from DingXiangYuan public data, which is available in https://github.com/BlankerL/DXY-COVID-19-Data

Fitted results can be found in the folder Fitted_Curve
