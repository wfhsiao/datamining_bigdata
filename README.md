# 期末作業與報告
作業題目：<br />
依此影片重做以下影片中Jupyter Notebook的內容.<br />
https://www.youtube.com/watch?v=0Lt9w-BxKFQ&feature=youtu.be&t=1 <br />
## 但要做如下的修改：<br />
1. 將wine的quality的切割改成<br />
bins=(2, 5.5, 10)<br />
所以你執行<br />
wine['quality'].value_counts().sort_index()<br />
會得到<br />
0    744<br />
1    855<br />
Name: quality, dtype: int64<br />
<br />
2. 加入KNN (k=5), LogisticRegression 兩方法的比較. 因此共有五種方法：<br />
'RandomForest:{}, SVM:{}, MLP:{}, KNN:{}, LogisticReg:{}'<br />
<br />
3. 最後預測的數據改為以下兩筆：<br />
[8.5,0.28,0.56,1.8,0.092,35.0,103.0,0.9969,3.30,0.75,10.5]<br />
[7.5,0.52,0.16,1.9,0.085,12.0,35.0,0.9968,3.38,0.62,9.5]<br />
這兩筆的quality應該都是1<br />
<br />
4. 我的svm是設成<br />
svm.SVC(kernel='rbf', C=8, gamma=1)<br />
因此測試數據的準確率最高. 而且也成功地將上述兩筆預測為1.<br />
<br />

##報告次序：<br />
由各位的座號之總和為亂數種子, 洗牌後的結果為:<br />
['BBF107011', 'BBF107008', 'CBF104040', 'BBF107016', 'BBF107007', 'BBF107013', 'BBF107009', 'BBF107006']<br />

# 課堂kmeans例子

# datamining_bigdata (data mining and big data analytics)
<pre>
from sympy import *
x=Symbol('x')
y=Symbol('y')
n=Symbol('n')
expand((x+y)**3)
factor(expand((x+y)**3))
simplify(2*x - y - x)
from scipy.special import binom
</pre>

# Pandas Introduction
10 minutes to Pandas: https://pandas.pydata.org/pandas-docs/stable/10min.html
