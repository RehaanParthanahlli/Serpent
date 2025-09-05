# N1 -
# 🧩 Setup: Two Files in the Same Folder
**filename:** ``module.py``
```python
def greet(name):
    print(f"Hello, {name}!")

if __name__ == '__main__':
    print("Running module.py directly")
```

**filename:**``main.py``
# import module  
# Import the entire module
```python
def main():
    module.greet("Rehaan")  # Call the function from module.py

if __name__ == '__main__':
    main()
```


# 🧪 Output When You Run main.py
Hello, Rehaan!



