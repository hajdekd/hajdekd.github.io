---
title: "Projects"
permalink: "/about/"
layout: page
---




## [Classification](https://github.com/hajdekd/Data-Science-Projects/blob/main/Dalibor_Hajdek_Classification_Labipynb.ipynb)
 
 
 **Overview**
 
The Loan dataset used for the project contains 14 variables and 5000 observations, without missing values. 

The objective of the project is to through logistic regression models predict which clients will apply for the loan. Additionally, the aim is to determine importance of features in model building. Following models are built and compared: 

* Decision Tree Without Hyperparameters
* Decision Tree With Hyperparameters
* Decision Tree With Cost Complexity Pruning 

![](/Images/classification.PNG)



## [Linear Regression](https://github.com/hajdekd/Data-Science-Projects/blob/main/Dalibor_Hajdek_Linear_Regression_Assignment.ipynb)

**Overview**

The goal for the project is to provide forecast in prices of used cars in market that was impacted by COVID-19 pandemic. 
The Used Cars dataset consists of both continuous and numerical variables.  
Techniques applied in the project are log transformation and treating outliers.    

![](/Images/linear_regression.PNG)




## [Ensemble Learning](https://github.com/hajdekd/Data-Science-Projects/blob/main/Dalibor_Hajdek_Ensemble_Lab.ipynb)

**Overview**

For this project, the objective is to forecast which clients might default in paying back their loans. 
Credit data set is used for the exercise.   

After performing thorough EDA and data pre-processing, the following models are created:
* Decision Tree Classifier
* Random Forest Classifier
* Bagging Classifier
* AdaBoost Classifier
* Gradient Boosting Classifier
* XGBoost Classifier  

Each of the models is afterwards Hyperparameter tunned. 
Predictions from multiple models are combined to seek the best predictive performance.











### Based on

- [Hyde](https://github.com/poole/hyde)
- [Minima](https://github.com/jekyll/minima)
- [Lagrange](https://github.com/LeNPaul/Lagrange)
- [Font Awesome](http://fontawesome.io/)
- [KaTeX](https://katex.org/)
- [Pygments](https://github.com/richleland/pygments-css)

## Installation (jekyll-remote-theme method)

You can use this theme with the `jekyll-remote-theme` plugin. Just create an empty repo, copy over the `index.html` file and add this to your `_config.yml`:

```yaml
remote_theme: niklasbuschmann/contrast@v2.11

plugins:
  - jekyll-remote-theme
```

Note: to enable icons you also need to copy over the `_data` folder.

## Config

Your `_config.yml` could for example look like this:

```yaml
title: "Blog Title"
author: "Blog Author"
description: "My personal blog about ... something"
permalink: /:title/
lang: "en"
excerpt_separator: "\n\n\n"
date_format: "%B %d, %Y"

# Layout

show_excerpts: true        # show article excerpts on the home page
show_frame: true           # adds a gray frame to the site
show_sidebar: false        # show a sidebar instead of the usual header

# Menu

navigation:                # accepts {file, title, url, icon, sidebaricon}
  - {file: "index.html"}
  - {file: "README.md"}

external:                  # shows a footer with social links - for available icons see fontawesome.com/icons
  - {title: Mail, icon: envelope, url: "mailto:niklasbuschmann@users.noreply.github.com"}
  - {title: Github, icon: github, url: "https://github.com/niklasbuschmann/contrast"}
  - {title: Subscribe, icon: rss, url: "/feed.xml"}

comments:
#  disqus_shortname: ""    # see https://disqus.com/
#  isso_domain: ""         # see https://posativ.org/isso/

plugins:
 - jekyll-feed

```

## MathJax

Contrast comes preinstalled with a leightweight alternative to MathJax called [KaTeX](https://katex.org/). To display equations in a post simply set `mathjax: true` in the article's front matter.

## License

[public domain](http://unlicense.org/)

## Screenshots

![screenshot](https://user-images.githubusercontent.com/4943215/109431850-cd711780-7a08-11eb-8601-2763f2ee6bb4.png)

![screenshot](https://user-images.githubusercontent.com/4943215/109431832-b6cac080-7a08-11eb-9c5e-a058680c23a1.png)

![screenshot](https://user-images.githubusercontent.com/4943215/73125194-5f0b8b80-3fa4-11ea-805c-8387187503ad.png)
