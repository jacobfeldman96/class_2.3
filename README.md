# Class_2.3
## Write up
This class we learned how to define and apply functions, time value of money, Net Present Value, how to import standard and custom python libraries, and how to read and write .txt files. 

A function is a block of code that performs an action and is reusable in later itterations of code. To initialize a function the first thing one must do is write def followed by the name_of_the_function and its (argument, or_argumennts). Afterwhich, one needs to specify the equation and then print return. A local variable that might have been used in the function should be reassigned as a global variable in order to be utilized later on in the code. 

After which we reviewed Dictionaries which included: dictionaries only having unique keys, keys cannot be of any data type, keys must be immutable, possible data types include: floats, integers, booleans or strings. 

**Time Value of Money:** This theory indicates that a sum of money will gain value as time passes depending on interest rates. Money today is worth than money tomorrow because money today has the opportunity to grow for longer. 

Future and Present Value equations are as follows:

**Future Value = Present Value * ([1 + (i/n)] ** (n*t))** 

where i is the interest, n is the number of compounding periods per year, and t is the number of years.

For present value, simply switch the FV and PV variables' locatins in the equation. 

We then discussed how to determine the potential profitability of 0 coupon bonds via the present value equation and the activity can be found in my JupyterLab file also in this repository. 

We then discussed Net Present Value and its application to business studies, cash flow projections, its use to calculate the Return on Investment and a company's potential profitability. The formula is as follows:

[NPV = cash flow / ((1 + i)**t) - |initial investment|]

where i = the discount rate of return that could be earned elsewhere and t = number of years.

The class finished with opening and reading .txt files. 

I struggled with two lines in python that I couldn't personally troubleshoot. The first you'll see is in line [86] where for some reason the .append command was not adding to the list - will ask in office hours. The second place was in line 49 where I couldn't troubleshoot line [35] and I could not find a viable option online - will ask in office hours. 

On a personal note, I finally feel I'm generally starting to get the hang of it. I still sometimes struggle with the conceptualization of applicable solutions but I reckon that with practice, that'll all get better. See you Tuesday!
