# Algorithms and Data Structures

## Content
* [Description](#description)
* [Learning Outcomes](#learning-outcomes)
* [Logistics](#logistics)
  + [Course Contacts](#course-contacts)
  + [Delivery instructions](#delivery-instructions)
* [Policies](#policies)
  + [Requirements](#requirements)
  + [Delivery of Module](#delivery-of-module)
  + [How the Technical Facilitator will deliver](#how-the-technical-facilitator-will-deliver)
  + [Expectations](#expectations)
  + [Lesson Schedule](#lesson-schedule)
  + [Textbooks](#textbooks)
* [Marking Scheme](#marking-scheme)
* [Policies](#policies)
* [Resources](#resources)
  + [Documents](#documents)
  + [Videos](#videos)
  + [How to get help](#how-to-get-help)
* [Folder Structure](#folder-structure)
* [Acknowledgements and Contributions](#acknowledgements-and-contributions)
* [Achnowledgements](#achnowledgements)
  + [Contributions ](#contributions)

## Description
The course was created by the University of Toronto's Data Science Institute. An understanding of data structures and algorithms (DSA), will aid the implementation of data science or machine learning methods in practice. Machine learning places emphasis on prediction, scalability, and autonomy. Understanding DSA is essential to the latter two aims of ML. For instance, students will be able to describe how an algorithms will perform when scaled or find practical methods for computers to solve problems autonomously. Finally, the industry often requires knowledge on DSAs and the ability to communicate the solving process. This course will provide the knowledge and terminology necessary to succeed in these situations.

The beginning of the course will introduce students to terminology to discuss algorithms. This includes Big-O notation, time and space complexity. The next section will explore array-based data structures, searching, and sorting. Students should be able to justify algorithm or data structure choices based off time and space complexity analysis. Then, students will be introduced to recursion. We will solve problems using recursion and implment data structures that are best understood from a recursive perspective. Again, students will justify their design choices. The last portion of the course will be dedicated to solving optimization problems quickly. Students will be introduced to a variety of techniques to solve problems, identify when and how a solution can be optimized.

This course is designed for those who have a degree in something other than Computer Science/Statistics who are looking to enhance their data science skills for their career.

## Learning Outcomes
By the end of the module, learners will:

1. Assess options and choices around fundamental algorithms and data structures using Big-O notation.
2. Develop comfort with recursive functions.
3. Decide on appropriate data structures
4. Take a client-led problem and translate it into an optimization problem.
5. Identify why code is running slowly and know how to improve its performance.

## Logistics

### Course Contacts
**Questions can be submitted to the #questions channel on Slack**

* Technical Facilitator: **{Name}** {Pronouns}. Emails to the Technical Facilitator can be sent to {first_name.last_name}@mail.utoronto.ca.
* Learning Support Staff: **{Name}** {Pronouns}. Emails to the Technical Facilitator can be sent to {first_name.last_name}@mail.utoronto.ca.

### Delivery instructions
The workshop will be held over three weeks, three days a week. Two of the three days will be 2-hours long and the last day will be 3-hours. Being mindful of online fatigue, there will be one break during each class where students are encouraged to stretch, grab a drink and snacks, or ask any additional questions.

There will be a live coding component in most classes. Students are expected to follow along with the coding and ask questions throughout. 

## Policies
* **Accessibility:** We want to provide an accessible learning environment for all. If there is something we can do to make this course more accessible to you, please let us know.
* **Course communications:** Communications take place over email or on Slack. If communicating over email, please include "DSI-Algo" or similar in the subject line, e.g. "DSI-Algo: BFS question"
* **Camera:** Keeping your camera on is optional.
* **Microphone:** Please keep microphones muted unless you need to speak. Please indicate your name before speaking as some Zoom configurations make it hard to tell who is talking!
* **Assessment:** There will be homework which **is not** graded, but highly recommended, and there will be two assignments which **are** graded.

### Requirements
* Learners are not expected to have any coding experience, we designed the learning contents for beginners.
* Learners are encouraged to ask questions, and collaborate with others to enhance learning.
* Learners must have a computer and an internet connection to participate in online activities.
* Learners must have VSCode installed with the following extensions: 
    * [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
    * [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
* Learners must not use generative AI such as ChatGPT to generate code in order to complete assignments. It should be use as a supportive tool to seek out answers to questions you may have.
* We expect learners to have completed the [onboarding repo](https://github.com/UofT-DSI/Onboarding/tree/tech-onboarding-docs).
* Camera is optional although highly encouraged. We understand that not everyone may have the space at home to have the camera on.

### Delivery of Module
The module will run sychronously three times a week on Zoom. The first three days are used as "lectures" and will last a maximum of 3 hours. During this time, the Technical Facilitator will introduce the concepts for the week. The last day is used for as optional, asychronous work periods. The work periods will also last for up to 3 hours. During the work period, an Technical Facilitator or TA will be present on Zoom to assist learners reach the intended learning outcomes.

### How the Technical Facilitator will deliver
The Technical Facilitators will introduce the concepts through a collaborative live coding session usiing the Python notebooks found under `/01-slides`. All Technical Facilitators will also upload any live coding files to this repository for any learners to revisit under `/live-code`.
 
### Expectations
Learners are encouraged to be active participants while coding and are encouraged to ask questions throughout the module.

### Lesson Schedule

| Lesson | Topic                                                       | Resources  |
|--------|-------------------------------------------------------------|------------|
| 1      | Motivation and Big-O Notation                               | [Slides](https://github.com/UofT-DSI/algorithms_and_data_structures/blob/main/lessons/1_motivation-big-o.pdf) |
| 2      | Data Structures, Sorting, and Searching                     | [Slides](https://github.com/UofT-DSI/algorithms_and_data_structures/blob/main/lessons/2_ds-search-sort.pdf) |
| 3      | Recursion              				                             | [Slides](https://github.com/UofT-DSI/algorithms_and_data_structures/blob/main/lessons/3_recursion.pdf) |
| 4      | Recursion              				                             | [Slides](https://github.com/UofT-DSI/algorithms_and_data_structures/blob/main/lessons/3_recursion.pdf) |
| 5      | Recursive Data Structures                                   | [Slides](https://github.com/UofT-DSI/algorithms_and_data_structures/blob/main/lessons/4_recursive-ds.pdf) |

### Textbooks

The course content, slides, and recommended problems follow these two textbooks. They are freely available online after a quick google search. 

* Bhargava, A. Y. (2016). *Grokking algorithms: An illustrated guide for programmers and other curious people.* Manning. ([link](https://www.manning.com/books/grokking-algorithms-second-edition))
  * This textbook is easy to understand and very accessible. We will go deeper than this text.
* Cormen, T. H. (Ed.). (2009). *Introduction to algorithms (3rd ed).* MIT Press.
  * We won't cover the majority of this textbook. Many topics are too advanced and it goes into a lot of detail. 

## Marking Scheme
| Assessment       | Description          | Due Date |
|------------------|----------------------|----------|
| [Assignment 1](https://github.com/UofT-DSI/algorithms_and_data_structures/blob/main/assignments/assignment%201.md) | DSA coding practice  | TBD |
| [Assignment 2](https://github.com/UofT-DSI/algorithms_and_data_structures/blob/main/assignments/assignment%202.md) | mock interview       | TBD |

## Policies
Students should be active participants while coding and are encouraged to ask questions throughout.

**How to submit assignments, late policy, academic integrity.**
Please submit your assignment by uploading the PDFs to your google drive folder used for assignment submissions.

Late policy: Everyone has a 24 hours grace period available in total for both assignments. Meaning if you submit the first assignment 12 hours late, you can submit the second assignment 12 
hours late with no penalty. Or if you submit the first assignment on time, you can submit the second assignment upto 24 hours late. After using your grace period time, there will be a 20% 
penalty for 24 hours, and a 100% penalty after that. 

If there are any extenuating circumstances, pleaese contact the course Technical Facilitator as soon as possible for accommodations. 

## Resources
Feel free to use the following as resources:

### Documents
- [Big O Cheatsheet](https://www.bigocheatsheet.com/)
- [Sorting Cheatsheet](https://www.interviewcake.com/sorting-algorithm-cheat-sheet)
- [Visual Go - Graph Traversal](https://visualgo.net/en/dfsbfs?slide=2)
- [Codecademy Explanation](https://www.codecademy.com/article/tree-traversal)

### Videos
- [15 Sorting Algorithms in 6 minutes](https://www.youtube.com/watch?v=kPRA0W1kECg) (Warning: This video could cause seizures for people with photosensitve epillepsy)
- [Big O Notation](https://www.youtube.com/watch?v=g2o22C3CRfU)
- [Breadth-first Search in 4 minutes](https://www.youtube.com/watch?v=HZ5YTanv5QE)
- [Depth-first Search in 4 minutes](https://www.youtube.com/watch?v=Urx87-NMm6c)
- [Nearest Neighbour Algorithm](https://www.youtube.com/watch?v=zPgsNsOfxQ8)
- [K-d Trees](https://www.youtube.com/watch?v=Glp7THUpGow)
- [Sorting Playlist](https://www.youtube.com/playlist?list=PL9xmBV_5YoZOZSbGAXAPIq1BeUf4j20pl)

### How to get help
![image](/steps-to-ask-for-help.png)

<hr>

## Folder Structure

```markdown
.
├── 01-slides
├── 02-assignments
├── 03-homework
├── 04-instructors
├── LICENSE
├── README.md
└── steps-to-ask-for-help.png
```

* **slides:** Course slides as interactive notebooks (.ipynb files)
* **html slides:** Course slides as HTML files that can be downloaded and viewed in a web browser
* **pdf slides:** Course slides as PDF files
* **live-coding:** Notebooks from class live coding sessions
* **homework:** Optional homework to practice concepts covered in class
* **assignments:** Graded assignments
* **instructors:** Instructions for the Technical Facilitator on what to teach
* **additional resources:** Additional materials not covered by the module
* README: This file!
* .gitignore: Files to exclude from this folder, specified by the Technical Facilitator

## Acknowledgements and Contributions

### Achnowledgements
* The module was devloped by [Alex Yu](https://www.linkedin.com/in/kunzhi-yu/) under the supervision of Rohan Alexander. 
* We wish to acknowledge this land on which the University of Toronto operates. For thousands of years it has been the traditional land of the Huron-Wendat, the Seneca, and most recently, the Mississaugas of the Credit River. Today, this meeting place is still the home to many Indigenous people from across Turtle Island and we are grateful to have the opportunity to work on this land.
### Contributions 
* `algorithms_and_data_structures` welcomes issues, enhancement requests, and other contributions. To submit an issue, use the [GitHub
issues](https://github.com/UofT-DSI/algorithms_and_data_structures/issues).
