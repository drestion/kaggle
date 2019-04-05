# kaggle
Useful leads
## Themes
https://github.com/dunovank/jupyter-themes
### full width with theme grade3
!jt -t grade3 -cellw 100%
### Restore image background
from jupyterthemes import jtplot
jtplot.style()
## xgboost
conda install -c anaconda py-xgboost

## notebook theme

## dataframe manipulations
### merge vs concat
https://stackoverflow.com/questions/38256104/differences-between-merge-and-concat-in-pandas


## interactive figure
import plotly.plotly as py
from plotly.offline import init_notebook_mode, enable_mpl_offline, iplot_mpl
#import cufflinks as cf
init_notebook_mode(connected=True)
#cf.go_offline(connected=True)
enable_mpl_offline()


f = plt.figure(figsize=(42,42))
#sns.scatterplot(train.bh_x, train.bh_y, train[(train.OilPeakRate<opr_median+100)&(train.OilPeakRate>opr_median-100)].OilPeakRate)
sns.scatterplot(train.bh_x, train.bh_y, size=train[train.OilPeakRate>500].OilPeakRate,marker='o',sizes=(200,400),palette="Set2")
sns.scatterplot(train.bh_x, train.bh_y, size=train[train.OilPeakRate<200].OilPeakRate,marker="x")
plt.title('Extreme vs BH')
iplot_mpl(f)


## common eda functions
https://www.kaggle.com/willkoehrsen/a-walkthrough-and-a-challenge

## the blending techniques
https://www.kaggle.com/ashishpatel26/different-basic-blends-possible
the root of blending: https://medium.com/weightsandbiases/an-introduction-to-model-ensembling-63effc2ca4b3

## really nice code boilerplaces
This comes with timers and ways to organize aggregations
https://www.kaggle.com/jsaguiar/lightgbm-7th-place-solution

