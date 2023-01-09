# python_lunch
python-lunch for python 3.x

fixed this issuse (Python-lunch Syntax Error: except ImportError , e:) 

https://stackoverflow.com/questions/70360866/python-lunch-syntax-error-except-importerror-e

  Traceback (most recent call last):
  
  File "/usr/bin/lunch", line 41, in <module>

    from lunch import runner

  File "/home/xor/.local/lib/python3.6/site-packages/lunch/runner.py", line 73

    except ImportError, e:
                      ^
  SyntaxError: invalid syntax
