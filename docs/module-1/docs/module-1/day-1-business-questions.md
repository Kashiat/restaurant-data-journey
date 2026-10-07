# Module 1 Day 1: Business Question to Data Question

## Exercise purpose

This exercise helped me turn a broad business question into a question that can be answered with data.

## My questions

**Starting business question:** Are we doing well?

This question is too broad to answer directly, so I broke it down into more specific data questions.

### Question 1

**Business question:**  
Which of our pizzas are the most popular and bring in the most money?

**Data question:**  
Which pizzas sell most often, and which generate the highest total sales value across the year?

**Fields or data needed:**  
Pizza name, size, type/category, price and order records.

**Can the current dataset answer it?**  
Yes. The dataset records every pizza sold with its name, size, category and price, so I can count sales and add up sales value per pizza.

### Question 2

**Business question:**  
When are we busiest, so we can plan staffing better?

**Data question:**  
Which times of day and days of the week have the highest number of orders?

**Fields or data needed:**  
Order ID, order date and order time.

**Can the current dataset answer it?**  
Yes. The dataset includes the date and time of each order, so I can group orders by hour and by day of the week.

### Question 3

**Business question:**  
Are our customers loyal and coming back?

**Data question:**  
Which customers place repeat orders, and how often do they return?

**Fields or data needed:**  
A customer ID linked to each order, plus order dates.

**Can the current dataset answer it?**  
No. The dataset has no customer identifier, so I cannot tell whether two orders came from the same person. I would need customer or loyalty-scheme data to answer this.

## What I learned

A business question like "Are we doing well?" is broad and open to interpretation, while a data question is specific, measurable and tied to the fields available. 
Breaking a big question into smaller data questions made it clear what I could actually answer with the dataset. 
I also learned that knowing what the data cannot tell me, such as repeat customers without a customer ID, is just as important as knowing what it can.
