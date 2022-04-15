# Stock Analysis

## ***Overview:***

In this challenge, we are using Visual Basic for Applications (VBA) to automate code so that Steve can research the stock market for his parents. They are interested in renewable energy and want to invest in companies that build green energy systems and components. Steve wants us to create code that, when run, will give him the total daily volume and annual return of the green energy companies. We will be refactoring code to loop through all given data and determining if refactoring makes the code more efficient.

### ***Results:***

In the original code, running code for 2017 took approximately 0.523 seconds.

![VBA_Challenge_2017(1)png](https://user-images.githubusercontent.com/87077325/160468905-b83ce8ed-1393-4d46-b819-73194f0b880e.png)

For 2018, it took about 0.531 seconds to run.

![VBA_Challenge_2018(1)](https://user-images.githubusercontent.com/87077325/160469090-c90815f4-6648-4e28-a22f-d855aaee0674.png)


After refactoring and adding a total of three output arrays, the code ran more effeciently than the original code. When running the refactored code for 2017, it took approximately 0.082 seconds.

![VBA_Challenge_2017](https://user-images.githubusercontent.com/87077325/160469416-55e308e8-7ba0-4ce6-bb0f-e047551d03c3.png)

Running the refactored code for 2018 0.078 seconds.

![VBA_Challenge_2018](https://user-images.githubusercontent.com/87077325/160469617-188368f6-cad1-4e92-96a7-3a4b3497b5e1.png)

## ***Summary:*** 

As shown by the images above, refactoring code can substantially increase runtime efficiency while being executed. Looping code saves time because writing individual code for every variable separately would be extremely time consuming. Refactoring code can also be easier to debug. One disadvantage of refactoring is that it can not improve underlying code building issues. This can be an issue when the programming language becomes dated. Another disadvantage to refactoring code is that it can potentially introduce bugs that take time to find and fix.
