# Week 4 Lab Report 2
## Victor Gutierrez Vargas

April 24, 2022

---

## Bug One:

**The first bug, encountered was an index out of bounds error that was caused by the code trying to access the items that didn't exist in the file. So we had to determine when the code should stop and keep going.**

![Image_one](https://raw.githubusercontent.com/victorvm77/lab-report-2-week-4/main/Report_1.png)

*Code*

[Link to First Error Inducing Test File](https://github.com/SathyaVen/markdown-parser/commit/922c11325f553e0e0692670a4c581ddc94e6f667#diff-c703a0ec03474d601c6bf846740b293e0538bccf38d5f677a302457479e9c652)

* The code ran with the index out of bounds error reporting that-1 even though the beginning was 0.

![Image_two](https://raw.githubusercontent.com/victorvm77/lab-report-2-week-4/main/Report_2.png)

*StringIndexOutOfBounds Error*

---

## Bug Two:

**The second bug we encountered was an index out of bounds error. It was the same error from the last time. So by adding the open and closed brackets () to determine when the code should stop searching.**

![Image_three](https://raw.githubusercontent.com/victorvm77/lab-report-2-week-4/main/Report_3.png)

*Code*

* The code ran with the index out of bounds error reporting that-1 even though the beginning was 0.

[Link to Second Error Inducing Test File](https://github.com/aaronchan32/markdown-parser/commit/e4100a4480e63bbe9a81c62d3bbfb03c60530329)

![Image_Four](https://raw.githubusercontent.com/victorvm77/lab-report-2-week-4/main/Report_4.png)

*StringIndexOutOfBounds Error*

---

## Bug Three:

**The third bug encountered was a heap error that was caused by an infinite loop.The code overwrites control of the information that the memory management functions use to control heap usage. We attempted to fix this by removing unnecessary lines after the line with the link**

![Image_Five](https://raw.githubusercontent.com/victorvm77/lab-report-2-week-4/main/Report_5.png)
*Code*

[Link to Third Error Inducing Test File](https://github.com/victorvm77/markdown-parser/commit/3ab322ece4969a6a6bc9ae893e149ba99c01d203)

![Image_Six](https://raw.githubusercontent.com/victorvm77/lab-report-2-week-4/main/Report_6.png)

*Symptom for OutOfMemory Error*
