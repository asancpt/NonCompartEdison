# NonCompart, Edison Science App Manual

- Sungpil Han
- 2017-01-06
- http://simp.ly/publish/CpFRmg

## Introduction

이것은 NonCompart, Edison Science App Manual 메뉴얼입니다.
이 프로그램은 [Github](http://github.com/shanmdphd/edisonNoncompart)에 소스코드가 올려져 있고 공개 프로그램으로 관리됩니다.
감사합니다.

- NonCompart Edison Science App 
- 개발환경 : R 3.3.2

2017년 1월
한성필

## NonCompart Edison

- `Online NonCompart` <https://asan.shinyapps.io/noncompart>
- `Online NonCompart` is open to everyone. We are happy to take your input. Please fork the repo, modify the codes and submit a pull request. <https://github.com/shanmdphd/noncompart>

### Installation of NonCompart R Package

```{r}
install.packages("NonCompart")
library(NonCompart)
NCA(Theoph, "Subject", "Time", "conc", Dose=320)
```

### Help

- `NonCompart` package help <https://cran.r-project.org/web/packages/NonCompart/NonCompart.pdf>

### Dataset requirement

- Undetectable concentrations for first time points should be entered as 0; for last points - as NA (missed values).

### Demo datasets
- `BE` <https://statist.shinyapps.io/bioeq_en/>
- `Theoph`: Oral 320 mg (N=12) <http://stat.ethz.ch/R-manual/R-devel/library/datasets/html/Theoph.html>
- `Indometh`: IV 25 mg (N=6) <http://stat.ethz.ch/R-manual/R-devel/library/datasets/html/Indometh.html>
- `sd_oral_richpk`: Oral 5000mg (N=50) <https://github.com/dpastoor/PKPDdatasets>
- `sd_iv_rich_pkpd`: IV diverse dosing (N=60) <https://github.com/dpastoor/PKPDdatasets>

### CDISC materials

- [CDISC SDTM Implementation Guide 3.2 PDF ](https://www.cdisc.org/sites/default/files/members/standard/foundational/sdtmig/sdtmig_20v3.2_20noportfolio.pdf)
- [CDISC Terminology PDF](https://evs.nci.nih.gov/ftp1/CDISC/SDTM/SDTM%20Terminology.pdf)

### Reference

- Rowland M, Tozer TN. Clinical Pharmacokinetics and Pharmacodynamics - Concepts and Applications.
4e. 2011
- Gibaldi M, Perrier D. Pharmacokinetics 2e revised and expanded. 1982

### R Packages
- Kyun-Seop Bae (2016). NonCompart: Noncompartmental Analysis of Pharmacokinetics. R package version 0.2.3. https://CRAN.R-project.org/package=NonCompart
- H. Wickham. ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York, 2009.
- Hadley Wickham. tidyr: Easily Tidy Data with `spread()` and `gather()` Functions. R package version 0.6.0.9000. https://github.com/hadley/tidyr
- Winston Chang, Joe Cheng, JJ Allaire, Yihui Xie and Jonathan McPherson (2016). shiny: Web Application Framework for R. R package version 0.14.2. https://CRAN.R-project.org/package=shiny
- JJ Allaire, Jeffrey Horner, Vicent Marti and Natacha Porte (2015). markdown: 'Markdown' Rendering for R. R package version 0.7.7. https://CRAN.R-project.org/package=markdown
- Philippe Grosjean and Frederic Ibanez (2014). pastecs: Package for Analysis of Space-Time Ecological Series. R package version 1.3-18. https://CRAN.R-project.org/package=pastecs
- Hadley Wickham and Romain Francois (2016). dplyr: A Grammar of Data Manipulation. R package version 0.5.0. https://CRAN.R-project.org/package=dplyr
- David Gohel. ggiraph: Make 'ggplot2' Graphics Interactive. R package version 0.3.2. https://davidgohel.github.io/ggiraph

