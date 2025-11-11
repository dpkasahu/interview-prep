1️⃣ What is Python?
--------------------------------
Answer:
Python is a high-level, interpreted, and object-oriented programming language known for its simplicity and readability.
-------------------------------------------------
2️⃣ What are the main features of Python?
------------------------------------------
Answer:
Easy to learn and read
Interpreted language
Dynamically typed
Object-oriented
Extensive standard libraries
Cross-platform
Open-source and free
Portable and embeddable
High-level language
Large community support
-----------------------
3️⃣ Who developed Python and when?

Answer:
Python was developed by Guido van Rossum in 1991.
---------------------
4️⃣ What are identifiers in Python?

Answer:
Identifiers are names used to identify variables, functions, classes, or other objects in Python.
They must follow rules:

Can contain letters, digits, and underscores

Cannot start with a digit

Case-sensitive

Cannot use special symbols or keywords.
--------------------
5️⃣ What is Python garbage collection?

Answer:
Garbage collection in Python automatically frees memory by removing unused objects.
It mainly works through reference counting and the gc module to clean up cyclic references.
----------------
6️⃣ What are Python keywords?

Answer:
Keywords are reserved words in Python that have predefined meanings (like if, else, while, class, etc.). They cannot be used as identifiers.
--------
7️⃣ What is a Data Type in Python?

Answer:
A data type in Python defines the type of value a variable can hold and determines what operations can be performed on that value.
Python is dynamically typed, meaning you don’t need to declare the data type explicitly — it’s assigned automatically when you give a value.
1. Numeric Data Types = int,float,complex
2. Sequence Data Types = string, list, tuple
3. Set Data Types = set
4. Mapping Data Types = dict
5. Boolean Data Types = bool
--------------------------------------

8️⃣ What is the difference between List and Tuple in Python?
     	List	                                                   Tuple
	    A list is an ordered, mutable collection of items.	A tuple is an ordered, immutable collection of items.
    	Created using square brackets []	                Created using parentheses ()
    	Mutable — items can be changed, added, or removed.	Immutable — items cannot be changed once created.
	    fruits = ["apple", "banana", "mango"]	            colors = ("red", "green", "blue")
        Slower due to mutability.	                        Faster as it’s immutable.
        Consumes more memory.	                            Consumes less memory.
     	Has many methods append(), remove(), sort()	        Limited methods (count(), index()).
        When data may need modification.                 	When data should remain constant.



-----------------------------------------------------------------------------------------------
9️⃣ What are String Methods in Python?
--------------------------------------------------
Method	Description	Example
upper()	Converts all characters to uppercase	                     "python".upper() → "PYTHON"
lower()	Converts all characters to lowercase	                     "HELLO".lower() → "hello"
title()	Converts first letter of each word to uppercase	             "hello world".title() → "Hello World"
capitalize()	Capitalizes the first character	                      "python".capitalize() → "Python"
swapcase()	Swaps lowercase to uppercase and vice versa	                 "PyThOn".swapcase() → "pYtHoN"
casefold()	Stronger version of lower() for case-insensitive matching	"PYTHON".casefold() → "python"
strip()	Removes whitespace from both ends	                            " hello ".strip() → "hello"
lstrip()	Removes whitespace from the left side                   	" hello".lstrip() → "hello"
rstrip()	Removes whitespace from the right side	                      "hello ".rstrip() → "hello"
replace(old, new)	Replaces substring with another string	               "good day".replace("good", "great") → "great day"
split()	Splits string into a list (default by space)	                   "a b c".split() → ['a', 'b', 'c']
splitlines()	Splits string by line breaks	                          "a\nb\nc".splitlines() → ['a','b','c']
join()	Joins iterable elements into one string                         	" ".join(['a','b','c']) → "a b c"
find()	Returns first index of substring (-1 if not found)              	"apple".find("p") → 1
rfind()	Returns last index of substring	                                     "apple".rfind("p") → 2
index()	Like find(), but raises error if not found	                     "apple".index("p") → 1
rindex()	Like rfind(), but raises error if not found	                  "apple".rindex("p") → 2
count()	Counts occurrences of a substring	                              "banana".count("a") → 3
startswith()	Checks if string starts with given value	                  "python".startswith("py") → True
endswith()	Checks if string ends with given value                      	"python".endswith("on") → True
isalpha()	True if all characters are alphabets	                     "abc".isalpha() → True
isdigit()	True if all characters are digits	                          "123".isdigit() → True
isalnum()	True if all characters are alphabets or digits	                 "abc123".isalnum() → True
isspace()	True if all characters are whitespace                      	" ".isspace() → True
isupper()	True if all characters are uppercase	                     "HELLO".isupper() → True
islower()	True if all characters are lowercase	                     "hello".islower() → True
istitle()	True if each word starts with uppercase	                       "Hello World".istitle() → True
center(width, char)	Centers string with padding	                          "hi".center(6, "*") → "**hi**"
ljust(width, char)	Left-aligns string with padding                     	"hi".ljust(5, "-") → "hi---"
rjust(width, char)	Right-aligns string with padding                    	"hi".rjust(5, "-") → "---hi"
zfill(width)	Pads number with zeros on the left	                       "42".zfill(5) → "00042"
encode()	Encodes string to bytes	                                       "hello".encode() → b'hello'
format()	Inserts values into placeholders {}	                           "My name is {}".format("Chitra") → "My name is Chitra"
format_map()	Uses dictionary to format strings	                       "Hi {name}".format_map({'name':'Riya'}) → "Hi Riya"
partition()	Splits string into 3 parts around a separator	                "hello world".partition(" ") → ('hello',' ','world')
rpartition()	Like partition(), but splits from right side	            "hello world hi".rpartition(" ") → ('hello world',' ','hi')
expandtabs()	Replaces tabs with spaces	                                "H\tE\tL\tO".expandtabs(2) → "H E L O"
-----------------------------------------------------------------------------------------------
🔟 What are List Methods in Python?

List methods are built-in functions used to perform operations like adding, removing, or modifying elements in a list.

Method	Description	Example
append(x)	Adds an element x to the end of the list.	fruits.append("mango")
extend(iterable)	Adds all elements of an iterable (like list, tuple, etc.) to the end.	fruits.extend(["grape", "melon"])
insert(i, x)	Inserts element x at index i.	fruits.insert(1, "banana")
remove(x)	Removes the first occurrence of element x.	fruits.remove("apple")
pop([i])	Removes and returns element at index i (last if not given).	fruits.pop()
clear()	Removes all elements from the list.	fruits.clear()
index(x)	Returns the index of first occurrence of x.	fruits.index("banana")
count(x)	Returns how many times x appears in the list.	nums.count(2)
sort()	Sorts the list in ascending order (modifies original list).	nums.sort()
sorted(list)	Returns a new sorted list without changing the original.	sorted(nums)
reverse()	Reverses the order of the list (in place).	nums.reverse()
copy()	Returns a shallow copy of the list.	new_list = nums.copy()
---------------------------------------------------
1️⃣1️⃣ What are Tuple Methods in Python?

Tuples are immutable, meaning their elements cannot be changed once created.
So, Python provides very few methods for tuples.

Method	Description	Example
count(x)	Returns how many times x appears in the tuple.	numbers.count(2)
index(x)	Returns the index of the first occurrence of x.	numbers.index(5)
-----------------------------------------------
1️⃣2️⃣ What are Set Methods in Python?

A set is an unordered collection of unique elements.
Python provides several methods to perform operations like union, intersection, and difference.

Method	Description	Example
add(x)	Adds element x to the set.	fruits.add("apple")
update(iterable)	Adds multiple elements to the set.	fruits.update(["banana", "cherry"])
remove(x)	Removes element x; raises error if not found.	fruits.remove("apple")
discard(x)	Removes element x if present; no error if not found.	fruits.discard("apple")
pop()	Removes and returns a random element.	fruits.pop()
clear()	Removes all elements from the set.	fruits.clear()
union(other)	Returns a set containing all unique elements from both sets.	A.union(B)
intersection(other)	Returns a set of common elements.	A.intersection(B)
difference(other)	Returns elements present in A but not in B.	A.difference(B)
symmetric_difference(other)	Returns elements not common to both sets.	A.symmetric_difference(B)
issubset(other)	Checks if all elements of set A are in B.	A.issubset(B)
issuperset(other)	Checks if all elements of B are in A.	A.issuperset(B)
isdisjoint(other)	Checks if sets have no common elements.	A.isdisjoint(B)
---------------------------------------------------
1️⃣3️⃣ What are Dictionary Methods in Python?

A dictionary stores data in key-value pairs.
Python provides many methods to add, remove, and access dictionary items.

Method	Description	Example
get(key)	Returns value of the key, or None if not found.	student.get("name")
keys()	Returns all keys in the dictionary.	student.keys()
values()	Returns all values in the dictionary.	student.values()
items()	Returns key-value pairs as tuples.	student.items()
update(other_dict)	Updates dictionary with elements from another dictionary.	student.update({"age": 22})
pop(key)	Removes item with given key.	student.pop("name")
popitem()	Removes and returns the last key-value pair.	student.popitem()
clear()	Removes all items from the dictionary.	student.clear()
copy()	Returns a shallow copy of the dictionary.	new_dict = student.copy()
setdefault(key, value)	Returns value of key; inserts key with value if not present.	student.setdefault("city", "Delhi")
fromkeys(keys, value)	Creates a new dictionary with given keys and same value.	dict.fromkeys(['a','b'], 0)
--------------------------------------------------------------------------
1️⃣4️⃣ Difference Between Set and Dictionary in Python

In Python, sets and dictionaries both use curly braces {}, but they serve very different purposes.
A set is an unordered collection of unique elements. It only stores values, not key-value pairs. Sets are useful when you want to eliminate duplicates or perform mathematical operations like union, intersection, and difference. For example, {1, 2, 3} represents a set with three unique values.

A dictionary, on the other hand, stores data as key-value pairs. Each key must be unique, but values can repeat. Dictionaries allow quick access to values using their keys, such as student["name"]. They are ideal when you need to map one piece of data to another — for instance, storing student names with their marks: {"Alice": 85, "Bob": 90}.

In short, a set holds unique items, while a dictionary holds relationships between keys and values.
----------------------------------
