# Lessons

## Lesson: Core Attributes
* A **Title**.
* A **Unique URL** scoped to the organisation for human-friendly access to the lesson.
* A **Image** which is used for thumbnails and giving, ideally, a visual summary of the lesson itself.
* A **Textual Description** that may contain math equations.
* A **Difficulty Level** assigned by the creator(s) of the lesson.
* A **Duration** estimate assigned by the  creator(s).
* A **Set of Tags** that content creators can define to help find the lesson.
* A **Knowledge Branch** such as **Math**, **Physics**, or **Biology** set by the content creators.

Lessons are made of what we call **learning atoms**. A learning atom contains a *prompt*, a *user-response* as well a form of *feedback* or *explanation* describing one way of solving the problem.

### Learning Atom: Core Attributes
* A **Prompt** giving a description of the problem
* A **User-Response** requiring the user to enter an answer or otherwise problem-solve in order to continue.
* A **Feedback / Explanation** allowing the user to get feedback on their input and/or see one possible solution path to the problem.

### About Lessons
- A lesson builds out a small branch in a user’s deep knowledge schemata tree. 
- A lesson should build knowledge of the problem space and help a user:
    - recognise the category of a given problem
    - develop a solution strategy for solving problems within the category
    - solve problems of the given type.
- A lesson is an ordered set of learning atoms.

Depending on the difficulty of the problem, lessons should provide worked examples and slowly progress from a worked example, to a partially worked example to full unsolved problems. At the end of a lesson the learner should be capable of solving problems where no parts of the solution are given.


## Lesson Actions

There are three main learning actions which can be applied to lessons, they are *learning*, *discussing*, and *practicing* which are focused on different aspects of the learning experience.

### Actions
1. Learn
2. Discuss
3. Practice

### Learn

This is a step-by-step walkthrough of the lesson with each learning-atom providing some information and a question prompt which must be answered in order to continue to the next step in the lesson. Each lesson is essentially a chainlink of *(prompt, user-answer, explanation)* tuples which must be completed in order to complete the lesson.

### Discuss

There are a couple of options under the discuss view. First, there is a comments browser where the user can comment on the lesson itself and on particular learning atoms within the lesson. This allows users to talk to one another about a particular problem and build and propose alternative solution paths. These alternative solutions can then be integrated into the course at a later time and the user which created it will gain EXP.
This view also has a feedback option (so the user can provide critical feedback to the developers for errors or other problems). Finally, there is a rating function, where you can rate a problem or an entire lesson in general.

### Practice

Practing allows users to build intuition and rapid problem solving capabilities. Under this options users can:
* Take a quiz based on all the questions from within the lesson itself.
* See the quiz-results over time and review the results of each quiz.
* Create a unique challenge link and invite others to do a gamified challenge to the questions within the quiz.
