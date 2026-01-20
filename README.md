# EXP-2-LIST-IN-PYTHON-25070123161
NAME - SAUMYA SHREE
PRN:25070123161

AIM - To study and implement various operations on Lists in Python, including creation, indexing, slicing, and the use of built-in list methods and functions.

ALGORITHM - 

The following logic was implemented across the code cells:

1. Initialization: Define lists using square brackets `[]` containing strings, integers, or mixed data types.
2. Accessing Elements:
   Use `list[index]` for specific elements.
   Use `list[start:end]` for slicing sub-lists.
3. Expansion:
   Add a single element to the end using `.append()`.
   Add an element at a specific position using `.insert()`.
   Combine two lists using `.extend()`.
4. COMMANDS : Calculate statistics on numerical lists using sum(), max(), min(), sorted().
5. For calculating the average first we declared a variable where we stored sum(list)/len(list) and then we printed the result 
6. Remove specific items from a list using `.remove()`.

THEORY - 
1. Indexing and Slicing

The experiment showcases how to retrieve data from the front and back of a list:

    Positive Index: list4[2] (Third element).

    Negative Index: list4[-3] (Third element from the end).

    Slicing: list4[1:4] (Elements from index 1 to 3).

2. List Methods
Method	Description
append(x)	Adds element x to the end of the list.
insert(i, x)	Inserts element x at index i.
extend(iterable)	Appends all elements from another list.
remove(x)	Deletes the first occurrence of x.

3. Mathematical Applications

For a list of marks [80, 82, 66, 76, 83], the script calculates:

    Total: sum(marks)

    Average: sum(marks) / len(marks)

    Sorting: sorted(marks) (Ascending order)

Example Execution: Grocery List

The project concludes with a practical application:

    Initial List: ['Rice', 'Wheat', 'Flour', 'Sugar', 'Bread']

    Action: Append "Vegetables", Remove "Sugar" and "Bread".

    Result: ['Rice', 'Wheat', 'Flour', 'Vegetables']
    
CONCLUSION -This experiment successfully demonstrated the creation, manipulation, and analysis of Python lists, proving their versatility as mutable containers for managing diverse data types through built-in methods and functions.



