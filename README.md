# Git-and-GitHub-final-assignment
This template repository hosts the final Git & GitHub assignment.

## Description
We learnt how to use Git & GitHub to keep records of milestones during  projects. Now, this is time for the final assignment that consists in creating *3 repositories* each having a *minimum of 3 commits* to host some of the previous projects you worked on, during the previous phase of the program and fill the table in the `Recap Table` section.

## Assignment
The following steps constitute your assignment :
1. **Clone this repository** on your local machine; 
1. Configure it as described in the `Setup` section;
1. Select `3` projects, your own ones or projects done during the previous part of the Azubi program ;
1. **Create one public repository** for each project, with a complete and personalized readme file and repository's description ;
1. **Commit** `at least 3 times for each repository` while including simple and clear commit's messages, and **push**;
1. **Fill** the table in the `Recap Table` section with the details of your created repositories.
1. Finally, **commit** with the message `My 3 repositories has been created`, then **push your commit**.

## Recap Table
The below table must contain the details of the repositories you will create, fill it please.


|  | Project's Name | Description    | GitHub's Link  |
|:--:|:--------------:|:--------------:|:--------------:|
| 1 |  Sage           | Welcome to Sage, a real-time platform providing the latest data on cryptocurrency prices and market metrics. With Sage, you can stay up-to-date with the ever-changing crypto landscape and visualize the trends for each coin effortlessly.            | https://github.com/coderacheal/Sage       |
| 2 |  Sunday            |  Sunday is an app embed with a machine learning model that warns users about the context of their message before they send them.             | https://github.com/coderacheal/Sunday      |
| 3 |  Everest            |    A finance app that enables you to track your expenses based on the type of expenses you define. Complete with authentication, it helps you stay on top of the dollar          | https://github.com/coderacheal/everest      |

**NB**: `Do not modify` the general structure of this table above to avoid issue of evaluation, just fill the rows .

## Setup
Install the required packages to be able to run the evaluation locally.

You need to have [`Python 3`](https://www.python.org/) on your system (**a Python version lower than 3.10**). Then you can clone this repo and being at the repo's `root :: repository_name> ...`  follow the steps below:


- Windows *(Python should be added to the Path variable of environment)*:
        
        python3 -m venv venv; venv\Scripts\activate; python -m pip install --upgrade pip; python -m pip install -r requirements.txt  

- Linux & MacOs:
        
        python3 -m venv venv; source venv/bin/activate; python -m pip install --upgrade pip; python -m pip install -r requirements.txt

The both long command-lines have a same structure, they pipe multiple commands using the symbol **;** but you may manually execute them one after another.

1. **Create the Python's virtual environment** that isolates the required libraries of the project to avoid conflicts;
2. **Activate the Python's virtual environment** so that the Python kernel & libraries will be those of the isolated environment;
3. **Upgrade Pip, the installed libraries/packages manager** to have the up-to-date version that will work correctly;
4. **Install the required libraries/packages** listed in the `requirements.txt` file so that it will be allow to import them into the python's scripts and notebooks without any issue.

## Evaluation
This evaluation will be automatically grade, so please follow the instructions carefully. 

You can run this command bellow being at the root of the repository to be sure your solutions are the good ones before to push your solutions.
```command
python -m pytest -v
```

If everything is okay, you will have such an output

```terminal
================================================= test session starts =================================================
platform xxx -- Python 3.9.6, pytest-7.2.0, pluggy-1.0.0 -- /xxx/python3
cachedir: .pytest_cache
rootdir: xxx/Git-and-GitHub-final-assignment
collected 3 items                                                                                                     

tests/test_filled_table.py::test_not_empty_table PASSED                                                         [ 33%]
tests/test_filled_table.py::test_not_empty_rows PASSED                                                          [ 66%]
tests/test_readme_table.py::test_contains_table PASSED                                                          [100%]

================================================== 3 passed in 0.000s ==================================================

```
