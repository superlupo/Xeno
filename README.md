# Xeno
Xeno aims to identify xenophobic language in preprocessed twitter feeds


## Input data
The data contains the set of tweets from 14605 users (one user per line). 

The first 3344 users are labelled as Xenophobic.

Each occurrence of a twitter handle (@username) is replaced with handleterm.
Each hashtag (e.g. #sometopic) is replaced with hashtagterm.
URLs are replaced with urlterm

```
handleterm   = twitter username
rt           = retweet
hashtagterm  = twitter information categories
urlterm      = URL
```

Good reference
https://books.google.ch/books?hl=en&lr=&id=KGIbfiiP1i4C&oi=fnd&pg=PR5&dq=Bird,+S.,+Klein,+E.,+Loper,+E.:+Natural+language+processing+with+Python.+O%E2%80%99Reilly+Media,+Inc.+(2009)&ots=Y3Akx7IGM5&sig=EfUfW5sFIYBoVggfHkwpofWaQFA&redir_esc=y#v=onepage&q&f=false
