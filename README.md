# stock-analysis
Help Steve's parents make a well-informed investment decision

	1.	Overview of Project: Explain the purpose of this analysis.
## Steve’s nostalgic parents were set on investing in a green energy company which had sentimental meaning to them more so than being a practical, informed decision. Steve had hoped we could provide his parents and him with data which reflected their preferred company’s investment returns, compared with similar companies in the green industry. Our task is to deliver this data in an accessible, user-friendly fashion comparing these companies over the course of two years.
	2.	Results: Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.
## From 2017 to 2018, we see a significant difference in the performance of the companies we have reviewed. 2017 is a rather good year for green energy companies, particularly Daqo, which is Steve's parents' preferred investment. In the following year, this trend has reversed. A majority of the companies tracked have fairly substantial losses in 2018, with Daqo at the very bottom of the pack. We can see that refactoring the code has shaved around 20% of the time required for the code to run. It's worth noting that the code is slightly longer after having been refactored, making this an even more impressive feat.
	

### 2017 Results:
![image](https://user-images.githubusercontent.com/76623937/112767124-857aeb80-8fda-11eb-895b-95f5eb154daa.png)

### 2018 Results:
![image](https://user-images.githubusercontent.com/76623937/112767177-c70b9680-8fda-11eb-9acc-799d4a7d1f1a.png)

### Prerefactored 2017:

![image](https://user-images.githubusercontent.com/76623937/112767761-23bc8080-8fde-11eb-9b00-4c2a6f527eeb.png)

### Refactored 2017:

![image](https://user-images.githubusercontent.com/76623937/112767889-c37a0e80-8fde-11eb-8931-ab3628f7ea14.png)

### Prerefactored 2018:

![image](https://user-images.githubusercontent.com/76623937/112768485-e0fca780-8fe1-11eb-8cb5-e92948938c0a.png)

### Refactored 2018:

![image](https://user-images.githubusercontent.com/76623937/112769491-ef998d80-8fe6-11eb-9cd8-533616f84023.png)

	3.	What are the advantages or disadvantages of refactoring code?
## As effeciency and functionability are two primary factors in the quality of code, refactoring code whenever possible seems to only be advantageous. When refactoring, we can substantially improve its effeciency, as well as having an impact on readability for other users. Refactoring can eliminate unnecessary redundancies, and we can also group statements (when possible) in a meaningful way to be more intuitive for a user reading the code for the first time. It is hard to think of disadvantages to refactoring, unless the coder is careless. There is always a risk of making functional code useless when moving around statements.
  
	4.	How do these pros and cons apply to refactoring the original VBA script?
## The advantages of refactoring our original VBA script is clear after viewing before and after runtimes. For code that runs for only 1/2 second, a 20% reduction is still rather substantial. It was most certainly a challenge- though not a con- to do this for the first time. We might say that for code this short, the only con is taking the time to do it, for an improvement of 0.1 seconds. 
