# kaggle-房价预测方案笔记
# 比赛链接：https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview
# 题目描述：
    让购房者描述他们的梦想之家，他们可能不会从地下室天花板的高度或靠近东西向的铁路开始。但这个竞赛的数据集证明，影响价格谈判的因素远比卧室数量或白板围栏要多。
    有79个解释变量描述了爱荷华州艾姆斯市住宅的（几乎）每一个方面，这个比赛挑战你预测每个房子的最终价格。
# 目标
    预测每栋房屋的销售价格是您的工作。对于测试集中的每个 Id，您必须预测 SalePrice 变量的值。 
# 评价指标
    提交的数据是根据预测值的对数和观察到的销售价格的对数之间的均方根误差（RMSE）进行评估。(取对数意味着预测昂贵房屋和廉价房屋的错误对结果的影响保持一致)。
# 提交格式
    Id,SalePrice
    1461,169000.1
    1462,187724.1233
    1463,175221
    etc.
