# predict-future-sales
predict future sales
首先对数据进行探索，对数据的类型以及异常值等等进行处理
然后，根据数据特征的性质进行征工程，这是一个时间序列的问题，其中用到了滑动窗口来平滑数据
最后使用的是CatBoost进行训练和预测，因为时间有限，这里使用的是单模型，考虑使用融合模型的方法对模型进行提升。
