---
layout: activity
permalink: /Activities/DataScienceEducation
title: "CS352: Computer Science Pedagogy - Teaching Data Science"


info:
  goals:
    - To design dataset-driven lessons in which students ask and answer questions with real data
    - To use K-12 data exploration tools such as CODAP and Tuva to prototype a data investigation
    - To evaluate data science curricula for pedagogical fit across grade bands and disciplines
  additional_reading:
    - title: "Data Moves (Harding)"
      link: "https://github.com/mahmoudharding/datamoves"
    - title: "Data Science Teaching Materials"
      link: "https://drive.google.com/drive/folders/1Y525XUtXPWd_bKSGTkjj2VP4d4Khy20t?_hsmi=369932214"
    - title: "Project Based R and Python for Data Science (Stokes)"
      link: "https://djstokes02.github.io/IntroRPython4DS/"
    - title: "CODAP: Common Online Data Analysis Platform"
      link: "https://codap.concord.org/"
    - title: "Tuva: Data Literacy for Grades K-12 (and Tuva Jr)"
      link: "https://tuvalabs.com/"
  guidingquestions:
    - "How is a data investigation lesson different from a programming lesson or a statistics lesson?  What belongs to each?"
    - "What makes a dataset a good teaching dataset for a particular grade band?"
    - "How can data science lessons connect to disciplines beyond CS and math, such as social studies, biology, or physical education?"
    - "What equity considerations arise when choosing datasets about people?"
  models:
    - model: |
        <div align="center">
        Open <a href="https://codap.concord.org/">CODAP</a> (no account required - click "Try CODAP," then open an example document such as <i>Mammals</i>).  With your group, work through a full data investigation cycle:
        <br><br>
        <b>1. Ask</b>: Pose a question the dataset might answer (e.g., "do larger mammals live longer?").<br>
        <b>2. Explore</b>: Drag attributes onto a graph.  Try at least two different pairings.<br>
        <b>3. Analyze</b>: Add a movable line or grouping.  What pattern (or lack of one) do you see?<br>
        <b>4. Communicate</b>: Write a one-sentence claim supported by your graph, and one limitation of that claim.
        </div>
      title: "Hands-On: A Data Investigation in CODAP"
      questions:
        - "What did CODAP make easy that a spreadsheet would make hard for a 6th grader, and vice versa?"
        - "Which 'data moves' did your group perform (filtering, grouping, summarizing, calculating, merging)?  Where would a novice get stuck?"
        - "How would you scaffold this same investigation for a student who has never seen a scatter plot?  How does that connect to multiple means of representation in UDL?"
        - "Rewrite your investigation question at each level of Bloom's taxonomy, from recalling a value in the table to creating a new investigation."
        - "Now try the same dataset exploration in <a href='https://tuvalabs.com/'>Tuva</a> if your group has time.  Compare the two tools: which would you choose for elementary students (consider Tuva Jr), and which for high school?"

tags:
  - datascience
  - udl
  - equity

---

## Teaching Data Science

Data literacy - the ability to ask questions of data, explore it, and communicate honest claims about it - is emerging as a core K-12 competency alongside computational thinking, and appears across the disciplines: census data in social studies, sensor data in science, survey data in health class.  Data science lessons are a natural vehicle for the equitable, culturally relevant, and cross-disciplinary computing pedagogy we have studied all semester, because every student's lived experience generates data worth investigating.

As with our other activities, this page models what it teaches: the *purpose* is to prepare you to design a dataset-driven lesson; the *task* is the CODAP investigation above plus the curriculum evaluation below; the *criteria* are the goals in the sidebar (a TILT-transparent design), and the investigation offers multiple entry points (visual tool, code-based curriculum, unplugged discussion) in the spirit of UDL.

### Dataset-Driven Lesson Design

A good data science lesson usually inverts the traditional order: instead of teaching a tool and then applying it, students begin with a **question about a dataset they care about** and acquire moves and tools as the investigation demands them.  This is guided inquiry - the same core tenet as [POGIL](POGIL).  When designing a data lesson, consider:

* **Choose data with a story**: local weather, school lunch menus, sports statistics, or student-collected survey data outperform abstract example tables.  Culturally relevant datasets let students bring their own expertise to class.
* **Plan the "data moves"**: anticipate which operations (filtering, grouping, summarizing, calculating new attributes, merging) students will need, and scaffold only those.
* **Design for claims, not just charts**: the deliverable of a data lesson should be an evidence-backed *claim with limitations*, which gives you an authentic assessment spanning Bloom's analyze/evaluate/create levels.
* **Mind the people in the data**: datasets about people (arrests, income, health) demand explicit framing.  Discuss with students who collected the data, who is represented or missing, and who could be harmed by a careless conclusion.

### Tools and Curricula to Adapt

Each resource below includes a note on what it is, when a teacher would reach for it, and one concrete usage idea.  As you review them, apply our usual lenses: Bloom's for goals, UbD for unit fit, and UDL for scaffolding.

* **[CODAP (Common Online Data Analysis Platform)](https://codap.concord.org/)**: a free, browser-based, drag-and-drop data exploration environment from the Concord Consortium, designed for grades 5-14 with no login and no programming required.  *When to use it*: as the primary environment for middle- and high-school data investigations, especially for students not yet ready for code.  *Usage idea*: the model activity above; extend it by importing a CSV of local data (e.g., your town's weather history) so students investigate a question about their own community.

* **[Tuva (and Tuva Jr)](https://tuvalabs.com/)**: a K-12 data literacy platform with hundreds of curated real-world datasets, built-in visualization tools, and lesson supports; Tuva Jr targets elementary learners with simplified plots and prompts.  *When to use it*: when you want vetted, standards-aligned datasets with teacher supports rather than sourcing your own; Tuva Jr is one of the few options appropriate for K-5.  *Usage idea*: for your service learning project, pick one Tuva dataset and design a three-act lesson (notice/wonder, investigate, claim) differentiated for two grade bands.

* **[Data Moves (Harding)](https://github.com/mahmoudharding/datamoves)**: an open GitHub repository of notebooks and materials organized around "data moves" - the concrete actions (filter, group, summarize, calculate, merge) that analysts perform on data.  *When to use it*: when planning the skills progression of a data unit; naming the moves gives you assessable, Bloom-friendly verbs for your objectives.  *Usage idea*: audit a data lesson you have drafted and label every step with its data move; any move you never taught but expect students to perform is a scaffolding gap.

* **[Project Based R and Python for Data Science](https://djstokes02.github.io/IntroRPython4DS/)**: a free, project-based online text introducing data science in both R and Python side by side.  *When to use it*: for high-school students (or your own upskilling!) ready to move from tool-based exploration in CODAP/Tuva to code-based analysis; the parallel R/Python presentation is itself a nice example of multiple means of representation.  *Usage idea*: have advanced students reproduce, in code, an investigation they first performed in CODAP - a concrete "low floor to high ceiling" pathway within one unit.

* **[Data Science Teaching Materials folder](https://drive.google.com/drive/folders/1Y525XUtXPWd_bKSGTkjj2VP4d4Khy20t?_hsmi=369932214)**: a curated collection of data science teaching resources, lesson materials, and professional development artifacts.  *When to use it*: as a browsing library when planning a unit, after you have fixed your goals (resist the temptation to pick activities first - UbD Stage 3 comes last!).  *Usage idea*: select one artifact from the folder and frame it in the UbD template: what are its transfer goals, essential questions, and evidence of understanding?

### Discussion and Practice

1. In pairs (ideally one CS student and one Education student), choose a non-CS subject area and sketch a one-lesson data investigation for it, naming the dataset, the driving question, the data moves required, and the claim students will produce.
2. Exchange sketches with another pair and give feedback using the 12 pedagogical principles: which principles does the lesson exhibit, and which one addition would strengthen it most?
3. Whole class: what belongs in a K-12 *data science* strand that is not already in the math standards or the CS standards?  Where should it live?
