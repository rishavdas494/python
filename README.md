### Dictionaries in Python

186. **What is a dictionary in Python?**
     A dictionary is an unordered collection of key-value pairs, where each key is unique:

```python
my_dict = {'name': 'John', 'age': 30}
```

187. **How do you create a dictionary in Python?**
     A dictionary is created using curly braces `{}` with key-value pairs:

```python
my_dict = {'key1': 'value1', 'key2': 'value2'}
```

188. **How do you access values in a dictionary?**
     You can access values using their keys:

```python
my_dict = {'name': 'John', 'age': 30}
print(my_dict['name'])  # John
```

189. **How do you add an item to a dictionary?**
     You can add an item by assigning a value to a new key:

```python
my_dict = {'name': 'John'}
my_dict['age'] = 30
print(my_dict)  # {'name': 'John', 'age': 30}
```

190. **How do you update an item in a dictionary?**
     You can update a dictionary item by assigning a new value to an existing key:

```python
my_dict = {'name': 'John', 'age': 30}
my_dict['age'] = 31
print(my_dict)  # {'name': 'John', 'age': 31}
```

191. **How do you remove an item from a dictionary?**
     You can remove an item using `del`, `pop()`, or `popitem()`:

```python
my_dict = {'name': 'John', 'age': 30}
del my_dict['age']
print(my_dict)  # {'name': 'John'}
```

192. **How do you check if a key exists in a dictionary?**
     You can use the `in` operator to check if a key exists:

```python
my_dict = {'name': 'John', 'age': 30}
print('name' in my_dict)  # True
```

193. **What is the get() method used for in dictionaries?**
     The `get()` method retrieves the value for a given key, returning `None` if the key is not found:

```python
my_dict = {'name': 'John', 'age': 30}
print(my_dict.get('name'))  # John
print(my_dict.get('address'))  # None
```

194. **How do you get all keys from a dictionary?**
     You can use the `keys()` method to get all the keys:

```python
my_dict = {'name': 'John', 'age': 30}
print(my_dict.keys())  # dict_keys(['name', 'age'])
```

195. **How do you get all values from a dictionary?**
     You can use the `values()` method to get all the values:

```python
my_dict = {'name': 'John', 'age': 30}
print(my_dict.values())  # dict_values(['John', 30])
```

196. **How do you iterate over a dictionary?**
     You can iterate over keys, values, or key-value pairs using a `for` loop:

```python
my_dict = {'name': 'John', 'age': 30}
for key, value in my_dict.items():
    print(key, value)
```

197. **What is the difference between items(), keys(), and values() in a dictionary?**

* `items()` returns a list of key-value pairs.
* `keys()` returns a list of keys.
* `values()` returns a list of values.

198. **How do you merge two dictionaries?**
     You can use the `update()` method or the `**` unpacking operator:

```python
dict1 = {'name': 'John'}
dict2 = {'age': 30}
dict1.update(dict2)
# or
merged_dict = {**dict1, **dict2}
```

199. **What is the pop() method in dictionaries?**
     The `pop()` method removes and returns the value for the specified key:

```python
my_dict = {'name': 'John', 'age': 30}
value = my_dict.pop('age')  # 30
print(my_dict)  # {'name': 'John'}
```

200. **How do you create a dictionary with default values?**
     You can use the `defaultdict` class from the `collections` module, or the `get()` method with a default value:

```python
from collections import defaultdict
my_dict = defaultdict(int)
print(my_dict['non_existing_key'])  # 0

# Or with get():
my_dict = {'name': 'John'}
print(my_dict.get('age', 25))  # 25 (default value)
```

---

These are the answers for your questions about lists, tuples, and dictionaries. Let me know if you'd like further explanations or examples!
