# Python Data Structures Review

started on December 27, 2023

The purpose of this repo is to track and store study and practice materials for python data structures

1. Basic Data Structures

- Lists: Dynamic arrays, useful for storing an ordered collection of items.
- Tuples: Immutable sequences, used for fixed collections of items.
- Sets: Unordered collections of unique elements, useful for membership testing, removing duplicates.
- [DONE] Dictionaries: Key-value pairs, highly efficient for lookup operations.

2. Advanced Data Structures

- Stacks: LIFO (Last In, First Out) structure, typically implemented using lists.
- Queues: FIFO (First In, First Out) structure, can be implemented with collections.deque.
- Priority Queues: Abstract data type similar to a regular queue but where each element has a priority.
- Heaps: Often used to implement priority queues, available in Python as heapq.
- Linked Lists: A sequence of nodes where each node points to the next node.
- Trees: Hierarchical data structure, including binary trees, binary search trees, AVL trees, etc.
- Graphs: Consists of nodes (vertices) connected by edges, useful in various algorithms.

3. Special Collections in Python's collections Module

- namedtuple: Factory function for creating tuple subclasses with named fields.
- deque: A double-ended queue, supports memory-efficient and fast appends/pops from both sides.
- Counter: A dict subclass for counting hashable objects.
- [DONE] defaultdict: Similar to the standard dictionary but with a default value for missing keys.
- [DONE] OrderedDict: Dictionary that maintains the order in which items are added.

4. String Manipulation

String Basics

- Concatenation: Combining strings together (str1 + str2).
- Slicing: Extracting a part of a string (str[1:5]).
- Indexing: Accessing individual characters (str[index]).  
  String Methods
- replace(): Replacing a substring within a string.
- split(): Splitting a string into a list of substrings based on a delimiter.
- join(): Joining a list of strings into a single string with a separator.
- strip(), rstrip(), lstrip(): Removing whitespaces or specified characters from the start and/or end of a string.
- upper(), lower(), capitalize(), title(): Changing the case of a string.  
  String Formatting
- String Interpolation: Using f-strings (formatted string literals) or str.format().
- Old-style Formatting: Using % operator.  
  Searching and Substrings
- find()/index(): Finding the position of a substring.
- count(): Counting occurrences of a substring.
- Regular Expressions: Using the re module for complex string patterns.
  Character and String Testing
- isdigit(), isalpha(), isalnum(), isspace(): Testing types of characters in strings.
- String Comparison: Comparing strings lexicographically.
  String Transformations
- Reversing a String: Using slicing (str[::-1]).
- Removing Characters: Using replace() or string comprehension.
- String Translation: Using str.translate() and str.maketrans() for complex replacements.
  String Parsing
- Parsing and Converting: Extracting numbers or data and converting between strings and other data types.
  Advanced Manipulations
- Unicode Handling: Working with Unicode characters.
- Encoding/Decoding: Converting between strings and bytes.

5. Other Structures and Concepts

- Bitwise Operations: Useful for problems involving binary numbers.
- Dynamic Programming/Memoization: Techniques often involving arrays or dictionaries to optimize recursive algorithms.
