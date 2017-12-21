# SST
Simulated Securities Trading

Brief Introduction:


The  SST project is an Simulated Securities Trading framework ,that is developed by traders, for  Securities Investor,The project is mainly written in C++,

This program will get the parameters which submitted by the specified path and write the processed data to the file in the specified path. It will work like the Securities simulation trading module,and it uses the free stock quotes API for data processing.


More details:


In order to work properly, you should format all parameters，The following is an example:
Input:


002618.sz,500,buy/sell/stopmarket/profitmarket,market,15.12,0

OutPut:


{OrderID: '5859',Quantity: 500, Price: 6.66, State: 'filled', Time: '2016-11-20 15:55:14'}



For more details, Please see the above picture and test by yourself.
