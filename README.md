# Strategy-implementation learning group
# 1st Meeting programme
+ Date: Friday, 11 Jan 2019
+ Time: 3.00pm to 5.00pm
+ Venue: Project Room 5-8, LKSLIB
___
## Personal Profile
### the programming ability
### what u hope to gain in the end or in long term
### if any, recommand some good reference
___
## Sharing--General knowledge about quantitative investing in reality
### five core element

#### tradeable financial product 
+ stock, bond, fund, option, fx, future)

#### historical data 
+ high freq: time interval less than 0.5 s
+ low freq: interval more than 1 minitue

####  investing strategy
+ when to buy, what product to buy, at what price
#### computer programming
#### platform for backtesting and trading

### strategy classfication
#### product classfication: stock, CTA(mainly for option), option, FOF
#### arbitrage ( the core is Mean Reversion, event-driven,fx/ bond）, hedge （core is risk management, buy / sell stock/index future.
#### trading signal: multi-factor, mean-reversion, momentum, machine learning

### common platform used
* quantopian (platform for backtesting strategy)
___
## Discussing
### which part to focus on
+ we build our own strategy implementation structure, starting from basic level
+ well-built platform with more data, friendly outlook, can be used as extention learning tool

### how do we organize
+ Learn from fulfill each task
+ We meet twice a month, share the code and determine next task.
 ___
 
# Task 1 Description
+ Data: Using data from Dr.Zhao\`s lectures, S3-5, named `CC3.SI.csv`.
+ Time interval: The same as the data\`s
+ Strategy: When the MA5 crossing 
    + when 15 MA exceed 50 MA, immediately buy the stock (no delay)
    + when 50 MA exceed 15 MA, immediately sell the stock (no delay)

+ Requried outcome
    + Complusory: Plot the date (on the x axis) vs net value (on the y axis). 
    + option: Show daily the transactions log & daily postion value
+ Using two methods
     + fix the each trade postion: number of share of each time is 1000
     + fix the initial value: 10000
