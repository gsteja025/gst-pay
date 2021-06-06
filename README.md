# gst-pay
# HOW TO USE
![2021-06-06 (3)](https://user-images.githubusercontent.com/62547559/120927803-03243d00-c697-11eb-8339-68e6db3ae1a4.png)
Enter your login details first namely username and pin.Then it will show your credentials on screen.
As of now there is no option for account creation.Furtherly will develop for sure.
![2021-06-06 (2)](https://user-images.githubusercontent.com/62547559/120927768-e2f47e00-c696-11eb-9974-ea2e0e101fc1.png)

In your account you can see three sections(request loan,transfer money and delete account):





these sections are created with help of event handlers as you can see from code.
transactions section(deposits and withdrawals) are updated each time by updateui function in code.
This function is called each time when you request loan or tranfer money or delete account.you can sort transaction section by clicking sort button below
This sort fuction is created by using lambda as it won't sort directly using sort inbuilt function in js(it sorts in order of their ascii values).
Timer below allows you to use your account for limited time, this ensures security to your account.Timer function is created by setTimeInterval() inbuilt method in js.
it takes arguments a call-back function and time.This time argument is used to update timer on screen after specified time.Dates beside each transaction is updated using 
date() method and Intl.DateTimeFormat method as shown in code.Several Array methods like filter,reduce and map are used to display summary money in your account.

