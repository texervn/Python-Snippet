# Some basic things working with Python

## Check the callable method existence in current file:
```python
if var in globals() and callable(globals().get(var)):
    print(True)
else:
    print(False)
```

## Check if class contains a method
```python
if hasattr(cls, med) and callable(getattr(cls, med)):
    print(True)
else:
    print(f'Method {med} does not exist')
```
