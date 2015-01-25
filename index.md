---
title       : Titanic Survivor Analysis
subtitle    : What classes of people were most likely to survive?
author      : John Fitzpatrick
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : standalone # {standalone, draft}
knit        : slidify::knit2slides
---

## Examine Titanic survivors by 3 characteristics

1. Passenger Class (1st, 2nd, 3rd, Crew)
2. Gender (Male, Female)
3. Age (Adult, Child)

--- .class #id 

## Passenger Class

1. 1st class had the best survival rate proportionally
2. The crew had the worst survival rate proportionally (went down with the ship?)
3. 3rd class also had a poor survival rate


```
##   Passenger Class Survived Count
## 1             1st       No   122
## 2             1st      Yes   203
## 3             2nd       No   167
## 4             2nd      Yes   118
## 5             3rd       No   528
## 6             3rd      Yes   178
## 7            Crew       No   673
## 8            Crew      Yes   212
```

--- .class #id 

## Gender

1. There were about 3 times more men than women aboard
2. Women had a dramatically better survival rate than men
3. Was it because women and children got on the lifeboats first?


```
##   Gender Survived Count
## 1   Male       No  1364
## 2   Male      Yes   367
## 3 Female       No   126
## 4 Female      Yes   344
```

--- .class #id 

## Age

1. Only a little more than 100 children aboard
2. Children had a dramatically better survival rate than Adults
3. Likely some correlation with the higher survival rate of women


```
##     Age Survived Count
## 1 Child       No    52
## 2 Child      Yes    57
## 3 Adult       No  1438
## 4 Adult      Yes   654
```

--- .class #id 




