# 953261 Lab 2 — Kad Café (Modern JavaScript)

| | |
|---|---|
| **Name** | _Thiti Rakdamrongphorn_ |
| **Nickname** | _Kookku_ |
| **Student ID** | _692115022_ |
| **Section** | 701 |

## How to run

```bash
cd lab02
npm run warmup   # Part B
npm test         # Part C
npm start        # Part D — the daily report
```

## My own function (Part D)

_Name of your function, what it returns, and which array methods it uses._
function name : cheapDrinks(menu, maxPrice)
it returns a new array of menu lines for available drinks costing at most.
Array methods it uses are
1.filter : Keeps item that are drinks, available, and priced at or under maxPrice
2.sort : Orders them by price, lowest first (a.price - b.price)
3.map : Turn each object into a text line using menuLine


## What I learned today

_Write 2–3 sentences in your own words: when would you use map, filter, find and reduce?_
I use map to turn every item in an array into something new, such as menu objects into names, and filter to keep only the items that pass a condition, such as available drinks. I use find to get the first item that matches, such as one menu item by its id. I use reduce to combine an array into one result, such as the total price of an order.
## AI-use statement

_Did you use an AI tool in this lab? If yes, which one and for what. If no, write "No AI tools used."_
I use AI in part C : data task
task 6-10, i used it to help me dubug the error/ explain why my code isn't working. And i did not copy all the Ai generated code.
