# Lesson Name

description of the lesson

## Typical workflow
1. clone repository to desktop
2. complete tasks described in `task.md` files
3. commit changes by uploading `Lesson` directory to a new branch of repo. All changes you made within the subdirectories will be uploaded. This saves you having to upload each individual file you changed or added
4. open a pull request and message teacher to indicate that work is ready for review
5. When completed satisfactorily, teacher will merge task branch

## Typical directory structure
```
Repository  
  |--README.md         overall description of lesson
  |--tasks  
  |  |--task1.md       description of the task 1
  |  |--task1.py       python framework for task 1 to be edited
  |  |--task2.md       description of the task 2
  |  |--task2.py       python framework for task 2 to be edited
  |
  |--tests
  |  |--test_task1.py  unit test for task 1
  |  |--test_task2.py  unit test for task 2
  |
  |--docs              use this to store documentation such as algorithms, data dictionaries etc
     |--README.md      use this to list and describe all the files in this directory
     |--task1.pseudo   pseudocode framework for task 1 to be edited
     |--task2.pseudo   pseudocode framework for task 2 to be edited
 ```
