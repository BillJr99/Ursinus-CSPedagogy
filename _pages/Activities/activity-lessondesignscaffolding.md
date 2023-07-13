---
layout: activity
permalink: /Activities/CSLessonDesign/Scaffolding
title: "CS471: Computer Science Pedagogy - CS Lesson Design: Scaffolding"
excerpt: "CS471: Computer Science Pedagogy - CS Lesson Design: Scaffolding"

info:
  goals: 
    - To explain the concept of scaffolding in the context of teaching and learning
    - To design computing lessons that supply and gradually remove scaffolding as the learner progresses
        
tags:
  - cseducation
  
---

## Scaffolding in CS Education and Pedagogy

Scaffolding is a pedagogical approach that helps students progress in their learning process by gradually removing support mechanisms as they gain proficiency. In computer science (CS) and specifically Python programming, it's about providing students with initial support or 'scaffolds' that help them solve complex problems.

### What is Scaffolding?

Scaffolding is a teaching method that involves providing students with temporary support structures that help them accomplish tasks that they couldn't otherwise do. The goal is to gradually remove these supports, allowing students to perform tasks independently. It's based on Vygotsky's Zone of Proximal Development (ZPD), which refers to the range of tasks that are too difficult for students to master alone but can be mastered with guidance and assistance from a teacher or more competent peers.

### Why is Scaffolding Important in CS Education?

Programming can be challenging for beginners due to abstract concepts and complex syntax. Scaffolding allows beginners to focus on learning concepts step by step, with less focus on the syntax. It allows students to learn and build confidence gradually, which leads to better engagement and retention.

### How to Implement Scaffolding in Python Programming Education

#### Step-by-Step Instructions

Beginners might struggle to understand a complex code at once. Breaking it down into smaller steps with clear instructions can help them grasp the logic more effectively. For example, when teaching a function to sort a list:

```python
def bubble_sort(list):
    for i in range(len(list)):
        for j in range(len(list) - 1):
            if list[j] > list[j + 1]:
                list[j], list[j + 1] = list[j + 1], list[j]
    return list
```

Before diving into this complex function, you could start with explaining smaller parts, like how to swap two elements in a list:

```python
# Explain this first
a, b = b, a
```

Then move to how to compare two adjacent elements, and finally to the whole sorting function.

#### Partial Code Examples

Providing partial codes allows students to understand a code structure without being overwhelmed by the entire code at once. It also encourages them to think about the remaining part of the code. For example:

```python
def greet(name):
    # TODO: Complete this function to print 'Hello, {name}!'
    pass
```

#### Think-Pair-Share 

Use pair programming as a scaffolding method, where one student 'drives' (codes) and the other 'navigates' (provides strategic direction). Afterward, they can share their approach and code with the rest of the class.

### Conclusion

Scaffolding is an essential aspect of pedagogy that can be used to effectively teach Python programming, or any other programming language, to beginners. By gradually reducing the level of support, we can help students gain confidence in their abilities and foster a deep understanding of programming concepts.
