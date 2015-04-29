# Database connfig file location

config file should be in home directory and called .my.cnf,
e.g. ~/.my.cnf

The .my.cnf format is as follows:

```
[intSitesDEV-dev]
user=YYYYYYY
password=XXXXXX
host=microb98.med.upenn.edu
port=3309
database=intsitesdev
```

# Dependencies

intSiteRetriever : https://github.com/esherm/intSiteRetriever 
(at present get the project in current folder:
```
git clone https://github.com/esherm/intSiteRetriever
```)
hiAnnotator
pipeUtils
colorspace

# pipeUtils requirement

needs a column type which is hard-coded as "insertion" for integration site
and "match" for match random contol(mrc).


