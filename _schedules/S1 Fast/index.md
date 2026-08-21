# Syllabus

**Fall 2026–2027**
 
**Track:** Full (Scientific Programming 1 + 2 and Data Processing - fast pace)

**Expected workload:** ~20 hours/week

## Teaching Team & Contact

**Teaching staff**

<table>
  <tr><td><img src = "https://github.com/spcourse/website/raw/2024/team/suzanne.jpg" style="max-width:90px" width = "150"><br>Suzanne</td><td> ...
  </td></tr>
  <tr><td><img src = "https://github.com/spcourse/website/raw/2025/team/anestasia.jpg" style="max-width:90px"><br>Anastasia</td><td> ...
  </td></tr>
  <tr><td><img src = "https://github.com/spcourse/website/raw/2025/team/luka.jpg" style="max-width:90px" width = "150"><br>Luka</td><td> ...
  </td></tr>
  <tr><td><img src = "https://github.com/spcourse/website/raw/2024/team/simon.jpg" style="max-width:90px" width = "150"><br>Simon</td><td> Simon studied Computer Science and then the Master of Logic at the University of Amsterdam (UvA). He conducted research in computational linguistics and robotics at Sony, Aldebaran (now Softbank), the Universitat Autònoma de Barcelona, and the UvA. He now works as a lecturer at the UvA and teaches programming in various programs.</td></tr>
</table>

**Contact email**
[scientific@proglab.nl](mailto:scientific@proglab.nl)

**Tutorial schedules & locations**
[Tutorial schedules (Datanose)](/datanose)

**Deadlines**
[jump to deadlines](#deadlines)

## Course Overview

This programming track introduces Python through scientific and data-oriented problems. It is designed for **students with no prior programming experience**, but can also accommodate students that already have some experience, but want to imrpove their programming skills.

The track consists of **three separate courses**:

* **Scientific Programming 1 (SP1)** – 3 EC, pass/fail
* **Scientific Programming 2 (SP2)** – 3 EC, pass/fail
* **Data Processing (DP)** – 6 EC, graded

These courses are designed to be taken **together**, but you may also take **one or two** of them separately.

## Prerequisites

### Scientific Programming 1

* No prior programming experience required.
* Some modules assume **high-school level mathematics or physics**, but alternatives are available.
* If you already have substantial programming experience, this course may not be appropriate—contact staff for advice.

### Scientific Programming 2

* Requires **Scientific Programming 1** (or equivalent experience).

### Data Processing

* Requires **Scientific Programming 2** (or equivalent experience).

If at any point you feel unsure whether this track fits your background, please contact us.

## Learning Goals

### After Scientific Programming 1, you:

- can transform the description of a simple algorithm into working code by combining basic program elements;
- can apply several scientific programming techniques from different areas of study;
- can use a couple of libraries in your program and know how to find and read documentation on other libraries;
- can make your programs simpler and easier to read by employing a few standard tactics;
- can trace and fix several common programming errors.

### After Scientific Programming 2, you:

- can use native python data structures (like sets, dictionaries, and tuples);
- analyze the complexity of an algorithm;
- quickly learn to use new python packages and know how to find documentation for them;
- import and analyze data;
- create advanced plots.

### After Data Processing, you:

- can read data into your programs from several structured standard formats;
- can transform data into a form suitable for further analysis by combining basic operators;
- can build meaningful visualizations of your data;
- understand how to write programs that are easy to understand for yourself and other programmers;
- are capable of using advanced programming concepts (like object oriented programming).

## Course Structure

### Modules and Levels

You learn programming through **modules**, grouped into **levels**.

Each module consists of:

* **Theory** (text + videos)
* **Pair assignments** (collaborative)
* **Individual assignments**
* **Challenges** (optional but recommended)

Key rules:

* You must complete **one module per level**.
* Some levels offer **alternative modules** covering the same concepts in different scientific contexts.
* Challenges are optional for SP1/SP2 (but, required for higher grades in Data Processing).

### Programming modules {#programming-modules}

An overview of all modules, per course. Click a module title to read what it is about.

<style>
.modules { width: 100%; border-collapse: collapse; margin-bottom: 1.5em; }
.modules th {
  text-align: left; padding: 0.4em 0.6em; font-size: 0.9em;
  background: #f0ede6; border: 1px solid #d8d2c4;
}
.modules td { vertical-align: top; padding: 0.5em 0.6em; border: 1px solid #d8d2c4; }
.modules td.mid { vertical-align: middle; }
.modules summary { cursor: pointer; font-weight: bold; }
.modules details p { margin: 0.6em 0 0; font-size: 0.9em; line-height: 1.4; }
.modules .or { margin: 0.5em 0; font-style: italic; }
.modules .todo { color: #8a6d3b; font-style: italic; }
</style>

#### Scientific Programming 1 (Level 1 - Level 3) {#sp1-modules}

<table class="modules">
  <tr>
    <th>Level 0</th>
    <th>Level 1 (choose one)</th>
    <th>Level 2 (choose one)</th>
    <th>Level 3</th>
  </tr>
  <tr>
    <td class="mid">
      <details><summary>INSTAL</summary>
        <p>Before you can start programming you set up your own machine: learn to use the command line, install Python together with uv and checkpy, and install the Zed editor. Work through these steps before Level 1.</p>
      </details>
    </td>
    <td>
      <details><summary>ALGORITHMS</summary>
        <p>Learn to think like a computer. Things that we intuitively know how to do, like drawing a pyramid or computing change for a payment, is hard to get a computer to do right. In this module you’ll learn how to break down such intuitive problems into steps that even a computer can understand.</p>
      </details>
      <p class="or">or</p>
      <details><summary>NUMBERS</summary>
        <p>How do you know if a number is a prime number? Number theory is the science about properties of numbers. In this mathematically oriented module you create a series of programs that compute this and other properties of numbers. No math knowledge required for this module. (You will learn some, though.)</p>
      </details>
    </td>
    <td>
      <details><summary>INTEGRATION</summary>
        <p>In many scientific fields you need to determine the surface area under a function. Integration is a mathematical tool for doing so. However this tool doesn't always work and in such cases we can use numerical integration techniques to let the computer do the work for us. You will learn two important techniques for numerical integration.</p>
      </details>
      <p class="or">or</p>
      <details><summary>TEXT</summary>
        <p>Natural language processing is the science of making a computer understand (something about) natural human language. You will learn how you can get a computer to understand the sentiment of tweets. Is the tone of the tweet positive or negative?</p>
      </details>
    </td>
    <td class="mid">
      <details><summary>BIG DATA</summary>
        <p>In this module you will learn to work with data. You will, for example, analyze weather from the Netherlands and answer questions like: When was the first heat-wave? What was the longest freezing period?</p>
      </details>
    </td>
  </tr>
</table>

#### Scientific Programming 2 (Level 4 - Level 6) {#sp2-modules}

<table class="modules">
  <tr>
    <th>Level 4</th>
    <th>Level 5</th>
    <th>Level 6</th>
  </tr>
  <tr>
    <td>
      <details><summary>MONOPOLY</summary>
        <p>When playing Monopoly, a starting player's advantage seems unfair. To verify, you could play many (millions) real games, but this would take way too much time. Instead, you'll write a computer simulation. This also allows you to experiment with game adjustments to make it fair. You're doing all this for a board game, but this simulation principle applies to various scientific fields (economy, chemistry, biology...).</p>
      </details>
    </td>
    <td>
      <details><summary>MONOPOLY 2</summary>
        <p class="todo">TODO: add description.</p>
      </details>
    </td>
    <td>
      <details><summary>POPULATIONS</summary>
        <p>Predator-prey simulations are models used in ecology and computer science to study the dynamics between populations of predators and their prey within an ecosystem. What's particularly interesting about these simulations is how they can reveal emergent patterns and complex behaviors that arise from relatively simple rules. To make it easier to program such a simulation you will learn a programming technique called object oriented programming (OOP).</p>
      </details>
    </td>
  </tr>
</table>

#### Data Processing (Level 7 - Level 10 + final project) {#dp-modules}

<table class="modules">
  <colgroup>
    <col style="width: 17%">
    <col style="width: 17%">
    <col style="width: 17%">
    <col style="width: 17%">
    <col style="width: 32%">
  </colgroup>
  <tr>
    <th>Level 7</th>
    <th>Level 8</th>
    <th>Level 9</th>
    <th>Level 10</th>
    <th>Final project</th>
  </tr>
  <tr>
    <td>
      <details><summary>PANDAS 1</summary>
        <p class="todo">TODO: add description.</p>
      </details>
    </td>
    <td>
      <details><summary>PANDAS 2</summary>
        <p class="todo">TODO: add description.</p>
      </details>
    </td>
    <td>
      <details><summary>DATABASES</summary>
        <p>When working with really large amounts of data, you typically won't store it in simple (text) files on your computer. You'd use something like a relational database. To get information from a database you'll need a specific language called Structured Query Language (SQL). You're going to practice SQL by solving a mystery...</p>
      </details>
    </td>
    <td>
      <details><summary>WIKIPEDIA</summary>
        <p class="todo">TODO: add description.</p>
      </details>
    </td>
    <td>
      <details><summary>FINAL PROJECT</summary>
        <p>Do you have data from your own studies or research that you would like to analyze? Do this with our help for the final project of this course. The goal here is to work on something that you find interesting and care about.</p>
      </details>
    </td>
  </tr>
</table>

### Tutorials and Support

Although the track is flexible, **you are not on your own**.

* Tutorials are on-campus working sessions.
* Teaching staff are present to answer questions and discuss solutions.
* **You are expected to attend at least one tutorial per week.**
* You select a tutorial group via the intake form.

Tutorial schedules:
[Tutorial schedules (Datanose)](/datanose)

## Getting Started

To begin:

1. Read this syllabus carefully.
2. Install Python (instructions on the website).
3. Start with **Level 1**, choosing either *Algorithms* or *Numbers*.

## Deadlines {#deadlines}
**Fall 2026/2027, (SP1 + SP2 + DP, Fast Pace) **

## Assessment & Grading

### Scientific Programming 1 & 2 (Pass/Fail)

Scientific Programming 1 & 2 are pass/fail courses. That means that you final grade will be one of the following:

* **AVV (Pass)**

  * All modules completed, discussed, and passed
  * Final exam passed
* **NAV (Insufficient)**

  * Active participation but incomplete or insufficient modules/exam
* **NAP (Non-attendance)**

  * No active participation

#### Coursework (Modules)

* Each module contains 5–9 submissions, mostly auto-graded.
* **All required submissions must be correct** to pass a module.
* After completion, you must **discuss your code in person** during a tutorial.
* A module is only passed after discussion.
* All modules must be passed **before** you can take the exam.

#### Final Exam

* You may participate in the final exam **only if you have completed all coursework**, meaning that all modules are *finished*, *discussed*, and marked as *pass*.
* If you do not meet these requirements (for example, if you still have an insufficient or a module hos not been discussed), you may not participate in the exam at that time. You must first complete the coursework and take the exam at a later date.
* The final exam is an **on-campus programming exam** conducted in a controlled setting. You will take the exam on a dedicated exam computer, not on your own laptop.
* The exam lasts approximately 3 hours and consists of 4 small programming assignments.
* To pass the exam, you must solve at least 3 of the 4 assignments correctly.
* Your exam will be evaluated solely on the correctness of your solutions. Code design, comments, and style are *not* taken into account.
* Checkpy is available during the exam, allowing you to verify the correctness of your solutions.
* You may use the course website as a resource (you may open *sp.proglab.nl* in a new tab after logging in).
* You may use a **printed version** of [these cheatsheets](/python/en/overview) during the exam.
* You may *not* import external modules such as `numpy`, `csv`, or others, unless the assignment explicitly states that this is allowed.

### Data Processing (Graded)

For Data Processing, you will receive a regular grade on a 1–10 scale. 

There is no final exam, only programming modules and a final project. Your final grade is determined by the grades for Level 7, Level 8, and the final project, weighted as follows:

| Module        | Weight |
| ------------- | ------ |
| Level 7       | 25%    |
| Level 8       | 25%    |
| Final Project | 50%    |

Note that, Levels 9 and 10 do not contribute to the final grade, but you must still submit them correctly in order to pass the course.

#### Coursework (modules)

Some assignments are **graded** (Level 7, Level 9, and the final project), while others are **pass/fail** (Level 8 and Level 10).

* All modules must be **discussed in person** after submission in order to receive a grade or pass.
* For pass/fail assignments, grading works the same as in Scientific Programming 1 and 2: they are assessed strictly as pass/fail.
* For graded assignments, your grade depends on the number of challenge assignments you complete.

  * Correctly completing the base assignments results in a grade of **7**.
  * Additional points are awarded for completed challenges.
* Final project grade, see below.

#### Final project grade

Your project will be evaluated on four criteria: **Research Question / Project Goal**, **Complexity**, **Novelty / Learning**, and **Quality**.

For each criterion, you can receive 0 to 3 points. All criteria contribute equally to the final project grade. The final grade is calculated as:

$$
\text{grade} = \frac{\text{question} + \text{complexity} + \text{novelty} + \text{quality}}{12} \times 9 + 1
$$


## Doing your own work

This course's philosophy on academic honesty is best stated as "be reasonable." The course recognizes that interactions with classmates and others can facilitate mastery of the course's material. However, there remains a line between enlisting the help of another and submitting the work of another. This policy characterizes both sides of that line.

The essence of all work that you submit to this course must be your own (unless explicitly stated otherwise). Collaboration on problem sets is not permitted except to the extent that you may ask classmates and others for help so long as that help does not reduce to another doing your work for you. Generally speaking, when asking for help, you may show your code to others, but you may not view theirs, so long as you and they respect this policy's other constraints. Collaboration on the course's test and quiz is not permitted at all.

Below are rules of thumb that (inexhaustively) characterize acts that the course considers reasonable and not reasonable. If in doubt as to whether some act is reasonable, do not commit it until you solicit and receive approval in writing from the course's heads. Acts considered not reasonable by the course are handled harshly.

### Reasonable

- Communicating with classmates about problem sets' problems in English (or some other spoken language).
- Discussing the course's material with others in order to understand it better.
- Helping a classmate identify a bug in his or her code at office hours, elsewhere, or even online, as by viewing, compiling, or running his or her code, even on your own computer.
- Incorporating a few lines of code that you find online or elsewhere into your own code, provided that those lines are not themselves solutions to assigned problems and that you cite the lines' origins.
- Reviewing past semesters' quizzes and solutions thereto.
- Sending or showing code that you've written to someone, possibly a classmate, so that he or she might help you identify and fix a bug.
- Sharing a few lines of your own code online so that others might help you identify and fix a bug.
- Turning to the course's heads for help or receiving help from the course's heads during the quiz or test.
- Turning to the web or elsewhere for instruction beyond the course's own, for references, and for solutions to technical difficulties, but not for outright solutions to problem set's problems or your own final project.
- Whiteboarding solutions to problem sets with others using diagrams or pseudocode but not actual code.
- Working with (and even paying) a tutor to help you with the course, provided the tutor does not do your work for you.

### Not Reasonable

- Accessing a solution to some problem prior to (re-)submitting your own.
- Asking a classmate to see his or her solution to a problem set's problem before (re-)submitting your own.
- Decompiling, de-obfuscating, or disassembling the staff's solutions to problem sets.
- Failing to cite (as with comments) the origins of code or techniques that you discover outside of the course's own lessons and integrate into your own work, even while respecting this policy's other constraints.
- Giving or showing to a classmate a solution to a problem set's problem when it is he or she, and not you, who is struggling to solve it.
- Looking at another individual's work during the test or quiz.
- Paying or offering to pay an individual for work that you may submit as (part of) your own.
- Providing or making available solutions to problem sets to individuals who might take this course in the future.
- Searching for or soliciting outright solutions to problem sets online or elsewhere. So, **avoid** sources like: **Stackoverflow, Google, chatGPT, GitHub, Copilot**, etc.
- Splitting a problem set's workload with another individual and combining your work.
- Submitting (after possibly modifying) the work of another individual beyond the few lines allowed herein.
- Submitting the same or similar work to this course that you have submitted or will submit to another.
- Submitting work to this course that you intend to use outside of the course (e.g., for a job) without prior approval from the course's heads.
- Turning to humans (besides the course's heads) for help or receiving help from humans (besides the course's heads) during the quiz or test.
- Viewing another's solution to a problem set's problem and basing your own solution on it.

In all cases we follow the directives regarding fraud and plagiarism of the
University of Amsterdam and of the Computer Science
BSc programme. Find them here in [English] and [Dutch].

[Dutch]: http://uva.nl/plagiaat
[English]: https://student.uva.nl/en/content/az/plagiarism-and-fraud/plagiarism-and-fraud.html


## Acknowledgements {#acknowledgements}
This course has been designed by Simon Pauw, Martijn Stegeman, Wouter Vrielink, Tim Doolan and Ivo van Vulpen.

It is partially based on many great programming resources that have been published as Open Courseware under a Creative Commons license. The resulting work itself is also published under the Creative Commons License Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. Feel free to re-use! If you would like to use the work commercially, please send an e-mail for arranging a license.

We have had lots of help from students as well as teaching assistants who tried the course or added ideas of their own. We especially thank:

- Jelle van Assema (assignments and checkpy)
- Puck te Rietmolen (revisions)
- Roan van Blanken (checkpy tests)
- Amir Sahrani (assignments)
- Natasja Wezel (videos, revisions)
- Iris Luden (video)
- Marianne de Heer Kloots (revisions and testing)
- Maarten Inja (DNA assignment)
- Quinten Post (translations)
- Marleen Rijksen (revisions)
- Huub Rutjes (films)
- Vera Schild (checkpy tests)
- Luca Verhees (artwork “semester of code”)

We have used many programming recourses for inspiration:

- 6.189 A Gentle Introduction to Programming Using Python by Sarina Canelake at MIT http://ocw.mit.edu
- 6.00 Introduction to Computer Science and Programming, Fall 2008 by Eric Grimson and John Guttag at MIT http://ocw.mit.edu
- CS50 Introduction to Computer Science I by David Malan at Harvard http://cs50.tv/
- 6.0001 Introduction to Computer Science and Programming in Python by Ana Bell, Eric Grimson and John Guttag at MIT http://ocw.mit.edu
- Think Python by Allen B. Downey http://greenteapress.com/wp/think-python/
