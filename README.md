# best-notebooks
This little repo is implementaiton of best practice of Databricks notebook recommended by [Databricks official docs](https://docs.databricks.com/aws/en/notebooks/best-practices)
The requirements are:
1 free Databricks account, 1 free GitHub account.
It includes:
1. create notebook, run it
2. modulize your .py files
3. unit testing using pytest
4. create a job and schedule it
5. implement CI in DAB (CLI+Bundle) way recommended as modern CICD path which did not follow the document which is run-notebook way.

Further improvement can be: 
For better security, consider using workload identity federation instead of a static token
