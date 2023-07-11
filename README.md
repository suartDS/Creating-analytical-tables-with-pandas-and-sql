# Creating analytical tables with pandas and sql

Here is an example of creating analytical tables using Pandas and Sql tools based on monthly sales data.
The examples show how to get important information for sales about user from raw data.


## Notebooks provide examples of creating:

* Сalculate total income and count, income for all indicators per month, taking into account inactive months
* Create templates for analytical table with add an **auxiliary key**
* Find user registration date
* Сalculate revenue per user (taking into account inactive months)
* Сalculate registered users
* Сalculate active users
* Mark active users who buy anything in month
* How many new users come per month
* Average number of items purchased by active customers and mean unique products mean

<p align="center">
  <img src="./img/at_1.png" alt="At_1" width="738">

  <img src="./img/at_2.png" alt="At_2" width="738">
</p>

## How to install
To work with **SQL_Creating_analytical_tables.ipynb** you must have a local Postgres installation deployed or
access to Postgres via a url like - postgresql://user:user_pass@db:5432/ from jupyterlab

How to deploy JupyterLab and Postgres locally you can see here -

[Docker JupyterLab and Postgres]: https://github.com/suartDS/docker-for-ds

### Packages used:
* pandas
* numpy
* matplotlib
* plotly
* sqlalchemy