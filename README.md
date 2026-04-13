# python-algorithm-lab.
README.md
Python Algorithm Lab Assignment


 The Phonebook Mental Model

Linear Search: You start at page 1 and read every name. If "Simba" is on the last page, how many names did you check.
Binary Search: You open the book to the exact middle. "Simba" must be in the second half. You ignore the first half and open the remainder to the middle again.
"How many steps does Binary Search take for 1 million items?" 
Binary search take 20 steps for 1 million items.
Dictionaries: The VIP Pass
What is a key and a value in python?

Key
A key is the identifier used to access a value in a dictionary.It must be unique within a dictionary (no two entries share the same key) and hashable (immutable types like int, float, str, tuple, etc.).Example: in {"name": "Alice", "age": 30}, the keys are "name" and "age".
Value
A value is the data associated with a key.It can be any Python object (string, number, list, another dictionary, a custom object, etc.)Example: in {"name": "Alice", "age": 30}, the values are "Alice" and 30.

The Difference: In a List, you find things by their position (index). In a Dictionary, you find things by a unique "Key" (like a name).
Why is a Dictionary faster than a List when looking up a specific person?
A dictionary is faster because it uses keys to directly access  data , while a list requires searching  through items one by one.

