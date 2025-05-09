# `double-take`

You are trying to be more judicious in your expense tracking and have starting tracking your expenses on your computer.

> [!NOTE]  
> There are two parts to this exercise! Read carefully!

## Part 1

You have designed a custom file format to track your monthly expenses. It is time for you to add your expenses for February 2025.

The process begins by creating a new file (format: `yyyy-MM.csv`) that will store all transactions for February 2025. The file needs to follow the same structure as previous months' records, including columns for Date (format: `yyyy-MM-dd`), Description, Amount.

This is what some of the records for January 2025 looks like (file also included):

```csv
Date,Description,Amount
2025-01-01,Opening Balance,0
2025-01-03,Salary Credit,3000
2025-01-10,Electricity Bill,-180,6700
```

Specifically, in February 2025, there were three expenses:

| Date            | Description         | Amount |
| --------------- | ------------------- | ------ |
| 3 February 2025 | Grocery store       | -55.35 |
| 3 February 2025 | Haircut             | -14.00 |
| 5 February 2025 | Dinner with friends | -50.25 |

### Task

Please add the above entries for your February 2025 expenses. Please name the file `2025-02.csv`. Feel free to add more entries for fun!

### Hints

<details>

<summary>Hint 1</summary>

Have you named the new expense file `2025-02.csv`?

</details>

<details>

<summary>Hint 2</summary>

Have you added the three expenses above?

</details>

<details>

<summary>Hint 3</summary>

Add the file `2025-02.csv` with the following content:

```csv
Date,Description,Amount
2025-02-03,Grocery store,-55.35
2025-02-03,Haircut,-14.00
2025-02-05,Dinner with friends,-50.25
```

</details>

## Part 2

As you were filling in your expenses for February 2025, you look back to the expenses logged for January 2025 and you notice that there are several erroneous entries.

Specifically, you realize that the "Description" for some of the entries are listed as "Unknown Transaction". That's not good for tracking!

### Task

Can you go through the expenses from January 2025 and find the erroneous entries and correct them? (Any other values work!)

### Hints

<details>

<summary>Hint 1</summary>

Have you taken a look at the `2025-01.csv` file?

</details>

<details>

<summary>Hint 2</summary>

These are the entries that need to be fixed:

- 2025-01-06: -250
- 2025-01-12: -500
- 2025-01-17: -1000
- 2025-01-23: -350

</details>

## Learning outcomes

- [ ] Apply `git add` and `git commit`

## Submission

To submit your progress, run the `submit.sh` script found in this repository:

```bash
bash submit.sh
```
