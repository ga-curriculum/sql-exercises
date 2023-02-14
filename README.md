# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) SQL Ladder Challengers

| Title                  | Type | Duration | Author               |
|------------------------|------|----------|----------------------|
| SQL Ladder Challengers | Lab  | 2:00     | Suresh Melvin Sigera |

Learn SQL by practicing. Problems in these folders start out easy and progressively get harder. The order of the
problems is designed so that the next rung of the SQL ladder is always within reach. If you get stuck, look at your
answers to previous problems and see if you can use that logic to solve the next problem.

We encourage the use of Googling to aid you in solving these problems! That's how the pros do it!

That is, Googling how to solve a problem. Not Googling solutions to problems.



## How to submit homework

### Setup

- Step 1. Fork the repository
- Step 2. Clone your fork
- Step 3. Open pgAdmin and find the Database Menu.
- Step 4. Right click on Database and select Create Database. Name this Database `sql-exercises` and hit save.
- Step 5. Open the PSQL tool.
- Step 6. Within the PSQL cli use the import (\i) psql command to create each step's table and seed its data. **This will need to be repeated for each step.**
  * Make sure of the correct path on your device and run this command at the beginning of each step. 

```
\i /Users/<yourname>/2023/abbottlabs/labs/sql-exercises/step-1/schema.sql
```

- Step 7. Write the queries requested.
 * For this lab, you are expected to use the psql command line interface. Write your queries in the `queries.sql` file and run them in psql with the \i command. It should look something like this:

```
$ psql sql_exercises_db
psql (9.6.1)
Type "help" for help.

sql_exercises_db=# \i queries.sql
```

### Submitting work

- Step 1. Create a folder for the specific homework
- Step 2. Push to your fork
- Step 3. Submit a pull request
- Step 3.1. Add first name, last name and comment

In the comment section, you must add the following:

```text
* Comfortability [0 to 5]
* Completeness [0 to 5]
* What was a win?
* What was a challenge?
* Any other comments
```
