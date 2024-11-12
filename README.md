# Python Project Model

Forms project model based on Python files within repository as well as provide base statistics.
Provides API for traversing the model as well as export in common format (TBP).

The model for Python looks like below:
```
folder
 |- .py file (LoC)
   |- import
   |- function (LoC, cyclomatic complexity)
     |- decorator
     |- parameter
   |- classA
     |- method (LoC, cyclomatic complexity)
       |- decorator
       |- parameter
       |- variables
     |- field
     |- ...
   |- classB
     |- ... 
   |- ...
 |- .java file
 |- ... 
```

Base statistics include:
- number of Python files
- number of classes
- avg/max number of methods per class
- avg/max method size (LoC)
