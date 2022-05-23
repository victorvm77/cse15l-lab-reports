# Week 8 Lab Report 4
## Victor Gutierrez Vargas
May 22, 2022

---

## *Link to my markdown-parse repo and link to the one reviewed in week 7.*
---
* [Link to my repository](https://github.com/victorvm77/markdown-parser)

* [Link to the repository reviewed](https://github.com/httrieu/markdown-parser)
---
**Showing the code in MarkdownParseTest.java for how you turned it into a test**

![Img1](https://raw.githubusercontent.com/victorvm77/lab-report-4-week-8/main/lab4SS1.png)

---
**For your implementation, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.**

![Img2](https://raw.githubusercontent.com/victorvm77/lab-report-4-week-8/main/lab4SS2.png)

---

**For the implementation you reviewed in Week 7, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.**

![Img3](https://raw.githubusercontent.com/victorvm77/lab-report-4-week-8/main/lab4SS3.png)

---
**Answers**


## Snippet 1
* *Adding an if statement checks if the brackets are preceded by a backtick because the inline b/c back ticks are scattered throughout. And if not add it the link to the arraylist*

## Snippet 2
* *In snippet 2 seems to be a little more difficult. It would be necessary to identify that multiple paranthesis are not the end of the link, which creates a problem with identifying whether the link is complete or not. Maybe adding an if statement.*

## Snippet 3
* *This snippet's problem is due to an incomplete link and new lines scattered in the file. However, it is possible to do within 10 lines, you would have to do is account for the empty space, by saving it as a string and maybe with an if statement changes the md file in order for the mark-downparse to work.*