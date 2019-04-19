# General Stretagy
It's the same: quick iteration. fix what's not working. Do not spend time working on features that are "routine". Do not spend time blindly testing "new" features.       
https://www.youtube.com/watch?v=bL4b1sGnILU

# kaggle
Useful leads

## Feature Engineering
https://www.slideshare.net/HJvanVeen/feature-engineering-72376750

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
f.....plot
plt.title('Extreme vs BH')
iplot_mpl(f)


## common eda functions
https://www.kaggle.com/willkoehrsen/a-walkthrough-and-a-challenge

## Cousera Courses
needs pandas to start.
https://www.coursera.org/learn/competitive-data-science

## the blending techniques
https://www.kaggle.com/ashishpatel26/different-basic-blends-possible
the root of blending: https://medium.com/weightsandbiases/an-introduction-to-model-ensembling-63effc2ca4b3

## really nice code boilerplaces
This comes with timers and ways to organize aggregations
https://www.kaggle.com/jsaguiar/lightgbm-7th-place-solution

## Machine learning model debug
https://eli5.readthedocs.io/en/latest/index.html
