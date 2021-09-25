# machine_learning_movie_recommender


本项目展示了如何处理一个包含用户对不同电影的评分的数据集，针对数据集中的用户对某电影评分进行预测，并对于用户可能感兴趣的电影进行推荐。 

数据集数据来源：GroupLens 官方网站，数据集来源：https://www.kaggle.com/rounakbanik/the-movies-dataset?select=movies_metadata.csv
文件包含2017年7月或之前发行的电影数据4.5万条，包含来自27万位用户对于4.5万部电影的2600万个评分，评分范围为0-5。


步骤1： 通过机器学习JupyterLab步骤进行数据处理并导出到Hive

步骤2： 通过机器学习JupyterLab步骤进行ALS模型预测与调参

步骤3： 通过机器学习JupyterLab步骤进行个性化推荐

预测结果的精准性：经过机器学习模型训练后，对于用户的电影评分预测值与真实值的平均绝对误差为1。
