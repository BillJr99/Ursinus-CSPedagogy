---
layout: activity
permalink: /Activities/RubricContract
title: "CS471: Computer Science Pedagogy - Rubrics and Contract Grading"
excerpt: "CS471: Computer Science Pedagogy - Rubrics and Contract Grading"

info:
  goals: 
    - To design rubrics that measure individual learning goals across a spectrum
    - To employ contract grading that enables students to start at multiple entry points for growth
        
tags:
  - assessment
  
---

## Assessing Learning: Rubrics and Contract Grading
As educators, the assessment of student learning is a critical aspect of our teaching practice. Traditional grading methods often fail to provide meaningful feedback and can sometimes hinder student growth. In recent years, alternative approaches such as rubrics and contract grading have gained attention for their potential to enhance learning outcomes. We will explore these two assessment techniques and examine their benefits and challenges. Additionally, we will summarize key findings from the following references: 

1. Reading: "A Unilateral Grading Contract to Improve Learning and Teaching" by Elbow and Danielewicz.
    - URL: [https://scholarworks.umass.edu/cgi/viewcontent.cgi?article=1002&context=eng_faculty_pubs](https://scholarworks.umass.edu/cgi/viewcontent.cgi?article=1002&context=eng_faculty_pubs)
2. Reading: "Techniques for Using Specifications Grading in Computer Science".
    - URL: [https://dl.acm.org/doi/abs/10.5555/3205191.3205226](https://dl.acm.org/doi/abs/10.5555/3205191.3205226)

## Rubrics
Rubrics are a valuable tool for assessing student work. They provide clear criteria and performance levels for evaluating assignments, projects, or exams. Rubrics not only make grading more transparent and consistent but also offer students a better understanding of what is expected of them. 

Research has shown that rubrics can lead to improved student performance and engagement. Elbow and Danielewicz (reference 1) conducted a study where they implemented a rubric-based grading approach in a writing course. They found that students who received detailed rubrics and ongoing feedback demonstrated enhanced critical thinking and higher quality work. Rubrics allowed for a more holistic evaluation, promoting a deeper understanding of the subject matter.

By utilizing rubrics, educators can provide specific feedback on strengths and areas of improvement, facilitating student learning and growth. Rubrics can also aid instructors in identifying trends or patterns in student performance, allowing for targeted instructional adjustments.

```python
# Example Rubric for Programming Assignment

rubric = {
  "Code Structure": {
    "Excellent": "Clear and well-organized code with proper indentation.",
    "Satisfactory": "Code structure shows minor deficiencies.",
    "Needs Improvement": "Code structure needs significant improvement.",
  },
  "Functionality": {
    "Excellent": "Program meets all requirements and produces correct output.",
    "Satisfactory": "Program meets most requirements, but with minor issues.",
    "Needs Improvement": "Program fails to meet several requirements.",
  },
  "Documentation": {
    "Excellent": "Comprehensive and well-documented code.",
    "Satisfactory": "Adequate documentation, but with some omissions.",
    "Needs Improvement": "Documentation is incomplete or unclear.",
  },
  # Additional criteria can be added as needed...
}

# Grading function utilizing the rubric
def grade_assignment(student_code):
    # Assess student code based on the rubric criteria
    # Calculate score for each criterion
    # Provide feedback based on performance levels
```

The rubric enables you to assess student work across each rubric criterion, calculate a score within a range dictated by each level of attainment, and an opportunity to provide directed feedback as to why each level was selected.

## Contract Grading
Contract grading is an approach that involves students and instructors agreeing upon specific learning outcomes and expectations at the beginning of a course. This collaborative process empowers students to take ownership of their learning journey and actively participate in their assessment.

In the study conducted by Elbow and Danielewicz (reference 1), a unilateral grading contract was implemented, allowing students to set their expectations and define their desired grades. The contract outlined the required work and performance levels for each grade category. This method not only motivated students but also encouraged self-reflection and goal setting.

Contract grading provides a more holistic evaluation of student learning by emphasizing effort, growth, and mastery of learning objectives. It shifts the focus from grades as a means of motivation to learning as the primary goal. However, implementing contract grading requires careful planning, clear communication, and ongoing support to ensure students have a comprehensive understanding of the expectations and assessment criteria.

Further research is needed to explore the efficacy and generalizability of contract grading across different disciplines and educational contexts. However, initial findings suggest that contract grading can be a promising alternative to traditional grading systems.

## Additional References
In addition to the summarized readings, the following scholarly articles and research papers explore various aspects of rubrics and contract grading:

1. "Rubrics: A Handbook for Construction and Use" by Valenti et al. (2009).
2. "Contract Grading in Graduate Clinical Courses: A Qualitative Study" by Thornton et al. (2017).
3. "The Impact of Rubrics on Learning Outcomes and Academic Integrity" by Johnson and Klavas (2019).
4. "Student Attitudes Towards Contract Grading in a Communication Course" by Smith and Banner (2016).

These references provide further insights and empirical evidence for educators interested in implementing rubrics and contract grading techniques in their teaching practice.
