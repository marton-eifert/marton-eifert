# Getting Started (January - February 2022)

Since 2012, I have gained profound knowledge in building classical data engineering and machine learning applications - especially with _R_ - in several projects in the banking industry at [RSU Rating Service Unit](https://www.rsu-rating.de/), e.g. credit risk scoring & [early warning systems](https://www.rsu-rating.de/produkte/risk-guard/) based on structered data such as score card input, balance sheet figures, market quotes time series etc. and unstructured data like news articles.

In these projects, I most oftenly made use of the following tools:
- data wrangling and visualization in _R_ ([data.table](https://cran.r-project.org/web/packages/data.table/index.html), [ggplot2](https://cran.r-project.org/web/packages/ggplot2/index.html), [tidyverse](https://www.tidyverse.org/), especially [stringr](https://stringr.tidyverse.org/), [reticulate](https://cran.r-project.org/web/packages/reticulate/index.html))
- natural language processing (in particular, text classification using bag-of-words like TF-IDF + SVM, or using word/document embeddings + logistic regression, as well as _named entity recognition_) in _R_ ([liblineaR](https://cran.r-project.org/web/packages/LiblineaR/), [text2vec](https://cran.r-project.org/web/packages/text2vec/index.html), [fastRtext](https://cran.r-project.org/web/packages/fastrtext/index.html), [keras](https://cran.r-project.org/web/packages/keras/index.html))
- relational database management (Microsoft SQL Server 2014/2019, [databases](https://docs.microsoft.com/en-us/sql/relational-databases/databases/databases?view=sql-server-2017), [tables](https://docs.microsoft.com/en-us/sql/relational-databases/tables/tables?view=sql-server-2017), [indexes](https://docs.microsoft.com/en-us/sql/relational-databases/indexes/indexes?view=sql-server-2017), [views](https://docs.microsoft.com/en-us/sql/relational-databases/views/views?view=sql-server-2017), [stored procedures](https://docs.microsoft.com/en-us/sql/relational-databases/stored-procedures/stored-procedures-database-engine?view=sql-server-2017), [user-defined functions](https://docs.microsoft.com/en-us/sql/relational-databases/user-defined-functions/user-defined-functions?view=sql-server-2017), [linked servers](https://docs.microsoft.com/en-us/sql/relational-databases/linked-servers/linked-servers-database-engine?view=sql-server-2017), ...) and administration (Windows Server 2012/2019)
- Regular expressions
- etc.

In these projects, I most oftenly worked with the following software:
- [RStudio](https://www.rstudio.com/) (including [projects](https://support.rstudio.com/hc/en-us/articles/200526207-Using-RStudio-Projects), [profiling](https://support.rstudio.com/hc/en-us/articles/218221837-Profiling-R-code-with-the-RStudio-IDE), and [debugging](https://support.rstudio.com/hc/en-us/articles/205612627-Debugging-with-the-RStudio-IDE))
- [SQL Server Management Studio](https://docs.microsoft.com/de-de/sql/ssms/sql-server-management-studio-ssms?view=sql-server-ver15)
- [Microsoft Office 2013-2019](https://support.microsoft.com/en-us/office/download-and-install-or-reinstall-office-2019-office-2016-or-office-2013-7c695b06-6d1a-4917-809c-98ce43f86479) as well as [Microsoft 365](https://www.microsoft.com/de-de/microsoft-365), in particular Excel.
- Notepad++ and UltraEdit for "batch-editing" plain text files.

Since 2022, I have been working for [Metafinanz Informationssysteme GmbH](https://metafinanz.de/) as Data Scientist Consultant. To get started with deeper fundamental concepts, I have been exploring fundamental concepts and deepening my experience in the following topcs.

## The cloud (in particular AWS)
- Launching my first [EC2 instance](https://aws.amazon.com/ec2/getting-started/?nc1=h_ls)
- Getting familiarized with Linux bash basics

## Coding and versioning
- Familiarized with:
  - [Git for Windows](https://gitforwindows.org/) and in general Git basics ([clone](https://www.atlassian.com/de/git/tutorials/setting-up-a-repository), [add + commit](https://www.atlassian.com/de/git/tutorials/saving-changes), [push](https://www.atlassian.com/de/git/tutorials/syncing/git-push), including concepts of [branching](https://www.atlassian.com/de/git/tutorials/using-branches))
  - [AWS CodeCommit](https://aws.amazon.com/de/codecommit/) basics
  - [PyCharm](https://www.jetbrains.com/pycharm/) (+ Integration with git + docker) 
- Setting up my first [github repository](https://github.com/marton-eifert/marton-eifert)

## Extending my R knowledge
- Building a simple crawler with _rvest_
- Object-oriented programming with _R6_
- Interfaces for Office files
  - [officeR](https://cran.r-project.org/web/packages/officer/index.html) package to merge docx files
  - Packages for pulling Sharepoint lists: [Microsoft365R](https://mran.microsoft.com/web/packages/Microsoft365R/index.html), [LukasK13/sharepointr](https://github.com/LukasK13/sharepointr), [esbeneickhardt/sharepointr](https://github.com/esbeneickhardt/sharepointr)

## Learning new database engines
- [PostgreSQL](https://www.postgresql.org/) basics (pgAdmin for Windows)
- PostgreSQL R interface:
  - [RPostgres](https://cran.r-project.org/web/packages/RPostgres/index.html)
  - [RPostgreSQL](https://cran.r-project.org/web/packages/RPostgreSQL/index.html)

## Extending My Python basics knowledge
- Refreshing [sklearn](https://scikit-learn.org)
  - Familiarize with concepts of [Pipelines](https://scikit-learn.org/stable/modules/compose.html#pipeline) 
    - Creating a first basic Pipeline
    - Extending with own Transformer / Estimator classes, see [[1]](https://towardsdatascience.com/custom-transformers-and-ml-data-pipelines-with-python-20ea2a7adb65) + [[2]](https://medium.com/analytics-vidhya/scikit-learn-pipelines-with-custom-transformer-a-step-by-step-guide-9b9b886fd2cc) + [[3]](https://www.section.io/engineering-education/custom-transformer/)
    - Extending pipelines with FeatureUnion class, see [[1]](http://zacstewart.com/2014/08/05/pipelines-of-featureunions-of-pipelines.html) + [[2]](https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.FeatureUnion.html)
- Refreshing [xgboost](https://machinelearningmastery.com/gentle-introduction-xgboost-applied-machine-learning/)
  - Facing the problem of [different sparsity classes for tf-idf matrices as input for xgboost](https://openscoring.io/blog/2021/02/27/sklearn_tf_tfidf_xgboost_pipeline/) and creating a solution with custom Transformer class 
- Introduction to [Polar](https://pola-rs.github.io/polars/py-polars/html/reference/dataframe.html)

## Web services and applications
- Rest API basics:
  - Python [FastAPI](https://fastapi.tiangolo.com/)
  - Python [request](https://www.w3schools.com/python/module_requests.asp) module
  - R [httr](https://cran.r-project.org/web/packages/httr/index.html) package
- Web Apps:
  - Python [Flask](https://flask.palletsprojects.com/en/2.0.x/)
  - R [shiny](https://shiny.rstudio.com/)
    - R [radiant](https://radiant-rstats.github.io/radiant/) package

## Containerization (Docker)
- [Docker basics](https://docs.docker.com/get-started/#download-and-install-docker)
- Docker application Part 1: [rocker](https://www.rocker-project.org/), see also [[1]](https://colinfay.me/docker-r-reproducibility/)
- Docker application Part 2: [jupyter/all-spark](https://github.com/jupyter/docker-stacks)

## Trying to apply the learned concepts to concrete NLP tasks
- Text classification: 

## Interesting data sources
- Kaggle (download dataset / CLI)

# Next steps (February/March 2022)
- NLP:
  - nltk, SpaCy, fastText, flair/flert huggingface.co 
  - Pytorch, Tensorflow / Keras
- Trying out _OpenRefine_ for Python
- Microsoft Tools:
  - Power BI
  - Power Automate
- CI/CD Pipelines, Kubernetes, ...



