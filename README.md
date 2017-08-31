# create-app
Python script that creates directory structure from template

# Introduction
Just a simple script that creates a directory structure from template

# How to use it?
1. Define the structure in a text file
..* Use '+' to create a file
..* Use spaces or tabs to define the hierarchy 
```
flask
 app
  template
  static
  main
   +__init__.py
   +errors.py
   +views.py
  +__init__.py
  +errors.py
  +models.py
 migrations
 tests
 +config.py
```
2. Run `create-app -s PATH_TO_STRUCTURE_FILE`


and it will create the defined structure in ~ directory


|-**flask**  
&nbsp;|-**app**  
&nbsp;&nbsp;|-**template**  
&nbsp;&nbsp;|-**static**  
&nbsp;&nbsp;|-**main**   
&nbsp;&nbsp;&nbsp;|-\_\_init\_\_.py  
&nbsp;&nbsp;&nbsp;|-errors.py  
&nbsp;&nbsp;&nbsp;|-views.py  
&nbsp;&nbsp;|-\_\_init\_\_.py  
&nbsp;&nbsp;|-errors.py  
&nbsp;&nbsp;|-models.py  
&nbsp;|-**migrations**  
&nbsp;|-**tests**  
&nbsp;|-config.py  

also see `create-app -h` for more details
