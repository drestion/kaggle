# General Stretagy
It's the same: quick iteration. fix what's not working. Do not spend time working on features that are "routine". Do not spend time blindly testing "new" features.       
https://www.youtube.com/watch?v=bL4b1sGnILU

# kaggle
Useful leads
## Video tutorial
fantastic 
https://www.bilibili.com/video/av42834527/?p=5
https://www.bilibili.com/video/av45664452?from=search&seid=13657101433764310245

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
```
def enable_interactive_plot():
    import plotly.plotly as py 
    from plotly.offline import init_notebook_mode, enable_mpl_offline, iplot_mpl #import cufflinks as cf 
    init_notebook_mode(connected=True) #cf.go_offline(connected=True) 
    enable_mpl_offline()
    
```


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
https://www.kaggle.com/danielbecker/careervillage-org-recommendation-engine

## Machine learning model debug
https://eli5.readthedocs.io/en/latest/index.html

## xgboost vs lightGBM
http://mlexplained.com/2018/01/05/lightgbm-and-xgboost-explained/   

## understanding transform
https://pbpython.com/pandas_transform.html

## numpy techniques
### concat two arrays
`
t1=[1,2,3]
t2=[4,5,6]
print(t1)
print(t2)
np.c_[t1, t2] 
`

## pandas techniques
### Select columns by booleans
https://stackoverflow.com/questions/29281815/pandas-select-dataframe-columns-using-boolean

## dataset distributions
### What to do when train and test come from different distributions
https://www.freecodecamp.org/news/what-to-do-when-your-training-and-testing-data-come-from-different-distributions-d89674c6ecd8/
