# 案例練習：監督式_分類_貸款違約預測
## 問題定義
於監督式分類框架中預測目標變數(charge-off)是否轉呆帳，轉呆帳拾取1，否則取0

## 資料轉換
- 正規化(np.log10())
- 分類特徵編碼(LabelEncoder)

## 探索性資料分析
- 敘述性統計(dataframe.head()、dataframe.describe()、dataframe.value_counts()、dataframe.corr())
- 長條圖(sns.barplot())
## 模型比較
- LogisticRegression
- LinearDiscriminantAnalysis
- KNeighborsClassifier
- DecisionTreeClassifier
- GaussianNB
- MLPClassifier
- AdaBoostClassifier
- GradientBoostingClassifier
- RandomForestClassifier
- ExtraTreesClassifier
## 模型評估
- 交叉驗證(KFold()、roc_auc)
- 混淆矩陣(confusion_matrix())
- 視覺化(pyplot.boxplot()、sns.heatmap())
## 其他參考指標
- 各變數的重要性(model.feature_importances_)
## 參考書籍
-   《金融機器學習與資料科學藍圖》