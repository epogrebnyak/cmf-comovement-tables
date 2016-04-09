# cmf-comovement-tables
Study cases to analyse correlation between detrended cylcical residuals in economic time series with different lags

Todo:

0. replicate table 1 in [Prescot](https://github.com/epogrebnyak/cmf-comovement-tables/blob/master/pres86.pdf) - uses HP filter
0. replicate feasible parts of table 30 in [ECB](https://github.com/epogrebnyak/cmf-comovement-tables/blob/master/ecbwp095.pdf) - uses BK filter
0. make sample table for Russia

Комментарий:  
(1) подобрать набор даннных во FREDe, который соответствует показателям из двух статей  
(2) посмотреть описательную статистику этих показателей (их стандартные отклонения)  
(3) посмотреть доступ к процедурам фильтров HP и BK в R, попробовать прогнать серии через эти фильтры  
(4) собственно корреляции циклических относительно ВВП
