# 953261 Lab 2 — Kad Café (Modern JavaScript)

| | |
|---|---|
| **Name** | Jiayu Li |
| **Nickname** | isa |
| **Student ID** | 692115503 |
| **Section** | 701 |

## How to run

```bash
cd lab02
npm run warmup   # Part B
npm test         # Part C
npm start        # Part D — the daily report
```

## My own function (Part D)

`itemsWithTag(menu, tag)` returns the names of the menu items that have a given tag. For example, `itemsWithTag(menu, "spicy")` returns `["Khao Soi", "Basil Chicken Rice"]`. It uses `filter` to keep the items whose `tags` array includes the tag, and `map` to turn those items into their names.

## What I learned today

I use `map` when I want a new array with one result for each item, `filter` when I want to keep only some items, `find` when I need one item, and `reduce` when I want to combine everything into one value, like a total. I also learned that `reduce` needs a start value, that a function needs `return` to give back its result, and that I should return new objects (with spread) instead of changing the original data.

## AI-use statement

I used Claude to explain the array methods and to help me debug errors in my code and Git. It gave me explanations and some code examples, and I typed, ran and tested the