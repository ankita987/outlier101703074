# Removal of outliers using IQR or Z-score

## Using IQR
 *It filters out all int and float columns. Then it calculates the IQR(interquartile range) for each column and checks all rows for presence of outliers. Outliers are values less than (Q1 - 1.5 × IQR) or greater than (Q3 - 1.5 × IQR). After that rows corresponding to outliers are removed from the data.*
#### Input

* ```"FileName.csv"``` - name of file containing input data

#### Output
* Final data after removing all rows containing outliers.
* prints the number of rows removed to the console in the form:
``` No. of rows removed by IQR method: 2```

## Using Z-score
 *It filters out all int and float columns. Then it calculates the z-score for all values in each column and checks them for outliers. Outliers are values whose absolute value is greater than the threshold value. After that rows corresponding to outliers are removed from the data.*
#### Input

* ```"FileName.csv"``` - Name of file containing input data
* ```threshold``` - the threshold value to identify outliers. Default value is ```2```.

#### Output
* Final data after removing all rows containing outliers.
* Prints the number of rows removed to the console in the form:
``` No. of rows removed by z-score method: 2```
### How to run
Run thorugh cmd line as:
```sh
python outlier101703074.py <InputDataFile>
```
Example:
```sh
python outlier101703074.py outlier.csv
```

License
----

MIT


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
