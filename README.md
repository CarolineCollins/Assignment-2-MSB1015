### This Project
Welcome to the repository of Assignment 2, where I have employed Github pages, Rmarkdown, 
SPARQL queries, the WikiData and CDK databases and multivariate statistics (PLS) to do some Computational chemistry. 
Visit the report page at 

[Reuseable Wiener](https://carolinecollins.github.io/Assignment-2-MSB1015/Reuseable-Wiener.html)

to see how I built two models, one knowledge- and one data-driven, to predict the boiling points of 
alkanes from descriptors of their structural chemistry.

As a prerequisite, this notebook needs a certain [Wikidata query R package which you can find here.](https://github.com/bearloga/WikidataQueryServiceR)

### Input - Output
A SPARQL query gets SMILEs molecule strings which are then evaluated in CDK, obtaining numeric descriptors
which are then used as input to a model which predicts the molecules' boiling points.

### Reuseable
By altering the SPARQL query you can reuse this code to predict different properties of different molecules.

### Scientific Programming
This assignment was part of weeks 4 and 5 of Scientific Programming 
on the [Master's Systems Biology at Maastricht University.](https://www.maastrichtuniversity.nl/education/master/master-systems-biology)
The Course Coordinator is Egon Willighagen. Some of the templates employed come from his github at egonw.

You are welcome to reuse my code, reuseability was, after all, the main focus of this assignment. 
If you have any comments I'd be happy to hear them, just get in touch.
