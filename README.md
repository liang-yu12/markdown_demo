
# Level 1 Heading
## Level 2 Heading
### Level 3 Heading


**Bold text**
*Italic text*

quote
> All models are wrong but some are useful.

Lists:
1. Numbered
1. Ordered

* item 1
* 

writing inline codes: `lrtest` in Stata

code block:

```
logit hiwrite female read
estimates store m1
logit hiwrite female read math science
estimates store m2
lrtest m1 m2
```


```r=
regression <- lm(y~x+z, data=df)
```

```sas=
proc sql;
select A, B
FROM templ;
quit; 
```


insert picture
![](https://i.imgur.com/9mCrCc0.jpg)

emoji :100: 

Insert a simple table:

1. Built in function in HackMD


| Column 1 |  a   |     | Column 2 |
| -------- | --- | --- | -------- |
| Text     |   x  |     | Text     |


2. Use other online tools: eg: https://tableconvert.com/

[Link](www.example.com)
[github demo](https://github.com/liang-yu12/markdown_demo)

Final step: copy and paste the codes to the `README.md` file in your GitHub












