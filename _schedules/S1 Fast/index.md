# Syllabus

**Fall 2026–2027**
 
**Track:** Full (Scientific Programming 1 + 2 and Data Processing - fast pace)

**Expected workload:** ~20 hours/week

## Teaching Team & Contact

**Teaching staff**

<style>
.team, .team thead, .team tbody, .team tr, .team th, .team td { background: transparent; }
</style>

<table class="team">
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

- [General info](#general-info)
  - [Schedule](#schedule)
  - [Attendance](#attendance)
- [Getting started](#getting-started)
- [Programming modules](#programming-modules)
- [Deadlines](#deadlines)
- [Grading](#grading)
- [Prerequisites](#prerequisites)
- [Learning goals](#learning-goals)
- [Course materials](#materials)
- [Doing your own work](#plagiarism)
- [Acknowledgements](#acknowledgements)

## General info {#general-info}

Welcome to this programming track! Here, you’ll use the Python programming language while learning to solve scientific problems from several fields of science. This track is intended for students who have no experience in programming at all. The Scientific Programming track consists of three courses:

- Scientific Programming 1 (SP1) — 3 EC, not graded but pass/fail.
- Scientific Programming 2 (SP2) — 3 EC, not graded but pass/fail.
- Data Processing (DP) — 6 EC, graded.

You learn about the Python language by working on programming problems from several scientific areas. The three courses from this track are designed to be taken together, but you can choose to only follow one or two of the courses.

### Schedule {#schedule}

You can follow each course at different paces to fit your schedule. This means you could do all three courses in a single semester, or you could do them spread out over several semesters. 

**You are following the Fast schedule**: Scientific Programming 1 in September,
Scientific Programming 2 in October, and Data Processing in November and December.

Your schedule is highlighted below. The other schedules are greyed out (they are
shown in case you would like to switch to another one).

<style>
.tracks {
  width: 100%; margin-bottom: 2.5em; font-size: 0.9em;
  border-collapse: separate; border-spacing: 3px 7px;
}
.tracks, .tracks thead, .tracks tbody, .tracks tr { background: transparent; }
.tracks th, .tracks td {
  border: none; padding: 0.4em 0.5em; text-align: center; background: transparent; font-weight: normal;
}
.tracks tbody th { text-align: left; white-space: nowrap;}
.tracks .sp1, .tracks .sp2, .tracks .dp { border-radius: 5px; }
.tracks .sp1 { background: #dbe3d1; color: #39492a; }
.tracks .sp2 { background: #f0e2be; color: #5d4713; }
.tracks .dp  { background: #d3e0dc; color: #2d4a43; }
.tracks .next { text-align: left; font-style: italic; color: #6b6455; white-space: nowrap; }
.tracks .sched { font-weight: bold; }
.tracks tr.dim td, .tracks tr.dim th { filter: grayscale(60%); opacity: 0.3; }
</style>

<table class="tracks">
  <thead>
    <tr>
      <th></th>
      <th>Sep</th><th>Oct</th><th>Nov</th><th>Dec</th><th>Jan</th>
      <th>Feb</th><th>Mar</th><th>Apr</th><th>May</th><th>Jun</th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th class="sched">Fast</th>
      <td class="sp1">SP1</td>
      <td class="sp2">SP2</td>
      <td class="dp" colspan="2">DP</td>
      <td colspan="6"></td>
      <td></td>
    </tr>
    <tr class="dim">
      <th class="sched">Standard</th>
      <td class="sp1" colspan="2">SP1</td>
      <td class="sp2" colspan="2">SP2</td>
      <td></td>
      <td class="dp" colspan="4">DP</td>
      <td></td>
      <td></td>
    </tr>
    <tr class="dim">
      <th class="sched">Relaxed</th>
      <td class="sp1" colspan="4">SP1</td>
      <td></td>
      <td class="sp2" colspan="4">SP2</td>
      <td></td>
      <td class="next">DP next year?</td>
    </tr>
  </tbody>
</table>

And, for reference, the schedules that start in Semester 2:

<table class="tracks">
  <thead>
    <tr>
      <th></th>
      <th>Sep</th><th>Oct</th><th>Nov</th><th>Dec</th><th>Jan</th>
      <th>Feb</th><th>Mar</th><th>Apr</th><th>May</th><th>Jun</th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr class="dim">
      <th class="sched">Fast</th>
      <td colspan="5"></td>
      <td class="sp1">SP1</td>
      <td class="sp2">SP2</td>
      <td class="dp" colspan="2">DP</td>
      <td></td>
      <td></td>
    </tr>
    <tr class="dim">
      <th class="sched">Standard</th>
      <td colspan="5"></td>
      <td class="sp1" colspan="2">SP1</td>
      <td class="sp2" colspan="2">SP2</td>
      <td></td>
      <td class="next">DP next year?</td>
    </tr>
    <tr class="dim">
      <th class="sched">Relaxed</th>
      <td colspan="5"></td>
      <td class="sp1" colspan="4">SP1</td>
      <td></td>
      <td class="next">SP2 next year?</td>
    </tr>
  </tbody>
</table>

The course load is of course dependent on your chosen track. The actual amount of work it takes to complete the course varies a lot for each student. But, as a rough estimate, count at least:

* 20 hrs per week for the **fast** track,
* 10 hrs per week for the **standard** track, and
* 5 hrs per week for the **relaxed** track.

You don't have to follow the entire Scientific Programming track, **you can also follow a single course**. 

### Attendance {#attendance}

There are no lectures (except for a non-compulsory kick-off meeting at the start of Scientific Programming 1) and the tutorials are flexible. 

The fact that the track offers a lot of flexibility doesn't mean you are on your own. In the tutorials, we do provide a lot of help with the programming assignments. You'll work on campus (together with other students) in a classroom. You can ask us questions while you're working on your assignments.

- You can find the times and locations here: [Tutorial and exam schedules](/datanose)
- **We expect all students to join at least one tutorial a week.** You can pick which one you prefer yourself.
- This is the main place where you talk with us and meet other students.


## Getting started {#getting-started}

To begin:

1. Read this syllabus carefully.
2. Install Python (instructions on the website).
3. Start with **Level 1**, choosing either *Algorithms* or *Numbers*.

## Programming modules {#programming-modules}

You're going to learn programming through a number of programming modules. 
The modules are grouped into levels, you have to make one module per level. 
For some levels you have the choice between two different modules. 
When there is such a choice, you will learn the same programming concepts, but often in different thematic context (i.e. different scientific fields).

Each module consists of theory sections, assignments and challenges. In the schedule
you will see these icons:

<ul class="types">
  <li><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-people-fill" viewBox="0 0 16 16"><path d="M7 14s-1 0-1-1 1-4 5-4 5 3 5 4-1 1-1 1zm4-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6m-5.784 6A2.24 2.24 0 0 1 5 13c0-1.355.68-2.75 1.936-3.72A6.3 6.3 0 0 0 5 9c-4 0-5 3-5 4s1 1 1 1zM4.5 8a2.5 2.5 0 1 0 0-5 2.5 2.5 0 0 0 0 5"/></svg> <b>Collaborative assignments</b>: you are encouraged to work on these
      together with other students, and copying each other's code is no problem here.</li>
  <li><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-person-fill" viewBox="0 0 16 16"><path d="M3 14s-1 0-1-1 1-4 6-4 6 3 6 4-1 1-1 1zm5-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6"/></svg> <b>Individual assignments</b>: you make these entirely on your own
      (with our help, of course). You may not copy code from anyone else.</li>
  <li><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-person-fill-gear" viewBox="0 0 16 16"><path d="M11 5a3 3 0 1 1-6 0 3 3 0 0 1 6 0m-9 8c0 1 1 1 1 1h5.256A4.5 4.5 0 0 1 8 12.5a4.5 4.5 0 0 1 1.544-3.393Q8.844 9.002 8 9c-5 0-6 3-6 4m9.886-3.54c.18-.613 1.048-.613 1.229 0l.043.148a.64.64 0 0 0 .921.382l.136-.074c.561-.306 1.175.308.87.869l-.075.136a.64.64 0 0 0 .382.92l.149.045c.612.18.612 1.048 0 1.229l-.15.043a.64.64 0 0 0-.38.921l.074.136c.305.561-.309 1.175-.87.87l-.136-.075a.64.64 0 0 0-.92.382l-.045.149c-.18.612-1.048.612-1.229 0l-.043-.15a.64.64 0 0 0-.921-.38l-.136.074c-.561.305-1.175-.309-.87-.87l.075-.136a.64.64 0 0 0-.382-.92l-.148-.045c-.613-.18-.613-1.048 0-1.229l.148-.043a.64.64 0 0 0 .382-.921l-.074-.136c-.306-.561.308-1.175.869-.87l.136.075a.64.64 0 0 0 .92-.382zM14 12.5a1.5 1.5 0 1 0-3 0 1.5 1.5 0 0 0 3 0"/></svg> <b>Challenges</b>: optional, considerably harder assignments,
      for when you want to get the most out of this course.</li>
</ul>

<style>
.types { list-style: none; padding-left: 0; }
.types li { margin-bottom: 0.5em; }
.types svg { vertical-align: -0.15em; margin-right: 0.3em; }
</style>

Here below is an overview of all modules for all courses. Click a module title to read what it is about.

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
</style>

### Scientific Programming 1 (Level 1 - Level 3) {#sp1-modules}

<table class="modules">
  <tr>
    <th>Level 0</th>
    <th>Level 1 (choose one)</th>
    <th>Level 2 (choose one)</th>
    <th>Level 3</th>
  </tr>
  <tr>
    <td class="mid">
      <details><summary>INSTALL</summary>
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

### Scientific Programming 2 (Level 4 - Level 6) {#sp2-modules}

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
        <p>This is a continuation of MONOPOLY. You’re going to improve the design of your Monopoly simulation. You will learn about more advanced data structures that can help you improve the design of your code dramatically, making it easier to debug, maintain and extend. You will also learn about computational complexity, which gives you a way to reason about the efficiency of your algorithms and shows why picking the right data structure can mean the difference between a run time of a couple of minutes and one of weeks. Redesigning code that you already wrote using more advanced concepts might seem redundant, but it can be one of the most valuable learning experiences on the way to becoming a good programmer.</p>
      </details>
    </td>
    <td>
      <details><summary>POPULATIONS</summary>
        <p>Predator-prey simulations are models used in ecology and computer science to study the dynamics between populations of predators and their prey within an ecosystem. What's particularly interesting about these simulations is how they can reveal emergent patterns and complex behaviors that arise from relatively simple rules. To make it easier to program such a simulation you will learn a programming technique called object oriented programming (OOP).</p>
      </details>
    </td>
  </tr>
</table>

### Data Processing (Level 7 - Level 10 + final project) {#dp-modules}

<table class="modules">
  <tr>
    <th>Level 7</th>
    <th>Level 8</th>
    <th>Level 9</th>
    <th>Level 10</th>
    <th width="32%">Final project</th>
  </tr>
  <tr>
    <td>
      <details><summary>PANDAS</summary>
        <p>Data processing is the art of reading and transforming data so that it can be easily analyzed, visualized and used in machine learning. You could do all of that with the for-loops and file I/O you already know, but it gets cumbersome very quickly, which is why Python has packages built for the job. In this and the next module we focus on the most widely used one, Pandas, though the principles carry over to most data-oriented packages and programming languages, such as SQL or R. Some subjects you will see in this module are: reading, selecting and grouping data, and dealing with missing values. In the end you will see how some of the *Weather* assignments from Scientific Programming 1 become considerably easier with Pandas.</p>
      </details>
    </td>
    <td>
      <details><summary>XKCD</summary>
        <p>This is a continuation of PANDAS. Some subjects you will see in this module are: data quality, combining data sets with concatenation and joins, reshaping data between long and wide form, and rolling windows. You finish with an assignment in which you have to combine data from wildly different sources, from biology, physics and astronomy, to reproduce an <a href="https://xkcd.com/3283/">XKCD comic</a>.</p>
      </details>
    </td>
    <td>
      <details><summary>DATABASES</summary>
        <p>When working with really large amounts of data, you typically won't store it in simple (text) files on your computer. You'd use something like a relational database. To get information from a database you'll need a specific language called Structured Query Language (SQL). You're going to practice SQL by solving a mystery...</p>
      </details>
    </td>
    <td>
      <details><summary>WIKIPEDIA</summary>
        <p>When you’re working with data, it does not always come packaged in a nice “machine readable” way, like a CSV file or a database. Sometimes the information we have is embedded in the HTML of a website. Knowing how to access, transform and visualize that information can be an extremely useful tool in many real-world data projects. In this module you will learn how to use BeautifulSoup, a Python package that allows you to extract data from websites, on a copy of Wikipedia that we host ourselves.</p>
      </details>
    </td>
    <td>
      <details><summary>FINAL PROJECT</summary>
        <p>Do you have data from your own studies or research that you would like to analyze? Do this with our help for the final project of this course. The goal here is to work on something that you find interesting and care about.</p>
      </details>
    </td>
  </tr>
</table>

## Deadlines {#deadlines}

**Fall 2026/2027 — SP1 + SP2 + DP, Fast pace**

*TODO: add the deadline table.*

## Grading {#grading}

Scientific Programming 1 and 2 are pass/fail courses, while Data Processing is a graded course.

### Scientific Programming 1 and Scientific Programming 2 {#sp-grading}

The grading for Scientific Programming 1 and 2 is exactly the same. For both, the grading is
based on three modules and a final exam.

#### Final grade

The course's final result will be "pass" or "fail", which means that no grades are assigned.
You pass by:

- submitting sufficient coursework (as detailed below)
- passing the final exam

#### Coursework (modules)

- Each module consists of several submissions (between 5 and 9), most of which are auto-graded.
  This allows you to track your progress instantly.

  - **Normal submissions** are compulsory; you must complete all of them with correct results
    to pass the module.
  - **Challenges** are not compulsory, but we highly recommend completing at least one per
    module to be fully prepared for the exam and/or future courses.

- Some assignments are marked as *collaborative* assignments. For those you can (we even
  encourage you to) work together, so you can learn from other students. For *individual*
  assignments, however, we expect them to be entirely your own work.
- After you have submitted all parts of a module, **you need to come to the tutorial and
  discuss your code in person**. At this stage, you may receive a **pass** or **fail** for the
  module.
- You must have **discussed** and **passed** all modules, before the final exam.
- You may not re-submit (variations of) solutions that you wrote for any other course's
  problems. In case you have done similar assignments before, discuss with the course staff
  whether this is the right course for you.

#### Final exam

- The final exam is an (on campus) programming exam in a controlled setting. This will take
  about 3 hours. It contains a couple of small programming assignments. You'll pass the exam
  when your answers are sufficiently correct.
- You can participate in the final exam if you're done with the coursework, meaning: all
  modules are *finished*, *discussed*, and marked as *pass*.
- If you do not meet these requirements (for example when you still have an insufficient, or
  one of the first two modules isn't graded yet) you cannot participate in the exam yet. You
  will have to finish the coursework first and do an exam at a later date.

### Data Processing {#dp-grading}

There is no final exam for Data Processing, only programming modules and a final project.

#### Coursework (modules)

For Data Processing, some of the modules are graded and some are pass/fail.

* **Level 8 (XKCD)** and **Level 10 (Wikipedia)** are graded. **Level 7 (Pandas)** and
  **Level 9 (Databases)** are pass/fail.
* All modules have to be discussed in person after submitting in order to get a grade.
* For the pass/fail modules the grading works the same as for Scientific Programming 1 and 2.
* For the graded modules you get a grade based on how many of the challenges you have
  finished. For correctly handing in the base modules you get a 7, and you get additional
  points for the challenges.

#### Final project grade

The final project is graded based on research question, complexity, novelty and quality. For
each of these you get points on a scale from 1 to 5.

#### Final grade

For Data Processing you will receive a regular grade (1-10). Your final grade is determined by
the grades for Level 8, Level 10 and your final project, as follows:

| Module        | Weight |
|---------------|--------|
| Level 8       | 25%    |
| Level 10      | 25%    |
| Final Project | 50%    |

Note that, even though Level 7 and Level 9 do not contribute to the grade, you still need to
hand them in correctly in order to pass the course.

## Prerequisites {#prerequisites}

### Scientific Programming 1

* No prior programming experience required.
* Some modules assume **high-school level mathematics or physics**, but alternatives are available.
* If you already have substantial programming experience, this course may not be appropriate—contact staff for advice.

### Scientific Programming 2

* Requires **Scientific Programming 1** (or equivalent experience).

### Data Processing

* Requires **Scientific Programming 2** (or equivalent experience).

If at any point you feel unsure whether this track fits your background, please contact us.

## Learning goals {#learning-goals}

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

## Course materials {#materials}

All the reading and video material is available on this website. You do not need to purchase any books or software. Every module consists of short explanations (written and in the form of videos) and assignments. _You do need to bring your own laptop._

## Doing your own work {#plagiarism}

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
