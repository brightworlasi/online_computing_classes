## Quiz 8 [Answers]


## PART 1: Python
**1. Describe what is meant by an array in programming.**   
**Ans**: An array is a data structure that stores a collection of elements of the same type in a contiguous block of memory, accessed using an index or                 position number.

**2. What is meant by "zero-based indexing"? Use an example.**  
**Ans**: This means the counting of elements starts at 0 rather than 1. For example, in a list [10, 20, 30], the first element (10) is at index 0. OR                   Zero-based indexing means the first element in an array is at position 0, not position 1. For example, in the array fruits = ["apple", "banana",               "orange"],"apple" is at index 0, "banana" at index 1, and "orange" at index 2.

**3. In the Python program below, what will be the output and why?**
    names = ["Ama", "Kojo", "Yaw", "Esi"]
    print("The second name is:", names[1])
    names[1] = "Kwame"
    print(names[1])

  **Ans**: _The output will be:_  
     The second name is: Kojo  
     Kwame  
     **Reason**: The code first prints the element at index 1 ("Kojo"). It then updates index 1 to "Kwame" and prints the new value.

**4. Write a Python code to create an array called students containing five student names.**  
   **Ans**: students = ["Ama", "Esi", "Yawa", "Aku", "Afi"] **OR** students = ["Alice", "Bob", "Charlie", "David", "Eve"]

**5. Given the Python array(list) scores = [78, 82, 65, 90, 73], write a Python code to print the total number of scores in the array.**  
   **Ans**: print(len(scores))
   The built-in **len()** function calculates and returns the number of elements in an object. The object must be a sequence or collection type that has a      defined length, such as a list, string, tuple, or dictionary.

**6. What would happen if you tried to execute print(scores[5]) on the scores array [54, 32, 63, 74, 56]? Explain why this error occurs.**    
   **Ans**: An IndexError would occur with the message "list index out of range". This happens because the array has only 5 elements (indices 0-4), but         we're trying to access index 5, which doesn't exist.

## PART 2: C++
_**Instructions: Answer questions 7 to 10 based on the C++ code provided.**_  
[![](/assets/images/cplusplus.png)](https://github.com/brightworlasi/online_computing_classes_y2/blob/main/cplusplus.png?raw=true)

**7. What would be the result of cout << scores[1]; be?**  
**Ans**: 70  

**8. Which array in the code stores text (string) values?**  
**Ans**: studentNames  

**9. How many elements can the newScores array store? What happens to the unused elements in it?**   
**Ans**: The newScores array can store 7 elements. The unused elements (positions 3-6) are automatically initialized to 0.  

**10. What is the index of the first element in every array in C++?**   
**Ans**: 0  

