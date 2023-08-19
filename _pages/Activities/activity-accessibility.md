---
layout: activity
permalink: /Activities/Accessibility
title: "CS471: Computer Science Pedagogy - Accessibility"
excerpt: "CS471: Computer Science Pedagogy - Accessibility"

info:
  goals: 
    - To design curricula with accessability in mind in support of the UDL philosophy
  models:
    - model: |
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 600">
          <!-- Title -->
          <text x="400" y="30" text-anchor="middle" font-size="20" font-weight="bold">Computing for Neurodiverse Students and Students with Disabilities</text>

          <!-- Inclusive Design Section -->
          <rect x="50" y="60" width="300" height="100" fill="#e6f7ff"/>
          <text x="200" y="90" text-anchor="middle" font-weight="bold">Inclusive Design</text>
          <text x="200" y="110" text-anchor="middle" font-size="12">Applying universal design principles to create accessible computing environments.</text>

          <!-- Assistive Technologies Section -->
          <rect x="450" y="60" width="300" height="100" fill="#ffebcc"/>
          <text x="600" y="90" text-anchor="middle" font-weight="bold">Assistive Technologies</text>
          <text x="600" y="110" text-anchor="middle" font-size="12">Integration of tools like screen readers, alternative input devices, etc.</text>

          <!-- Collaboration Section -->
          <rect x="50" y="180" width="300" height="100" fill="#d9f7be"/>
          <text x="200" y="210" text-anchor="middle" font-weight="bold">Collaboration</text>
          <text x="200" y="230" text-anchor="middle" font-size="12">Collaboration between special education professionals and computing educators.</text>

          <!-- Barriers & Solutions Section -->
          <rect x="450" y="180" width="300" height="100" fill="#ffd1e8"/>
          <text x="600" y="210" text-anchor="middle" font-weight="bold">Barriers & Solutions</text>
          <text x="600" y="230" text-anchor="middle" font-size="12">Identifying and addressing common barriers faced by neurodiverse students.</text>
        </svg>
      title: "Promoting Accessibility in Computing Education"
      questions:
        - "How can inclusive design principles be applied to create accessible computing environments for neurodiverse students and students with disabilities?"
        - "What are some common barriers faced by neurodiverse students in computing education, and how can educators address these barriers?"
        - "How can assistive technologies be integrated into the computing curriculum to support students with disabilities?"
        - "What role do empathy and understanding play in creating an inclusive computing classroom? Can you provide examples of strategies that promote empathy?"
        - "How can collaboration between special education professionals and computing educators enhance the learning experience for students with diverse needs?"
    - model: |
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 700">
          <!-- Title -->
          <text x="500" y="30" text-anchor="middle" font-size="20" font-weight="bold">Career Pathways to Computing</text>

          <!-- Education & Training Section -->
          <rect x="50" y="60" width="180" height="100" fill="#e6f7ff"/>
          <text x="140" y="90" text-anchor="middle" font-weight="bold">Education & Training</text>
          <text x="140" y="110" text-anchor="middle" font-size="12">Aligning curricula with industry demands and fostering growth mindset.</text>

          <!-- Diversity & Inclusion Section -->
          <rect x="250" y="60" width="180" height="100" fill="#ffebcc"/>
          <text x="340" y="90" text-anchor="middle" font-weight="bold">Diversity & Inclusion</text>
          <text x="340" y="110" text-anchor="middle" font-size="12">Promoting diversity in computing careers for underrepresented groups.</text>

          <!-- Internships & Mentorships Section -->
          <rect x="450" y="60" width="180" height="100" fill="#d9f7be"/>
          <text x="540" y="90" text-anchor="middle" font-weight="bold">Internships & Mentorships</text>
          <text x="540" y="110" text-anchor="middle" font-size="12">Role of practical experience in expanding career pathways.</text>

          <!-- Industry Trends Section -->
          <rect x="650" y="60" width="180" height="100" fill="#ffd1e8"/>
          <text x="740" y="90" text-anchor="middle" font-weight="bold">Industry Trends</text>
          <text x="740" y="110" text-anchor="middle" font-size="12">Understanding current trends and future directions in computing.</text>

          <!-- Ethical Considerations Section -->
          <rect x="850" y="60" width="180" height="100" fill="#ffe7e7"/>
          <text x="940" y="90" text-anchor="middle" font-weight="bold">Ethical Considerations</text>
          <text x="940" y="110" text-anchor="middle" font-size="12">Instilling a sense of responsibility and ethics in computing professionals.</text>
        </svg>
      title: "Expanding Career Pathways to Computing"
      questions:
        - "What are the current trends in computing careers, and how can educational institutions align their curricula to meet industry demands?"
        - "How can educators promote diversity and inclusion in computing careers, especially for underrepresented groups such as women, minorities, and individuals with disabilities?"
        - "What role do internships, mentorships, and industry partnerships play in expanding career pathways to computing?"
        - "How can educational institutions foster a growth mindset and resilience in students to prepare them for the rapidly changing landscape of computing careers?"
        - "What are some ethical considerations in computing careers, and how can educators instill a sense of responsibility and ethics in future computing professionals?"
  
  additional_reading:
    - title: "How to Design Computer Science for Students with Disabilities"
      link: "https://www.edweek.org/teaching-learning/how-to-design-computer-science-for-students-with-disabilities/2018/10"  
    - title: "Plasman.  Promoting persistence: Can computer science career and technical education courses support educational advancement for students with learning disabilities?"
      link: "https://www.researchgate.net/publication/358630604_Promoting_persistence_Can_computer_science_career_and_technical_education_courses_support_educational_advancement_for_students_with_learning_disabilities"    
    - title: "Building Ecosystems of Belonging for Neurodiverse Students"
      link: "https://par.nsf.gov/servlets/purl/10356929"      
    - title: "WAVE Toolkit"
      link: "https://wave.webaim.org/"

tags:
  - udl
  - accessibility
  
---

## Accessibility in CS Educational Design

Accessibility is an important aspect of educational design in the field of Computer Science (CS). It ensures that individuals with disabilities have equal access to educational materials, resources, and opportunities. We will explore the topic of accessibility in CS educational design, discussing various guidelines, tools, and practices that can be employed to improve inclusivity and support students with disabilities.

## Web Content Accessibility Guidelines (WCAG)

The **Web Content Accessibility Guidelines (WCAG)** provide a comprehensive set of guidelines for making web content more accessible. These guidelines, formulated by the World Wide Web Consortium (W3C), aim to ensure that web content can be perceivable, operable, understandable, and robust for all users, including those with disabilities[^1].

To implement WCAG guidelines, CS educators can adopt techniques such as:

- Providing alternative text descriptions for images, graphics, and multimedia content.
```
<img src="image.jpg" alt="Description of the image">
```

- Ensuring compatibility with assistive technologies like screen readers.
```
<button onClick="doSomething()" aria-label="Perform action">Click Me</button>
```

- Designing forms with clear labels and instructions.
```
<label for="name">Name:</label>
<input type="text" id="name" name="name" required>
```

For a more detailed understanding of WCAG guidelines and techniques, refer to the original document at [https://www.w3.org/TR/WCAG21/](https://www.w3.org/TR/WCAG21/).

## Web Accessibility Evaluation (WAVE) Tool

The **Web Accessibility Evaluation (WAVE) Tool** is a web-based tool that helps in the evaluation of web content accessibility. It provides visual representations and detailed reports of the accessibility features and issues present in a web page. WAVE can be used by CS educators to identify and correct accessibility issues in their educational materials and websites[^2].

To utilize the WAVE Tool, educators can follow these steps:

1. Go to the WAVE website: [https://wave.webaim.org/](https://wave.webaim.org/).
2. Enter the URL of the web page to be evaluated.
3. Analyze the generated report highlighting accessibility errors, alerts, and features.
4. Make necessary modifications to address the issues and improve accessibility.

## How to Design Computer Science for Students with Disabilities

The article "How to Design Computer Science for Students with Disabilities" published in EdWeek provides valuable insights into designing CS education that accommodates and supports students with disabilities[^3]. The article emphasizes the importance of Universal Design for Learning (UDL) principles, which promote accessible and flexible educational materials and activities.

CS educators can implement UDL principles in various ways such as:

- Providing multiple means of representation: Presenting content in different formats (e.g., text, audio, video) to cater to diverse learning preferences.
- Offering multiple means of action and expression: Allowing students to express their understanding and ideas using different modalities (e.g., written, verbal, visual).
- Providing multiple means of engagement: Offering various ways to motivate and engage students in CS activities.

## Promoting Persistence: Can Computer Science Career and Technical Education Courses Support Educational Advancement for Students with Learning Disabilities?

The research study conducted by Plasman et al. explores the potential of computer science career and technical education (CTE) courses to support the educational advancement of students with learning disabilities[^4]. The study investigates the experiences of students and educators and highlights strategies that can foster persistence and success for students with disabilities in CS education.

CS educators can consider the following strategies based on the study's findings:

- Provide clear and consistent language support throughout the course.
- Offer scaffolding techniques to guide students through complex CS concepts.
- Implement hands-on and project-based learning activities to enhance engagement and understanding.

## Building Ecosystems of Belonging for Neurodiverse Students: A Discussion of Instructor Practices and Training Needs

The article by Bonnette discusses the importance of creating inclusive learning environments for neurodiverse students in CS education[^5]. It provides valuable insights into instructor practices and training needs to ensure the inclusion and success of these students.

CS educators can consider the following practices to build inclusive environments:

- Setting clear expectations and communication channels.
- Providing organized and structured learning materials.
- Offering flexibility in assessments and assignments.

## Conclusion

Accessibility in CS educational design is crucial for ensuring equal opportunities and inclusivity for individuals with disabilities. By adopting guidelines and utilizing tools like WCAG and WAVE, CS educators can improve the accessibility of their materials. Practices such as Universal Design for Learning, fostering persistence, and creating inclusive learning environments further support the needs of students with disabilities in CS education.