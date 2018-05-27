# Titanic
[Kaggle](https://www.kaggle.com/c/titanic)

## Env
1. Python 3.6

## Tips
1. 使用LR、DT、RF、GBDT、SVM等模型，其中RF得到的本地和LB成绩最好。
2. 尝试了Stacking进行模型融合，但并不起作用。有可能是因为数据集太小。
3. baseline将name特征直接抛弃了，但其中可以提取出很多信息。比如，可以提取出称谓（Mr Mrs Miss Master Doctor Major等）来观察不同称谓的生存率。
4. 年龄应该离散化分段处理，可以从其中提取出两段和其他年龄段生存率有显著差别的年龄段。