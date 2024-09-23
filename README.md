# machine-learning

实验环境

	•	编程语言: Python 3.8
	•	操作系统: Windows 10 或 macOS Big Sur （根据你的实际系统进行调整）
	•	开发环境: Jupyter Notebook 或其他IDE（如 PyCharm, Visual Studio Code）

使用的库和版本

	•	pandas: 用于数据加载和预处理，版本 1.2.0
	•	numpy: 用于数值计算，版本 1.19.5
	•	scikit-learn: 用于模型训练、评估和预测，版本 0.24.1
	•	LogisticRegression: 逻辑回归模型
	•	train_test_split: 数据集划分
	•	StandardScaler: 特征标准化
	•	cross_val_score: 交叉验证评估
	•	roc_curve, roc_auc_score: 计算和评估 ROC 曲线
	•	matplotlib: 用于绘制图表，版本 3.3.3

参数设置

	•	模型训练
	•	random_state: 42（用于确保结果的可重复性）
	•	test_size: 0.2（20%的数据用作测试集）
	•	LogisticRegression
	•	solver: ‘lbfgs’（逻辑回归的求解算法，适用于中小数据集）
	•	max_iter: 100（求解器的最大迭代次数）
