# data-tech-challenge
Hey Data Scientist. Welcome. Your mission, should you choose to accept it is to analyse the following data and get back to us with the results.

## The Data

(see repository)

You are given a sample data dump (csv-format) comprising of invoiced items of various orderbird customers. A row consists of 
venue_id (string)
itemname (string)
datetime_invoiced (string)
turnover (double)
where 
datetime_invoiced denotes the timestamp when the item was invoiced,
turnover (in EUR) is the invoiced price 
As you will see, the item names do not follow any conventions, could be misspelled or even abbreviated. 
  
Your task is to create some statistics and figures for a report for a German beverage company called Jägermeister.
To this end, we ask you to create a jupyter/IPython notebook in which you solve the following tasks. Popular tools for tackling such tasks are Pandas or pySpark. If you prefer another tool, please explain why. Finally, for a better understanding of your approaches and ideas, please comment your code.

## The Tasks:

1. Extract a list of all distinct Jägermeister (JM) item names
2. What are the top 10 most sold JM items in terms of 
item count turnover?
3. Create a histogram illustrating the number of sold JM items per hour. 
4. In which hour are the most JM items sold?
5. For each venue find the weekday on which the most JM items (in terms of item count) are sold 
6. find the item name which is sold the most in terms of turnover
7. BONUS: Come up with an additional (potentially interesting) insight based on the given data. What else could you compare? E.g. else what would be iteresting to learn for Jägermeister?  

If you have any questions regarding these tasks, please just get in touch ( Tech-challenge@orderbird.com )so we can claryfy.

## And now what?
Please send your jupyter/IPython notebook to Tech-challenge@orderbird.com and we will get back to you asap. 
Please *do not* create a pull request of fork this repository as your solution should not be end up being public afterwards.

Good luck and happy coding!


