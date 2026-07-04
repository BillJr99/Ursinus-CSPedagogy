---
layout: activity
permalink: /Activities/RubricContract
title: "CS352: Computer Science Pedagogy - Rubrics and Contract Grading"


info:
  goals: 
    - To design rubrics that measure individual learning goals across a spectrum
    - To employ contract grading that enables students to start at multiple entry points for growth
  additional_reading:
    - title: "A Unilateral Grading Contract to Improve Learning and Teaching"
      link: "https://scholarworks.umass.edu/cgi/viewcontent.cgi?article=1002&context=eng_faculty_pubs"
    - title: "Techniques for Using Specifications Grading in Computer Science"
      link: "https://dl.acm.org/doi/abs/10.5555/3205191.3205226"  
    - title: "TILT Higher Ed: Transparency in Learning and Teaching"
      link: "https://tilthighered.com/"
  guidingquestions:
    - "What is the benefit of using a rubric to evaluate student work?"
    - "Should a rubric be shared with students prior to completing an assessment?  Why or why not?"
    - "How might it be beneficial to evaluate students using the same rubric multiple times during the year?"
    - "How might contract grading improve communication of expectations?"
    - "How can Bloom's Taxonomy influence the criteria, classifications, and/or descriptions within a rubric?"
    - "Design a rubric, and a grading contract, for a class activity on binary number encodings."
    - "How do rubrics, grading contracts, and the TILT framework each answer a student's question: &quot;what do you actually want from me on this assignment?&quot;"
    
tags:
  - assessment
  
---

## Rubrics
Rubrics are a valuable tool for assessing student work. They provide clear criteria and performance levels for evaluating assignments, projects, or exams. Rubrics not only make grading more transparent and consistent but also offer students a better understanding of what is expected of them. 

Research has shown that rubrics can lead to improved student performance and engagement. Elbow and Danielewicz (reference 1) conducted a study where they implemented a rubric-based grading approach in a writing course. They found that students who received detailed rubrics and ongoing feedback demonstrated enhanced critical thinking and higher quality work. Rubrics allowed for a more holistic evaluation, promoting a deeper understanding of the subject matter.

By utilizing rubrics, educators can provide specific feedback on strengths and areas of improvement, facilitating student learning and growth. Rubrics can also aid instructors in identifying trends or patterns in student performance, allowing for targeted instructional adjustments.

### Rubric Design

When creating rubrics for computer science classrooms, teachers should follow several best practices:

* Align criteria to learning objectives and standards. The rubric criteria should directly connect to the skills and knowledge students are expected to demonstrate based on academic standards and lesson objectives. For a coding project, criteria may include functionality, code quality, documentation, etc.

* Limit the number of criteria. Aim for 3-5 criteria that focus on the most essential skills and knowledge. Too many criteria can overwhelmed students and make the rubric difficult to use efficiently. Prioritize the most important elements.

* Use clear classifications and descriptions. The levels of achievement, often labeled things like "exemplary" or "needs improvement," should have clear, descriptive definitions. Avoid overly broad terms and subjective language. Use concrete details like "code includes comments for every function" or "program crashes during execution."

* Consider starting with 3 classification levels. Beginner-friendly rubrics often have 3 rating levels like "meets expectations," "approaches expectations" and "below expectations." This simplicity provides clear distinction. More advanced rubrics may require 4 levels.

* Adjust rubric and expectations to students' skill levels. While holding students to high standards, make sure the rubric criteria and rating scales match the capabilities of the class. For beginning coders, a rubric may weigh process and effort more heavily than polished functionality.

* Involve students in rubric creation when possible. Asking students to contribute to rubrics can help them better understand expectations. Have them help define what quality work looks like.

### Example

| Criteria          | Excellent                                                                 | Good                                               | Satisfactory                                          | Needs Improvement                                      | Unsatisfactory                                         |
|-------------------|---------------------------------------------------------------------------|----------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|--------------------------------------------------------|
| **Code Structure**    | Clear and well-organized code with proper indentation; no nesting issues. | Minor deficiencies in indentation; one nesting issue. | Code structure shows minor deficiencies; two nesting issues. | Code structure needs significant improvement; three nesting issues. | Code is incoherent or completely lacking structure; four or more nesting issues. |
| **Functionality**     | Program meets all requirements; produces correct output for all test cases. | Meets most requirements; fails 1 test case.        | Meets most requirements; fails 2-3 test cases.        | Program fails to meet several requirements; fails 4-5 test cases. | Program does not run or fails more than 5 test cases.   |
| **Documentation**     | Comprehensive and well-documented code; all functions documented.        | Adequate documentation; 90% of functions documented. | Adequate documentation; 75% of functions documented.  | Documentation is incomplete; 50% of functions documented. | Documentation is unclear or less than 50% documented.   |

The rubric enables you to assess student work across each rubric criterion, calculate a score within a range dictated by each level of attainment, and an opportunity to provide directed feedback as to why each level was selected.

## Contract Grading
Contract grading is an approach that involves students and instructors agreeing upon specific learning outcomes and expectations at the beginning of a course. This collaborative process empowers students to take ownership of their learning journey and actively participate in their assessment.

In a study conducted by [Elbow and Danielewicz](https://scholarworks.umass.edu/cgi/viewcontent.cgi?article=1002&context=eng_faculty_pubs), a unilateral grading contract was implemented, allowing students to set their expectations and define their desired grades. The contract outlined the required work and performance levels for each grade category. This method not only motivated students but also encouraged self-reflection and goal setting.

Contract grading provides a more holistic evaluation of student learning by emphasizing effort, growth, and mastery of learning objectives. It shifts the focus from grades as a means of motivation to learning as the primary goal. However, implementing contract grading requires careful planning, clear communication, and ongoing support to ensure students have a comprehensive understanding of the expectations and assessment criteria.

### Design Considerations

Compared to traditional point-based grading, contract grading can reduce student stress and support learning by focusing on task completion rather than chasing points. Implementing contract grading successfully in computer science involves the following key principles:

* Collaborate with students. Involve students in developing contract grading specs as much as possible to increase engagement and ownership.

* Connect contract items to learning goals. Each contract requirement should directly relate to course objectives and help build essential skills. Avoid busy work.

* Be clear and specific. Provide detailed expectations and due dates for each contract item. Remove ambiguity about what students need to do to earn their targeted grade.

* Scaffold major assignments. Break down large coding projects into smaller milestones with multiple check-ins that support incremental development.

* Offer flexibility and choice. Where possible, give students options between assignment topics or let them customize projects to their interests.

* Focus on learning and improvement. The contract should encourage growth by allowing resubmission of some assignments and emphasizing the iterative coding process.

* Design tiered grade targets. Offer multiple grade tiers (A, B, C) with clear differentiation in contract requirements, not just pass/fail options.

* Regularly review and revise. Seek ongoing student feedback and adjust contract specs to improve clarity, relevance, rigor and support.

### Example

| Criteria          | A (Excellent)                                                           | B (Good)                                            | C (Satisfactory)                                      | D (Needs Improvement)                                 | F (Unsatisfactory)                                    |
|-------------------|-------------------------------------------------------------------------|-----------------------------------------------------|-------------------------------------------------------|-------------------------------------------------------|-------------------------------------------------------|
| **Teamwork**          | All team members contribute equally; effective communication throughout. | Minor communication issues; mostly equal contribution. | Unequal contribution; some communication problems.    | Significant imbalances in contribution; poor communication. | No collaboration or communication among team members.  |
| **Presentation**       | Clear, engaging, and professional; all key points covered.              | Minor issues in clarity or engagement; one key point missed. | Lacks enthusiasm or clarity; two key points missed.  | Disorganized and unprofessional; three key points missed. | Incomplete or incoherent; four or more key points missed. |
| **Documentation**      | Comprehensive, well-organized; all functions documented.               | Minor omissions; 90% of functions documented.        | Lacks detail or organization; 75% of functions documented. | Incomplete documentation; 50% of functions documented. | No or unclear documentation; less than 50% documented.   |
| **Code Quality**       | Proper structure, efficiency, readability; no errors.                   | Minor deficiencies; less than 3 minor errors.       | Significant room for improvement; less than 5 minor errors. | Poor structure and readability; more than 5 errors.   | Incoherent, incorrect, or completely lacking; unrunnable code. |
| **Innovation**         | Highly innovative solution; creative use of technology.                 | Some creative elements; minor innovation.           | Standard solution; limited innovation.                 | Lack of innovation or creativity; follows existing solutions. | No innovation or creativity; copies existing solutions. |

## Transparent Assignment Design: The TILT Framework

Rubrics and contracts make *grading* transparent; the [TILT framework (Transparency in Learning and Teaching)](https://tilthighered.com/) makes the *assignment itself* transparent.  Developed by Mary-Ann Winkelmes and colleagues, TILT research found that when instructors made just two assignments per term transparent, students - and especially first-generation, low-income, and underrepresented students - showed significant gains in academic confidence, sense of belonging, and persistence.  That makes TILT an *equity* practice as much as an assessment practice, and a natural companion to the equitable computing pedagogy at the heart of this course.

A TILTed assignment states three things **before students begin work**:

1. **Purpose**: *Why* am I asking you to do this?  What skills will you practice, what knowledge will you gain, and how does it connect to your longer-term goals (the rest of the course, your career, your life)?
2. **Task**: *What* exactly will you do, and *how*?  What are the steps, and what pitfalls should you avoid?
3. **Criteria**: *What does success look like?*  Provide the rubric or contract in advance - and ideally an annotated example of good work.

Notice how the pieces of this activity fit together: the **Criteria** component is precisely where the rubrics and grading contracts above live.  TILT wraps them with the *why* and the *how* that novices - who cannot yet infer our unstated expectations - need most.  (Meta-note: the activity pages in this course practice this framework: the sidebar goals are the purpose, the models and guided questions are the task, and the rubrics and contracts on assignment pages are the criteria.)

### Before and After: TILTing a CS Assignment

**Before (opaque)**:

> **Homework 3.** Write a Python program that reads a file of temperatures and prints the average, minimum, and maximum.  Due Friday.  10 points.

The task is clear to the *instructor*, who knows why file I/O matters, remembers the edge cases, and has an implicit rubric.  The student who has never seen our expectations must guess at all of it.

**After (TILTed)**:

> **Homework 3: Weather Station Statistics.**
>
> **Purpose**: Real programs rarely have their data typed into the code; they read it from files.  This assignment gives you practice with file input, accumulator loops (from Unit 2), and defensive programming.  These same patterns appear in every data-processing task you will do this year, including your final project.
>
> **Task**: Write a Python program that (1) opens `temps.txt`, (2) reads one temperature per line, (3) computes and prints the average, minimum, and maximum.  Suggested steps: start by printing each line; then convert to numbers; then add the statistics one at a time, testing after each.  *Common pitfalls*: forgetting to convert strings to floats; assuming the file is non-empty; dividing by zero.  You may work with a partner using the pair programming roles we practiced.
>
> **Criteria**: Full credit requires: correct statistics on our three test files (6 pts), graceful handling of an empty file (2 pts), and descriptive variable names with a comment per function (2 pts).  See the attached rubric and an annotated example solution to a *similar* problem (word counts) so you can see what "graceful" and "descriptive" mean in practice.

Same assignment, same rigor - but the second version distributes the instructor's insider knowledge to every student, not just those with the background to guess it.

### Checklist: TILTing One of Your Own Assignments

Take an assignment you have written (your UbD lesson plan's performance task, a lab from a class you have taken, or one of mine!) and TILT it using this checklist:

* **Purpose**
  * [ ] Names the specific skills students will practice
  * [ ] Names the knowledge/concepts the work will build
  * [ ] Connects the work to something beyond this assignment (course goals, later units, authentic practice)
* **Task**
  * [ ] States what to do and how to begin
  * [ ] Breaks large work into suggested steps or milestones
  * [ ] Warns about known pitfalls and clarifies what help/collaboration is allowed
* **Criteria**
  * [ ] Includes the rubric or contract *with* the assignment, not after
  * [ ] Defines success in observable terms (echo your Bloom verbs!)
  * [ ] Provides or points to an annotated example of quality work
* **Accessibility check (UDL tie-in)**
  * [ ] A student who missed class could still understand the assignment from the document alone
  * [ ] Language is free of unexplained jargon and idioms

Exchange your TILTed assignment with a partner and review each other's work against the checklist: could you complete the assignment, and predict your grade, using only the document in front of you?
