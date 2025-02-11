# Double take

> [!NOTE]  
> There are two parts to this exercise! Read carefully!

## Part 1

You have designed a custom file format to track your monthly expenses. It is time for you to add your expenses for February 2025.

The process begins by creating a new file that will store all transactions for February 2025. The file needs to follow the same structure as previous months' records, including columns for Date, Description, Amount.

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

### Goal

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

## Submission

To submit your progress, run the `submit.sh` script found in this repository:

```bash
bash submit.sh
```
