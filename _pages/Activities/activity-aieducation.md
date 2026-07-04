---
layout: activity
permalink: /Activities/AIEducation
title: "CS352: Computer Science Pedagogy - Teaching AI in K-12"


info:
  goals:
    - To explain the AI4K12 "Five Big Ideas in AI" as a framing for K-12 artificial intelligence lessons
    - To design an unplugged or tool-based AI activity appropriate for a target grade band
    - To evaluate AI teaching tools and curricula for pedagogical fit, equity, and accessibility
  additional_reading:
    - title: "AI4K12: The Five Big Ideas in Artificial Intelligence"
      link: "https://ai4k12.org/"
    - title: "MIT Teaching Systems Lab: An Ethics of Artificial Intelligence Curriculum Guidebook"
      link: "http://tsl.mit.edu/ai-guidebook"
    - title: "Machine Learning for Kids: Worksheets and Projects"
      link: "https://machinelearningforkids.co.uk/#!/projects"
    - title: "ISTE/GM Hands-On AI Projects for the Classroom (Elementary)"
      link: "https://d3btwko586hcvj.cloudfront.net/uploads/pdf/file/522/ISTEGM_AIGuides_Elementary_EN-1706651202.pdf"
    - title: "AI for Kids Slide Deck"
      link: "https://docs.google.com/presentation/d/1AJ5sfkMVzl_JNnnVeTOnEZD__fe8b7LN_2sPTpFLH44/mobilepresent#slide=id.g2e0877b7850_0_356"
    - title: "AI for Literacy"
      link: "https://drive.google.com/file/d/1dCL7Aj_c-XqLqBwrZRmx3qpJafafI3ss/view"
    - title: "Image Compression Activity Materials"
      link: "https://drive.google.com/drive/folders/1KhJsf9mWc-33scob4hzFV_9pUQ7EW2G-"
  guidingquestions:
    - "Which of the Five Big Ideas in AI could you teach without a computer at all?  Sketch an unplugged activity for one of them."
    - "How is teaching a machine learning lesson different from teaching a traditional programming lesson?  What misconceptions might students bring to each?"
    - "What ethical questions should accompany any K-12 AI lesson, and at what grade band would you introduce each?"
    - "Train a text or image classifier in Machine Learning for Kids.  Where did your model succeed and fail, and how would you turn that failure into a teachable moment?"
  models:
    - model: |
        <div align="center">
        <iframe src="https://ai4k12.org/wp-content/uploads/2020/12/AI4K12_Five_Big_Ideas_Poster.pdf" width="100%" height="500px"></iframe>
        <br>
        The AI4K12 initiative organizes all of K-12 AI education around Five Big Ideas: (1) Perception, (2) Representation and Reasoning, (3) Learning, (4) Natural Interaction, and (5) Societal Impact.
        </div>
      title: "The Five Big Ideas in AI (AI4K12)"
      questions:
        - "For each of the Five Big Ideas, name one everyday technology a K-12 student already uses that illustrates it."
        - "The Big Ideas are deliberately not tied to any programming language or tool.  Why might the AI4K12 working group have made that choice, and how does it echo the Understanding by Design approach we studied earlier?"
        - "Choose one Big Idea and one grade band (K-2, 3-5, 6-8, 9-12).  Using the AI4K12 grade band progression charts, what should a student at that level be able to do, and what would be developmentally inappropriate to expect?"
        - "Where does 'Societal Impact' show up in the other four Big Ideas?  Should ethics be a separate lesson or woven throughout?  Defend your position."
    - model: |
        <div align="center">
        Train your own machine learning model - no programming experience required!  Visit <a href="https://machinelearningforkids.co.uk/#!/projects">Machine Learning for Kids</a> and follow the project flow below with your group:
        <br><br>
        <b>1. Collect</b>: Create a project to recognize text as "compliments" or "insults."  As a group, author 10-15 training examples of each.<br>
        <b>2. Train</b>: Train the model on your examples.<br>
        <b>3. Test</b>: Try phrases that were NOT in your training data, including sarcasm, slang, and neutral statements.<br>
        <b>4. Reflect</b>: Where is the model confidently wrong?  What is missing from your training data?
        </div>
      title: "Hands-On: Machine Learning for Kids"
      questions:
        - "What happened when you tested a sarcastic phrase or a phrase in another language?  What does this reveal about how the model 'learned'?"
        - "How does the size and diversity of your training data affect the model's behavior?  How would you help a 5th grader discover this on their own rather than telling them?"
        - "This activity follows a discovery arc much like POGIL: explore a model, answer guided questions, and construct the concept.  Which POGIL roles would you assign during this activity, and what would each do?"
        - "What data privacy considerations should a teacher address before students supply training examples in class?"

tags:
  - ai
  - aieducation
  - equity

---

## Teaching AI in K-12

Artificial intelligence is now part of the daily life of every K-12 student, from recommendation systems and voice assistants to generative chatbots.  Teaching *about* AI (how it works, what it can and cannot do, and how it affects people) is rapidly becoming as fundamental as teaching programming.  In this activity, we frame K-12 AI education using the AI4K12 Five Big Ideas, practice with hands-on tools that make machine learning tangible for young learners, and evaluate a portfolio of curricula you can adapt for your own classroom.

In keeping with what we have studied so far, notice that this page itself is designed transparently (in the spirit of the TILT framework we discuss with [rubrics and contract grading](RubricContract)): the *purpose* is to prepare you to design an AI lesson; the *task* is the guided model exploration above and the resource evaluations below; and the *criteria* are the learning goals in the sidebar.

### Framing: The Five Big Ideas in AI

The [AI4K12 initiative](https://ai4k12.org/) (a joint effort of AAAI and CSTA) provides national guidelines for teaching AI in K-12, organized around **Five Big Ideas**:

1. **Perception**: Computers perceive the world using sensors.
2. **Representation and Reasoning**: Agents maintain representations of the world and use them for reasoning.
3. **Learning**: Computers can learn from data.
4. **Natural Interaction**: Intelligent agents require many kinds of knowledge to interact naturally with humans.
5. **Societal Impact**: AI can impact society in both positive and negative ways.

**What it is**: grade-band progression charts (K-2, 3-5, 6-8, 9-12) describing what students should know and be able to do for each Big Idea, plus a curated resource directory.

**When a teacher would use it**: at unit-planning time, exactly where Understanding by Design places Stage 1.  The Big Ideas serve as your "established goals," and the grade band charts calibrate developmentally appropriate expectations before you choose activities or tools.

**Concrete usage idea**: before writing an AI lesson, print the grade band progression chart for your target band and highlight the one or two cells your lesson will address; write your essential questions directly from those cells.

### Hands-On Tools for Teaching Machine Learning

#### Machine Learning for Kids

**What it is**: [Machine Learning for Kids](https://machinelearningforkids.co.uk/#!/projects) is a free, web-based tool by Dale Lane that lets students train text, image, number, and sound classifiers, and then *use* those models inside Scratch, Python, or App Inventor programs.  It ships with dozens of ready-made worksheets and lesson plans.

**When a teacher would use it**: any time students are ready to move from *talking about* machine learning to *doing* it, roughly grades 3 and up.  Because trained models plug into Scratch, it pairs naturally with block-based programming units students may already know from code.org.

**Concrete usage idea**: follow the "Collect, Train, Test, Reflect" model above as a whole-class activity, then let pairs build a Scratch character that responds to the classifier's output (for example, a pet that smiles at compliments).  This walks students through Big Ideas 3 (Learning) and 4 (Natural Interaction) in a single lesson.

#### Unplugged AI: Image Compression and Data Representation

**What it is**: this [folder of image compression activity materials](https://drive.google.com/drive/folders/1KhJsf9mWc-33scob4hzFV_9pUQ7EW2G-) supports a kinesthetic activity in which students encode, compress, and reconstruct images by hand, building intuition for how computers represent and reduce data (see also our [Pixel Pandemonium POGIL activity](POGIL)).

**When a teacher would use it**: as an unplugged on-ramp to Big Idea 2 (Representation) before introducing machine learning.  Students cannot reason about what a model "sees" until they understand that an image is numbers, and that representations can lose information.

**Concrete usage idea**: run the compression activity, then connect it to AI by asking: "if a lossy image still looks fine to you, could an AI trained on compressed images make mistakes a human wouldn't notice?"  This bridges representation to model behavior and bias.

### Curricula and Guides to Adapt

Each of the following is a ready-made resource you can borrow from, adapt, or teach directly.  As you review each one, practice the evaluation lens we developed earlier this semester: check its goals against Bloom's taxonomy, its scaffolding against UDL, and its examples against culturally relevant pedagogy.

* **[ISTE/GM Hands-On AI Projects for the Classroom (Elementary)](https://d3btwko586hcvj.cloudfront.net/uploads/pdf/file/522/ISTEGM_AIGuides_Elementary_EN-1706651202.pdf)**: a free PDF guide of complete, standards-aligned AI projects for elementary classrooms (the series also includes secondary, electives, and CTE volumes).  *When to use it*: when you need a fully worked project with student handouts rather than a framework.  *Usage idea*: assign one project to each group in your class; have groups map their project onto the Five Big Ideas and identify its UDL supports (or missing ones) before presenting it as a lightning talk.

* **[MIT Teaching Systems Lab AI + Ethics Guidebook](http://tsl.mit.edu/ai-guidebook)**: a middle-school curriculum guidebook interleaving AI concepts with ethics activities such as redesigning the YouTube recommendation algorithm for different stakeholders.  *When to use it*: when planning Big Idea 5 (Societal Impact), or to embed ethics checkpoints inside a technical unit.  *Usage idea*: adapt its "ethical matrix" activity (stakeholders vs. values) as a 15-minute closer for any AI lesson you teach.

* **[AI for Kids slide deck](https://docs.google.com/presentation/d/1AJ5sfkMVzl_JNnnVeTOnEZD__fe8b7LN_2sPTpFLH44/mobilepresent#slide=id.g2e0877b7850_0_356)**: a classroom-ready introductory presentation on AI concepts for young learners.  *When to use it*: as the "multiple means of representation" component of a first AI lesson, paired with an unplugged or hands-on activity so the lesson is not lecture-only.  *Usage idea*: critique and remix - have your students (or you, for your service learning project) evaluate which slides work for their target grade band and rebuild the rest.

* **[AI for Literacy](https://drive.google.com/file/d/1dCL7Aj_c-XqLqBwrZRmx3qpJafafI3ss/view)**: materials connecting AI to reading and language literacy, a bridge for teaching AI *outside* the CS classroom.  *When to use it*: for cross-disciplinary co-teaching with an ELA colleague, or in a school without a standalone CS course.  *Usage idea*: pair it with a Machine Learning for Kids text classifier, and have students investigate how word choice in their training data changes the model, making vocabulary and connotation suddenly computational.

### AI in Educator Preparation ("AI for CEP")

Beyond teaching AI *to students*, consider AI's role in **computing educator preparation** itself: programs like this course must now prepare pre-service teachers to (a) teach AI content, (b) use AI tools responsibly in their own lesson planning and assessment, and (c) set classroom policies for student AI use.  Discuss with a partner: which of these three did your own K-12 experience prepare your teachers for?  What would you add to a teacher preparation program (or to this course!) to close the gap?  Bring one concrete suggestion to share with the class.
