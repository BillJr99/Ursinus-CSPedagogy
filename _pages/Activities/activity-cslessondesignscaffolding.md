---
layout: activity
permalink: /Activities/CSLessonDesign/Scaffolding
title: "CS471: Computer Science Pedagogy - Computer Science Lesson Design: Scaffolding"
excerpt: "CS471: Computer Science Pedagogy - Computer Science Lesson Design: Scaffolding"

info:
  goals:
    - To develop scaffolding as appropriate to provide multiple entry points for students to engage with an activity

tags:
  - scaffolding

---

### Quicksort Algorithm Implementation in Python

#### Objective
Implement the quicksort algorithm in Python to sort a list of integers.

#### Instructions

##### For Beginner Students:
1. **Understanding Quicksort**: Read about the quicksort algorithm and understand how it works, focusing on the partitioning process and recursion.
2. **Scaffolding Code**: Use the following code snippet as a starting point:

   ```python
   def partition(arr, low, high):
       # TODO: Choose a pivot element
       # TODO: Rearrange the elements around the pivot
       # TODO: Return the pivot index
       pass

   def quicksort(arr, low, high):
       if low < high:
           # TODO: Call the partition function
           # TODO: Recursively call quicksort on left and right subarrays
       return arr
   ```

3. **Guided Steps**:
   - **Partition Function**:
     - Choose a pivot element (e.g., the last element in the current subarray).
     - Rearrange the elements so that elements less than the pivot are on the left, and elements greater than the pivot are on the right.
     - Return the index of the pivot.
   - **Quicksort Function**:
     - Call the partition function to partition the current subarray.
     - Recursively call quicksort on the left and right subarrays.
   - **Testing**: Test your code with a sample list, such as `[3, 6, 8, 10, 1, 2, 1]`.

##### For Intermediate Students:
1. **Understanding Quicksort**: Ensure you understand the quicksort algorithm, including partitioning and recursion.
2. **Scaffolding Code**: Use the following code snippet as a starting point:

   ```python
   def partition(arr, low, high):
       # TODO: Implement the partitioning logic
       return pivot_index

   def quicksort(arr, low, high):
       # TODO: Implement the recursive calls
       return arr
   ```

3. **Guided Steps**:
   - Implement the partitioning logic inside the `partition` function.
   - Implement the recursive calls inside the `quicksort` function.
   - Test your code with different lists.

##### For Advanced Students (Extensions):
1. **Optimizations**: Implement a version of quicksort that chooses the pivot in different ways (e.g., median of three).
2. **Time Complexity Analysis**: Analyze the time complexity of your implementation and compare it with other sorting algorithms.
3. **Visualization Tool**: Create a visualization tool that shows the sorting process step by step.

#### Assessment
- **Code Quality**: Your code should be well-commented, and variables should have meaningful names.
- **Functionality**: Your implementation should correctly sort the given list.
- **Understanding**: You may be asked to explain your code and the quicksort algorithm.

#### Submission
Submit your Python file through the designated platform.

#### Resources
- [Quicksort Algorithm Explanation](https://en.wikipedia.org/wiki/Quicksort)
- [Python Documentation](https://docs.python.org/3/)

---
