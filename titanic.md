One of the reasons that the shipwreck led to such loss of life was that there were **not enough lifeboats** for the **passengers and crew**. 
Although there was some **element of luck** involved in **surviving** the sinking, **some groups of people were more likely to survive than others**| 
such as **women**, **children**, and the **upper-class**.

Let's try to explain that though data

what sorts of people were likely to survive?
Let's predict which passengers survived the tragedy.

Let's start by understanding the data

Descriptive statistics and visualization

PassengerId|Survived|Pclass|Name|Sex|Age|SibSp|Parch|Ticket|Fare|Cabin|Embarked
1|0|3|"Braund| Mr. Owen Harris"|male|22|1|0|A/5 21171|7.25||S
2|1|1|"Cumings| Mrs. John Bradley (Florence Briggs Thayer)"|female|38|1|0|PC 17599|71.2833|C85|C
3|1|3|"Heikkinen| Miss. Laina"|female|26|0|0|STON/O2. 3101282|7.925||S
4|1|1|"Futrelle| Mrs. Jacques Heath (Lily May Peel)"|female|35|1|0|113803|53.1|C123|S
5|0|3|"Allen| Mr. William Henry"|male|35|0|0|373450|8.05||S
6|0|3|"Moran| Mr. James"|male||0|0|330877|8.4583||Q
7|0|1|"McCarthy| Mr. Timothy J"|male|54|0|0|17463|51.8625|E46|S
8|0|3|"Palsson| Master. Gosta Leonard"|male|2|3|1|349909|21.075||S
9|1|3|"Johnson| Mrs. Oscar W (Elisabeth Vilhelmina Berg)"|female|27|0|2|34


X_train=pd.read_csv('train.csv')
# .columns .describe() .shape .