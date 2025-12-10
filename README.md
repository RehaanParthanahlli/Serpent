# N1 -
## 🧩 Setup - 2 Files in the Same Folder!
**filename:** ``module.py``
```python
def greet(name):
    print(f"Hello, {name}!")

if __name__ == '__main__':
    print("Running module.py directly")
```

**filename:**``main.py``
## Import the entire module!
```python
import module  
def main():
    module.greet("Rehaan")  # Call the function from module.py

if __name__ == '__main__':
    main()
```


## 🧪 Output !
**filename:**``main.py``
```Bash
python main.py
```
``Output - Hello, Rehaan!``

# N2-
```Python
def greet(name: str) -> str:
    return "Hello " + name

def add(a: int, b: int) -> int:
    return a + b
```


