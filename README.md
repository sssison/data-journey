# 📊 Personal Developer Road Map Focused on Data Science and Data Analytics

As a recent graduate, I want to be able to continuously upskill in the field of data. I got inspired by Ken Jee's #66DaysOfData challenge. So, this repository will serve as the documentation of my own version of the challenge.

## 💻 Tech Stack

- Python

## 📁 Projects

## 📅 Timeline

### <mark style="background-color: #344966"> Day 01: Reviewing Python </mark>

Today, I went back through my EEE 111 syllabus to refamiliarize myself about the basics of programming using python. I also used W3Schools as a reference. To give myself some structure and some test, I followed the Introduction to Python course of Datacamp.

Some of the topics that I refreshed were:
1. Variables: Naming Scheme, Assignment
2. Datatypes: Primitive Datatypes, Typecasting,
3. String Operations: Slicing, Methods, Escape Characters,
4. Boolean
5. Operators: Arithmetic, Bitwise
6. Loops and Conditionals: If-else, Switch-case, For, While, 

I think that's it for now. I might get into some data structures later, particularly lists, array, tuples, and dictionary as a precursor to the actual DSA that I will get into tomorrow or maybe I'll follow it up with OOP first before the aactual DSA.

### <mark style="background-color: #344966"> Day 02: Data Structers and Algorithms Pt. 1 (Arrays, Linked Lists) </mark>

After refreshing the basics of python programming, I delved into DSA. The main DSA that I want to recall is about Arrays, Linked Lists, Stacks, Queues, Hash Tables, Trees, and Graphs, which would help me improve my solutions towards Leetcode problems and recall time and space complexity. For today, I focused on Arrays and Linked Lists. For arrays, its basically just a python list. While the DSA part of the website in W3schools did not include the time complexity operations, I looked through other resources. The image below shows the time complexity of all linked lists.
<!-- Insert array operation complexity here -->
![l56sp](https://github.com/sssison/data-journey/assets/63900699/cc46e3e9-0abf-45f5-b6cd-ddbdb2e5e0a8)


I also recalled the different sorting algorithms:
1. Bubble Sort - Iterates each element and swap if the current element is greater than (or less than) the next element. Iterate only until n-1.
2. Selection Sort - Iterates over all the elements and takes note of the least (or greatest) value. After iterating, swap it to the current index.
3. Insertion Sort - Keeps track of the current sorted part of the list. For each element in the array, insert it into its correct place in the sorted part of the list.
4. Quick Sort - A recursive sorting algorithm that uses a pivot point. Values less than the pivot point are in the left partition while values greater than the pivot point are put in the right partition. Call quicksort again for each partition until the partitions are small enough to be considered sorted.
5. Counting Sort - Keeps track of the frequency count for each item in the list. After getting the frequency count, return the sorted list by generating it using the frequency count.
6. Radix Sort - Sort the digits by each radix point starting from the least significant bit to the most significant bit. This can be implemented through a hash map with stack data structure.
7. Merge Sort - A divide and conquer algorithm. The list is broken up into smaller sub-lists and merged together. Uses two function calls, the main mergeSort function to divide the arrays into two sub-arrays and a merge function that merges the sub-arrays.

In addition, I also recalled two searching algorithms: Binary Search and Linear Search.
1. Linear Search - Searches through all the elements of the array in a linear fashion until the desired element is seen. This is best used for an unsorted list.
2. Binary Search - Requires the use of a sorted list. If the desired element is less than the middle of the array, use the left side of the array otherwise use the right side of the array. Do these until the desired element is seen.

The Array data structure is one of the simplest data structures that we normally use. It is so versatile. The other one is linked lists, which is basically just an array but with multiple nodes. A node is its simplest element containing the data and a pointer to the next value or the previous value. Typically, linked lists are used if the memory allocation needed is dynamic. Arrays have fixed size while linked lists can be dynamic with its size. Another main benefit of using linked lists is its constant time in deleting and inserting new data. In arrays, the shifting of other elements is required.

That's it for today! Tomorrow I'll focus on Stacks, Queues, and Hash Tables!
