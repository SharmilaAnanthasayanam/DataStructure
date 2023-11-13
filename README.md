# DataStructure
```python
class Stack:
  def __init__(self):
    self.value = []
    self.limit = 10
    
  def push(self,val):
    if len(self.value)< self.limit:
      self.value.append(val)
    else:
      print("Stack Overflow")
  
  def pop(self):
    if len(self.value)>0:
      self.value.pop()
    else:
      print("Stack Underflow")
      
  def display(self):
    print(self.value)
```
