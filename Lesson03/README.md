# Lesson03: Variable Sizes -- [Video Link](https://youtu.be/ULpbUtqboaY)

* [Reference Code](https://repl.it/@VaibhavGupta4/Lesson3)

Type|Size (in bytes)|Min|Max
---|---|---|---
bool | 1 | 0 | 1
char | 1 | `TBD` | `TBD`
short | 2 | -2<sup>15</sup> | 2<sup>15</sup>-1
unsigned short | 2 | 0 | 2<sup>16</sup>-1
float | 4 | `TBD` | `TBD`
int | 4 | -2<sup>31</sup> | 2<sup>31</sup>-1
unsigned int | 4 | 0 | 2<sup>31</sup>-1
long | 4 | -2<sup>31</sup> | 2<sup>31</sup>-1
unsigned long | 4 | 0 | 2<sup>31</sup>-1
long long | 8 | -2<sup>63</sup> | 2<sup>63</sup>-1
unsigned long long | 8 | 0 | 2<sup>64</sup>-1


If you haven't done so already:
* Sign up for the [Slack Community](https://forms.gle/Jx3TBiqDFkqB4CEj6)
* Do the previous assignments!



Your assignment this week is to do the following.
* Create memory tables for adder assignment from Lesson02. Make sure you use different inputs as test cases in this memory table.
* Find two values for which your calculator doesn't work.
  * If you are able to, can you change it to make it work for those values? Why or why not?
  * Are there two more values for this new calculator doesn't work? Why or why not?
* How big is 2<sup>64</sup>? Check this with [Wolfram Alpha](http://wolframalpha.com/)! That's about how large an unsigned long long can get!
* For each of the following types, come up with 5 real world examples when you would use them. Write these down along with a sentance for each explaining why that type is appropriate.
  * bool
  * unsigned short
  * int
  * unsigned long long
* Powers of 2 are very important in computer science. Calculate the following table until you feel you know all of the values off the tip of your tongue. **NO CALCULATORS**

Short hand | Full Value
-- | --
2<sup>0<sup> | 
2<sup>1<sup> | 
2<sup>2<sup> | 
2<sup>3<sup> | 
2<sup>4<sup> | 
2<sup>5<sup> | 
2<sup>6<sup> | 
2<sup>7<sup> | 
2<sup>8<sup> | 
2<sup>9<sup> | 
2<sup>10<sup> | 

### Final note
We intentionally try and make sure every assignemnt pushes your boundaries. 
Not everything you need in order to do the assignment was given to you in the videos. 
The goal is to help build your muscle of asking The Right Question. Sometimes you may feel stuck, 
and its important to remember that's completely normal.

First write on paper on what you are trying to get the code to do. 
Then go ahead and ask the question in the Slack Channel for this assignment. Be sure to link your Repl in the question and include a description of
* What line you think is causing the problem (if you don't know for sure, try and have a guess regardless)
* What you **want** your code to do
* What your code is **doing**

Do your best to google for the answer only after you've tried asking in the Slack channel. These assignments aren't to just get done, they are there to help you start building connections in your mind. Talking through your code with others is often the best way to do that!
